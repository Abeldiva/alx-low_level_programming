Another ALX task, and my sandbox is still not opening. I guess I will have to use through github.
Define a new type struct dog with the following elements: name, type = char *
age, type = float
owner, type = char *
FIlename: dog.h
Write a function that initialize a variable of type struct dog
File: 1-init_dog.c
Prototype: void init_dog(struct dog *d, char *name, float age, char *owner);
Write a function that prints a struct dog
File: 2-print_dog.c
Prototype: void print_dog(struct dog *d);
Format: see example bellow
You are allowed to use the standard library
If an element of d is NULL, print (nil) instead of this element. (if name is NULL, print Name: (nil))
If d is NULL print nothing.
Define a new type dog_t as a new name for the type struct dog. File: dog.h
Write a function that creates a new dog.
File: 4-new_dog.c
Prototype: dog_t *new_dog(char *name, float age, char *owner);
You have to store a copy of name and owner
Return NULL if the function fails
Write a function that frees dogs.
File: 5-free_dog.c
Prototype: void free_dog(dog_t *d);
