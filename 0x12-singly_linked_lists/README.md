This is a 0x12. C - Singly linked lists

0. Write a function that prints all the elements of a list_t list.
File: 0-print_list.c
Prototype: size_t print_list(const list_t *h);
Return: the number of nodes
	Format: see example
If str is NULL, print [0] (nil)
	You are allowed to use printf

	1. Write a function that returns the number of elements in a linked list_t list.
	File: 1-list_len.c
	Prototype: size_t list_len(const list_t *h);

	2. Write a function that adds a new node at the beginning of a list_t list.
	File: 2-add_node.c
	Prototype: list_t *add_node(list_t **head, const char *str);
Return: the address of the new element, or NULL if it failed
str needs to be duplicated
You are allowed to use strdup

3. Write a function that adds a new node at the end of a list_t list.
File: 3-add_node_end.c
Prototype: list_t *add_node_end(list_t **head, const char *str);
Return: the address of the new element, or NULL if it failed
str needs to be duplicated
You are allowed to use strdup

4. Write a function that frees a list_t list.
File: 4-free_list.c
Prototype: void free_list(list_t *head);

5. Write a function that prints You're beat! and yet, you must allow,\nI bore my house upon my back!\n before the main function is executed.
File: 100-first.c
You are allowed to use the printf function

6. Write a 64-bit program in assembly that prints Hello, Holberton, followed by a new line
File: 101-hello_holberton.asm
You are only allowed to use the printf function
You are not allowed to use interrupts
Your program will be compiled using nasm and gcc:
