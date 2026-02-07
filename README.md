# String Square Root Calculator

## Overview
This project is a command-line square root calculator that can compute the square root of near-infinitely long numbers. 

Instead of being confined to the integer limit, the program uses string math on its input. This allows the program to compute arbitrarily large values, including irrational numbers rounded to specified precision.

## Features

- Supports numbers exceeding the integer limit.
- Computes the square root of a number to a user-defined decimal precision.
- Handles irrational results with user controlled rounding.

## Example

```
Enter a non-negative integer that you would like to take the square root of! : 5838583958395839683968344968

How many decimal places would you like to see? 50

The square root is : 76410627260845.331212424537183031762890889250607770
```

## Running the Program

I used MSVC to compile my project; however, I believe you should also be able to run the project on Linux using gcc or clang.

## Why I built this?

This was my first program in my Data Structures course. I found it interesting that we could use strings to computer integer values.