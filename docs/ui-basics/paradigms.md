---
layout: default
title: Paradigms
parent: Programming Basics
nav_order: 1
---

# Programming Paradigms
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Overview

“If I had more time, I would have written a shorter letter.” This witticism, sometimes attributed to Blaise Pascal, is surprising because we assume that, in writing, more time translates to more words and greater length.

There exists a similar paradox in programming. Programs with great complexity, with many moving parts and interdependent components, seem initially impressive. However, the ability to translate a real-world problem into a simple or elegant solution requires deep understanding. When writing code, therefore, we might say, “If I had more time, I would have written a simpler program.”

Unlike a bridge, a road, an office building, or some other physical construction, the only limiting factor when writing a program is cognition—the time, attention, and understanding of the programmer. For this reason, when programming, complexity is always the enemy. The more complex a program becomes, the harder it is to work with and reason about. Managing complexity is, arguably, a programmer’s main concern.

A major source of complexity in a program is “state”—basically, what a program has to keep track of as it moves forward through time. If parts of your program refer to, or change, a variable, the program can easily get into an untenable state. If you’ve ever wondered why turning your computer on and off again solves so many problems, the answer is state. If you reset the state of your machine’s memory, you’ve also resolved any ongoing state-based conflicts.

So how do programmers deal with complexity? There are many general approaches that reduce complexity in a program or make it more manageable, and arguably most of the major innovations in programming are concerned with this question. Here, though, we’ll discuss some broad approaches to managing complexity and, specifically, state. These approaches are called programming paradigms.[<sub>\[1\]</sub>](#references)

## Understanding Paradigms

Paradigms can essentially be thought of as a way to classify programming languages into different groups. It is from these groups we can see characteristics of different languages and what functions they would be best at performing. There are many paradigms, but I will talk about two of the main ones: Imperative vs. Declarative.

### Declarative

Declarative programming is one of the many paradigms of computer programming. The main principle of this paradigms is that the programmer declares/describes properties of the result but not actually how to compute for the result. In essence, the program will be described to it what should be accomplished but not how to do it. By doing this, the structures and elements of programs are built which express the logic of computation. This has made the process of parallel computing much easier in recent years. Thus, allowing computers to divide huge problems into smaller ones by doing many calculations simultaneously. However, this is still too general so there are sub-paradigms within declarative:

* Functional-a style of building the structure and elements of programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
* Logic- a paradigm in which program statements express facts and rules about problems within a system of formal logic
* Constraint- a paradigm wherein relations between variables are stated in the form of constraints
* Dataflow- models a program as a directed graph of the data flowing between operations implementing dataflow principles and architecture.
* Ontology- more of a language type in which formal languages are used to form ontologies(representation, formal naming and definition of the categories, properties and relations between the concepts, data and entities that substantiate one, many or all domains of discourse).

While declarative programming is certainly powerful this is not the type of programming the average person thinks about. Usually, the average software engineer follows the idea of imperative programming -specifically object oriented programming.[<sub>\[2\]</sub>](#references)

#### Declarative Languages

* Analytica
* C++
* C#
* ECL (data-centric programming language)
* F#
* Gremlin
* Lustre
* Mercury
* Oz
* RDQL
* SequenceL
* SPARQL
* SQL
* Wolfram Language
* XSL Transformations

### Imperative

Imperative programming is what the average person will think of when they think of software development or engineering. It is a paradigm that uses statements that change a program’s state. This contrasts declarative programming which describes “what” a program should accomplish, imperative programming explicitly tells the computer “how” to accomplish it. Most hardware is written to with this paradigm and even machine code uses this method of development when it is written. This is the paradigm used for application development around the world and the stereotypical idea of development. Since it is used so widely once again there are sub-paradigms to imperative programming:

* Procedural- the concept of the calling routines, subroutines, or functions(procedures). These simply contain a series of computational steps to be carried out. Any procedure can be called at any point during a program’s execution, including by other procedures or itself.
* Object-Oriented(O.O.P.)- termed by Alan Kay-based on the concept of objects, which can contain data, in the form of fields (attributes or properties), and code, in the form of methods (procedures). In this paradigm code can be structured as reusable components, some of which may share properties or behaviors.

Both imperative(specifically O.O.P.) and declarative programming are taught in school and useful in their own ways. However, each programming language is not necessarily just one paradigm. In fact, many languages multi-paradigm and can do both imperative and declarative functions.[<sub>\[2\]</sub>](#references)

#### Imperative Languages

* C++
* C#
* COBOL
* FORTRAN
* F#
* Groovy
* Java
* Julia
* MATLAB
* Machine language
* OCaml
* Pascal
* Perl
* PHP
* Python
* Ruby
* Swift
* Wolfram Language

---

### [References](#references)

1. [Digital Fellows: Into to Paradigms](https://digitalfellows.commons.gc.cuny.edu/2018/03/12/an-introduction-to-programming-paradigms/)
2. [Towards Data Science: Paradigms](https://towardsdatascience.com/computer-programming-c5e5793eb250)
