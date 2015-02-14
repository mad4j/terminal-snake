CC ?= gcc
NAME = snake

WARN = -ansi -Wall -Wextra -Werror
CFLAGS =
LFLAGS =

SRC = snake.c

$(NAME): $(SRC)
	$(CC) $(CFLAGS) $(SRC) $(LFLAGS) $(WARN) -o $(NAME)

all: $(SRC)
	$(CC) $(CFLAGS) $(SRC) $(LFLAGS) $(WARN) -o $(NAME) -O3

clean: $(NAME)
	rm $(NAME)
