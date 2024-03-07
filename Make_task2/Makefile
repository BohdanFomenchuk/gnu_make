all: main

main: main.o src1.o src2.o src3.o
	gcc -o main main.o src1.o src2.o src3.o 

include: make1.mk
include: make2.mk
include: make3.mk

main.o: main.c
	gcc -c main.c -o main.o

clean:
	rm -r main *.o
