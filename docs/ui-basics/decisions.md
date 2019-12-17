---
layout: default
title: Decisions
parent: Programming Basics
nav_order: 7
---

# Decisions
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Overview

Decision making structures require that the programmer specify one or more conditions to be evaluated or tested by the program, along with a statement or statements to be executed, if the condition is determined to be true, and optionally, other statements to be executed if the condition is determined to be false.[<sub>\[1\]</sub>](#references) In alternative texts, decisions are also known as conditions or conditionals. The key concept is using a boolean condition to direct or alter control flow.

Most programming languages are equipped with specific statements that allow to check a condition and execute certain parts of code depending on whether the condition is true or false. Such statements are called conditional, and are a form of composite statement.

## Understanding Decisions

Following is the general form of a typical decision making structure found in most of the programming languages −

## if..then Construct

An if...then statement consists of a logical expression followed by one or more statements and terminated by an end if statement. If the logical expression evaluates to true, then the block of code inside the if...then statement will be executed. If logical expression evaluates to false, then the first set of code after the end if statement will be executed.[<sub>\[2\]</sub>](#references)

```
if (logical expression) then
    (statement(s))
end if
```

![if-then](../../../assets/images/if-then.jpg)


## if...then...else Statement

An if...then statement can be followed by an optional else statement, which executes when the logical expression is false. If the logical expression evaluates to true, then the block of code inside the if…then statement will be executed, otherwise the block of code inside the else block will be executed.[<sub>\[3\]</sub>](#references)

```
if (logical expression) then
    (statement(s))
else
    (alternative statement(s))
end if
```

![if-then](../../../assets/images/if-then-else.jpg)


## if...then...else...else construct

An if statement construct can have one or more optional else-if constructs. When the if condition fails, the immediately followed else-if is executed. When the else-if also fails, its successor else-if statement (if any) is executed, and so on. This structure is also known as a nested-if.

The optional else is placed at the end and it is executed when none of the above conditions hold true.
* All else statements (else-if and else) are optional.
* else-if can be used one or more times.
* else must always be placed at the end of construct and should appear only once.[<sub>\[4\]</sub>](#references)

```
if (logical expression 1) then
    (statement block 1)
else if (logical expression 2) then
    (statement block 2)
else if (logical expression 3) then
    (statement block 3)
else
    (statement block 4)
end if
```

## Examples of Decisions

__Python__

<div class="code-example" markdown="1">
```python
a = 200
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")
```
</div>

__Java__

<div class="code-example" markdown="1">
```java
int a = 200;
int b = 33;
if (b > a) {
  System.out.println("b is greater than a");
} else if (a == b) {
  System.out.println("a and b are equal");
} else {
  System.out.println("a is greater than b");
}
```
</div>

__C/C++__

<div class="code-example" markdown="1">
```c++
int a = 200;
int b = 33;
if (b > a) {
  cout << "b is greater than a";
} else if (a == b) {
  cout << "a and b are equal";
} else {
  cout << "a is greater than b";
}
```
</div>

__JavaScript__

<div class="code-example" markdown="1">
```javascript
var a = 200;
var b = 33;
if (b > a) {
  result = "b is greater than a";
} else if (a == b) {
  result = "a and b are equal";
} else {
  result = "a is greater than b";
}
```
</div>

## Key Terms

* _decision_ - The action or process of deciding something or of resolving a question.[<sub>\[5\]</sub>](#references)
* _pseudocode_ - A notation resembling a simplified programming language, used in program design.[<sub>\[6\]</sub>](#references)
* _control flow_ - The order in which the instructions of a program are executed.[<sub>\[7\]</sub>](#references)

---

### [References](#references)

1. [TutorialsPoint: Decisions](https://www.tutorialspoint.com/fortran/fortran_decisions.htm)
2. [TutorialsPoint: if-then](https://www.tutorialspoint.com/fortran/If_then_construct.htm)
3. [TutorialsPoint: if-then-else](https://www.tutorialspoint.com/fortran/If_then_else_construct.htm)
4. [TutorialsPoint: if-then-if-else](https://www.tutorialspoint.com/fortran/if_elseif_else_construct.htm)
5. [Oxford Dictionary: Decision](https://www.lexico.com/en/definition/decision)
6. [Oxford Dictionary: Pseudocode](https://www.lexico.com/en/definition/pseudocode)
7. [Oxford Dictionary: Control Flow](https://www.lexico.com/en/definition/control_flow)
