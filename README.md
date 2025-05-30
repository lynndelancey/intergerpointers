#Integer Pointers in C++
Overview
This repository contains a simple C++ program demonstrating dynamic memory allocation using pointers. The program prompts the user to enter three integer values, stores them in variables, and dynamically allocates memory for each value using pointers. It then displays both the stored values and the dereferenced pointer values before properly deallocating memory.

Features
Accepts three integer inputs from the user.

Uses dynamic memory allocation (new) to store values in the heap.

Displays both original variables and pointer values.

Safely deallocates memory (delete) to prevent leaks.

Implements best practices for pointer usage, including setting pointers to nullptr after deletion.Usage
Clone the repository

bash
git clone https://github.com/lynndelancey/intergerpointers.git
Navigate to the directory

bash
cd intergerpointers
Compile the program

bash
g++ integer_pointers.cpp -o integer_pointers
Run the executable

bash
./integer_pointers
Example Output
Enter three integer values: 7 15 23

Variable values:
num1: 7, num2: 15, num3: 23

Pointer values:
*ptr1: 7, *ptr2: 15, *ptr3: 23
Memory Management
This program ensures proper memory management by:

Using new to allocate memory dynamically.

Using delete to free allocated memory.

Setting pointers to nullptr to avoid dangling references.


