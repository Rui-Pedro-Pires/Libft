# Libft

## Description
**Libft** is my first personal C library, containing a collection of essential functions that will be used throughout my journey in C programming. The library includes implementations of various standard C library functions as well as additional utility functions for string manipulation, memory allocation, and list handling. This project provided me with the opportunity to dive deeper into C and better understand how some of the most fundamental functions work behind the scenes.

## Features
### Part 1: Libc Functions
This section involves re-implementing several standard C library functions. Each function replicates the behavior of its corresponding standard function, but with the prefix `ft_`. These functions include:
- **Character checks**: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
- **String and memory handling**: `ft_strlen`, `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_strlcpy`, `ft_strlcat`
- **Case conversion**: `ft_toupper`, `ft_tolower`
- **String search**: `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`
- **Memory search and comparison**: `ft_memchr`, `ft_memcmp`
- **String to integer conversion**: `ft_atoi`
- **Memory allocation functions**: `ft_calloc`, `ft_strdup`

### Part 2: Additional Functions
In this section, I implemented several additional utility functions that are not part of the libc but are extremely useful for various tasks. These functions include:
- **String manipulation**: `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`
- **Integer to string conversion**: `ft_itoa`
- **String iteration**: `ft_strmapi`, `ft_striteri`
- **File descriptor output**: `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### Bonus: Linked List Functions
I also implemented a set of functions to handle linked lists:
- **Creating and adding elements**: `ft_lstnew`, `ft_lstadd_front`, `ft_lstadd_back`
- **Accessing elements**: `ft_lstsize`, `ft_lstlast`
- **Removing elements**: `ft_lstdelone`, `ft_lstclear`
- **Iterating and mapping**: `ft_lstiter`, `ft_lstmap`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/rui-pedro-pires/Libft.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Libft
   ```
3. Compile the library:
   ```bash
   make
   ```

## Usage
After compiling, you can include the library in your C projects. Simply add the `libft.a` to your project’s linking step and include the header file:
```c
#include "libft.h"
```

## Requirements
- The project is written in C.
- Follows strict memory management rules (no memory leaks).
- Global variables are forbidden.