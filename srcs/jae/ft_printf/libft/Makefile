NAME	=	libft.a
CC		=	gcc
FLAG	=	-Wall -Wextra -Werror
SRC		=	ft_hexchanger.c \
			ft_isdigit.c \
			ft_itoa.c \
			ft_utoa.c \
			ft_tolower.c \
			ft_substr.c \
			ft_strtolower.c \
			ft_strlen.c \
			ft_strjoin.c \
			ft_strdup.c \
			ft_strdchar.c \
			ft_strchr.c \
			ft_putstr.c \
			ft_putchar.c \
			ft_octchanger.c\
			ft_calloc.c\
			ft_bzero.c\
			ft_strncmp.c\
			ft_memcpy.c\
			ft_atoi.c\

INC		=	libft.h

OBJS	=	${SRC:.c=.o}

$(NAME) : ${OBJS}
	ar rcs ${NAME} ${OBJS}

%.o		:	%.c $(INC)
	@$(CC) $(FLAG) -c $< -o $@

all		:	${NAME}

clean	:
	 rm -f ${OBJS}
fclean	:	clean
	 rm -f ${NAME}
re		:	fclean all
