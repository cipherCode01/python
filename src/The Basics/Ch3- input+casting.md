# This chapter deals with...
* Getting user input
* Type casting
* Using user input


# Getting user input

User input is necessary for tons of applications.

Because who honestly wants a programme that lacks any user input that control how the application works.

Quiet simply, to get user input:
```python
x = input("Enter input text here") # This gets user input and stores it in variable x
```

Thats all there is.

This input will be stored as a string.

But what if we wanted a number?

Well lets try:
```python
num = input("Enter a number:")
#User enters a number

print(num + 2)
```
Output:
```python
TypeError: can only concatenate str (not "int") to str
```

Theres an error! 