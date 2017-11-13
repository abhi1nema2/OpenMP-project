# OpenMP-project
To Find Duplicate Files in an Directory

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
gcc -fopenmp omp_serial.c
