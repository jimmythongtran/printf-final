# This project creates the printf function.
**The main files of the project are:**<br>
-1: main.c<br>
0. holberton.h<br>
1. _printf.c<br>
  * print_funcs.c
  * print_number.c
  * _putchar.c

  I chose to organize to present the file structure this way
  because: I consider main.c file the tester file which is the goalsetter -
  our desired output/outcome. The header file is the zero - the proverbial
  chicken that gives birth to all the eggs (function prototypes). Then
  _printf.c is the motherboard which needs the other according print_funcs
  and print_number functions.

**main.c**
Contains various printf statements of different data types: char, string and integers.

**holberton.h**
Self-created header file that holds all the function prototypes and the struct used for printf.c

**_printf.c**
The main body of the function that calls the other (print_funcs.c and print_number.c) functions.
