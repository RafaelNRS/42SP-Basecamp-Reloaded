# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: ranascim <ranascim@42.student.42sp.org.    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/04/02 18:48:59 by ranascim          #+#    #+#              #
#    Updated: 2022/04/02 19:00:40 by ranascim         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = ft_display_file
SOURCE = ft_display_file.c
OBJ = ft_display_file.o
COMPILER = gcc
FLAGS = -Wall -Wextra -Werror

all: $(NAME)

$(NAME):
		$(COMPILER) $(FLAGS) -c $(SOURCE)
		$(COMPILER) -o $(NAME) $(OBJ) 

clean:
		/bin/rm -f $(OBJ)

fclean:
		/bin/rm -f $(NAME)
