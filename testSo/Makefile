
all:so test.c
	gcc -o test test.c -L. -ltest
so:test_a.c test_b.c
	gcc test_a.c test_b.c -fPIC -shared -o libtest.so
clean:
	rm -rf *.o test *.so

