# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: lhayward <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2020/11/04 13:36:14 by lhayward          #+#    #+#              #
#    Updated: 2020/11/04 14:51:36 by lhayward         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #


SRCS		=	ft_memcpy.c \
				ft_memmove.c \
				ft_strlcpy.c \
				ft_strlcat.c \
				ft_atoi.c \
				ft_memset.c \
				ft_strlen.c \
				ft_bzero.c \
				ft_putchar.c \
				ft_strmapi.c \
				ft_calloc.c \
				ft_putchar_fd.c \
				ft_strncmp.c \
				ft_isalnum.c \
				ft_putendl_fd.c \
				ft_strnstr.c \
				ft_isalpha.c \
				ft_putnbr.c \
				ft_strrchr.c \
				ft_isascii.c \
				ft_putnbr_fd.c \
				ft_strtrim.c \
				ft_isdigit.c \
				ft_putstr.c \
				ft_substr.c \
				ft_isprint.c \
				ft_putstr_fd.c \
				ft_tolower.c \
				ft_itoa.c \
				ft_split.c \
				ft_toupper.c \
				ft_memccpy.c \
				ft_strchr.c \
				ft_memchr.c \
				ft_strdup.c \
				ft_memcmp.c \
				ft_strjoin.c 
			
BONUS		=		ft_lstadd_back.c \
				ft_lstadd_front.c \
				ft_lstclear.c \
				ft_lstdelone.c\
				ft_lstiter.c \
				ft_lstlast.c \
				ft_lstmap.c \
				ft_lstnew.c \
				ft_lstsize.c
				
OBJC		= ${SRCS:.c=.o}

NAME		= libft.a

CC			= gcc

RM			= rm -f

CFLAGS		= -Wall -Wextra -Werror

.c.o:
			${CC} ${CFLAGS} -c $< -o ${<:.c=.o}

$(NAME):	${OBJC}
			ar rc libft.a ${OBJC}

all:		${NAME}

bonus:		all

clean:		
			${RM} ${OBJC}

fclean:		clean
			${RM} ${NAME}

re:			fclean	all

.PHONY:		all clean fclean re