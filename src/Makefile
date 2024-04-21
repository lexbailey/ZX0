all: zx0 dzx0

zx0: zx0.c optimize.c compress.c memory.c zx0.h
	$(CC) $(CFLAGS) -o $@ zx0.c optimize.c compress.c memory.c

dzx0: dzx0.c
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm zx0 dzx0
