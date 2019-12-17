---
layout: default
title: Operators
parent: Programming Basics
nav_order: 3

---

# Operators
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Overview

Operators are symbols that tell the compiler to perform specific mathematical or logical manipulations.[<sub>\[1\]</sub>](#references)

## Understanding Operators

First, let's categorize them:
1. Arithmetic
2. Relational
3. Bitwise
4. Logical
5. Assignment
6. Increment

Keep in mind that all listed operators may or may not be used with a specific programming language.
{: .label .label-yellow }

### Arithmetic Operators[<sub>\[1\]</sub>](#references)

| Symbol   | Operation       | Usage   | Explanation                                                                   |
|:---------|:----------------|:--------|:------------------------------------------------------------------------------|
| `+`      | addition        | `x + y` | Adds values on either side of the operator                                    |
| `-`      | subtraction     | `x - y` | Subtracts the right hand operand from the left hand operand                   |
| `*`      | multiplication  | `x * y` | Multiplies values on either side of the operator                              |
| `/`      | division        | `x / y` | Divides the left hand operand by the right hand operand                       |
| `%`      | modulus         | `x % y` | Divides the left hand operand by the right hand operand and returns remainder |

### Relational Operators[<sub>\[1\]</sub>](#references)

These operators are used for comparison. They return either true or false based on the comparison result. The operator '==' should not be confused with '='. The relational operators are as follows:

| Symbol   | Operation             | Usage    | Explanation                                                                                                                            |
|:---------|:----------------------|:---------|:---------------------------------------------------------------------------------------------------------------------------------------|
| `==`     | equal                 | `x == y` | Checks if the values of two operands are equal or not, if yes then condition becomes true.                                             |
| `!=`     | not equal             | `x != y` | Checks if the values of two operands are equal or not, if values are not equal then condition becomes true.                            |
| `>`      | greater than          | `x > y`  | Checks if the value of the left operand is greater than the value of the right operand, if yes then condition becomes true.            |
| `<`      | less than             | `x < y`  | Checks if the value of the left operand is less than the value of the right operand, if yes then condition becomes true.               |
| `>=`     | greater than or equal | `x >= y` | Checks if the value of the left operand is greater than or equal to the value of the right operand, if yes then condition becomes true.|
| `<=`     | less than or equal    | `x <= y` | Checks if the value of the left operand is less than or equal to the value of the right operand, if yes then condition becomes true.   |

### Bitwise Operators[<sub>\[1\]</sub>](#references)

These operators are very useful and we have some tricks based on these operators. These operators convert the given integers into binary and then perform the required operation, and give back the result in decimal representation.

| Symbol   | Operation   | Usage    | Explanation                                                                                                                                     |
|:---------|:------------|:---------|:------------------------------------------------------------------------------------------------------------------------------------------------|
| `&`	     | bitwise AND | `x & y`  | Sets the bit to the result if it is set in both operands.                                                                                       |
| `^`	     | bitwise XOR | `x ^ y`  | Sets the bit if it is set in one operand but not both                                                                                           |
| `|`      | bitwise OR	 | `x | y`  | Sets the bit to the result if it is set in either operand.                                                                                      |
| `~`	     | bitwise NOT | `~x`	    | Unary operator and has the effect of 'flipping' bits, i.e., flips 1 to 0 and 0 to 1.                                                            |
| `<<`	   | left shift  | `x << y` | The left operand's value is moved left by the number of bits specified by the right operand. It is equivalent to multiplying x by 2<sup>y</sup> |
| `>>`	   | right shift | `x >> y` | The left operand's value is moved right by the number of bits specified by the right operand. It is equivalent to dividing x by 2<sup>y</sup>   |

For more information about how these operators work, see : [Bit Manipulation](https://en.wikipedia.org/wiki/Bit_manipulation)


### Logical Operators[<sub>\[1\]</sub>](#references)

These operators take boolean values as input and return boolean values as output.
Note: Each programming language will have own set of logical operators In C, C++ and Java, the operators are symbolic. Python uses mnemonic identifiers of `AND`, `OR` and `NOT`.

| Symbol   | Operation   | Usage    | Explanation                                                    |
|:---------|:------------|:---------|:---------------------------------------------------------------|
| `&&`     | logical AND | `x && y` | Returns true if both x and y are true else returns false.      |
| `|`      | logical OR  | `x || y` | Returns false if neither x nor y is true else returns true.    |
| `!`      | logical NOT | `! x`    | Unary operator. Returns true if x is false else returns false. |

### Assignment Operators[<sub>\[1\]</sub>](#references)

An assignment operator is the operator used to assign a new value to a variable, property, event or indexer element.

| Symbol   | Operation                  | Usage             | Explanation                                                                                                  |
|:---------|:---------------------------|:------------------|:-------------------------------------------------------------------------------------------------------------|
| `=`      | assignment                 |	`x = y`           | Assigns value from the right side operand(s) to the left side operand.                                       |
| `+=`     | add and assignment         |	`x += y	x = x+y`  |	Adds the right side operand to the left side operand and assigns the result to the left side operand.        |
| `-=`     | subtract and assignment    |	`x -= y	x= x-y`   |	Subtracts the right side operand from the left side operand and assigns the result to the left side operand. |
| `*=`     | multiply and assignment    |	`x *= y	x= x*y`   | Multiplies the right side operand with the left side operand and assigns the result to the left side operand.|
| `/=`     | divide and assignment      |	`x /= y	x= x/y`   | Divides the left side operand with the right side operand and assigns the result to the left side operand.   |
| `%=`     | modulus and assignment     |	`x%=y	x= x%y`     | Takes modulus using the two operands and assigns the result to the left side operand.                        |
| `<<=`    | left shift and assignment  |	`x<<=y	x= x<< y` | Shifts the value of x by y bits towards the left and stores the result back in x.                            |
| `>>=`    | right shift and assignment |	`x>>=y	x= x>>y`  | Shifts the value of x by y bits towards the right and stores the result back in x.                           |
| `&=`     | bitwise AND and assignment |	`x&=y	x= x&y`     | Does x&y and stores result back in x.                                                                        |
| `|=`     | bitwise OR and assignment  |	`x|=y	x= x|y`     | Does x\|y and stores result back in x                                                                         |
| `^=`     |bitwise XOR and assignment  |	`x^=y	x= x^y`     | Does x^y and stores result back in x.                                                                        |

### Increment/Decrement Operators[<sub>\[1\]</sub>](#references)

These are unary operators. Unary operators are the operators which require only one operand.

| Symbol   | Operation     | Usage    | Explanation                                                    |
|:---------|:--------------|:---------|:---------------------------------------------------------------|
| `++`     | Postincrement | `x++`    | Increment x by 1 after using its value                         |
| `--`     | Postdecrement | `x--`    | Decrement x by 1 after using its value                         |
| `++`     | Preincrement  | `++x`    | Increment x by 1 before using its value                        |
| `--`     | Predecrement  | `--x`    | Decrement x by 1 before using its value                        |

## Key Terms

* _operator_ - A symbol or function denoting an operation (e.g. ×, +).[<sub>\[2\]</sub>](#references)

---

### [References](#references)

1. [Hacker Earth: Operators](https://www.hackerearth.com/practice/basic-programming/operators/basics-of-operators/tutorial/)
2. [Oxford Dictionary: Operator](https://www.lexico.com/en/definition/operator)
