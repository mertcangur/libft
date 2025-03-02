# 42 Libft Project

The **Libft** project is a personal implementation of some of the most commonly used functions in the C programming language. The goal is to create a library of functions that mimic those found in the standard C library, while also gaining a deeper understanding of memory management, string manipulation, and system-level programming.

## Project Objective

In this project, you will be expected to:
- Implement a set of standard C functions that you can reuse in future projects.
- Practice low-level C programming, memory management, and handling of edge cases.
- Improve your ability to work with system libraries and understand their inner workings.

## Key Functions Implemented

The library consists of functions from various categories:

### Memory Functions
- `void *ft_memset(void *s, int c, size_t len)`  
  Fills the first `len` bytes of the memory area pointed to by `s` with the constant byte `c`.
  
- `void *ft_memcpy(void *dest, const void *src, size_t n)`  
  Copies `n` bytes from memory area `src` to memory area `dest`.
  
- `void ft_bzero(void *s, size_t len)`  
  Sets the first `len` bytes of the memory area pointed to by `s` to zero.

### String Functions
- `size_t ft_strlen(const char *str)`  
  Returns the length of the string `str`.
  
- `char *ft_strdup(const char *s1)`  
  Duplicates the string `s1` by allocating memory and copying the content.

- `char *ft_strcat(char *dest, const char *src)`  
  Appends the `src` string to the `dest` string, returning the resulting string.

- `char *ft_strchr(const char *s, int c)`  
  Locates the first occurrence of `c` (converted to a char) in the string `s`.

### Character Classification
- `int ft_isalpha(int c)`  
  Checks if the character `c` is an alphabetic letter (either lowercase or uppercase).
  
- `int ft_isdigit(int c)`  
  Checks if the character `c` is a digit.

- `int ft_isalnum(int c)`  
  Checks if the character `c` is alphanumeric (a letter or a digit).

### Conversion Functions
- `int ft_atoi(const char *str)`  
  Converts a string `str` to an integer, handling edge cases like leading spaces and signs.

- `char *ft_itoa(int n)`  
  Converts an integer `n` to a string.

### Additional Utilities
- `void ft_strdel(char **as)`  
  Frees the memory of the string pointed to by `as` and sets it to NULL.

- `void ft_putchar(char c)`  
  Outputs the character `c` to the standard output.

- `void ft_putstr(char const *s)`  
  Outputs the string `s` to the standard output.

## Compilation

To compile the library, run:

```bash
make
