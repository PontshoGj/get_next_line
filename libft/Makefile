# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: pmogwere <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/06/09 14:38:38 by pmogwere          #+#    #+#              #
#    Updated: 2019/06/27 17:40:09 by pmogwere         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #
NAME=libft.a

CC=gcc

CFLAGS=-Wall -Wextra -Werror -c -I .

RM=rm -f

SRC=ft_memset.c ft_bzero.c ft_memcpy.c ft_memccpy.c \
ft_memmove.c ft_memchr.c ft_memcmp.c ft_memalloc.c ft_memdel.c\
ft_strlen.c ft_strdup.c ft_strcpy.c ft_strncpy.c ft_strcat.c ft_strncat.c \
ft_strlcat.c ft_strchr.c ft_strrchr.c ft_strstr.c ft_strnstr.c \
ft_strcmp.c ft_strncmp.c ft_atoi.c \
ft_isalpha.c ft_isdigit.c ft_isalnum.c ft_isascii.c ft_isprint.c \
ft_toupper.c ft_tolower.c \
ft_strnew.c ft_strdel.c ft_strclr.c ft_striter.c ft_striteri.c \
ft_strmap.c ft_strmapi.c ft_strequ.c ft_strnequ.c ft_strsub.c ft_strjoin.c \
ft_strtrim.c ft_strsplit.c ft_itoa.c \
ft_putchar.c ft_putstr.c ft_putendl.c ft_putnbr.c ft_putchar_fd.c \
ft_putstr_fd.c ft_putendl_fd.c ft_putnbr_fd.c \
ft_lstadd.c ft_lstdel.c ft_lstdelone.c ft_lstiter.c ft_lstmap.c ft_lstnew.c \
ft_iswhitespace.c ft_elementcount.c ft_str_is_lowercase.c ft_str_to_upper.c \
ft_str_is_printable.c ft_islower.c ft_isupper.c ft_strsplit_lst.c \
ft_str_is_alpha.c ft_strrev.c ft_strlenc.c ft_intlen.c ft_printlst.c \
ft_str_to_upper.c ft_isspace.c ft_wordlen.c ft_str_to_lower.c \

OBJ=$(SRC:.c=.o)

$(NAME): 
	$(CC) $(CFLAGS) $(SRC)
	ar rc $(NAME) $(OBJ)

all: $(NAME)

clean:
	$(RM) $(OBJ)

fclean: clean
	$(RM) $(NAME)

re: fclean all
