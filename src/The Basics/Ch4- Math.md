# This chapter deals with...
* importing
* math operators in python
* How to write mathamatical equations
* Math module

# Importing
Importing in Python can be seen as allowing your script to have access to more python code.

So instead of you having to write all the logic, you can import the package and immediately use the contents.

## Two ways to import:
To import **everything** from a module:
```python
import <modulename>
```
Then to call functions from the module:

```python
modulename.functioname(...)
```

To import **only select functions** from a module:
```python
from <modulename> import <functioname>
```
Then to call the function:

```python
functioname(...)
```

Either way works, but to increase your build times/reduce script sizes, we only import what we need.
It also makes it easier for other people to understand the dependencies that our script has

# Operators
In python, there are operators that can execute mathemitical statements.

For example -> 1+2=3, in this case -the "+" is the mathamtical operator.


So the avialable operators in python math is:

Operator | Symbol
-------- | ---------
add | +
minus | -
multiply | *
divide | /
expotent | **
Modulus/Remaider | %
Integer division | //

## Add
This operator adds numbers together

```python
print(2+3) #outputs 5
```

## Minus
This operator minuses numbers together

```python
print(5-3) #outputs 2
```

## Multiply
This operator multiplies numbers together

```python
print(2*3) #outputs 6
```

## Expotent
This operator raises one number to another

```python
print(2*3) #Raises 2 to the power of 3. Therefore -> 8
```

## Modulus remainder
This operator returns the remainder of a sum

For example:
8%2 = 0
Since 2 divided by 2 returns no remainders, the % operator will return 0 - no remainders

<br>
8%3 = 2
Since 3 can go into 8 twice:
8-3 -3 = 2
We are left with a remainder of 2, which is what the % operator returns in this case

<br>
8%5 = 3
Since 35 can go into 8 once:
8-5 = 3
We are left with a remainder of 3, which is what the % operator returns in this case

<br>
8%9 = 3
Since 9 can't go into 8, we are left with a remainder of 8
This is the case for whenever a > b where a is the dividor and the b is dividend

## Integer division
This operator converts a number to an integer in case a division results in a float. And floors it

For example

```python
print(5//2) # Normally would be 2.5, but since we are using the // operator, it will be 2
```

# How to write mathemitcal equations

The way python evaluates equation is BEDMAS, and the for its brackets it does an inside->outside approach. 

## NB BEDMAS
1. B- Brackets
1. E- expotents
1. D- divide
1. M- multiply
1. A- Add 
1. S-subtraction


## Example
(2+ (3+1))

Python recognizes that there are brackets:
Since (3+1) is the most "inside" bracket, it will execute first then result in:
(2+4)
Thus (6)

Just for you to see the difference:
```python
print((2+3) * 2) # outputs 10
print(2+3 * 2) # outputs 8
```

For the first one, since there is brackets, by BEDMAS, there is a B, so the brackets executes
For the second one, since there is no brackets, the M will occur first then the A.
So the 3*2 happens first then the add operation

## NB
In the case when python is left with some thing like:
```python
print(2*6 / 3)
```
Python will execute from left-to-right
So this equations will become:
* 12 / 3
* 4

This is the same case for when its:
```python
print(2+3-1)
```

# Math module

At the top of your script, we will import the math module:
```python
#main.py -> does some math
import math
```

Now we have access to all the functions inside the *math* module.

Lets look at some of the functions:

function | Explaination | example | result
-------- | ------------ | -------- | -------
math.pi|Math pi constant|math.pi|3.14159
math.ceil()|Rounds up number | math.ceil(2.5) | 3
math.floor()|Rounds down number | math.floor(2.5) | 2
math.sqrt()|Square roots a number|math.sqrt(4) | 2
math.degrees()|converts radians to degrees|math.degrees(2 * math.pi)|360.0
math.radians()|converts degrees to radians|math.radians(360)|6.283
math.log()|performs log calculation to a inputted base, or as a ln otherwise |math.log(10)|2.30
math.sin()/cos()/tan()|Gets ratio from given angle. Inputted angle is radians| math.sin(math.radians(90))|1
math.asin()/acos()/atan()| Return the arc sine (measured in radians) of inputted value| math.asin(1)|1.570


## Example program

Lets write a simple program that does some calculations.


Lets say i want the user to input the number, then i will perform the following operations:
1. Add 2 to it
2. Multiply it by 3
3. Apply it to the power of 2
4. Minus 2

Lets start from the beginning
```python
x = int(input("Enter a number:")) # gets input

# Now if i want to add 2 to this value of x, i need to alter its value
# So i will do this

x = x + 2  #This takes the current value of x and adds 2 to it
           #Or you could do x+=2

x= x * 3 # Multiply it by 3
         #Or you could do x*=3

x= x ** 2 # apply to a power of 2
         #Or you could do x**=2

x= x - 2 #Minus 2
         #Or you could do x-=2

print("Your value is " + str(x))
```

Example running:
```
Enter a number:
1
Your value is 79
```
# Exercises
