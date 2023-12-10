step1:
	gcc -E vi.c -o vi.i

step2:
	gcc -S vi.i -o vi.S

step3:
	gcc -c vi.S -o vi.o

step4:
	gcc -o vi vi.o

all:
	gcc vi.c -o vi

clean:
	rm -rf vi.i vi.S vi.o vi
