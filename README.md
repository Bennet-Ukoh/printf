# printf
A re-creation of the printf function in C!

#Requirements for this project
Code must comply with the Betty style and document checks.
Compile code using flags: -Wall, -Werror, -Wextra, -pedantic, -Wno-format
Cannot use global variables.
Restricted to no more than 5 functions per file.
Function prototypes should be included in header file holberton.h
Header files should be include guarded.
Authorized functions and macros: ..* write (man 2 write) ..* malloc (man 3 malloc) ..* free (man 3 free) ..* va_start (man 3 va_start) ..* va_end (man 3 va_end) ..* va_copy (man 3 va_copy) ..* va_arg (man 3 va_arg)

# File Descriptions

printf.c
contains the fucntion _printf, which uses the prototype int _printf(const char *format, ...);. The format string is composed of zero or more directives. See man 3 printf for more detail. _printf will return the number of characters printed (excluding the null byte used to end output to strings) and will write output to stdout, the standard output stream.

_putchar.c
contains the function _putchar, which writes a character to stdout.
main.h *contains all function prototypes used for _printf.

man_3_printf
manual page for the custom _printf function.

functions.c functions1.c functions2.c
contains all function of each specifier used for _printf.
all function have its own description inside the file.

handle_print.c
contains arguments types used for _printf.

get_flags.c
contains all function for each flag use for _printf.

utils.c
contains some necessary functionalities for _printf.

ger_width.c
contains functions to get width for spcifics spcifiers.

writee_handlers.c
contains write functions.

# Team
Bennet Ukoh | Angel Onuoha
