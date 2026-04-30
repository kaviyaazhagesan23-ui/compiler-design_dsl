# Custom DSL Compiler (C Project)

## Overview

This project is a simple compiler/interpreter for a custom Domain-Specific Language (DSL) implemented in C. It demonstrates the basic concepts of compiler design including lexical analysis, parsing, and execution of instructions.

The DSL supports variable declarations, addition, and print operations.


## Features

* Reads custom DSL input
* Supports variable assignment (a, b)
* Performs arithmetic operation (addition)
* Prints final result
* Simple interpreter implemented in C (Dev-C++ compatible)

## Supported DSL Syntax

let a = 10;
let b = 20;
let c = a + b;
print(c);


## How It Works

1. Reads input line by line
2. Detects keywords like `let` and `print`
3. Stores values of variables `a` and `b`
4. Computes `c = a + b`
5. Displays output when `print(c)` is called

## Code Execution Steps (Dev-C++)

1. Open Dev-C++
2. Create a new C project
3. Paste the source code
4. Compile and run
5. Enter DSL input when prompted




