# 📚 Libft [![fduque-a's 42 Libft Score](https://badge42.vercel.app/api/v2/cli4i2e8c001108jt19bvwefz/project/3063782)](https://github.com/JaeSeoKim/badge42)

## Disclaimer: This is the current libft I use, with a lot of bonus functions (functions not mandatory by the project's subject). The bonus functions are marqued with "*" both in this README and in the libft.h file with a comment.
## Also, the subject requires you to add a bonus rule to compile the bonus function, but after being evaluated I deleted my bonus rule and added the bonus source files to the mandatory ones, which is wrong, DO NOT COPY PASTE IT.
## Use it at your own risk.

## Description

This project consists of coding basic C functions (see below), which are then compiled into a library for use in other projects of the cursus.

## Functions

### Functions from `<ctype.h>` library

* [`ft_isascii`](libft/srcs/is/ft_isascii.c)			- test for ASCII character.
* [`ft_isalnum`](libft/srcs/is/ft_isalnum.c)			- alphanumeric character test.
* [`ft_isalpha`](libft/srcs/is/ft_isalpha.c)			- alphabetic character test.
* [`ft_islower`](libft/srcs/is/ft_islower.c) *	- lower-case character test.
* [`ft_isupper`](libft/srcs/is/ft_isupper.c) *	- upper-case character test.
* [`ft_isdigit`](libft/srcs/is/ft_isdigit.c)			- decimal-digit character test.
* [`ft_isxdigit`](libft/srcs/is/ft_isxdigit.c) *	- hexadecimal-digit character test.
* [`ft_isprint`](libft/srcs/is/ft_isprint.c)			- printing character test (space character inclusive).
* [`ft_isgraph`](libft/srcs/is/ft_isgraph.c) *	- printing character test (space character exclusive).
* [`ft_isspace`](libft/srcs/is/ft_isspace.c) *	- white-space character test.
* [`ft_isblank`](libft/srcs/is/ft_isblank.c) *	- space or tab character test.
* [`ft_ispunct`](libft/srcs/is/ft_ispunct.c) *	- punctuation character test.
* [`ft_iscntrl`](libft/srcs/is/ft_iscntrl.c) *	- control character test.
* [`ft_tolower`](libft/srcs/to/ft_tolower.c)			- upper case to lower case letter conversion.
* [`ft_toupper`](libft/srcs/to/ft_toupper.c)			- lower case to upper case letter conversion.

### Functions from `<stdlib.h>` library

* [`ft_atoi`](libft/srcs/to/ft_atoi.c)		- convert ASCII string to integer.
* [`ft_atof`](libft/srcs/to/ft_atof.c) *		- convert ASCII string to double.
* [`ft_calloc`](libft/srcs/mem/ft_calloc.c)	- memory allocation.
* [`ft_atol`](libft/srcs/to/ft_atof.c) *		- convert ASCII string to long.

### Functions from `<strings.h>` library

* [`ft_bzero`](libft/srcs/mem/ft_bzero.c)		- write zeroes to a byte string.
* [`ft_memset`](libft/srcs/mem/ft_memset.c)		- write a byte to a byte string.
* [`ft_memchr`](libft/srcs/mem/ft_memchr.c)		- locate byte in byte string.
* [`ft_memcmp`](libft/srcs/mem/ft_memcmp.c)		- compare byte string.
* [`ft_memmove`](libft/srcs/mem/ft_memmove.c)	- copy byte string.
* [`ft_memcpy`](libft/srcs/mem/ft_memcpy.c)		- copy memory area.
* [`ft_memccpy`](libft/srcs/mem/ft_memccpy.c)	- copy string until character found.

### Functions from `<string.h>` library

* [`ft_strlen`](libft/srcs/str/ft_strlen.c)				- find length of string.
* [`ft_strlen_2d`](libft/srcs/str/ft_strlen_2.c) *				- find length of 2D array (i.e. splitted string).
* [`ft_strchr`](libft/srcs/str/ft_strchr.c)				- locate character in string (first occurrence).
* [`ft_strrchr`](libft/srcs/str/ft_strrchr.c)			- locate character in string (last occurence).
* [`ft_strstr`](libft/srcs/str/ft_strstr.c) *		- locate a substring in a string.
* [`ft_strnstr`](libft/srcs/str/ft_strnstr.c)			- locate a substring in a string (size-bounded).
* [`ft_strcmp`](libft/srcs/str/ft_strcmp.c) *		- compare strings.
* [`ft_strncmp`](libft/srcs/str/ft_strncmp.c) *			- compare strings (size-bounded).
* [`ft_strnrcmp`](libft/srcs/str/ft_strnrcmp.c)			- reversely compare strings (size-bounded).
* [`ft_strcpy`](libft/srcs/str/ft_strcpy.c) *		- copy strings.
* [`ft_strncpy`](libft/srcs/str/ft_strncpy.c) *	- copy strings (size-bounded).
* [`ft_strdup`](libft/srcs/str/ft_strdup.c)				- save a copy of a string (with malloc).
* [`ft_strndup`](libft/srcs/str/ft_strndup.c) *	- save a copy of a string (with malloc, size-bounded).
* [`ft_strcat`](libft/srcs/str/ft_strcat.c) *		- concatenate strings (s2 into s1).
* [`ft_strncat`](libft/srcs/str/ft_strncat.c) *	- concatenate strings (s2 into s1, size-bounded).
* [`ft_strlcpy`](libft/srcs/str/ft_strlcpy.c)			- size-bounded string copying.
* [`ft_strlcat`](libft/srcs/str/ft_strlcat.c)			- size-bounded string concatenation.

### Functions from `<math.h>` library

* [`ft_sqrt`](libft/srcs/math/ft_sqrt.c) *	- square root function.
* [`ft_pow`](libft/srcs/math/ft_pow.c) *	- power function.

### Non-standard functions

* [`ft_swap`](libft/srcs/mem/ft_swap.c) *			- swap value of two integers.
* [`ft_putchar`](libft/srcs/put/ft_putchar.c) *	- output a character to stdout.
* [`ft_putchar_fd`](libft/srcs/put/ft_putchar_fd.c)		- output a character to given file.
* [`ft_putstr`](libft/srcs/put/ft_putstr.c) *		- output string to stdout.
* [`ft_putstr_fd`](libft/srcs/put/ft_putstr_fd.c)		- output string to given file.
* [`ft_putendl`](libft/srcs/put/ft_putendl.c) *	- output string to stdout with newline.
* [`ft_putendl_fd`](libft/srcs/put/ft_putendl_fd.c)		- output string to given file with newline.
* [`ft_putnbr`](libft/srcs/put/ft_putnbr.c) *		- output integer to stdout.
* [`ft_putnbr_fd`](libft/srcs/put/ft_putnbr_fd.c)		- output integer to given file.
* [`ft_itoa`](libft/srcs/to/ft_itoa.c)					- convert integer to ASCII string.
* [`ft_substr`](libft/srcs/str/ft_substr.c)				- extract substring from string.
* [`ft_strtrim`](libft/srcs/str/ft_strtrim.c)			- trim beginning and end of string with the specified characters.
* [`ft_strjoin`](libft/srcs/str/ft_strjoin.c)			- concatenate two strings into a new string (with malloc).
* [`ft_split`](libft/srcs/str/ft_split.c)				- split string, with specified character as delimiter, into an array of strings.
* [`ft_split_free`](libft/srcs/str/ft_split_free.c) *				- free splitted string.
* [`ft_strmapi`](libft/srcs/str/ft_strmapi.c)			- create new string from modifying string with specified function.
* [`ft_ftoa_rnd`](libft/srcs/str/ft_ftoa_rnd.c)			- convert float to ASCII string.

### Linked list functions

* [`ft_lstnew`](libft/srcs/lst/ft_lstnew.c)				- create new list.
* [`ft_lstsize`](libft/srcs/lst/ft_lstsize.c)			- count elements of a list.
* [`ft_lstlast`](libft/srcs/lst/ft_lstlast.c)			- find last element of list.
* [`ft_lstadd_back`](libft/srcs/lst/ft_lstadd_back.c)	- add new element at end of list.
* [`ft_lstadd_front`](libft/srcs/lst/ft_lstadd_front.c)	- add new element at beginning of list.
* [`ft_lstdelone`](libft/srcs/lst/ft_lstdelone.c)		- delete element from list.
* [`ft_lstclear`](libft/srcs/lst/ft_lstclear.c)			- delete sequence of elements of list from a starting point.
* [`ft_lstiter`](libft/srcs/lst/ft_lstiter.c)			- apply function to content of all list's elements.
* [`ft_lstmap`](libft/srcs/lst/ft_lstmap.c)				- apply function to content of all list's elements into new list.

## Makefile explained

_Coming soon..._

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

## Third-party testers

* [xicodomingues/francinette](https://github.com/xicodomingues/francinette)

# Found any issue? Contact me! 📥

◦ Email: fduque-a@student.42porto.com

# Might interest you!

### - Check my 42 common-core progress ↙️

[HERE](https://github.com/fduquea/42cursus)

### - My 42 intra profile ↙️
[HERE](https://profile.intra.42.fr/users/fduque-a)
