# Chapter 1
Welcome to chapter1 of [Let's Learn Python](https://github.com/zerosignal0/lets-learn-python)

## How to interact with python

Python has a couple of different ways in which it can be invoked and used.  Either by using an interactive interpreter or saving code within files and executing them without the interpreter.

1. Interactively (with interpreter)
2. Non-interactively (without interpreter)

**What does interpreter mean?!**

The interpreter operates somewhat like the Unix shell: when called with standard input connected to a tty device, it reads and executes commands interactively; when called with a file name argument or with a file as standard input, it reads and executes a script from that file.

So if you want to write and execute python code interactively, line by line and see the results immediately, you can use python **interactively** by invoking the interpreter with no arguments.

[See more here](https://docs.python.org/3/tutorial/interpreter.html#interactive-mode) 

For our first couple of chapters we will mostly remain in interactive interpreter mode, however eventually we will move into storing code in files and executing them non-interactively.

## Writing your first application

Anxious to get started? **GOOD!** Let's get right down to business and write our first application, called a hello world.

Interestingly to note, if you followed the introduction chapter you have already written a hello world application, you just might not have known it yet. "Hello, world" is a name generally given to the first application that someone writes / executes with a new programming language.  This type of application is very basic, and provides you the ability to get started and also validates that your programming languages environment is setup and working.

### Start python interpreter interactively

We now will start the python interpreter.  Open a new terminal / powershell prompt and type the following:

```bash
python
```

If your python interpreter is installed and working, you should see something similar to the following **(note most of my examples will be windows based so your path maybe different)**:

```bash
C:\Users\garyw> C:\Python34\python.exe
Python 3.4.3 (v3.4.3:9b73f1c3e601, Feb 24 2015, 22:43:06) [MSC v.1600 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

This is a interactive interpreter, which will allow you to execute python code in real time and view the results of its execution.

Time to make your debut and write your first python application.  Type the following in the newly opened python interpreter window:

```bash
print ('Hello, World!')
```

After you type the above and press enter, you should see output similar to the below output:

```bash
C:\Users\garyw> C:\Python34\python.exe
Python 3.4.3 (v3.4.3:9b73f1c3e601, Feb 24 2015, 22:43:06) [MSC v.1600 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> print ('Hello, World!')
Hello, World!
```

### OK, so how did that work?

First of all, congratulations on writing your first python application.  While this is not the most useful thing ever, it is a first step that will help you to build your fundamentals and confidence in python development.

Let's review what we just did and how it took the input that you provided and displayed it to the screen.

This is the command in which you entered above:

```bash
print ('Hello, World!')
```

The first thing we will look at is the term **print**.  Python has many built-in functions that provide you the ability to perform common, repeatable tasks easily, without the need for you to write them all yourself.  A full list of these built-in functions can be found **[here](https://docs.python.org/3/library/functions.html). We will just focus on the one called print for now.

The **print** built-in function is meant to simply write text to your terminals STDOUT.  If you are unfamiliar with STDOUT, might I suggest reading more **[here](http://en.wikipedia.org/wiki/Stdout)**.  If you are at all familiar with previous versions of Python, you will notice the use of parentheses around our string object. This is because Python3.x requires parentheses to be used for wrapping print statements, where in Python2.7.x and less this is not required (though still supported).  If you are unfamiliar with the term **[string](https://docs.python.org/3/library/stdtypes.html#str)**, please feel free to take a look at the link provided.

More can be read on how the print built-in method works by reading **[here](https://docs.python.org/3/library/functions.html?highlight=print#print)**

## Running our hello world non-interactively

Now we will move to writing a python application in which we can save in a file and execute anytime we like without having to type the source code out again.  This is called running an application in non-interactive mode.

To do this, we will open a new text file anywhere that you feel comfortable on your system and save it with a filename **"hello_world.py"**.  Now we will add the following to the file, saving the file afterwards.

```shell
print ('Hello, World!')
```

We will now execute the file that we just created with our python interpreter.  To do this, open a new terminal / powershell and run the following command:

```shell
c:\Python34\python c:\Path\To\hello_world.py
```

If everything has worked as expected, you should see the following output:

```shell
Hello, World!
```

Congratulations, you have written your first python based application and have now learned the difference between interactive / non-interactive execution of python applications.

To see a working example of hello_world.py, please see the source directory for chapter1, which can be found **[here](https://github.com/zerosignal0/lets-learn-python/blob/master/source/Chapter1/hello_world.py)**.

Now that you have completed chapter1, you are ready to move onto **[chapter2](https://github.com/zerosignal0/lets-learn-python/tree/master/source/chapter2)**
