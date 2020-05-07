CFLAGS = -DSQLITE_ENABLE_ATOMIC_WRITE -DSQLITE_ENABLE_BATCH_ATOMIC_WRITE -DHAVE_FDATASYNC -fno-omit-frame-pointer

LIBS = -lpthread -ldl -lz

c_insertTest:c_insertTest.c
	gcc -o c_insertTest c_insertTest.c sqlite3.c $(LIBS) $(CFLAGS)

clean:
	rm -f c_insertTest
