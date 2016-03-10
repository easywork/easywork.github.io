---
layout: post
title: Python Feature
categories:
- Common Tec
tags:
- MarkDown
---

#### Below discuss some features of python

1. Python is dynamically typed, this means that you don't need to state the types of variables when you declare them or anything like that. You can do things like x=111 and then x="I'm a string" without error

1. Python is well suited to object orientated programming in that it allows the definition of classes along with composition and inheritance. Python does not have access specifiers (like C++'s public, private). 

1. Python functions are first-class objects. This means that they can be assigned to variables, returned from other functions and passed into functions. Classes are also first class objects

1. Writing Python code is quick but running it is often slower than compiled languages. Fortunately， Python allows the inclusion of C based extensions so bottlenecks can be optimised away and often are. The numpy package is a good example of this, it's really quite quick because a lot of the number crunching it does isn't actually done by Python

1. Generators allow for iterative processing of things, one item at a time. This doesn't seem so fancy, until you start to realize that normal iterative processing of a list requires a list. A list takes memory. A really big list takes a lot of memory. Where this becomes particularly handy is when you have a long chain of processes you need to apply to a set of data. Generators allow you to grab source data one item at a time, and pass each through the full processing chain.

1. Python has gained a reputation as being easy to learn. The syntax of the language is designed to be readable. There's plenty of argument on the subject, but the facts speak for themselves.

1. Much of Python's popularity is in fields like scientific computing. The people working in this field are scientists first, and programmers second (if at all).

1. Python lets you code in a more semantic way. For example, if you want to specify a value x, that 2<=x<=5, in python you can code it as 'x in range(2,6)'.

1. If you are not sure the usage of a built-in function of a language, what can you do? For example, you are not sure if you can do 'str1' + 'str2', in python, you can just try in out in the intactive terminal, but in Java, you need to code a class and compile it before you know if you can do it.

Advanced systems like NumPy and SciPy were started not by teams of software engineers, but by domain experts building the tools they needed to get a job done.

