# Arbitrary Precision Calculator in C

## Overview

Arbitrary Precision Calculator is a software application developed in C/C++ to perform arithmetic operations on integers of unlimited size beyond the range supported by standard data types. The project was implemented using object-oriented programming concepts, doubly linked lists, and dynamic memory allocation techniques.

The application supports large integer arithmetic by storing each digit dynamically in linked list nodes, enabling accurate computation for extremely large numbers without overflow limitations. The project follows a structured software development approach including modular design, testing, debugging, and validation of arithmetic edge cases.

## Features

* Addition of large integers
* Subtraction of large integers
* Multiplication of large integers
* Division support
* Dynamic memory allocation
* Doubly linked list implementation
* Sign handling for positive and negative values
* Carry and borrow logic validation
* Modular software design

## Technologies Used

* C
* C++
* OOP Concepts
* Doubly Linked Lists
* Dynamic Memory Allocation
* GCC Compiler
* Linux Environment

## Concepts Implemented

* Object-Oriented Programming
* Data Structures
* Linked Lists
* Dynamic Memory Management
* Arithmetic Logic Handling
* Software Design and Testing

## Project Workflow

1. Input large integer values
2. Store digits dynamically using linked lists
3. Perform arithmetic operations digit by digit
4. Handle carry/borrow operations
5. Display computed results

## Learning Outcomes

* Understanding of dynamic memory allocation
* Practical implementation of linked lists
* Experience with modular software design
* Handling arithmetic operations on large datasets
* Debugging and validation of edge cases

## Build & Run

Compile the program using GCC/G++ compiler:

```bash
gcc main.c -o calculator
./calculator
```

OR

```bash
g++ main.cpp -o calculator
./calculator
```
