# This chapter deals with...
* "Hello world!" program
* How the intrepreter executes the code

# Before you can begin
Right so now that you have installed Python and a suitable IDE. It's time to get coding.

So in the Computer Science world, the "Hello World" program is always a coder's first program in any language.


# First program
So for us to write "Hello World" in Python->

1)Open your IDE

**VSCODE**:
1. Go to your file explorer and create a file somewhere named "pythonprojects"
1. Now click the top left symbol that looks like a file
1. It should open a panel that says "Explorer", "UNTITLED(WORKSPACE)
1. Under the heading with "WORKSPACE" in its name:
    * right click and select "Add Folder to workplace"
    * Navigate to the folder you just created
    * Click the folder and click "add"
1. Now right click on the folder in the explorer tab and click "Create new file"
1. type in the filename as "helloworld.py" -> the .py extention tells the computer that this file is a python file

**PyCharm**:
1. Create a new project
1. Name it whatever you want
1. On the left, by the file explorer
1. Right click your project and hover over "New"
1. Right click "Python file"
1. Name it "helloworld.py"


## Hello world
Now type the following code into your IDE and click "run" - green triangle

```python
print("Hello world")
```
Output:
Hello world!<br><br>

Thats it. You've completed your first program.

## What's happening?

We need to understand what the computer has done to output this text of "Hello world"

A computer program is like a book.

At the top of your program, you have line 1-- start of your book--, ending at line n- where n is your last line of code -- end of your book.

Now what the interpreter will do is this:
* Starting at line 1, it will go line by line and execute python code
* In this case, since on line 1 there is the code "print("Hello world")", our interpreter will thus execute this line
* Now the interpreter sees that line 1 had the last line of code, so it ends the programme

## Another program
So lets take another program:

You can type this into your current .py file or make another- whatever you want.


```python
print("Hello world") #prints out text
print("The weather is nice today!") # prints out text
```

Output:
Hello world!
The weather is nice today!

## What's happening?

So the interpreter in this case has:
* Read line 1 and seen the python code "print("Hello world")", and executed it
* Read line 2 and seen the python code print("The weather is nice today!") and executed it
* Now the interpreter sees that this is the last line and ends the program.


## Invalid python code 
So thats how the interpreter will see your programs. All it does is go from top->bottom and executing valid python code.

It will throw an error if there's any invalid python code- so for example:

```python
print(Hello world) #Notice there is no "" marks

Output:
print(Hello world!)
                ^
SyntaxError: invalid syntax
```
But more on errors in python later


# Exercises

Write a program to output the following text:


Hello my name is Jason
I love to cook and knit
But i hate pineapple on pizza