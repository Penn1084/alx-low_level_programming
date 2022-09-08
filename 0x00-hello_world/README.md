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
