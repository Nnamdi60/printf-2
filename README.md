_printf
Create the printf function This is a colaborative project of Christopher Christian Nnamdi and Maduka chinedu The _printf function accepts an argument and prints to the standard output

printf
Description
The printf function sends formatted output to stdout. A custom _printf() for learning purposes was developed by cohort #9 students Christopher Christian Nnamdi and Ebube Okeke. _printf() function format string is a character string, beginning and ending in its initial shift state, if any. These arguments are placed using the percentage '%' operator
Dependencies
The _printf function was coded on an Ubuntu 20.04 LTS machine with gcc version 11.2.0.

Resources
Secrets of printf by prof Don colton https://alx-intranet.hbtn.io/rltoken/gxdsTXxWMklkBTgY197HYQ

Authorized functions and macros
write (man 2 write) malloc (man 3 malloc) free (man 3 free) va_start (man 3 va_start) va_end (man 3 va_end) va_copy (man 3 va_copy) va_arg (man 3 va_arg)

Compilation
The code must be compiled this way:

*$ gcc -Wall -Werror -Wextra -pedantic .c

As a consequence, be careful not to push any c file containing a main function in the root directory of your project (you could have a test folder containing all your tests files including main functions)

The main files will include your main header file (holberton.h): #include holberton.h

Use & Examples
Prototype: int _printf(const char *format, ...); Use - General: _printf("format string", var1, var2, ...);

Examples:

Basic String: _printf("%s Holberton", "Hello");`

Output: Hello Holberton
Print integers: _printf("This is an array element: arr[%d]:%c", 32, arr[32]);`

Output: This is an array element arr[32]:A
Many other specifiers and flags were added and by combinig those the _printf() function generate a different ouput. The following list are the specifiers and flags allowed.

Use & Examples
Specifiers
Specifier	Output	Examples
c	Character	y
d or i	Signed integer	1024, -1024
s	String of characters	Hello Holberton
b	Binary Representation of unsigned integer	01010110
u	Unsigned integer	1024
o	Unsigned octal	432
x	Unsigned hexadecimal integer	3ca
X	Unsigned hexadecimal integer (uppercase)	3CA
S	String with hex-ascii value replacing special chars	\x0A\x0A
p	Pointer address	0x403212
r	Reversed string of characters	dlroW olleH
R	ROT13 Translation of string	Uryyb
Tasks required for this project
I am not going anywhere. You can print that wherever you want to. I'm here and I am a Spur for life. I am not going anywhere. You can print that wherever you want to. I'm here and I am a Spur for life.
Write a function that produces output according to a format. Handle the following conversion specifiers:

%
c
s
Education is when you read the fine print. Experience is what you get if you dont
Handle the following conversion specifiers:

i
d
Just because its in print doesn't mean its the gospel
Create a man page for the function

With a face like mine, I do better in print
Handle the following conversion specifiers:

b
What one has not experienced, one will never understand in print
Handle the following conversion specifiers:

u
x
o
x
X
Nothing in fine print is ever good news
Use a local buffer of 1024 chars in order to call write as little as possible.

Handle the following custom conversion specifier
S : prints the string.
Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters).
How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print
Handle the following conversion specifier: p

The big print gives and the small print takes away
Handle the following flag characters for non-custom conversion specifiers:

??+??
space
??#??
Sarcasm is lost in print
Handle the following length modifiers for non-custom conversion specifiers:

h
l Conversion specifiers to handle: d, i, u, o, x, X
Print some money and give it to us for the rain forests
Handle the field width for non-custom conversion specifiers.

The negative is the equivalent of the composer's score, and the print the performance
Handle the precision for non-custom conversion specifiers.

It's depressing when you're still around and your albums are out of print
Handle the 0 flag character for non-custom conversion specifiers.

Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection
Handle the - flag character for non-custom conversion specifiers.

Print is the sharpest and the strongest weapon of our party
Handle the following custom conversion specifier:

r : prints the reversed string
The flood of print has turned reading into a process of gulping rather than savoring
Handle the following custom conversion specifier:

R: prints the rot13'ed string
*
All the above options work well together.

Authors ??
Christopher Christian Nnamdi < Nnamdi60
Chinedu Maduka < machina94
