C Programming Notes
Chapter 01

Topics:
Variables and Constants
Arithmetic
Contol Flow
Functions
Rudiments of Input and Output

Definitions:
Function				- contains statements that specify the computing operations to be done (eg. main()).

main()					- a special function. your program begins executing here. every program must have a main()
						  function somewhere. main() will usually call other functions to help perform its job.

Variable				- stores values used during computation.
						- must be declared before they can be used.

#include <stdio.h>		- tells the compiler to include information about the stadard input/output library.

Argument				- a list of values that communicate data between functions.

printf					- is a library function that prints output.

character string		- a sequence of characters in double quotes. See also: string constant.

string constant			- a sequence of characters in double quotes. See also: character string.

newline character(\n)	- used in the printf character string. advances the output to the left margin on the next line.

escape sequence			- provides a general and extensive mechanism for representing hard-to-type or invisible characters.
						- examples include: \t for tab \b for backspace \" for the double quote \\ for the backslash itself

comment					- briefly explains what the program does. very helpful for program flow and notes.
						- example: C \* comment goes inside (can be multi-lined) *\ C++ // comment goes after (single lined)

declaration				- announces the properties of variables. consists of a taype name and a list of variables.
						- examples include: int fahr, celcius;
											int lower, upper, step;

int type variable		- means that variables listed are integers.	//All sizes of these data types are machine-dependent.
						- 2 or 4 bytes								//These sizes are based on 16/32/64-bit PCs.
						- -32,768 to 32,767 and -2,147,483,648 to 2,147,483,647
						- other types include: unsigned int
						- 2 or 4 bytes
						- 0 to 65,535 and 0 to 4,294,967,295
						- short
						- 2 bytes
						- -32,768 to 32,767
						- unsigned short
						- 2 bytes
						- 0 to 65,535
						- long
						- 4 bytes
						- -2,147,483,648 to 2,147,483,647
						- and unsigned long
						- 4 bytes
						- 0 to 4,294,967,295

float type variable		- means that variables listed are integers or decimals.
						- 4 bytes
						- 6 decimal places
						- 1.2E-38 to 3.4E+38
						- other types include: double
						- 8 byte
						- 2.3E-308 to 1.7E+308
						- 15 decimal places
						- and long double
						- 10 byte
						- 3.4E-4932 to 1.1E+4932
						- 19 decimal places

char type variable		- means that variables listed can be any letter, number, punctuation marks, symbols or whitespace.
						- 1 byte
						- other types include: unsigned char
						- 1 byte
						- 0 to 255
						- and signed char
						- 1 byte
						- -128 to 127

assignment-statements	- set the varaibles to their intial values.

individual statements	- are always terminated by semicolons.

while loop				- repeats once per output line.
						- condition in parenthasis is tested as true or false.
						- if the condition is true, then the body of the loop is executed. The condition is then re-tested.
						- if the condition is false, the loop ends, and execution continues at the statement that follows the loop.
						- body of while loop can be one or more statements enclosed in braces
						- statments controlled by the while loop are indented one tab stop (four spaces)
						
integer truncation		- integer division can cause truncation. 5 and 9 are integers. 5/9 is a fraction. fractional parts are discarded.

printf function			- general-purpose output formatting function.
						- %d specifies an integer arguement
						- each arguement must match up by number and data type
						- not part of the C language; no input or output defined by C itself.
						- just a useful function from the standard library of functions that are normally accessible to C programs.
						- behavior is defined by the ANSI standard.
						- %o octal
						- %x hexadecimal
						- %c character
						- %s character string
						- %% % character

Equations:
C = (5/9) * (F-32) //Converts Fahrenheit to Celsius
C = (F-32) / (9/5) //Converts Celsius to Fahrenheit
