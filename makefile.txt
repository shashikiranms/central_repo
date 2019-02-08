ABC.exe:main.c big.c fact.c
        gcc -o ABC.exe main.c big.c fact.c
main.c:main.o
        gcc -c main.c
big.c:big.o
        gcc -c big.c
fact.c:fact.o
        gcc -c fact.c
