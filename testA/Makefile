
all:a test.c
	gcc -o test test.c -static -L. -ltest
a:test_a.c test_b.c
	gcc -c test_a.c test_b.c
	ar -r libtest.a test_a.o test_b.o
clean:
	rm -rf *.o test *.a

