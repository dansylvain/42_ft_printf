# ft_printf Project Documentation
Precision printing for optimal formatting.

## Introduction

The "ft_printf" function is a custom implementation of the printf function in C, allowing for formatted output to standard output or a file stream. It serves as a versatile tool for generating formatted data, supporting a comprehensive range of format specifiers, flags, and conversion specifiers akin to the standard printf function. However, "ft_printf" also introduces additional features such as custom conversion specifiers and precision modifiers, providing users with enhanced flexibility and control over their formatted output.

This project aims to provide a reliable and efficient alternative to the standard printf function while enabling users to deepen their understanding of string formatting, memory management, and utility function design in C programming. By exploring and experimenting with "ft_printf," users can not only improve their C programming skills but also gain insights into creating robust and efficient software applications.

## Execution
### Cloning the Repository

To use the "ft_printf" function in your project, clone the repository containing the necessary files from GitHub:

```bash
git clone <https://github.com/dansylvain/42_ft_printf>
```
### Compiling Your Program
Navigate to the project directory and compile your program using the Makefile:
```bash
cd ft_printf
make
```
## Dependencies
My implementation of the "ft_printf" project includes all necessary dependencies within the source code, requiring no additional installations.
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
