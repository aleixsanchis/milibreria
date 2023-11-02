main.o: main.c
	gcc -c -I "../include" main.c

milibreria.o: milibreria.c
	gcc -c -I "../include" milibreria.c

all: main.o milibreria.o
	gcc main.o milibreria.o -o ejecutable

clean:
	rm main.o milibreria.o ejecutable