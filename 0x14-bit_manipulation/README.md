C - Bit Manipulation
Tests: heavy_check_mark:
tests: Folder containing test files
Header File
main.h: Prototypes
File and Prototype Correspondence
File	Prototype
0-binary_to_uint.c	unsigned int binary_to_uint(const char *b);
1-print_binary.c	void print_binary(unsigned long int n);
2-get_bit.c	int get_bit(unsigned long int n, unsigned int index);
3-set_bit.c	int set_bit(unsigned long int *n, unsigned int index);
4-clear_bit.c	int clear_bit(unsigned long int *n, unsigned int index);
5-flip_bits.c	unsigned int flip_bits(unsigned long int n, unsigned long int m);
100-get_endianness.c	int get_endianness(void);
Tasks :page_with_curl:
Task 0. 0

0-binary_to_uint.c: C function that converts a binary number
to an unsigned int.
The parameter b is a pointer to a string of 0 and 1 characters.
If b is NULL or there are one or more characters in b that are
not 0 or 1, it returns 0.
Otherwise, it returns the converted number.
Task 1. 1

1-print_binary.c: C function that prints the binary representation
of a number.
Task 2. 10

2-get_bit.c: C function that returns the value of a bit at a
given index.
Indices start at 0.
If an error occurs, it returns -1.
Otherwise, it returns the value of the bit at the given index.
Task 3. 11

3-set_bit.c: C function that sets the value of a bit at a given index
to 1.
If an error occurs, it returns -1.
Otherwise, it returns 1.
Task 4. 100

4-clear_bit.c: C function that sets the value of a bit at
a given index to 0.
If an error occurs, it returns -1.
Otherwise, it returns 1.
Task 5. 101

5-flip_bits.c: C function that returns the number of bits needed
to be flipped to get from one number to another.
Task 6. Endianness

100-get_endianness.c: C function that checks the endianness.
If big-endian, it returns 0.
If little-endian, it returns 1.
Task 7. Crackme3

101-password: File containing the password for the crackme3 executable.
