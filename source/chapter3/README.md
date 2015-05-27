# Chapter 3
Welcome to chapter3 of [Let's Learn Python](https://github.com/zerosignal0/lets-learn-python)

In this chapter we will be introducing your to basic data-types which are mostly all common basics to most programming languages. 

We will start out here in order to help you understand how to write the simplest of applications, in order to move onto more complex usage with more advance applications.

For this chapter, we will be using the interactive interpreter to provide you with real time feedback of what you are doing. 

To open a new interactive shell, open a new terminal / powershell and type the following:

## linux/OSX
```bash
python3
```
## Windows
```bash
c:\Python34\python.exe
```

# Data types

## Working with Booleans

This portion will be short for now, as I don't want to get too far into Booleans without talking about relational and operational operators.  For now we will just provide a brief description.

Boolean data types are True and False. Internal to Python, True is stored as a 1 and False is stored as 0 (binary integer).

Here is a simply example:

```shell
>>> isequal = 5==5
>>> isequal
True
```

In the above example evaluating the variable that we assigned the evaluation of 5==5 stored the bool value True.  This is because 5 does indeed equal itself as a integer, so the Bool result of the operation is stored in the variable isequal.

Now we will try another:

```shell
>>> isequal = 4==5
>>> isequal
False
```

In the above example, our bool result this time is False, as 4 does not equal 5.

## Working with numbers

Different examples of numbers within python are as follows:
```
integers:  42
floats:  3.49283
long: 20L
binary integers: bin(20)
```

Standard arithmetic operators 
```
>>> 2+2
4
>>> 6-3
3
>>> 3*8
24
>>> 132/2
66

```

You can also perform modules:
```
>>> 6 % 3
0
>>> 3 % 2
1
```

Exponent Operator:
```
>>> 2 ** 4
16
```

Python is capable of mixing different variations of numbers, such as adding integer with float.

```
>>> 1+2.2
3.2
```

Also, just as in real life, arithmetic in python follows standard order operations MDAS.

```
>>> 3+4*5
23
```

If you want to override the order of precedence, you can do so as follows:

```
>>> (2+3)*4
20
```

You can also see the power of a number by using the pow() method (we will describe methods in further detail in future chapters).

```
>>> pow(2,3)
8
```

Absolute value can be determined using the abs() method.

```
>>> abs(-2)
2
```

Round will provide the nearest rounded number using the round() method.

```
>>> round(2.4)
2
```

Much more advanced mathematics can also be performed with the "math" module, which will will introduce as well as what modules are in future chapters.


## Strings

Strings are any sequence of characters specified within single / double quotation.  There is no difference in using either single or double quotes for strings, however you must match sets.  This means you can't start a string expression with single quotes and end it with a double quote.

```shell
>>> var = 'Hello, World!'
>>> var = "Hello, world!"
```

You can concatenate strings, as we have seen earlier in this chapter.

```shell
>>> str1 = "Hello, World!"
>>> str2 = " Goodbye, World!"
>>> str3 = str1 + str2
>>> str3
'Hello, World! Goodbye, World!'
```

There are quite a few built-in operations / functions that we can use with strings in order to determine all different aspects about them.  One is called the length function, len().  As you will see in the example len will provide the amount of characters that make up a string.

```shell
>>> str1 = "Hello, World!"
>>> len(str1)
13
```

Strings are stored as sequences within python, which allows for you to access any single character within a sequence of characters.  This sequencing looks similar to an array for some of you that may be familiar with arrays from other languages.  An example below will show accessing the first and last character of a string.  There are plenty of other ways to dynamically slice strings as well, we will touch upon them in later chapters.

```shell
>>> str = "Hello, World!"
>>> str[0]
'H'
>>> str[13]
'!'
```

You can also slice the above example, which will provide you with a segment of characters from a starting position to ending position.

```shell
>>> str = "Hello, World!"
>>> str[0:5]
'Hello'
```

Some other slice examples:

```shell
>>> str = "Hello, World!"
>>> str[4:]
'o, World!'
>>> str[:5]
'Hello'
```

You can also use an operator called split split(), to split a string on a specific character.  For example, lets take a comma separated sequence and use split().  This will introduce you to a new return data type called a list [].  Lists are denoted by square braces and contain a series of other data types within them (we will go over lists later in this chapter).

```shell
>>> str = 'h,e,l,l,o'
>>> str.split(',')
['h', 'e', 'l', 'l', 'o']
```

You can remove spaces from on the extreme left / right of a string, the strip() operator can remove them.

```shell
>>> str = ' hello, world!  '
>>> str.strip()
'hello, world!'
```

# List data-type

This is an introduction to the lists data type.  We will not go into full details about EVERYTHING lists have available, as these will be covered in future chapters.  

Lists are almost self describing as a "list" of objects.  This list can contain any data types like strings, int and even other lists.  A list is represented by "[]" square bracing.  

There are a few different ways to create a new list can be created.  For these chapters we will focus on creating new lists by simply using [], as shown below.

```shell
>>> mylist = []
>>> type(mylist)
<class 'list'>
```

You can add objects to a list by using the append() operation on a list.  **NOTE** we will go into removing items from lists later.

```shell
>>> mylist = []
>>> mylist.append(1)
[1]
```

If you want to access a specific list item, or element, you can provide an index value as follows:

```shell
>>> mylist = [1,2,3]
>>> mylist[1]
2
```

We can also access slices of lists, the same way we were able to with strings.  This will provide another list containing only the values of index number 1-2.

```shell
>>> mylist = [1,2,3,4]
>>> mylist[0:2]
[1, 2]
```

As we had discussed previously, you can also use the len() operator to provide the length, or in this case number of elements in a list.

```shell
>>> mylist = [1,2,3]
>>> len(mylist)
3
```

You can concatenate lists together as well, such as the example below.

```shell
>>> mylist1 = ['a','b','c']
>>> mylist2 = [4,5,6]
>>> mylist3 = mylist1 + mylist2
['a', 'b', 'c', 4, 5, 6]
```

Finally, you can add a sub list into a list and even access specific items from within the sublist.

```shell
>>> mylist1 = ['a', 'b', 'c']
>>> mylist2 = [1, 2, 3, mylist1]
>>> mylist2
[1, 2, 3, ['a', 'b', 'c']
>>> mylist2[3]
['a', 'b', 'c']
>>> mylist2[3][0]
'a'
```



# Dictionaries data-type

This is an introduction to the dictionary data type.  We will not go into full details about EVERYTHING dictionaries have available, as these will be covered in future chapters.

# Tuple data-type

This is an introduction to the tuple data type.  We will not go into full details about EVERYTHING tuples have available, as these will be covered in future chapters.

Now that you have completed chapter3, you are ready to move onto **[chapter4](https://github.com/zerosignal0/lets-learn-python/tree/master/source/Chapter4/README.md)**