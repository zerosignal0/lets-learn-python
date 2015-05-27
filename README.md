# lets-learn-python
This project is to provide learning the basics of python and python scripting.  In most of our examples we will focus on Python 3.x, although most will be backwards compatiable with Python 2.7.

## **This is meant to be followed as a tutorial guidebook**
Make sure you complete the introduction, which is found below before moving onto the chapters.  This will ensure that you have the building blocks to completete the examples.


# Chapters
* Introduction - continue reading further down this page **START HERE FIRST!**
* Chapter 1 - [Hello World!](https://github.com/zerosignal0/lets-learn-python/tree/master/source/Chapter1/README.md)
* Chapter 2 - [Expressions, Statements and Variables](https://github.com/zerosignal0/lets-learn-python/tree/master/source/Chapter2/README.md)
* Chapter 3 - [Introduction to data-types](https://github.com/zerosignal0/lets-learn-python/tree/master/source/Chapter3/README.md)


# Introduction
This project is meant to be used as a guide to follow basic usage / development of python based applications.  Having knowledge of application development isn't a requirement, although it certainly wouldn't hurt.  :smile: 

It is advised that you follow this guide in order of chapters, as some chapters build off of one another.  All of the supplemental example code can be found **[here](https://github.com/zerosignal0/lets-learn-python/tree/master/source)**


# What is Python?

excerpt from **[python.org](https://wiki.python.org/moin/BeginnersGuide/Overview)**

Python is a clear and powerful object-oriented programming language, comparable to Perl, Ruby, Scheme, or Java.

## **Some of Python's notable features:**

* Uses an elegant syntax, making the programs you write easier to read.
* Is an easy-to-use language that makes it simple to get your program working. This makes Python ideal for prototype development and other ad-hoc programming tasks, without compromising maintainability.
* Comes with a large standard library that supports many common programming tasks such as connecting to web servers, searching text with regular expressions, reading and modifying files.
* Python's interactive mode makes it easy to test short snippets of code. There's also a bundled development environment called IDLE.
* Is easily extended by adding new modules implemented in a compiled language such as C or C++.
* Can also be embedded into an application to provide a programmable interface.
* Runs on many different computers and operating systems: Windows, MacOS, many brands of Unix, OS/2, ...
* Is free software in two senses. It doesn't cost anything to download or use Python, or to include it in your application. Python can also be freely modified and re-distributed, because while the language is copyrighted it's available under an open source license.

## **Some programming-language features of Python are:**

## **A variety of basic data types are available:** 

* numbers (floating point, complex, and unlimited-length long integers), strings (both ASCII and Unicode), lists, and dictionaries.
* Python supports object-oriented programming with classes and multiple inheritance.
Code can be grouped into modules and packages.
* The language supports raising and catching exceptions, resulting in cleaner error handling.
* Data types are strongly and dynamically typed. Mixing incompatible types (e.g. attempting to add a string and a number) causes an exception to be raised, so errors are caught sooner.
* Python contains advanced programming features such as generators and list comprehensions.
* Python's automatic memory management frees you from having to manually allocate and free memory in your code.
See the SimplePrograms collection of short programs, gradually increasing in length, which show off Python's syntax and readability.

# Installing Python

In order to get started with our tutorials, we will first need to install the Python executable in order to have an environment to work with.  This process varies slightly between OS platforms, however is pretty easy and straight-forward.

For our examples, we will install Python 3.x, however every stride will be taken to provide code that will work with backward compatibility, in most cases.

**[Click here](https://www.python.org/downloads/)** and select your OS platform, following the guide to install. **MAKE SURE YOU INSTALL PYTHON 3.4.x!** While most of this guide will work with Python2.7.x, we want to ensure that we are all working with the same environments in order to ensure success following this guide. Ensure to reboot after you have installed Python to ensure that the installation is completed successfully, and that the binaries are added to your $PATH.

## Validate Python is installed correctly

Let us now validate that your python 3.4 installation was completed successfully.  Open a new terminal / powershell window and enter the following:

```shell
python -c "print ('Hello, World!')"
```

We will review a bit later what the above application does, however for now lets just run it.  You should see a result similar to:

```shell
Hello, World!
```

If you see the above then you have successfully installed Python, congratulations! :smile: 
We will now move onto Chapter1, which can be found **[here](https://github.com/zerosignal0/lets-learn-python/tree/master/source/Chapter1/README.md)**, have fun!
