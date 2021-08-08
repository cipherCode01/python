# Before you can begin
Right so now that you have installed Python and a suitable IDE. It's time to get coding right?

Not yet.

Before you can even start coding, you need to understand how a program works.

So in the Computer Science world, the "Hello World" program is always a coder's first program in any language.


# First program
So for us to write "Hello World" in Python->
1)Open your IDE

IF IN VSCODE:
1) Go to your file explorer and create a file somewhere named "pythonprojects"
2) Now click the top left symbol that looks like a file
3) It should open a panel that says "Explorer", "UNTITLED(WORKSPACE)
4)Under the heading with "WORKSPACE" in its name:
    4.1)right click and select "Add Folder to workplace"
    4.2)Navigate to the folder you just created
    4.3)Click the folder and click "add"
5)Now right click on the folder in the explorer tab and click "Create new file"
6)type in the filename as "helloworld.py" -> the .py extention tells the computer that this file is a python file

IF IN PYCHARM:
1)Create a new project
2)Name it whatever you want
3)On the left, by the file explorer
4)Right click your project and hover over "New"
5)Right click "Python file"
6)Name it "helloworld.py"

Now type this into the code section and click "run":

```python
print("Hello world")
```
Output:
Hello world!


Thats it. You've completed your first program.

We need to understand what the computer has done to output this text of "Hello world"

A computer program is like a book.

At the top of your program, you have line 1-- start of your book--, ending at line n- where n is your last line of code -- end of your book.

Now what the interpreter will do is this:
-Starting at line 1, it will go line by line and execute python code
-In this case, since on line 1 there is the code "print("Hello world")", our interpreter will thus execute this line
-Now it sees that this is the only code, so thus it ends the program.

So lets take another program:

```python
print("Hello world")
print("The weather is nice today!")
```
Output:
Hello world!
The weather is nice today!

### Code end

So the interpreter in this case has:
-Read line 1 and seen the python code "print("Hello world")", and executed it
-Read line 2 and seen the python code print("The weather is nice today!") and executed it
-Now the interpreter sees that this is the last line and ends the program.



So thats how the interpreter will see your program. All it does is go from top->bottom and executing valid python code.
