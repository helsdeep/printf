0x11. C - printf

This team project is part of the curriculum of ALX. _printf replicates the C standard library printf() function.

By the end of this project you should be familiar with the following:
	. How to use git in a team setting
	. Applying variadic functions to a big project
	. The complexities of printf
	. Managing a lot of files and finding a good workflow

Prototype
int _printf(const char *format, ...);

Usage
	. Prints a string to the standard output, according to a given format
	. All files were created and compiled on Ubuntu 14.04.4 LTS using GCC 4.8.4 with the
	command gcc -Wall -Werror -Wextra -pedantic *.c
	. Returns the number of characters in the output string on success, -1 otherwise
	. Calls it this way: _printf("format string", arguments...) where format string can
	contain conversation specifiers and flags, along with regular characters

