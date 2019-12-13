---
layout: default
title: IDEs & Code Editors
nav_order: 3
has_children: true
has_toc: false
permalink: /docs/ui-ides
---

# IDEs and Code Editors
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What Are IDEs and Code Editors?

An IDE (or Integrated Development Environment) is a program dedicated to software development. As the name implies, IDEs integrate several tools specifically designed for software development. These tools usually include:

An editor designed to handle code (with, for example, syntax highlighting and auto-completion)
Build, execution, and debugging tools
Some form of source control
Most IDEs support many different programming languages and contain many more features. They can, therefore, be large and take time to download and install. You may also need advanced knowledge to use them properly.

In contrast, a dedicated code editor can be as simple as a text editor with syntax highlighting and code formatting capabilities. Most good code editors can execute code and control a debugger. The very best ones interact with source control systems as well. Compared to an IDE, a good dedicated code editor is usually smaller and quicker, but often less feature rich.

To make it as easy as possible to write documentation in plain Markdown, most UI components are styled using default Markdown elements with few additional CSS classes needed.


## Requirements for a Good Python Coding Environment

So what things do we really need in a coding environment? Feature lists vary from app to app, but there are a core set of features that makes coding easier:

* Save and reload code files
* If an IDE or editor won’t let you save your work and reopen everything later, in the same state it was in when you left, it’s not much of an IDE.
* Run code from within the environment
* Similarly, if you have to drop out of the editor to run your Python code, then it’s not much more than a simple text editor.
* Debugging support
* Being able to step through your code as it runs is a core feature of all IDEs and most good code editors.
* Syntax highlighting
* Being able to quickly spot keywords, variables, and symbols in your code makes reading and understanding code much easier.
* Automatic code formatting
* Any editor or IDE worth it’s salt will recognize the colon at the end of a while or for statement, and know the next line should be indented.

Of course, there are lots of other features you might want, like source code control, an extension model, build and test tools, language help, and so on. But the above list is what I’d see as “core features” that a good editing environment should support.


## Which Python IDE is Right for You?

Only you can decide that, but here are some basic recommendations:

* New Python developers should try solutions with as few customizations as possible. The less gets in the way, the better.
* If you use text editors for other tasks (like web pages or documentation), look for code editor solutions.
* If you’re already developing other software, you may find it easier to add Python capabilities to your existing toolset.

{: .fs-1 .fw-300 }

_Article information was pulled from Ficher, John. Python IDEs and Code Editors Guide (2019).
In Real Python. Retrieved December 11, 2019 from https://realpython.com/python-ides-code-editors-guide._
