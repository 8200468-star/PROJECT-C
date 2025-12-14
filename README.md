# [Joshmar Robinos]_Coursera - Statistical Analytics Project (C1M1)

## Author
[Joshmar Robinos ]
[8200468@ntc.edu.ph]

## Project Description
This repository contains C code for a simple application that performs statistical analysis on an array of unsigned char data. The program calculates the minimum, maximum, mean, and median of the dataset, and sorts the array from largest to smallest. All statistics are rounded down to the nearest integer.

## Repository Contents
* `stats.c`: Implementation file for all required functions.
* `stats.h`: Header file containing function declarations and documentation.
* `README.md`: Project description and author information.

## Compilation and Execution
The code can be compiled and run on a Linux host machine using GCC:
```bash
gcc -std=c99 -Wall -Wextra -Werror -o stats stats.c
./stats
