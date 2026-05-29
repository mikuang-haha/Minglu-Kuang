Lecture 12: 

Assumption: 1 int is 8 bits (1 byte).\
n1 = 0xF1 = 1111 0001\
n2 = 0xC0 = 1100 0000\

n1<<4 == 0001 0000 (left shit 4 bits)

// would be different if int == 16 bits, 32 bits ... greater than 8 bits\
n1<<4 == 0000 1111 0001 0000 (16 bits)\

// some operators\
n1 | n2 = 1111 0001 = 0xF1\
n1 & n2 = 1100 0000 = 0xC0\
n1 ^ n2 = 0011 0001 = 0x31 (exclusive or)\
~ n1 = 0x0E = 0000 1110

If n1 ^ n2 = 0x00, what do we know about n1 and n2?\
n1 and n2 are equal bit-for-bit! XOR gives 1 only when two bits are different.

