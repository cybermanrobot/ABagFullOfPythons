---
layout: default
title: Data Types
parent: Programming Basics
nav_order: 4
---

# Data Types
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Overview

The data type of a value (or variable in some contexts) is an attribute that tells what kind of data that value can have. Most often, the term is used in connection with static typing of variables in programming languages like C/C++, Java, C#, etc., where the type of a variable is known at compile time. Data types include the storage classifications like integers, floating-point values, strings, characters, etc.

Data types define particular characteristics of data used in software programs and inform the compilers about predefined attributes required by specific variables or associated data objects.[<sub>\[1\]</sub>](#references)

## Understanding Data types

A software program may create many variables and objects that correspond to different program completion aspects. For example, a payroll program may include employee variables such as name, identification/Social Security numbers, and contact information, wherein each variable will contain different data types. A Social Security number variable consists of characters, creating an integer data type variable, whereas an employee name variable is solely comprised of alpha characters, creating a character data type variable. Each variable is initialized with a data type during coding to inform the compiler about the expected variable data. Initialization is also necessary because each data type has different characteristics that require preallocated space and memory.

Every language uses data types and some languages will have their own unique or proprietary data types. The most common data types include:

* Integer
* Floating-point number
* Character
* String
* Boolean

## Basic Data Type: Integer

An integer is a whole number (not a fraction) that can be positive, negative, or zero. Therefore, the numbers 10, 0, -25, and 5,148 are all integers. Unlike floating point numbers, integers cannot have decimal places.

Integers are a commonly used data type in computer programming. For example, whenever a number is being incremented, such as within a "for loop" or "while loop," an integer is used. Integers are also used to determine an item's location within an array.

When two integers are added, subtracted, or multiplied, the result is also an integer. However, when one integer is divided into another, the result may be an integer or a fraction. For example, 6 divided by 3 equals 2, which is an integer, but 6 divided by 4 equals 1.5, which contains a fraction. Decimal numbers may either be rounded or truncated to produce an integer result.[<sub>\[2\]</sub>](#references)

## Basic Data Type: Floating-point Number

As the name implies, floating point numbers are numbers that contain floating decimal points. For example, the numbers 5.5, 0.001, and -2,345.6789 are floating point numbers. Numbers that do not have decimal places are called integers.

Computers recognize real numbers that contain fractions as floating point numbers. When a calculation includes a floating point number, it is called a "floating point calculation." Older computers used to have a separate floating point unit (FPU) that handled these calculations, but now the FPU is typically built into the computer's CPU.[<sub>\[3\]</sub>](#references)

## Basic Data Type: Character

A character is any letter, number, space, punctuation mark, or symbol that can be typed on a computer. The word "computer," for example, consists of eight characters. The phrase "Hi there." takes up nine characters. Each character requires one byte of space, so "computer" takes up 8 bytes. The list of characters that can be typed is defined by the ASCII and extended ASCII set. Some of the symbols available are pretty strange and may even make you say, "That's quite a character!"[<sub>\[4\]</sub>](#references)

## Basic Data Type: String

A string is a data type used in programming, such as an integer and floating point unit, but is used to represent text rather than numbers. It is comprised of a set of characters that can also contain spaces and numbers. For example, the word "hamburger" and the phrase "I ate 3 hamburgers" are both strings. Even "12345" could be considered a string, if specified correctly. Typically, programmers must enclose strings in quotation marks for the data to recognized as a string and not a number or variable name.[<sub>\[4\]</sub>](#references)

For example, in the comparison:

if (Option1 == Option2) then ...

Option1 and Option2 may be variables containing integers, strings, or other data. If the values are the same, the test returns a value of true, otherwise the result is false. In the comparison:

if ("Option1" == "Option2") then ...

Option1 and Option2 are being treated as strings. Therefore the test is comparing the words "Option1" and "Option2," which would return false. The length of a string is often determined by using a null character.[<sub>\[5\]</sub>](#references)

## Basic Data Type: Boolean

Boolean, or boolean logic, is a subset of algebra used for creating true/false statements. Boolean expressions use the operators AND, OR, XOR, and NOT to compare values and return a true or false result. These boolean operators are described in the following four examples:

* x AND y - returns True if both x and y are true; returns False if either x or y are false.
* x OR y - returns True if either x or y, or both x and y are true; returns False only if x and y are both false.
* x XOR y - returns True if only x or y is true; returns False if x and y are both true or both false.
* NOT x - returns True if x is false (or null); returns False if x is true.

Since computers operate in binary (using only zeros and ones), computer logic can often expressed in boolean terms. For example, a true statement returns a value of 1, while a false statement returns a value of 0. Of course, most calculations require more than a simple true/false statement. Therefore, computer processors perform complex calculations by linking multiple binary (or boolean) statements together. Complex boolean expressions can be expressed as a series of logic gates.
Boolean expressions are also supported by most search engines. When you enter keywords in a search engine, you can refine your search using boolean operators. For example, if you want to look up information about the Apple iMac, but want avoid results about apples (the fruit) you might search for "Apple AND iMac NOT fruit." This would produce results about iMac computers, while avoiding results with the word "fruit." While most search engines support boolean operators, their syntax requirements may vary. For example, instead of the words AND and NOT, the operators "+" and "-" may be required. You can look up the correct syntax in the help section of each search engine's website.[<sub>\[6\]</sub>](#references)

## Examples of Basic Data Types

Please note the examples are of _basic data types_. Every language will have its own set of defined data types.
{: .label .label-yellow }

__Python__

<div class="code-example" markdown="1">
```python
max_points = 100   # integer (whole number)
point_deductions = -5 # integer (negative number)
score = 80.33 # floating-point
greeting = 'Have a good day!' # string
letter = 'a' # for character, Python treats the type as string
start = False # boolean
```
</div>

__Java__

<div class="code-example" markdown="1">
```java
int max_points = 100;   // integer (whole number)
int point_deductions = -5; // integer (negative number)
float score = 80.33;  // floating-point
String greeting = 'Have a good day!'; // string
char letter = 'a'; // character
boolean start = true; // boolean
```
</div>

Java has additional data types for numbers including byte, short, long and double.

__C/C++__

<div class="code-example" markdown="1">
```c
int max_points = 100   // integer (whole number)
int point_deductions = -5 // integer (negative number)
float score = 80.33  // floating-point
char letter = 'a' // character
```
</div>

The C language does not support string or boolean data types.

__JavaScript__

<div class="code-example" markdown="1">
```javascript
let max_points = 100;   // integer (whole number), JavaScript treats the type as number
let point_deductions = -5; // integer (negative number), JavaScript treats the type as number
let score = 80.33;  // floating-point, JavaScript treats the type as number
let greeting = 'Have a good day!'; // string
let letter = 'a'; // for character, JavaScript treats the type as string
let start = true; // boolean
```
</div>

## Key Terms

* _data type_ - A data storage format that can contain a specific type or range of values.[<sub>\[2\]</sub>](#references)
* _integer_ - One of the positive or negative numbers 1, 2, 3, etc., or zero.[<sub>\[7\]</sub>](#references)
* _floating-point_ - A decimal point whose location is not fixed, used especially in computer operations.[<sub>\[7\]</sub>](#references)
* _character_ - Any symbol, as a number, letter, punctuation mark, etc., that represents data and that, when encoded, is usable by a machine.[<sub>\[7\]</sub>](#references)
* _string_ - A linear sequence of symbols, words, characters, or bits that is treated as a unit.[<sub>\[7\]</sub>](#references)
* _boolean_ - Of or relating to a data type having two possible values representing “true” or “false.”[<sub>\[7\]</sub>](#references)

---

### [References](#references)

1. [Techopedia: Data Types](https://www.techopedia.com/definition/3349/data-type)
2. [TechTerms: Integer](https://techterms.com/definition/integer)
3. [TechTerms: Floating-point](https://techterms.com/definition/floatingpoint)
4. [TechTerms: Character](https://techterms.com/definition/character)
5. [TechTerms: String](https://techterms.com/definition/string)
6. [TechTerms: Boolean](https://techterms.com/definition/boolean)
7. [Dictionary.com: Definitions](https://dictionary.com)
