# Debug-buffer-overrun
This repository will use gdb to analyze the different sections of a given C code to debug its vulnerability on buffer overrun 

#Buffer overrun
Buffers provide a temporary area for programs to store data. A buffer overflow, also known as a buffer overrun, is when a program overruns a buffer's boundary and overwrites adjacent memory locations in the process.

#Input
A program (grade.c) written in C is given to run on ARMv8 architecture. It reads input from command line or an input file. It is vulnerable for buffer overrun by large input data. 

#Tasks
The task is to use gdb to analyze the typical sections of the program: text (i.e. instructions), initialized data segment, uninitialized data segment (bss), heap and stack. Create memory map for each of the section, based on gdb.

The next step is to write a C code to generate input file which causes the given grade.c program to have buffer overrun issue. In other words, based on the analysis of the vulnerability of grade.c's sections, create a "attack" input file to show the vulnerability. 

This project is a COS217 assignment. https://www.cs.princeton.edu/courses/archive/spr23/cos217/asgts/06overrun/

A complete code is a private repository and it is available upon request only for employment purpose.
