CC=g++
CPPFLAGS=-Wall -g
BIN=server client
all:$(BIN)
%.o:%.c
        $(CC) $(CFLAGS) -c $< -o $@

.PHONY:clean
clean:
        rm -f *.o $(BIN)
