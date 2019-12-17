---
layout: default
title: Constants
parent: Programming Basics
nav_order: 6
---

# Constants
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Overview

A constant is a value that cannot be altered by the program during normal execution, i.e., the value is constant or immutable. When associated with an identifier, a constant is said to be “named,” although the terms “constant” and “named constant” are often used interchangeably.[<sub>\[1\]</sub>](#references)

## Understanding Constants

A constant is a data item whose value cannot change during the program’s execution. Thus, as its name implies – the value is constant.[<sub>\[2\]</sub>](#references)

Constants are used in two ways. They are:

* literal constant
* named constant

A literal constant is a value you type into your program wherever it is needed. Examples could be typing your name when prompted or entering a menu selection number from the keyboard. A named constant will have an identifier name and the constant value assigned to it. Every programming language will have it own paradigm with handling constants.

## Defining Constants

Named constants must be assigned a value when they are defined.[<sub>\[2\]</sub>](#references) Many programming languages use ALL CAPS to define named constants so they are easy to identify when reading code.

## Examples of Constants

__Python__

<div class="code-example" markdown="1">
```python
print('Hello World');
```
</div>

In the example above, the constant value is `Hello World` is a literal constant. Each time the statement executes, it will display the same message.

<div class="code-example" markdown="1">
```python
PI = 3.14159;
```
</div>

In this example, the constant name is `PI` and the constant value is `3.14159`. Technically, Python does not support named constants, meaning that it is possible (but never good practice) to change the value of a constant later. There are workarounds for creating constants in Python, but they are for more advanced topics.[<sub>\[2\]</sub>](#references)

__Java__

<div class="code-example" markdown="1">
```java
private static final double PI = 3.14159;
```
</div>

In the example above, the constant name is `PI` and the constant value is `3.14159`. Java identifies a constant with the `final` keyword. The keyword `double` is a data type assignment indicating a number with decimals.

__C/C++__

<div class="code-example" markdown="1">
```c
#define PI 3.14159;
```
</div>

In the example above, the constant name is `PI` and the constant value is `3.14159`. C/C++ identifies a constant with the `define` keyword. There is also alternative keyword called `const` that can be used.

__JavaScript__

<div class="code-example" markdown="1">
```javascript
const double PI = 3.14159;
```
</div>

In the example above, the constant name is `PI` and the constant value is `3.14159`. JavaScript identifies a constant with the `const` keyword. The keyword `double` is a data type assignment indicating a number with decimals.

## Key Terms

* _constant_ - Something that does not or cannot change or vary.[<sub>\[3\]</sub>](#references)
* _immutable_ - Not mutable; unchangeable; changeless.[<sub>\[3\]</sub>](#references)
* _statement_ - A single sentence or assertion.[<sub>\[3\]</sub>](#references)
* _keyword_ - A word that serves as a key, as to the meaning of another word, a sentence, passage, or the like.[<sub>\[3\]</sub>](#references)

---

### [References](#references)

1. [Wikipedia: Constant (computer programming)](https://en.wikipedia.org/wiki/Constant_(computer_programming))
2. [Rebus: Constants and Variables)](https://press.rebus.community/programmingfundamentals/chapter/constants-and-variables/)
3. [Dictionary.com: Definitions](https://dictionary.com)
