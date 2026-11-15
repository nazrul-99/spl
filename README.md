# Structured Programming in C: Interactive Theory and Lab

Interactive companion for **CSE 1201 Structured Programming**.

Prepared by **Md Nazrul Islam [NI]**, Lecturer, Dept. of CSE, Southeast University.

Open `index.html` through GitHub Pages (for a repository named `spl`, the site is https://nazrul-99.github.io/spl/). Every page is a single self-contained HTML file; no installation is needed.

## Theory (`theory/`)

- `theory/01-intro-to-c.html`: **Introduction to C Programming**. Program structure, compiling and linking, tokens, data types with real sizes, printf and scanf.
- `theory/02-operators-expressions.html`: **Operators and Expressions**. All C operator families, an expression evaluator that shows precedence step by step, bitwise operations and type conversion.
- `theory/03-decision-making-branching.html`: **Decision Making and Branching**. if, if-else, nested if, else-if ladder and switch drawn as live flowcharts; De Morgan's rule, dangling else and goto.
- `theory/04-loops.html`: **Decision Making and Looping**. while, do-while and for animated phase by phase, nested loops that draw patterns, break and continue, sentinel loops.
- `theory/05-one-dimensional-arrays.html`: **One-Dimensional Arrays**. Array memory and addresses, initialisation rules, an animated bubble sort, linear search and max/min scans.
- `theory/06-two-dimensional-arrays.html`: **Two-Dimensional Arrays**. Rows and columns, row-major memory layout, and animated matrix addition, multiplication and transpose.
- `theory/07-character-arrays-strings.html`: **Character Arrays and Strings**. Characters as ASCII codes, strings and the null character, scanf vs fgets, ctype.h tests and atoi/atof.
- `theory/08-user-defined-functions.html`: **User-Defined Functions**. Library and user functions, prototype-definition-call, the call stack in action, parameters, scope and top-down design.
- `theory/09-recursion.html`: **Functions Calling Functions, and Recursion**. Nested calls, base and general cases, an animated recursion tree with the call stack for factorial, Fibonacci and nCr.
- `theory/10-pointers.html`: **Pointers**. Addresses and memory cells, declaring and initialising pointers, the & and * operators, and pass by value versus pass by pointer.
- `theory/11-pointer-arithmetic-arrays.html`: **Pointer Arithmetic, Arrays and Pointers**. Pointer increment, addition, subtraction and comparison scaled by the type size, and why A[i] means *(A + i).
- `theory/12-structures.html`: **Structures**. Defining struct types, member access with . and ->, nesting, typedef, memory layout with padding, and passing structures to functions.
- `theory/13-file-management.html`: **File Management**. Files as byte streams, FILE pointers, fopen modes and NULL checks, and reading and writing with fgetc, fputc, fprintf, fscanf and fgets.

## Lab (`lab/`)

- `lab/01-fundamentals.html`: **Lab 01 · Fundamentals, Bitwise and Ternary Operators**. Input/output, arithmetic, unit conversions, bit tricks and the ?: operator.
- `lab/02-if-else-switch.html`: **Lab 02 · Decision Making with if-else and switch**. Maximum of numbers, sign and divisibility checks, leap year, character class, quadratic roots and switch menus.
- `lab/03-loops-patterns.html`: **Lab 03 · Loops and Star Patterns**. Counting loops, digits of a number, power and factorial, then seven pyramid and diamond patterns.
- `lab/04-loop-practice.html`: **Lab 04 · Loop Practice: 30 Problems**. Easy, medium and nested-loop problems: primes, GCD/LCM, Armstrong, palindromes, Floyd and Pascal triangles.
- `lab/05-arrays.html`: **Lab 05 · Arrays**. Input and print, sum, second largest, copy, insert, delete, reverse, linear search and sorting.
- `lab/06-array-practice.html`: **Lab 06 · Array Practice: 40 Problems**. Counting, searching, frequency, duplicates, merging, rotation and sorting, each with sample input and output.
- `lab/07-strings.html`: **Lab 07 · Strings**. Length, copy, concatenation, comparison, reverse and palindrome, with and without <string.h>.
- `lab/08-functions-recursion.html`: **Lab 08 · Functions and Recursion**. Cube, circle, max/min, prime/Armstrong/perfect checks, then recursive factorial, Fibonacci and array sum.
- `lab/09-pointers.html`: **Lab 09 · Pointers**. Addresses, pointer variables, arithmetic through pointers, swap by pointer and arrays through pointers.

## How the step-through works

Every C program was compiled with `gcc -g -O0` and executed under GDB, which recorded the line, the call stack, all variables and the console before each line. The pages replay those recordings, so values, addresses and output are real.

Keyboard: ← and → step backwards and forwards when a program viewer has focus.

## Copyright

© 2026 Md Nazrul Islam [NI]. All rights reserved. Shared with students for study purposes only. Do not modify, republish or redistribute without the author's permission.
