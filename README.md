# OpenMP-project
To Find Duplicate Files in an Directory

# Getting Started

To get you started you can simply clone this project's repository and install the dependencies:


# Overview of OpenMP


The OpenMP Application Programming Interface (API) was developed
to enable portable shared memory parallel programming.

It aims to support the parallelization of applications from many
disciplines.

It is highly desirable to enable programmers to work with a single
source code: if a single set of source files contains the code for both
the sequential and the parallel versions of a program, then program
maintenance is much simplified.

# Introduction
The program will compare the contents of the given two data files. If both files contains same contents , the program will display the output as the two files are Identical. If both files are having different contents, the program will display the output as the two files are not Identical.

 
1. Firstly Declare two file pointers for two files.
 2. Open two files in read mode. Using fopen command. 
3. Now Inside while loop using fgets command to read both files character by character.( in arrays ch1 and ch2 and display it using puts )
4. Check both characters whether they are equal or not.
5. Check inside if statement ch1 and ch2, then both files are said to be equal otherwise both files are non identicle.

# Prerequisites
Program must be on UBUNTU with Installed OPENMP

# Run the Application

gcc -fopenmp omp_parallel.c 
(for parallel code)

gcc -fopenmp omp_serial.c
(for serial code)


