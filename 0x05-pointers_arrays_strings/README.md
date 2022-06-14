#		C - Pointers, arrays and strings in C-LOW-LEVEL PROGRAMMING LANGUAGE




				Author: Oseni Sakariyau Oluwadamilare




			This file will denotes what each script does per task.


0. This writes a function that takes a pointer to an int as parameter and updates the value it points to to 98.
		. Prototype: void reset_to_98(int *n);

1. This writes a function that swaps the values of two integers.

    	. Prototype: void swap_int(int *a, int *b);

2. This writes a function that returns the length of a string.

    	. Prototype: int _strlen(char *s);


3. This writes a function that prints a string, followed by a new line, to stdout.

    	. Prototype: void _puts(char *str);

FYI: The standard library provides a similar function: puts. Run man puts to learn more.


4. This writes a function that prints a string, in reverse, followed by a new line.

    	. Prototype: void print_rev(char *s);


5. This writes a function that reverses a string.

    	. Prototype: void rev_string(char *s);


6. This writes a function that prints every other character of a string, starting with the first character, followed by a new line.

    	. Prototype: void puts2(char *str);


7. This writes a function that prints half of a string, followed by a new line.

    	. Prototype: void puts_half(char *str);
    	. The function should print the second half of the string
    	. If the number of characters is odd, the function should print the last n characters of the string, where n = (length_of_the_string - 1) / 2


8. This writes a function that prints n elements of an array of integers, followed by a new line.

    	. Prototype: void print_array(int *a, int n);
    where n is the number of elements of the array to be printed
    	. Numbers must be separated by comma, followed by a space
    	. The numbers should be displayed in the same order as they are stored in the array
    	. You are allowed to use printf


9. This writes a function that copies the string pointed to by src, including the terminating null byte (\0), to the buffer pointed to by dest.

	. Prototype: char *_strcpy(char *dest, char *src);

    	. Return value: the pointer to dest

FYI: The standard library provides a similar function: strcpy. Run man strcpy to learn more.


10. This writes a function that convert a string to an integer.

    	. Prototype: int _atoi(char *s);
    	. The number in the string can be preceded by an infinite number of characters
    	. You need to take into account all the - and + signs before the number
    	. If there are no numbers in the string, the function must return 0
    	. You are not allowed to use long
    	. You are not allowed to declare new variables of “type” array
    	. You are not allowed to hard-code special values
    	. We will use the -fsanitize=signed-integer-overflow gcc flag to compile your code.

FYI: The standard library provides a similar function: atoi. Run man atoi to learn more.
 
