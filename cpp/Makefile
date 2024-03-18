NAME  = hello
SRCS  = hello.cpp
OBJS  = $(SRCS:.c=.o)
CC    = g++

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
