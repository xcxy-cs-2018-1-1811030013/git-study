#this is a makefile example
depen= clean main.o testa testb
main: $(depen)
	gcc -o main main.o

main.o:main.c
	gcc -c main.c

testa:
	touch testa

testb:
	touch testb

clean: 
	-rm $(depen)
.PHONY:clean