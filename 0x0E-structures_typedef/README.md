#	C - Structures, typedef in C-LOW-LEVEL PROGRAMMING LANGUAGE





		   Author: Oseni Sakariyau Oluwadamilare



	    This file will denotes what each script does per task.



0. This script defines a new type struct dog with the following elements:

    	. name, type = char *
    	. age, type = float
    	. owner, type = char *


1. This script writes a function that initialize a variable of type struct dog

    	. Prototype: void init_dog(struct dog *d, char *name, float age, char *owner);


2. This script writes a function that prints a struct dog

    	. Prototype: void print_dog(struct dog *d);
    	. Format: see example bellow
    	. You are allowed to use the standard library
    	. If an element of d is NULL, print (nil) instead of this element. (if name is NULL, print Name: (nil))
    	. If d is NULL print nothing.


3. This script defines a new type dog_t as a new name for the type struct dog.

4. This script writes a function that creates a new dog.

    	. Prototype: dog_t *new_dog(char *name, float age, char *owner);
    	. You have to store a copy of name and owner
    	. Return NULL if the function fails

