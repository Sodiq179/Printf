# Printf
C programming language Printf function implementaion

## Description
**_printf()** : In this project, we recreated a mini-verison of the ```printf``` function found in the ```stdio.h``` library in the C programming language. This function allows  us to print any argument given to the standard output or terminal. This means we can print any combinations of strings, intergers, and other different data types.

## Authorized functions and macros
- write (man 2 write)
- malloc (man 3 malloc)
- free (man 3 free) s
- va_start (man 3 va_start)
- va_end (man 3 va_end)
- va_copy (man 3 va_copy)
- va_arg (man 3 va_arg)

## Description of what each file shows:
man_3_printf ----------------------- custom manpage for custom _printf function

printf.c ---------------------------- holds custom _printf function

main.h ------------------------ holds prototypes of functions spread across all files

functions.c --------------------------- holds the custom-made putchar, convert_to and string_len functions

placeholder_1.c --------------------------- holds the functions for character, strings, signed integers and unsigned integers placeholder

placeholder_2.c --------------------------- holds the functions for lowrcase hexadecimal, uppercase hexadecimal, octal and address placeholder

## Environment
- Language: C
- OS: Ubuntu 14.04 LTS
- Compiler: gcc 4.8.4
- Style guidelines: Betty style

## How To Install & Compile
(terminal)$ git clone https://github.com/Sodiq179/printf.git
(terminal)$ cd printf
Sample main program inside print.c:

**int main(void)
{
	_printf("%s %c%drld %s", "Hello", "W", 0, "ALX students.");
	return (0);
}**
====================================
(terminal)$ gcc -Wall -Werror -Wextra -pedantic -Wno-format *.c -o print_out
(terminal)$ ./print_out
Hello W0rld ALX students.
(terminal)$

## NOTE
Our mini-version does not handle all the general function of the original printf function in C programming language. It currently handles conversion specifiers: c, s, %, d, i, x, X, o and does not yet support field width, precision, flag characters, or length modifiers.

## Authors
- Sodiq Babawale
- Ibrahim Ibrahim
