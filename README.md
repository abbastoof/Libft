# libft Library

## Introduction
This library contains the implementation of several standard library functions, as well as additional ones to handle memory and strings. It provides a consistent way of using these functions across different platforms and systems.

## Compilation & Usage
```bash
make all    # compile the library
make bonus  # compile the bonus functions
make clean  # remove object files
make fclean # remove object files and the library
make re     # recompile the library
```

## List of Functions

### Standard Functions

- **ft_strlcat.c**: Appends string src to the end of dst.
- **ft_strlen.c**: Computes the length of the string.
- **ft_bzero.c**: Writes n zeroed bytes to the string.
- **ft_isalnum.c**: Checks if the character is alphanumeric.
- **ft_isalpha.c**: Checks if the character is alphabetic.
- ... (and many more)

### Bonus Functions

- **ft_lstnew_bonus.c**: Creates a new list.
- **ft_lstadd_front_bonus.c**: Adds the element to the start of the list.
- **ft_lstsize_bonus.c**: Returns the number of elements in the list.
- ... (and many more)

## Implementation Details
The library is implemented in C and can be used in C projects. Below are the details of a few of the functions:

### ft_atoi
Converts the initial part of the string to an integer.
```c
int	ft_atoi(const char *str)
{
	...
	return (sign * result);
}
```

### ft_bzero
Sets the first len bytes of the byte string to zero.
```c
void	ft_bzero(void *s, size_t len)
{
	...
}
```

### ft_calloc
Allocates memory for an array of count objects.
```c
void	*ft_calloc(size_t count, size_t size)
{
	...
	return (pointer);
}
```

... (and many more)

## Header File
The library comes with a `libft.h` header file, which contains the declarations of the functions and data structures.

## Notes
This library provides a foundational set of functions and can be expanded as per the requirements of the project. It is optimized for performance and can be easily integrated into other projects.
