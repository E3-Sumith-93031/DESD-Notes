
TARGET=main

CSRCS=main.c mmath.c file1.c file2.c
COBJS=$(CSRCS:.c=.o)

CC=gcc 

CFLAGS=-Wall   //compilation flags
LDFLAGS=-lm   // linker flags

$(TARGET).out: $(COBJS)
	$(CC) $(LDFLAGS) -o $@ $^

%.o: %.c
	$(CC) $(CFLAGS) -c $<

# % - stem (it is compared with single or multiple characters)

run:
	./$(TARGET).out

clean:
	rm -f *.o $(TARGET).out













