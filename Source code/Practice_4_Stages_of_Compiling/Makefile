step1:
	gcc -E stage.c -o stage.i
step2:
	gcc -S stage.i -o stage.S
step3:
	gcc -c stage.S -o stage.o
step4:
	gcc -o stage stage.o
all:
	gcc -o stage stage.c
clean:
	rm -rf stage.i stage.S stage.o stage
