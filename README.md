# Dangling Pointers and Memory Leaks in C

This repository demonstrates a common coding error in C related to dangling pointers and memory leaks. The code illustrates how improper pointer handling can lead to unexpected behavior and potential vulnerabilities.

## Bug Description
The `bug.c` file contains a simple program that demonstrates a dangling pointer. A pointer is created that points to a variable which goes out of scope and still is being accessed. 

## Solution
The `bugSolution.c` file provides a corrected version of the code that avoids the issue by properly managing the pointers and memory allocation.