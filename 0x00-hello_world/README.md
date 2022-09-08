THIS IS AN ALX PROJECT CONTAINING DESCRIPTION OF COMMANDS USED FOR C PROGRAMMING LANGUAGE EXECUTION.
gcc $CFILE -E -o c a script that runs a C file through the preprocessor and save the result into another file.
gcc -c $CFILE a script that compiles a C file but does not link.
gcc -S $CFILE a script that generates the assembly code of a C code and save it in an output file
gcc $CFILE -o cisfun a script that compiles a C file and creates an executable named cisfun.
#include <stdio.h>

/**
 * main - Entry point
 *
 * Return: Always 0 (Success)
 */
int main(void)
{
	puts("\"Programming is like building a multilingual puzzle");
	return (0);
}is a C program that prints exactly "Programming is like building a multilingual puzzle, followed by a new line.
Use the function puts
You are not allowed to use printf
Your program should end with the value 0
#include <stdio.h>

/**
 * main - Entry point
 *
 * Return: Always 0 (Success)
 */
int main(void)
{
	printf("with proper grammar, but the outcome is a piece of art,\n");
	return (0);
}isa C program that prints exactly with proper grammar, but the outcome is a piece of art,, followed by a new line.
#include <stdio.h>

/**
 * main - Entry point
 *
 * Return: Always 0 (Success)
 */
int main(void)
{
	int a;
	long int b;
	long long int c;
	char d;
	float f;

	printf("Size of a char: %lu byte(s)\n", (unsigned long)sizeof(d));
	printf("Size of an int: %lu byte(s)\n", (unsigned long)sizeof(a));
	printf("Size of a long int: %lu byte(s)\n", (unsigned long)sizeof(b));
	printf("Size of a long long int: %lu byte(s)\n", (unsigned long)sizeof(c));
	printf("Size of a float: %lu byte(s)\n", (unsigned long)sizeof(f));
	return (0);
}
gcc -S -masm=intel $CFILE a script that generates the assembly code (Intel syntax) of a C code and save it in an output file.'
#include <stdio.h>

/**
 * main - Entry point
 *
 * Return: Always 0 (Success)
 */
int main(void)
{
	write(2, "and that piece of art is useful\" - Dora Korpar, 2015-10-19\n", 61);

	return (1);
} is a C program that prints exactly and that piece of art is useful" - Dora Korpar, 2015-10-19, followed by a new line, to the standard error
