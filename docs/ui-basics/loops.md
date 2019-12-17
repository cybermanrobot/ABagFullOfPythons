---
layout: default
title: Loops
parent: Programming Basics
nav_order: 8
---

# Constants
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Overview

In computer science, a loop is a programming structure that repeats a sequence of instructions until a specific condition is met. Programmers use loops to cycle through values, add sums of numbers, repeat functions, and many other things.[<sub>\[1\]</sub>](#references)

## Understanding Loops

Loops are supported by all modern programming languages, though their implementations and syntax may differ. Two of the most common types of loops are the while loop and the for loop.[<sub>\[1\]</sub>](#references)

### While Loop

A while loop is the simplest form of a programming loop. It states that while a condition is valid, keep looping.[<sub>\[1\]</sub>](#references) The while construct consists of a block of code and a condition/expression. The condition/expression is evaluated, and if the condition/expression is true, the code within all of their following in the block is executed. This repeats until the condition/expression becomes false. Because the while loop checks the condition/expression before the block is executed, the control structure is often also known as a pre-test loop.[<sub>\[2\]</sub>](#references)

![while loop](../../../assets/images/while-loop.png)

### For Loop

A for loop is similar to a while loop, but streamlines the source code. The for loop statement defines the start and end point as well as the increment for each iteration. Below is the same loop above defined as a while loop.[<sub>\[1\]</sub>](#references) A for-loop has two parts: a header specifying the iteration, and a body which is executed once per iteration. The header often declares an explicit loop counter or loop variable, which allows the body to know which iteration is being executed. For-loops are typically used when the number of iterations is known before entering the loop. For-loops can be thought of as shorthands for while-loops which increment and test a loop variable.[<sub>\[4\]</sub>](#references)

![for loop](../../../assets/images/for-loop.png)

## Examples of Loops

__Python__

<div class="code-example" markdown="1">
```python
# while loop; the output will be numbers 1, 2, 3, 4, and 5 on separate lines
i = 1
while i < 6:
  print(i)
  i += 1

# for loop; the output will be strings b, a, n, a, n, a on separate lines

for x in "banana":
  print(x)

```
</div>

__Java__

<div class="code-example" markdown="1">
```java
// while loop; the output will be numbers 0, 1, 2, 3, and 4 on separate lines
int i = 0;
while (i < 5) {
  System.out.println(i);
  i++;
}

// for loop; the output will be numbers 0, 1, 2, 3, and 4 on separate lines
for (int i = 0; i < 5; i++) {
  System.out.println(i);
}
```
</div>

__C/C++__

<div class="code-example" markdown="1">
```c++
// while loop; the output will be numbers 0, 1, 2, 3, and 4 on separate lines
int a = 0;
while( a < 5 ) {
   cout << a << endl;
   a++;
}

// for loop; the output will be numbers 0, 1, 2, 3, and 4 on separate lines
for( int a = 0; a < 5; a = a + 1 ) {
   cout << a << endl;
}
```
</div>

__JavaScript__

<div class="code-example" markdown="1">
```javascript
// while loop; the output will be numbers 0, 1, 2, 3, and 4 on separate lines
var text = "";
var i = 0;
while (i < 5) {
  text += i;
  i++;
}

// for loop; the output will be numbers 0, 1, 2, 3, and 4 on separate lines
for (i = 0; i < 5; i++) {
  text += i + "<br>";
}
```
</div>

## Key Terms

* _loop_ - A programming structure that repeats a sequence of instructions until a specific condition is met.[<sub>\[1\]</sub>](#references)

---

### [References](#references)

1. [TechTerms: Loop](https://techterms.com/definition/loop)
2. [Wikipedia: While Loop](https://en.wikipedia.org/wiki/While_loop)
3. [Wikipedia: For Loop ](https://en.wikipedia.org/wiki/For_loop)
