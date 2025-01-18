# C Pointer Modification Bug

This repository contains a simple C program that demonstrates a potential error related to pointer modification. The program initializes an integer variable 'x', creates a pointer 'ptr' to 'x', and then modifies the value pointed to by 'ptr'.  The bug lies in the potential for unexpected behavior if the pointer is not properly managed. This example illustrates a basic scenario, but similar issues can occur in more complex code involving dynamic memory allocation and pointer arithmetic.

## Bug Description
The program modifies the value of 'x' indirectly through the pointer 'ptr'. This is a common and often straightforward technique; however, without proper understanding or care, mistakes can easily occur.