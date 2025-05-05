# Data Structures Template Collection

This repository provides a set of C source files and a header (`ds.h`) implementing core data structures. 

## Usage Steps

1. **Copy Files**: Place all `.c` files and `ds.h` in your folder.
2. **Include Header**: In your `main.c` or other source files, add:
   ```c
   #include "ds.h"
    ```
3. **Compile**: Use the following command to compile your code:
    ```bash
    gcc -std=c11 queue.c stack.c your_main.c -o your_program
    ```
4. **Run**: Execute your program:
    ```bash
    ./your_program    
    ```

## Brief Explanations
- ds.h: Defines types and declares all functions for binary trees, heaps, linked lists, queues, and stacks.
- bt.c: Implements a binary search tree with insertion, deletion (including three cases), and inorder traversal.
- heap.c: Provides a min-heap supporting array-based creation, heapify, insert, delete (extract min), and cleanup.
- ll.c: Manages a singly linked list with head insertion, deletion by value, and printing of elements.
- queue.c: Implements a circular queue with fixed capacity, supporting enqueue, dequeue, and destruction.
- stack.c: Implements a simple array-based stack with push, pop, and destroy operations.
- graph.c   – Graph implementation supporting both unweighted and weighted undirected graphs.
- avl.c   – AVL tree implementation with insertion, deletion, and balancing operations.

Note: In case there is anything missing or you want something to be added, please contact the TAs. Check for any mistakes in the templates and report them before the exam. These templates are given to you before exam to refer. CPPReference will also be available during the exam. 
