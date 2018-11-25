	# **************************************************************************** #
	#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: jaelee <marvin@42.fr>                      +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/11/19 17:43:20 by jaelee            #+#    #+#              #
#    Updated: 2018/11/19 17:48:43 by jaelee           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME =	libft.a

SRC =	./ft_memalloc.c \
		./ft_strdel.c \
		./ft_strdup.c \
		./ft_strlen.c \
		./ft_memcpy.c \
		./ft_bzero.c \
		./ft_memdel.c \
		./ft_memset.c \
		./ft_strnew.c \
		./ft_strchr.c \
		./ft_strjoin.c \
		./ft_strsub.c

FLAG = -Wall -Wextra -Werror

OBJ = ./ft_memalloc.o \
	  ./ft_strdel.o \
	  ./ft_strdup.o \
	  ./ft_strlen.o \
	  ./ft_memcpy.o \
	  ./ft_bzero.o \
	  ./ft_memdel.o \
	  ./ft_memset.o \
	  ./ft_strnew.o \
	  ./ft_strchr.o \
	  ./ft_strjoin.o \
	  ./ft_strsub.o

HEADER = ./../

all: $(NAME)

$(NAME):
	gcc $(FLAG) -c  $(SRC) -I $(HEADER)
	ar rc $(NAME) $(OBJ)
	ranlib $(NAME)

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re: fclean all
