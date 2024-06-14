# Welcome!!!

I trust that you've reviewed the previous files and have set up your environment to write your first Python code. It doesn't have to be the examples I recommended; the key is to ensure that you can run a Python code successfully.

## What We Will Cover

Before diving in, let's outline the topics we'll be covering:

1. **Python Syntax**
2. **Data Types**
3. **Python Operators**
4. **Variables**
5. **Basic Standard Functions** 

It's worth noting that some topics may be combined within a single example to enhance comprehension.

# Getting Started

If you haven't set up your Python environment yet, make sure to do so. Once you're ready, let's start our exploration of Python's fundamentals. 

```python
# Your first Python code
print("Hello, This is my fisrt Python code!")
```

Feel free to run this simple code to ensure everything is set up correctly. You're encouraged to modify the sentence enclosed in double quotes according to your liking. 
Let's embark on this learning journey together!

# Python Syntax

The syntax of a programming language sets it apart from others, defining how commands are structured. In Python, some distinctive features shape its syntax:

1. **New Lines to End Statements**: Python concludes statements with new lines. Unlike some languages using semicolons or parentheses, Python simplifies readability by relying on line breaks.

2. **Indentation Signifies Code Blocks**: Python uses indentation, typically four white spaces or a tab, to indicate code blocks. This is unlike languages such as C++, which deploy curly braces. Proper indentation clarifies the scope of functions, loops, and conditional statements.

3. **Flexibility in Indentation**: While four white spaces or a tab is the standard, Python allows using any number of white spaces, though it's generally not recommended.

4. **Case Sensitivity**: Python distinguishes between uppercase and lowercase letters. For instance, "ME," "Me," and "me" are all considered distinct.

5. **Comments**: In Python, the pound symbol (hash) is used to add comments to a line of code. Comments are ignored by the IDE or editor. Notably, Python lacks a native way for block commenting.

Let's delve into an example for illustration. For now, don't worry too much about understanding the code's functionality. The aim is to familiarize you with how the syntax operates:

```python
taking_First_Step = True  # Boolean variable declaration

def is_He_in():  # Function declaration
    if taking_First_Step:  # Conditional statement
        print('He is in')  # Print function
    else:  # Conditional statement
        print('He is out')  # Conditional statement

is_He_in()  # invoking the function
```

This example shows various elements of Python syntax, including variable declaration, function definition, conditional statements, and function invocation. As we progress, we'll see the details of each of these components.

# Data Types

The most basic data types used extensively in programming (python and others) are:

1. Integer (int): Represents whole numbers without decimal points, such as 5 or -10.

2. Float (float): Represents numbers with decimal points, like 3.14 or -0.5.

3. String (str): Represents sequences of characters, enclosed in single (' ') or double (" ") quotes, like "Hello, Python!".

4. Boolean (bool): Represents binary values, either True or False.

These fundamental data types form the building blocks for more complex data structures and are widely employed in programming for various applications.
We shall see some examples very soon. 
The good thing about python with regards to data types is that it automatically detects what is the type of data in question without you telling it. Also there is no need for you to declare the data type of a variable as in other languages like C++.

# Python Operators
**There are various operators in python, but the basic operators and oparations are:**
 ## 1. Arithmetic Operators
Arithmetic operators perform basic mathematical operations.
1. Addition (+): Adds two values.
``` python
result = 5 + 3  # Output: 8
print(result)
```
2. Subtraction (-): Subtracts the second value from the first.
```python
result = 5 - 3  # Output: 2
print(result)
```
3. Multiplication (*): Multiplies two values.
``` python
result = 5 * 3  # Output: 15
print(result)
```
4. Division (/): Divides the first value by the second.
``` python
result = 5 / 3  # Output: 1.666...
print(result)
```
5. Floor Division (//): Divides and returns the integer part of the quotient.
``` python
result = 5 // 3  # Output: 1
print(result)
```
6. Modulus (%): Returns the remainder of the division.
``` python
result = 5 % 3  # Output: 2
print(result)
```
7. Exponentiation (**): Raises the first value to the power of the second.
```python
result = 5 ** 3  # Output: 125
print(result)
```

### Order of Operations (PEMDAS)
The order of arithmetic operations in Python follows PEMDAS:
Parentheses: ()
Exponents: **
Multiplication and Division: *, /, //, % (left to right)
Addition and Subtraction: +, - (left to right)
Example:

``` python
result = (3 + 2) * 2 ** 2 / (5 - 3) + 6
# Steps:
# 1. Parentheses: (3 + 2) -> 5 and (5 - 3) -> 2
# 2. Exponents: 2 ** 2 -> 4
# 3. Multiplication/Division (left to right): 5 * 4 -> 20, 20 / 2 -> 10.0
# 4. Addition: 10.0 + 6 -> 16.0
print(result)  # Output: 16.0
```
Understanding these operators and their precedence is crucial for writing accurate and efficient Python code.

## 2. Comparison Operators
Comparison operators compare two values and return a boolean result.
1. Equal to (==): Checks if two values are equal.
``` python
result = (5 == 3)  # Output: False
print(result)
```
2. Not equal to (!=): Checks if two values are not equal.
``` python
result = (5 != 3)  # Output: True
print(result)
```
3. Greater than (>): Checks if the first value is greater than the second.
``` python
result = (5 > 3)  # Output: True
print(result)
```
5. Less than (<): Checks if the first value is less than the second.
``` python
result = (5 < 3)  # Output: False
print(result)
```
6. Greater than or equal to (>=): Checks if the first value is greater than or equal to the second.
``` python
result = (5 >= 3)  # Output: True
print(result)
```
7. Less than or equal to (<=): Checks if the first value is less than or equal to the second.
``` python
result = (5 <= 3)  # Output: False
print(result)
```
## 3. Logical Operators
Logical operators combine conditional statements.
1. AND (and): Returns True if both statements are true.
``` python
result = (5 > 3 and 2 < 4)  # Output: True
print(result)
```
2. OR (or): Returns True if at least one statement is true.
``` python
result = (5 > 3 or 2 > 4)  # Output: True
print(result)
```
3. NOT (not): Reverses the result; returns False if the result is true.
``` python
result = not(5 > 3)  # Output: False
print(result)
```
## 4. Assignment Operators
Assignment operators are used to assign values to variables.
1. Assign (=): Assigns a value to a variable.
```
python
x = 5
print(x)
```
2. Add and Assign (+=): Adds and assigns the result to the variable.
``` python
x += 3  # Equivalent to x = x + 3
print(x)
```
3. Subtract and Assign (-=): Subtracts and assigns the result to the variable.
``` python
x -= 3  # Equivalent to x = x - 3
print(x)
```
4. Multiply and Assign (*=): Multiplies and assigns the result to the variable.
``` python
x *= 3  # Equivalent to x = x * 3
print(x)
```
5. Divide and Assign (/=): Divides and assigns the result to the variable.
``` python
x /= 3  # Equivalent to x = x / 3
print(x)
```
6. Floor Divide and Assign (//=): Floor divides and assigns the result to the variable.
``` python
x //= 3  # Equivalent to x = x // 3
print(x)
```
7. Modulus and Assign (%=): Takes modulus and assigns the result to the variable.
``` python
x %= 3  # Equivalent to x = x % 3
print(x)
```
8. Exponent and Assign (**=): Raises to the power and assigns the result to the variable.
``` python
x **= 3  # Equivalent to x = x ** 3
print(x)
```
# Variables in Python
Variables are containers for storing data values. In Python, you don't need to declare variables before using them, and the data type is inferred from the value assigned to the variable.

## Key Points About Variables in Python:
Naming Conventions:
1. Variable names must start with a letter (a-z, A-Z) or an underscore (_).
2. The subsequent characters can be letters, numbers, or underscores.
3. Variable names are case-sensitive (myVar and myvar are different).

## Assignment:
You can assign a value to a variable using the equals sign (=).
The data type of the variable is automatically determined by the value assigned.
``` python
x = 5           # Integer
y = "Hello"     # String
z = 3.14        # Float
is_active = True  # Boolean
```
### Multiple Assignments:
You can assign multiple variables in a single line.
```python
a, b, c = 1, 2, 3
```
### Reassignment:
You can change the value of a variable at any time.
```python
x = 10
x = "Now I'm a string"
```
### Swapping Variables:

Python allows easy swapping of variable values.
``` python
a, b = b, a
```

Example Code:
``` python
# Assigning values to variables
name = "Alice"
age = 30
height = 5.7
is_student = True

# Printing variable values
print(name)       # Output: Alice
print(age)        # Output: 30
print(height)     # Output: 5.7
print(is_student) # Output: True

# Multiple assignments
x, y, z = 1, 2, 3
print(x, y, z)    # Output: 1 2 3

# Swapping variables
x, y = y, x
print(x, y)       # Output: 2 1
```

# Basic Standard Functions in Python.
Python has many standard functions that can be utilised, making it easy to write and implement programs. The following are basic functions to familiarise yourself with:

1. print(): 
Prints the specified message to the console or other standard output device.
``` python
print("Hello, World!")  # Output: Hello, World!
```
2. type(): 
Returns the type of the specified object.
``` python
print(type(5))  # Output: <class 'int'>
```
3. len(): 
Returns the length (the number of items) of an object.
``` python
print(len("Hello"))  # Output: 5
```
4. int(), float(), str(), bool(): 
Convert values to an integer, float, or string, respectively.
``` python
print(int("10"))   # Output: 10
print(float("10")) # Output: 10.0
print(str(10))     # Output: '10'
print(bool(10))    # Output: True
```
5. input(): 
Reads a line from input (usually from the user), converts it to a string, and returns it.
``` python
name = input("Enter your name: ")
print("Hello, " + name)
```
6. sum(): 
Sums the items of an iterable from left to right and returns the total.
``` python
print(sum([1, 2, 3, 4]))  # Output: 10
```
7. max() and min(): 
Return the largest and smallest items in an iterable, respectively.
``` python
print(max(1, 2, 3, 4))  # Output: 4
print(min(1, 2, 3, 4))  # Output: 1
```
8. abs(): 
Returns the absolute value of a number.
``` python
print(abs(-5))  # Output: 5
```
9. round(): 
Rounds a number to a specified number of decimal places.
``` python
print(round(3.14159, 2))  # Output: 3.14
```
10. range():
Generates a sequence of numbers, which is often used in for loops.
``` python
for i in range(5):
    print(i)
# Output: 0 1 2 3 4
```
11. list(), tuple(), set(), dict():
Create a list, tuple, set, or dictionary.
``` python
print(list("Hello"))   # Output: ['H', 'e', 'l', 'l', 'o']
print(tuple("Hello"))  # Output: ('H', 'e', 'l', 'l', 'o')
print(set("Hello"))    # Output: {'o', 'H', 'e', 'l'}
print(dict(a=1, b=2))  # Output: {'a': 1, 'b': 2}
``` 
12. sorted():
Returns a sorted list of the specified iterable's items.
``` python
print(sorted([3, 1, 4, 1, 5, 9]))  # Output: [1, 1, 3, 4, 5, 9]
```
13. help():
Invokes the built-in help system. It can be used to get documentation on modules, classes, functions, and more.
``` python
help(print)
```
14. dir():
Returns a list of the attributes and methods of any object (e.g., modules, lists, strings).
``` python
print(dir(str))  # Lists all attributes and methods of the string class
```
These basic standard functions provide a foundation for performing a variety of common tasks in Python programming. They are essential for beginners to learn and understand how to utilize them effectively. You can refer to [PYTHON DOCUMENTATION](https://docs.python.org/3/library/functions.html) for more of these functions.


# Congratulations!

You're on the right path! This guide covers some of the most essential information an absolute beginner in Python will need. Remember, practice is key. Without practice, what you learn today might be forgotten tomorrow. So, keep coding and experimenting!

Feel ready? Great! Let's move on to the next file and continue your journey into the world of Python programming. Keep up the great work!
