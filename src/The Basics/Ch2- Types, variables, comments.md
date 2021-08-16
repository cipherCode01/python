# This chapter deals with...
* the print() function
* comments
* Types

# Reminder
Our basic "Hello world" program is:

```python
print("Hello world")
```

# Comments

Your code does the "How" of the program, and your comments explain the "Why" of the program

There are a few ways to leave a comment:

```python
#This is a 1 line comment

#This is a
#2 line comment

"""
These are docstrings
You see how i don't need to put in hashtags
here to make a multiline comment?
Made with triple quotes on both sides of the text
"""
```
Your comments should be as effective and concise as possible- but not so concise that it's impossible to understand


```python
# main.py -> Prints out hello world

print("hello world") #prints out text
```

The comment above is fine enough

# The "print" function

The 
```python
print()
```
Function is a very useful function.

Its uses are:
* output strings
* debugging


# Types

This is the correct point to introduce types.

A "type" in programming refers to the type of data that a piece of a inforamtion can be catorgized into.

For example:
1. The number *2* is an Integer
1. The number *2.56* is a Float

Types are important because each type behaves differnetly and each have their attributes

So the basic types are:

Type name | Example
------------ | -------------
Integer | 2
Float | 2.34
Char(Character) | 'c'
String | "Hello world"
Boolen | True/False

The above are the **primitive** types in python.

We will introduce non-primitive types later

# Variables

A variable is as a placeholder for some value.

## Example 1
```python
x = 5 #x equals some Integer of value 5
y = "Hello world" #y equals some String of value "Hello world"

print(x) # Outputs 5
print(y) # Outputs "Hello world"
```

Just put the above code into your IDE to see for yourself.

### What's happening?

Basically by using the *=* operator, we are telling Python that we want this placeholder value to equal some value:

So in this case:
1. we are telling that we want *x* to equal *5*
1. also that *y* to equal *Hello world*

## Some more examples:

```python
num1 = 5 #Lets num1 = 5
num2 = 2 # Lets num2 = 2

num3 = num1 + num2 # Basically this will sub num1 for 5, and sub num2 for 2 -> which results in num3 = 7

print(num1)
print(num2)
print(num3)

Output:
5
2
7
```

```python
str1 = "My name is John"
str2 = "I am 28 years old"


print(str1)
print(str2)
```
Output:
My name is John
I am 28 years old

# Naming
Before you write can write a variable name, you must give it an appriopiate name.

These are general rules to follow when naming variables:
* Ensure your naming hints at what the variable is for
```python
cat = 5 # Poor variable name
number1 = 5 #Good name
```
* Use camelCase
```python
numberOfCats = 5 #first word's first letter is lowercase, then each consecutive word's first letter is capital
```
* Avoid lengthly variable names
* Ensure to comment the purpose of the variable


# Exercises

1. State the type/s of the following data
    1. 2
    2. "I live in Brazil"
    3. 'c'
    1. True
    1. 2.542
1. Give variable names to the following:
    1. 5
    1. "My cat's name is Roger"
    1. "I am 16 years old"
1. Write a program with variables that...
    1. Adds two numbers together
    1. Prints out your name,age,height, and where you live