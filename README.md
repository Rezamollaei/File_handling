This program demonstrates various C file I/O and standard input/output operations while using constants and basic arithmetic. It reads from ../Input.txt and writes processed content to ../Output.txt.

Purpose:
Illustrates file I/O, standard input/output, and string/character processing.
How It Works:
File Handling:

Opens ../Input.txt for reading and ../Output.txt for writing.
Handles file opening errors with error messages.
Standard Input/Output:

Reads an integer, a character, and a string from the user.
Outputs them using printf, putchar, and puts.
Casting and Arithmetic:

Performs a calculation involving a constant (PINUMBER) and user input, demonstrating type casting.
File Copying:

Character-by-Character Copy:
Uses fgetc to read characters and fputc to write them to ../Output.txt.
Line-by-Line Copy:
Uses fgets to read and fputs to write lines, appending newlines for clarity.
Word-by-Word Copy:
Reads words with fscanf and writes them using fprintf.
Rewind:

Resets the file pointer to the beginning of the input file before each new operation.

