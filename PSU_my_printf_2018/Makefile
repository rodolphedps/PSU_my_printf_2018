
##
## EPITECH PROJECT, 2018
## Makefile printf
## File description:
## makefile
##

INC	=	./include/
LIB	=	./lib/my/

NAME	=	libmy.a

LDFLAGS	=	-L $(LIB_DIR) -lmy

SRC	=	$(LIB)my_printf.c	\
		$(LIB)my_putchar.c	\
		$(LIB)my_put_nbr.c	\
		$(LIB)my_putstr.c	\
		$(LIB)my_strlen.c	\
		$(LIB)my_strcpy.c	\
		$(LIB)functions.c	\
		$(LIB)functions2.c	\
		$(LIB)functions3.c	\
		$(LIB)my_put_nbr_unsigned.c	\

OBJ	=	$(SRC:.c=.o)

all:	$(NAME)

$(NAME): $(OBJ)
	ar rc $(NAME) $(OBJ)

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re:	fclean all
