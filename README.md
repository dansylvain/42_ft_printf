# ft_printf Project Documentation
Precision printing for optimal formatting.

## Introduction

The "ft_printf" function is a custom implementation of the printf function in C, allowing for formatted output to standard output or a file stream. It serves as a versatile tool for generating formatted data, supporting a comprehensive range of format specifiers, flags, and conversion specifiers akin to the standard printf function. However, "ft_printf" also introduces additional features such as custom conversion specifiers and precision modifiers, providing users with enhanced flexibility and control over their formatted output.

This project aims to provide a reliable and efficient alternative to the standard printf function while enabling users to deepen their understanding of string formatting, memory management, and utility function design in C programming. By exploring and experimenting with "ft_printf," users can not only improve their C programming skills but also gain insights into creating robust and efficient software applications.

## Execution
### Cloning the Repository

To use the "ft_printf" function in your project, clone the repository containing the necessary files from GitHub:

```bash
git clone https://github.com/dansylvain/42_ft_printf ft_printf
```
### Compiling Your Program
Navigate to the project directory and compile your program using the Makefile:
```bash
cd ft_printf
make
```
## Dependencies
My implementation of the "ft_printf" project includes all necessary dependencies within the source code, requiring no additional installations.

## Adding "ft_printf" as a Dependency

To add "ft_printf" as a dependency in your project, follow these steps:

* Copy the "ft_printf" directory into your project directory, or specify its location in your project's Makefile.
* Modify your project's Makefile to include rules for compiling "ft_printf" along with your project. Here's an example of how to do it:

```make
FT_PRINTF_DIR = path/to/ft_printf

$(NAME): $(OBJ) $(FT_PRINTF_DIR)/ft_printf.a
    gcc -o $(NAME) $(OBJ) -L$(FT_PRINTF_DIR) -lftprintf

$(LIBFT_DIR)/ft_printf.a:
    make -C $(FT_PRINTF_DIR)
```
> [!IMPORTANT]
> Replace path/to/libft with the actual path to the "libft" directory in your project.
* Update your project's compilation rules to ensure that "libft" is compiled before your project.


## Using the Function
Once compiled successfully, you can use the "ft_printf" function in your program to print formatted output to the console or a file stream. Ensure that you include the necessary header file in your source code:
```bash
#include "ft_printf.h"
```
Now you can use the "ft_printf" function in your program as demonstrated in the previous example.
## Examples
Here's a simple example demonstrating the usage of the "ft_printf" function to display a formatted message:

```c
#include "ft_printf.h"

int main() {
    ft_printf("The %s is %d years old.\n", "cat", 5);
    return 0;
}
```

Make good use of ft_printf! 🖨️
