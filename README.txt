1. Compile with make
gcc -Wall -ggdb -c blockedq.c
gcc -Wall -ggdb oss.c blockedq.o -o oss
gcc -Wall -ggdb user.c -o user

2. Run the program
$ ./oss -c 7
$ cat log.txt
