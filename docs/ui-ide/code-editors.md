---
layout: default
title: Code Editors
parent: IDEs & Code Editors
nav_order: 3
---

# Code Editors
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Atom

Website: [https://atom.io/](https://atom.io/)

Available on all platforms, Atom is billed as the “hackable text editor for the 21st Century.” With a sleek interface, file system browser, and marketplace for extensions, open-source Atom is built using Electron, a framework for creating desktop applications using JavaScript, HTML, and CSS. Python language support is provided by an extension that can installed when Atom is running.

![atom](../../../assets/images/atom.png)

**Pros**: It has broad support on all platforms, thanks to Electron. Atom is small, so it downloads and loads fast.

**Cons**: Build and debugging support aren’t built-in but are community provided add-ons. Because Atom is built on Electron, it’s always running in a JavaScript process and not as a native application.


## Sublime Text

Website: [http://www.sublimetext.com](http://www.sublimetext.com)

Written by a Google engineer with a dream for a better text editor, Sublime Text is an extremely popular code editor. Supported on all platforms, Sublime Text has built-in support for Python code editing and a rich set of extensions (called packages) that extend the syntax and editing features.

Installing additional Python packages can be tricky: all Sublime Text packages are written in Python itself, and installing community packages often requires you to execute Python scripts directly in Sublime Text.

![sublime-text](../../../assets/images/sublime-text.png)

**Pros**: Sublime Text has a great following in the community. As a code editor, alone, SublimeText is fast, small, and well supported.

**Cons**: Sublime Text is not free, although you can use the evaluation version for an indefinite period of time. Installing extensions can be tricky, and there’s no direct support for executing or debugging code from within the editor.


## Visual Studio Code

Website: [https://code.visualstudio.com/](https://code.visualstudio.com/)

Python tools: [https://marketplace.visualstudio.com/items?itemName=ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

Not to be confused with full Visual Studio, Visual Studio Code (aka VS Code) is a full-featured code editor available for Linux, Mac OS X, and Windows platforms. Small and light-weight, but full-featured, VS Code is open-source, extensible, and configurable for almost any task. Like Atom, VS Code is built on Electron, so it has the same advantages and disadvantages that brings.

Installing Python support in VS Code is very accessible: the Marketplace is a quick button click away. Search for Python, click Install, and restart if necessary. VS Code will recognize your Python installation and libraries automatically.

![visual-studio-code](../../../assets/images/visual-studio-code.png)

**Pros**: Thanks to Electron, VS Code is available on every platform, surprisingly full-featured despite having a small footprint, and open-source.

**Cons**: Electron means VS Code is not a native app. Plus, some people may have principled reasons to not use Microsoft resources.

[RealPython.com](https://realpyhton.com) has a [tutorial](https://realpython.com/python-development-visual-studio-code/) and [companion video course](https://realpython.com/courses/python-development-visual-studio-code-setup-guide/) on using Visual Studio Code for Python development.

---

{: .fs-1 .fw-300 }

_Article information was pulled from Ficher, John. Python IDEs and Code Editors Guide (2019).
In Real Python. Retrieved December 11, 2019 from https://realpython.com/python-ides-code-editors-guide._
