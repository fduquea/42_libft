# 📚 Libft [![fduque-a's 42 Libft Score](https://badge42.vercel.app/api/v2/cli4i2e8c001108jt19bvwefz/project/3063782)](https://github.com/JaeSeoKim/badge42)

## Disclaimer: This is the current libft I use, with a lot of bonus functions (functions not mandatory by the project's subject). The bonus functions are marqued with "*" both in this README and in the libft.h file with a comment. Also, the subject requires you to add a bonus rule to compile the bonus function, but after being evaluated I deleted my bonus rule and added the bonus source files to the mandatory ones, which is wrong, DO NOT COPY PASTE IT. Use it at your own risk.

###____________________________________________________________________________________________________________________________________________

## Description

This project consists of coding basic C functions (see below), which are then compiled into a library for use in other projects of the cursus.

## Functions

### Functions from `<ctype.h>` library

* [`<ft_isascii>`](libft/srcs/is/ft_isascii.c)			- test for ASCII character.
* [`<ft_isalnum>`](libft/srcs/is/ft_isalnum.c)			- alphanumeric character test.
* [`<ft_isalpha>`](libft/srcs/is/ft_isalpha.c)			- alphabetic character test.
* [`<ft_islower>`](libft/srcs/is/ft_islower.c) *	- lower-case character test.
* [`<ft_isupper>`](libft/srcs/is/ft_isupper.c) *	- upper-case character test.
* [`<ft_isdigit>`](libft/srcs/is/ft_isdigit.c)			- decimal-digit character test.
* [`<ft_isxdigit>`](libft/srcs/is/ft_isxdigit.c) *	- hexadecimal-digit character test.
* [`<ft_isprint>`](libft/srcs/is/ft_isprint.c)			- printing character test (space character inclusive).
* [`<ft_isgraph>`](libft/srcs/is/ft_isgraph.c) *	- printing character test (space character exclusive).
* [`<ft_isspace>`](libft/srcs/is/ft_isspace.c) *	- white-space character test.
* [`<ft_isblank>`](libft/srcs/is/ft_isblank.c) *	- space or tab character test.
* [`<ft_ispunct>`](libft/srcs/is/ft_ispunct.c) *	- punctuation character test.
* [`<ft_iscntrl>`](libft/srcs/is/ft_iscntrl.c) *	- control character test.
* [`<ft_tolower>`](libft/srcs/to/ft_tolower.c)			- upper case to lower case letter conversion.
* [`<ft_toupper>`](libft/srcs/to/ft_toupper.c)			- lower case to upper case letter conversion.

### Functions from `<stdlib.h>` library

* [`<ft_atoi>`](libft/srcs/to/ft_atoi.c)		- convert ASCII string to integer.
* [`<ft_atof>`](libft/srcs/to/ft_atof.c) *		- convert ASCII string to double.
* [`<ft_calloc>`](libft/srcs/mem/ft_calloc.c)	- memory allocation + bzero.
* [`<ft_atol>`](libft/srcs/to/ft_atof.c) *		- convert ASCII string to long.

### Functions from `<strings.h>` library

* [`<ft_bzero>`](libft/srcs/mem/ft_bzero.c)		- write zeroes to a byte string.
* [`<ft_memset>`](libft/srcs/mem/ft_memset.c)		- write a byte to a byte string.
* [`<ft_memchr>`](libft/srcs/mem/ft_memchr.c)		- locate byte in byte string.
* [`<ft_memcmp>`](libft/srcs/mem/ft_memcmp.c)		- compare byte string.
* [`<ft_memmove>`](libft/srcs/mem/ft_memmove.c)	- copy byte string.
* [`<ft_memcpy>`](libft/srcs/mem/ft_memcpy.c)		- copy memory area.
* [`<ft_memccpy>`](libft/srcs/mem/ft_memccpy.c)	* - copy string until character found.

### Functions from `<string.h>` library

* [`<ft_strlen>`](libft/srcs/str/ft_strlen.c)				- find length of string.
* [`<ft_strlen_2d>`](libft/srcs/str/ft_strlen_2.c) *				- find length of 2D array (i.e. splitted string).
* [`<ft_strchr>`](libft/srcs/str/ft_strchr.c)				- locate character in string (first occurrence).
* [`<ft_strrchr>`](libft/srcs/str/ft_strrchr.c)			- locate character in string (last occurence).
* [`<ft_strstr>`](libft/srcs/str/ft_strstr.c) *		- locate a substring in a string.
* [`<ft_strnstr>`](libft/srcs/str/ft_strnstr.c)			- locate a substring in a string (size-bounded).
* [`<ft_strcmp>`](libft/srcs/str/ft_strcmp.c) *		- compare strings.
* [`<ft_strncmp>`](libft/srcs/str/ft_strncmp.c) 			- compare strings (size-bounded).
* [`<ft_strnrcmp>`](libft/srcs/str/ft_strnrcmp.c) *			- reversely compare strings (size-bounded).
* [`<ft_strcpy>`](libft/srcs/str/ft_strcpy.c) *		- copy strings.
* [`<ft_strncpy>`](libft/srcs/str/ft_strncpy.c) *	- copy strings (size-bounded).
* [`<ft_strdup>`](libft/srcs/str/ft_strdup.c)				- save a copy of a string (with malloc).
* [`<ft_strndup>`](libft/srcs/str/ft_strndup.c) *	- save a copy of a string (with malloc, size-bounded).
* [`<ft_strcat>`](libft/srcs/str/ft_strcat.c) *		- concatenate strings (s2 into s1).
* [`<ft_strncat>`](libft/srcs/str/ft_strncat.c) *	- concatenate strings (s2 into s1, size-bounded).
* [`<ft_strlcpy>`](libft/srcs/str/ft_strlcpy.c)			- size-bounded string copying.
* [`<ft_strlcat>`](libft/srcs/str/ft_strlcat.c)			- size-bounded string concatenation.

### Functions from `<math.h>` library

* [`<ft_sqrt>`](libft/srcs/math/ft_sqrt.c) *	- square root function.
* [`<ft_pow>`](libft/srcs/math/ft_pow.c) *	- power function.

### Non-standard functions

* [`<ft_swap>`](libft/srcs/mem/ft_swap.c) *			- swap value of two integers.
* [`<ft_putchar>`](libft/srcs/put/ft_putchar.c) *	- output a character to stdout.
* [`<ft_putchar_fd>`](libft/srcs/put/ft_putchar_fd.c)		- output a character to given file.
* [`<ft_putstr>`](libft/srcs/put/ft_putstr.c) *		- output string to stdout.
* [`<ft_putstr_fd>`](libft/srcs/put/ft_putstr_fd.c)		- output string to given file.
* [`<ft_putendl>`](libft/srcs/put/ft_putendl.c) *	- output string to stdout with newline.
* [`<ft_putendl_fd>`](libft/srcs/put/ft_putendl_fd.c)		- output string to given file with newline.
* [`<ft_putnbr>`](libft/srcs/put/ft_putnbr.c) *		- output integer to stdout.
* [`<ft_putnbr_fd>`](libft/srcs/put/ft_putnbr_fd.c)		- output integer to given file.
* [`<ft_itoa>`](libft/srcs/to/ft_itoa.c)					- convert integer to ASCII string.
* [`<ft_substr>`](libft/srcs/str/ft_substr.c)				- extract substring from string.
* [`<ft_strtrim>`](libft/srcs/str/ft_strtrim.c)			- trim beginning and end of string with the specified characters.
* [`<ft_strjoin>`](libft/srcs/str/ft_strjoin.c)			- concatenate two strings into a new string (with malloc).
* [`<ft_split>`](libft/srcs/str/ft_split.c)				- split string, with specified character as delimiter, into an array of strings.
* [`<ft_split_free>`](libft/srcs/str/ft_split_free.c) *				- free splitted string.
* [`<ft_strmapi>`](libft/srcs/str/ft_strmapi.c)			- create new string from modifying string with specified function.

### Linked list functions

* [`<ft_lstnew>`](libft/srcs/lst/ft_lstnew.c)				- create new list.
* [`<ft_lstsize>`](libft/srcs/lst/ft_lstsize.c)			- count elements of a list.
* [`<ft_lstlast>`](libft/srcs/lst/ft_lstlast.c)			- find last element of list.
* [`<ft_lstadd_back>`](libft/srcs/lst/ft_lstadd_back.c)	- add new element at end of list.
* [`<ft_lstadd_front>`](libft/srcs/lst/ft_lstadd_front.c)	- add new element at beginning of list.
* [`<ft_lstdelone>`](libft/srcs/lst/ft_lstdelone.c)		- delete element from list.
* [`<ft_lstclear>`](libft/srcs/lst/ft_lstclear.c)			- delete sequence of elements of list from a starting point.
* [`<ft_lstiter>`](libft/srcs/lst/ft_lstiter.c)			- apply function to content of all list's elements.
* [`<ft_lstmap>`](libft/srcs/lst/ft_lstmap.c)				- apply function to content of all list's elements into new list.

## Makefile explained

#Unless you reached a relatively far level during the piscine, this might be the first Makefile you need to do, and if you look at mine, it might be overwellming, so, let's first make one that does exactly what mine does, but simplier! 

```make
NAME = libft.a
CFLAGS = -Wall -Werror -Wextra
RM = rm -f
HDR = -I .
SRCS = $(wildcard *.c)
OBJS = ${SRCS:.c=.o}

%.o : %.c 
	cc ${CFLAGS} ${HDR} -c $< -o $@

$(NAME) : ${OBJS}
	ar rcs ${NAME} $(OBJS)

all : ${NAME}

clean :
	$(RM) *.o

fclean : clean
	${RM} ${NAME}

re : fclean all
	
.PHONY : all clean fclean re bonus
```
# What does every line do?

**`NAME = libft.a`** : Defines a variable NAME with the value "libft.a". This variable represents the name of the output library file.
CFLAGS = -Wall -Werror -Wextra: Defines a variable CFLAGS with compiler flags to enable additional warnings and treat warnings as errors.

**`RM = rm -f`** : Defines a variable RM with the command to forcefully remove files. The -f flag ensures that no error is reported if the file doesn't exist.

**`HDR = -I .`** : Defines a variable HDR with the compiler flag to specify the include directories. Here, it includes the current directory (.).

**`SRCS = $(wildcard *.c)`** : Uses the wildcard function to find all the .c files in the current directory and assigns them to the variable SRCS. This collects all the source files.

**`OBJS = ${SRCS:.c=.o}`** : Defines a variable OBJS by replacing the .c extension with .o for each file in SRCS. This creates a list of object files corresponding to the source files.

**`%.o : %.c`** : Specifies a pattern rule to compile .c files to .o files. It states that for any .c file, the corresponding .o file can be generated by running the command in the following line.

**`cc ${CFLAGS} ${HDR} -c $< -o $@`** : The command to compile a source file to an object file. It uses the $< automatic variable to represent the prerequisite file (source file) and $@ to represent the target file (object file). ${CFLAGS} and ${HDR} are the compiler flags and include directories, respectively.

**`$(NAME) : ${OBJS}`** : Specifies a target $(NAME) that depends on the object files (OBJS). It indicates that the library file $(NAME) can be built by running the command in the following line.

**`ar rcs ${NAME} $(OBJS)`** : `ar` is the command-line utility for creating and modifying static library archives.
    `rcs` are options for the ar command:
        `r`: Inserts or replaces files in the archive. In this case, it is used to add the object files to the library.
        `c`: Creates the archive if it doesn't already exist.
        `s`: Writes an index to the archive, making symbol resolution faster during linking.
    `${NAME}` is the variable that holds the name of the library file (libft.a in this case).
    `$(OBJS)` is the variable that holds the list of object files generated from the source files. It represents all the .o files required to build the library.The command to create the library file ($(NAME)) using the ar utility. The rcs options mean create (r), use the specified name ($(NAME)), and operate in silent mode (s). $(OBJS) are the object files to be included in the library.

**`all : ${NAME}`** : Specifies a target all that depends on $(NAME). It indicates that running make all will build the library file.

**`clean :`**: Specifies a target clean with no prerequisites. It represents the action of cleaning up the build artifacts (object files).

**`$(RM) *.o`** : The command to remove all the object files. $(RM) is the command stored in the RM variable, and *.o represents all the object files.

**`fclean : clean`** : Specifies a target fclean that depends on clean. It represents a more thorough clean, removing both object files and the library file.

**`${RM} ${NAME}`** : The command to remove the library file ($(NAME)).

**`re : fclean all`** : Specifies a target re that depends on fclean and all. It represents the action of rebuilding the project from scratch by first cleaning everything and then rebuilding it.

**`.PHONY : all clean fclean re bonus`** : Declares the targets all, clean, fclean, re, and bonus as phony targets. This tells Makefile that these targets do not correspond to actual files or directories.

# Please note that in this version of the makefile, both the header **`libft.h`** file and all source **`*.c`** files need to be in the same directory as the **Makefile**.

## 🛠️ Usage

### Requirements

The library is written in C language and thus needs the **`gcc` compiler** and some standard **C libraries** to run.

### Instructions

**1. Compiling the library**

To compile the library, run:

```shell
$ cd path/to/libft && make
```

**2. Using it in your code**

To use the library functions in your code, simply include its header:

```C
#include "libft.h"
```

and, when compiling your code, add the required flags:

```shell
-lft -L path/to/libft.a -I path/to/libft.h
```

## Third-party tester

* [xicodomingues/francinette](https://github.com/xicodomingues/francinette)

# Found any issue? Contact me! 📥

◦ Email: fduque-a@student.42porto.com

# Might interest you!

### - Check my 42 common-core progress ↙️

[HERE](https://github.com/fduquea/42cursus)

### - My 42 intra profile ↙️
[HERE](https://profile.intra.42.fr/users/fduque-a)
