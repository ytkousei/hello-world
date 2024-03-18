NAME  = hello
SRCS  = hello.c
OBJS  = $(SRCS:.c=.o)
CC    = gcc

$(NAME): $(OBJS)
	gcc $(OBJS) -o $(NAME)

all: $(NAME)

.c.o:
	$(CC) -c $< -o $@

clean:
	rm -f $(OBJS)

fclean: clean
	rm -f $(NAME)

re: fclean all
