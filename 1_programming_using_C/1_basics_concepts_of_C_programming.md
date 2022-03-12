# Basic Concepts of C Programming
***
<br>

## Overview of C
***

### Some Facts
* Developed by Dennis Ritchie.
* C is a structured programming language.
* C supports functions that enables easy maintainability of code, by breaking large file into smaller modules.
* It is a low-level language.

### Header Files

* The files that are specified in the include section is called as header file.
* These are pre-compiled files that has some functions defined in them.
* We can call those program in our program by suppluing parameters.
* Header file is given an extension <code>.h</code>
* C source file is given an extension <code>.c</code>

### Main Function

* It is the entry point of the program.
* It is a compulsory for any C program.

## Data Types
***

1. Primitive data types
    * `int`    - integer type
    * `float`  - floating point type
    * `double` - provides double precision than float
    * `char`   - character type

2. Aggregate data types
    * `arrays`

3. User defined data types
    * `stucts` - collection of variables (can be of different types) under a single name
    * `enum`   - an enumeration type that consists of integral constants

## Rules for Naming Variables
***

1. Shouldn't be a reserved word like `int`.
2. Should start only with a letter or an underscore ( _ ).
3. Can contain letters, numbers and underscore. No other special characters are allowed (including space).

## Operators
***

1. Arithmetic : `+`, `-`, `*`, `/`, `%`
2. Relational : `<`, `>`, `<=`, `>=`, `==`, `!=`
3. Logical : `&&`, `||`, `!`
4. Bitwise : `&`, `|`
5. Assignment : `=`
6. Compound Assignment : `+=`, `*=`, `-=`, `/=`, `%=`, `&=`, `=`
7. Shift : `>>`, `<<`

## String Functions
***

1. `strlen(str)` - finds the length of the string
2. `strrev(str)` - reverses the string
3. `strcat(str1, str2)` - append `str2` to `str1`
4. `strcpy(str1, str2)` - copies the content of `str2` to `str1`
5. `strcmp(str1, str2)` - compares the two strings
6. `strcmpi(str1, str2)` - case insensitive comparison

## Numeric Functions
***

1. `pow(n, x)`
2. `ceil(1.3)` - returns 2
3. `floor(1.3)` - return 1
4. `abs(num)` - returns the absolute value
5. `log(x)`
6. `sin(x)`
7. `cos(x)`

## Function and Procedure

### Function
It is one among the fundamental thought in the computer programming. It is used to calculate something from a given input. The function program has a block of code that performs some specific tasks.

### Procedure
In programming a particular set of instructions or commands along known as a procedure. Counting on the programming language it is known as a procedure, subroutine, function or a subprogram.

### Difference between Function and Procedure
| Function | Procedure  |
|---|---|
| A function deals with an expression. | Whereas a procedure doesn't deal with an expression. |
| The function can be called by a procedure. | Whereas a procedure can't be called a function. |

## Type Def

* The `typedef` operator is used for creating alias of a data type.
* For example : `typedef int integer;`

