CC = clang

NAME = mini_printf
INCLUDE = ./../include
OBJDIR = ./../obj
HEADERDIR = ./../include

SRC = ./../mini_printf.c

all: $(NAME)

$(NAME):
	$(CC) $(SRC)
	mv ./a.out ./mini_printf
	mv ./mini_printf ./../

clean:
	- rm -f ./../*.o
	- rm -f ./../*~
	- rm -f ./../*.out

fclean: clean
	rm -f ./../$(NAME)

re: fclean $(NAME)
