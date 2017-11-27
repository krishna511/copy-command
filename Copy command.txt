i=0
while read line;
do
my[$i]="$line"
i=$(($i+1))
done <"a.txt"
echo "${my[*]}">c1.txt