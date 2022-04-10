# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: ranascim <ranascim@42.student.42sp.org.    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/04/02 18:11:23 by ranascim          #+#    #+#              #
#    Updated: 2022/04/02 20:06:17 by ranascim         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a
SOURCE = ./srcs
HEADER = ./includes/
SRC_FILES = $(SOURCE)/ft_putchar.c $(SOURCE)/ft_putstr.c $(SOURCE)/ft_strcmp.c \
				$(SOURCE)/ft_strlen.c $(SOURCE)/ft_swap.c
COMPILER = gcc
FLAGS = -Wall -Wextra -Werror
OBJ = ft_putchar.o ft_putstr.o ft_strcmp.o ft_strlen.o ft_swap.o

all: $(NAME)

$(NAME):
		$(COMPILER) $(FLAGS) -c $(SRC_FILES) -I $(HEADER)
		ar -rc $(NAME) $(OBJ)

clean:
		/bin/rm -f $(OBJ)

fclean:
		/bin/rm -f $(NAME)

re: fclean all