---
layout: default
title: Variables
parent: Programming Basics
nav_order: 5
---

# Variables
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Overview

The most simple form of storage is called a variable. It's an area of memory that stores one item of data, such as a number or a character. They have two purposes - the programmer is able to choose the names of the variables, making programming easier, and also, you can write programs or functions that will work with any values. If you're familiar with spreadsheets already, you can think of variables as being like the cells, which you can then use in formulae regardless of the values they contain. All procedural programming languages, such as C, BASIC and Pascal, have variables, although they may support different types and let you manipulate them in different ways.[<sub>\[1\]</sub>](#references)

## Understanding Variables

An important attribute of a variable is its lifecycle or scope. A variable's scope determines where in a program a variable is available for use. A scope is defined by where the variable is initialized or created. In the Python example below, the variable `var_x` has been defined in two locations in the sample program. The first is in the function called `somefuntion()` and the second is main section of the program. When the function is called, the value of 5 will be displayed in the console. However, when the second print statement executes, the program will get a syntax error. Why, you ask? The `var_x` variable defined in function `somefunction()` is called a local variable. Local variables only exist when the function is executed and then are cleared when the function terminates. So when the second print statement executes, the interpreter cannot find the memory area for the name `var_x` and tosses a syntax error.

<div class="code-example" markdown="1">
```python
def somefunction():
  var_x = 5
  print(var_x)

somefunction()
print(var_x)
```
</div>

Before we move on, you should be aware that there are five types of variables. Constants, global variables, class variables, instance variables, and local variables. While you should not worry too much about these topics in depth yet, here is a brief description of each.

* Constants - Used for storing data that never needs to change.
* Global variables - Variables available throughout your entire app, overriding all scope boundaries. Use carefully.
* Class variables - Variables are accessible by instances of your class, as well as the class itself. Used in object-oriented programming.
* Instance variables - Variables available throughout the current instance of the parent class.
* Local variables - Local variables are the most common variables you will use and obey all scope boundaries.

## Defining Variables

Some languages are strongly typed, whereas others aren't typed at all. Some require that you declare a variable before you use it, and others let you go straight in and define a variable's value without declaring it first. Declaring a variable gives the variable a name, and, in most programming languages, gives it a type - in effect it creates the container that stores your value.[<sub>\[1\]</sub>](#references)

Naming variables is known as one of the most difficult tasks in computer programming. When you are naming variables, think hard about the names. Try your best to make sure that the name you assign your variable is accurately descriptive and understandable to another reader. Sometimes that other reader is yourself when you revisit a program that you wrote months or even years earlier.

When you assign a variable, you use the `=` symbol. The name of the variable goes on the left and the value you want to store in the variable goes on the right.[<sub>\[2\]</sub>](#references)

## Examples of Variables

__Python__

<div class="code-example" markdown="1">
```python
width = 10
```
</div>

In the example above, the variable name is `width` and the value is `10`. Python is not strongly typed with variables. This means that you can reassign a string, object or another variable to `width`.

__Java__

<div class="code-example" markdown="1">
```java
int width = 10;
```
</div>

In the example above, the variable name is `width` and the value is `10`. Java uses strong types for variables meaning that only values of the same type can be assigned. For `width`, only integers can be assigned else the compiler will toss a syntax error.

__C/C++__

<div class="code-example" markdown="1">
```c
int width = 10;
```
</div>

In the example above, the variable name is `width` and the value is `10`. C/C++ uses strong types for variables.

__JavaScript__

<div class="code-example" markdown="1">
```javascript
var width = 10;
```
</div>

In the example above, the variable name is `width` and the value is `10`. JavaScript is not strongly typed with variables.

## Key Terms

* _variable_ - A quantity or function that may assume any given value or set of values..[<sub>\[3\]</sub>](#references)
* _scope_ - Refers to the visibility of variables. In other words, which parts of your program can see or use it.[<sub>\[4\]</sub>](#references)
* _function_ - A block of organized, reusable code that is used to perform a single, related action. [<sub>\[5\]</sub>](#references)
* _syntax error_ - A character or string incorrectly placed in a command or instruction that causes a failure in execution.[<sub>\[3\]</sub>](#references)

---

### [References](#references)

1. [Advanced ICT: Variables](https://www.advanced-ict.info/programming/variables.html)
2. [LaunchSchool: Variables](https://launchschool.com/books/ruby/read/variables)
3. [Dictionary.com: Definitions](https://dictionary.com)
4. [Cardiff School: Variables](https://users.cs.cf.ac.uk/Dave.Marshall/PERL/node52.html)
5. [TutorialsPoint: Functions](https://www.tutorialspoint.com/computer_programming/computer_programming_functions.htm)
