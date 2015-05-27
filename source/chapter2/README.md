# Chapter 2
Welcome to chapter2 of [Let's Learn Python](https://github.com/zerosignal0/lets-learn-python)

In this chapter we will be introducing your to expressions, statements and variables which are all common basics to most programming languages. 

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

# Expressions

Expressions are a piece of literal data which represent something such as a string, a integer or a class.  Expressions are comprised of the following:

## Identifiers
```
identifier	::=	(letter|"_") (letter | digit | "_")*
letter	::=	lowercase | uppercase
lowercase	::=	"a"..."z"
uppercase	::=	"A"..."Z"
digit	::=	"0"..."9"
```

## Literals
Literals are notations for constant values of some built-in types.


## Operators
```
+       -       *       **      /       //      %
<<      >>      &       |       ^       ~
<       >       <=      >=      ==      !=      <>
```
The comparison operators <> and != are alternate spellings of the same operator. != is the preferred spelling; <> is obsolescent.

The most basic example of an expression in python is the following:

```shell
>>> 1
1
```

In the above output, we have expressed the integer 1 by simply typing the number 1 and pressing enter.  This is an expression that evaluates to itself.  

Another example of a expression would be an arrhythmic expression like the following:

```shell
>>> 1+2
3
```

In the above output, we have expressed the arrhythmic expression with 2 liters (1,2) and have also applied an arithmetic  operator (+).

Expressions aren't just for numbers though, strings are also included within expressions, such as:

```shell
>>> 'hello' + 'world'
'helloworld'
```

As you can see from the above output, we have provided 2 literal strings, "hello" and "world", applied an addition operator and yielded the resulting concatenated string 'helloworld'.  Also note that I have placed the strings in single quotes.  You can place them in single or double interchangeably for expressions without any issues.

Another type of an expression a Boolean expression.  Boolean expressions are an evaluation that provides a True/False answer.  An example would be the following:

```shell
>>> 100 > 200
False
```

There are more variations of expressions, however for now we will use these string, integer and Boolean examples. 

# Statments

Statements in simple terms are a grouping of expressions in which do something within your application.  These statements are logical and can be comprised of one or many lines.  Example of statements are assignment, looping, if, conditional, etc.

Let us take a look at assignment statements as our first example.  Assignment statements are used to assign values to variables.  We are going to cover variables next, but this will be a good intro to them before going into further details.

```shell
>>> num = 100
```

The above statement is assigning the integer 100 to the variable num.  This means that if you were to evaluate num you would see that it would return the integer 100.

```shell
>>> num = 100
>>> num
100
>>> type(num)
<class 'int'>
```

A whole lot was introduced above that we will go into further details in later chapters.  For now, the above output simply proves that we have created an object called "num", assigned the integer 100 to it and can access the value of num, along with evaluating its type.

Python automatically attempts to assign a data type to variables when they are created, provided what type of data is provided in the statement.  In our above, we assigned an integer, so python automatically set the datatype of num to integer.

What if we assign the value "one" to the variable num?

```shell
>>> num = "one"
>>> num
'one'
>>> type(num)
<class 'str'>
```

As you can see above, because we provided the string 'one' in the assignment statement the type of the variable num is now the string "one".

Can you evaluate using statements? Yes you can! 

```shell
>>> num1 = 100
>>> num2 = 200
>>> sum = num1 + num2
>>> sum
300
>>> type(sum)
<class 'int'>
```

In the above example we setup 2 variables, num1 and num2, with the integer values 100 and 200.  Then we created a new variable called sum, which is set to equal the results of the arithmetic expression num1 + num2.

More examples of simple statements can be found [here](https://docs.python.org/2/reference/simple_stmts.html).

# Variables

Since we have provided a good amount of examples above setting variables, I will simply provide a definition here.  We will work heavily with variables throughout a majority of the future chapters.

A variable is something that holds a value that may change. In simplest terms, a variable is just a box that you can put stuff in. You can use variables to store all kinds of stuff, but for now, we are just going to look at storing numbers in variables. The equal sign (=) is used to assign a value to a variable.

More examples of variables can be found [here](https://docs.python.org/3.4/tutorial/introduction.html)

Now that you have completed chapter2, you are ready to move onto **[chapter3](https://github.com/zerosignal0/lets-learn-python/blob/master/source/Chapter3/README.md)**
