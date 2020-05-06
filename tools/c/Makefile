c_insertTest:c_insertTest.c
	gcc -o c_insertTest c_insertTest.c sqlite3.c -lpthread -ldl -fno-omit-frame-pointer -DSQLITE_ENABLE_ATOMIC_WRITE -DSQLITE_ENABLE_BATCH_ATOMIC_WRITE

clean:
	rm -f c_insertTest
