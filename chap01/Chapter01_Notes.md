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

#include <stdio.h>		- tells the compiler to include information about the stadard input/output library.

Argument				- a list of values that communicate data between functions.

printf					- is a library function that prints output.

character string		- a sequence of characters in double quotes. See also: string constant.

string constant			- a sequence of characters in double quotes. See also: character string.

newline character(\n)	- used in the printf character string. advances the output to the left margin on the next line.

escape sequence			- provides a general and extensive mechanism for representing hard-to-type or invisible characters.
						- examples include: \t for tab \b for backspace \" for the double quote \\ for the backslash itself

Examples:
"hello, world"
#include <stdio.h>				//include information about the standard library
main()							//define a function called main that receives no argument values
{								//statements of main() are enclosed in braces
	printf("hello, world\n");	//main calls library function printf to print this sequence of characters
								//\n represents a newline character
}

"hello, world" v.2
#include <stdio.h>
main()
{
	printf("hello, ");
	printf("world");
	printf("\n");
}
