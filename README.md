# Python-DSA
Data Structures and Algorithms with Python 

# 🐍 Python Roadmap: Beginner → Advanced
A complete Python learning path from **absolute beginner** to **expert-level** and **specializations**.
---

## 1️⃣ Beginner – Python Foundations

These are the basics — must master them before moving forward.

### 📌 Setup & Environment
- Installing Python
- Using **IDLE**, **VS Code**, or **PyCharm**
- Running `.py` files
- Python Interactive Shell (REPL)

### 📌 Basic Syntax
- Keywords, Identifiers, Indentation rules
- Comments:  
  - Single-line: `# comment`
  - Multi-line: `""" comment """`

### 📌 Data Types
- Numbers: `int`, `float`, `complex`
- Strings: `str`
- Booleans: `True`, `False`
- None type: `None`

### 📌 Variables
- Assignment: `=`, multiple assignment
- Naming conventions (**PEP8**)

### 📌 Operators
- Arithmetic: `+`, `-`, `*`, `/`, `//`, `%`, `**`
- Comparison: `==`, `!=`, `>`, `<`, `>=`, `<=`
- Logical: `and`, `or`, `not`
- Assignment: `+=`, `-=`, etc.
- Membership: `in`, `not in`
- Identity: `is`, `is not`

### 📌 Input/Output
- `input()`, `print()`
- f-strings & formatting

### 📌 Basic Flow Control
- `if`, `elif`, `else`
- `for` loops, `while` loops
- `break`, `continue`, `pass`

---

## 2️⃣ Intermediate – Core Python Skills

Now you move into working with **collections**, **functions**, and **error handling**.

### 📌 Data Structures
- Lists
  - Creation, Indexing, Slicing
  - Methods: `append()`, `pop()`, `sort()`, etc.
- Tuples
- Sets
- Dictionaries
- Nested structures

### 📌 Strings (Advanced)
- Methods: `split()`, `join()`, `replace()`, etc.
- String formatting

### 📌 Functions
- Defining & calling functions
- Parameters & return values
- Default, keyword, variable-length arguments (`*args`, `**kwargs`)
- Lambda functions
- Scope: `local`, `global`, `nonlocal`

### 📌 Modules & Packages
- Importing: `import`, `from ... import`
- Standard library usage
- Creating your own module

### 📌 File Handling
- Opening, reading, writing files
- File modes
- `with` statement (context manager)

### 📌 Exception Handling
- `try`, `except`, `else`, `finally`
- Raising exceptions: `raise`
- Custom exceptions

### 📌 Comprehensions
- List, set, dict comprehensions
- Conditional comprehensions

---

## 3️⃣ Advanced – Deep Python

At this stage, you focus on **powerful features** and **patterns**.

### 📌 Object-Oriented Programming (OOP)
- Classes & Objects
- Attributes & Methods
- `__init__` constructor
- Inheritance, Multiple Inheritance
- Method overriding
- Encapsulation & Access modifiers
- `@classmethod`, `@staticmethod`
- `@property` decorators
- Magic/Dunder methods: `__str__`, `__len__`, `__iter__`, etc.

### 📌 Iterators & Generators
- `__iter__` & `__next__`
- `yield` keyword
- Generator expressions

### 📌 Decorators
- Function decorators
- Chaining decorators

### 📌 Context Managers
- `with` statement
- Creating custom context managers (`__enter__`, `__exit__`)

### 📌 Functional Programming
- `map()`, `filter()`, `reduce()`
- Closures
- Partial functions

### 📌 Error Logging
- `logging` module

### 📌 Type Hints
- `typing` module basics

---

## 4️⃣ Expert – High-level Concepts

These topics make you stand out as an advanced Python developer.

### 📌 Advanced OOP
- Abstract Base Classes (`abc` module)
- Multiple inheritance & MRO
- Metaclasses

### 📌 Concurrency & Parallelism
- Multithreading
- Multiprocessing
- AsyncIO (`async` / `await`)

### 📌 Memory Management
- Garbage collection
- `sys.getsizeof`

### 📌 Advanced Data Structures
- `collections` module: `namedtuple`, `deque`, `Counter`, etc.
- `heapq`

### 📌 Advanced Functions
- Coroutines
- Generators with `.send()`

### 📌 Design Patterns
- Singleton, Factory, Observer, etc.

### 📌 Testing
- `unittest` framework
- `pytest`
- Mocking

---

## 5️⃣ Specialization Paths

Once you’re advanced, choose **career-focused** paths.

### 📌 Data Science / Machine Learning
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn, TensorFlow, PyTorch

### 📌 Web Development
- Django, Flask, FastAPI
- Jinja templates
- REST API development

### 📌 Automation & Scripting
- `os`, `shutil`, `pathlib`
- Web scraping: BeautifulSoup, Scrapy, Selenium

### 📌 System Programming
- `subprocess`, `threading`, `sockets`

### 📌 Game Development
- Pygame

### 📌 Cybersecurity / Hacking Tools
- `scapy`, `socket`, `cryptography`

### 📌 DevOps
- Python for CI/CD
- Cloud SDKs: AWS Boto3, Azure SDK

---



# 📜 Python Roadmap: Beginner → Advanced

| Level              | Topic              | Description                     | Example Code                          |
| ------------------ | ------------------ | ------------------------------- | ------------------------------------- |
| **Beginner**       | Installing Python  | Setup environment and IDE       | `python --version`                    |
|                    | Basic Syntax       | Indentation, keywords, comments | `# This is a comment`                 |
|                    | Variables          | Assigning values                | `x, y = 5, 10`                        |
|                    | Data Types         | int, float, str, bool, None     | `type(3.14)`                          |
|                    | Operators          | Arithmetic, comparison, logical | `a = 5; b = 2; print(a+b)`            |
|                    | Input/Output       | `input()` and `print()`         | `name = input("Name: ")`              |
|                    | Flow Control       | if, elif, else                  | `if a > b: print("A")`                |
|                    | Loops              | for, while, break, continue     | `for i in range(5): print(i)`         |
| **Intermediate**   | Lists              | Indexing, slicing, methods      | `nums = [1,2,3]; nums.append(4)`      |
|                    | Tuples             | Immutable sequences             | `t = (1,2,3)`                         |
|                    | Sets               | Unique unordered items          | `s = {1,2,3}`                         |
|                    | Dictionaries       | Key-value pairs                 | `d = {'a': 1}`                        |
|                    | Nested Structures  | Lists in dicts, dicts in lists  | `data = {'nums': [1,2,3]}`            |
|                    | String Methods     | split, join, replace            | `"hi world".split()`                  |
|                    | Functions          | Defining and calling            | `def add(a,b): return a+b`            |
|                    | Arguments          | default, \*args, \*\*kwargs     | `def f(*args): print(args)`           |
|                    | Modules            | import, from-import             | `import math`                         |
|                    | File Handling      | open, read, write               | `open('file.txt').read()`             |
|                    | Exception Handling | try-except-finally              | `try: 1/0 except: print("Err")`       |
|                    | Comprehensions     | List, dict, set                 | `[x*x for x in range(5)]`             |
| **Advanced**       | OOP                | Classes, objects, methods       | `class A: pass`                       |
|                    | Inheritance        | Parent-child classes            | `class B(A): pass`                    |
|                    | Dunder Methods     | **str**, **len**                | `def __str__(self): return "Hi"`      |
|                    | Iterators          | **iter**, **next**              | `iter_obj = iter([1,2])`              |
|                    | Generators         | yield keyword                   | `def gen(): yield 1`                  |
|                    | Decorators         | Function wrappers               | `@decorator`                          |
|                    | Context Managers   | with, **enter**, **exit**       | `with open('f.txt') as f:`            |
|                    | Functional Prog.   | map, filter, reduce             | `list(map(str, [1,2]))`               |
|                    | Logging            | logging module                  | `import logging`                      |
|                    | Type Hints         | typing module                   | `def f(x: int) -> str:`               |
| **Expert**         | ABCs               | Abstract classes                | `from abc import ABC`                 |
|                    | Metaclasses        | Class creation control          | `class Meta(type): pass`              |
|                    | AsyncIO            | async, await                    | `async def main(): pass`              |
|                    | Multithreading     | Thread class                    | `from threading import Thread`        |
|                    | Multiprocessing    | Process class                   | `from multiprocessing import Process` |
|                    | Memory Mgmt        | gc, sys.getsizeof               | `import gc`                           |
|                    | Collections        | deque, namedtuple               | `from collections import deque`       |
|                    | Coroutines         | send, yield from                | `yield from gen()`                    |
|                    | Design Patterns    | Singleton, Factory              | `class Singleton:`                    |
|                    | Testing            | unittest, pytest                | `import unittest`                     |
| **Specialization** | Data Science       | NumPy, Pandas, Matplotlib       | `import numpy as np`                  |
|                    | Web Dev            | Flask, Django, FastAPI          | `from flask import Flask`             |
|                    | Automation         | os, shutil, pathlib             | `import os`                           |
|                    | Web Scraping       | BeautifulSoup, Scrapy           | `from bs4 import BeautifulSoup`       |
|                    | Game Dev           | Pygame basics                   | `import pygame`                       |
|                    | Cybersecurity      | socket, cryptography            | `import socket`                       |
|                    | DevOps             | AWS boto3, Docker SDK           | `import boto3`                        |

---
# 2. 📚 Intermediate Python Topics with Examples
This section covers **Core Python Skills** you’ll need to work with **collections, functions, and error handling** effectively.

## 1. Data Structures
```python
# 1️⃣. Lists – Ordered, mutable collections.
# Methods: append(), pop(), sort(), etc.
list = [1, 2, 3]

# Adding elements
list.append(4)        # Add single element → [1, 2, 3, 4]
list.extend([5, 6])   # Add multiple elements → [1, 2, 3, 4, 5, 6]
list.insert(1, 10)    # Insert at index → [1, 10, 2, 3, 4, 5, 6]

# Removing elements
list.remove(10)       # Remove first occurrence of value
list.pop(2)           # Remove by index (default last) → returns removed element
list.clear()          # Remove all elements → []

# Reset list for examples
list = [1, 2, 3, 4, 5, 6]  # Reset list

# Searching & counting
print(list.index(4))  # Find index of element → 3
print(list.count(2))  # Count occurrences → 1

# Sorting & reversing
list.sort()           # Sort list in ascending order → [1, 2, 3, 4, 5, 6]
list.sort(reverse=True) # Sort in descending order → [6, 5, 4, 3, 2, 1]
list.reverse()        # Reverse list → [1, 2, 3, 4, 5, 6]

# Copy & built-ins
copy_list = list.copy()  # Return shallow copy
print(len(list))      # Length of list → 6
print(min(list))      # Minimum value → 1
print(max(list))      # Maximum value → 6
print(sum(list))      # Sum of elements → 21

# Slicing
print(list[1:4])      # Elements from index 1 to 3 → [2, 3, 4]
print(list[:3])       # First 3 elements → [1, 2, 3]
print(list[::2])      # Every second element → [1, 3, 5]

# List Comprehensions – Shorter way to create lists
squares = [x**2 for x in range(5)]            # Squares → [0, 1, 4, 9, 16]
evens = [x for x in range(10) if x % 2==0]    # Even numbers → [0, 2, 4, 6, 8]
print(squares, evens)

# 2️⃣. Tuples – Ordered, immutable collections.
tup = (1, 2, 3, 2)

print(tup.count(2))       # Count occurrences → 2
print(tup.index(3))       # Find index → 2
print(tup[1:3])           # Slice → (2, 3)
print(tup[0])             # 1
print(len(tup), min(tup), max(tup), sum(tup)) # 4, 1, 3, 8

# "Tuple comprehensions" don't exist — use generator expressions
gen = (x**2 for x in range(5)) # Creates generator, not tuple
print(tuple(gen))              # Convert to tuple → (0, 1, 4, 9, 16)

# 3️⃣. Sets – Unordered, unique items.
s = {1, 2, 2, 3}

print(s)                  # {1, 2, 3} , because Set is unique items
s.add(4)                  # Add element → {1, 2, 3, 4}
s.update([5, 6])          # Add multiple elements
s.remove(2)               # Remove (error if not found)
s.discard(10)             # Remove if exists (no error)
s.pop()                   # Remove and return random element
s.clear()                 # Remove all → set()

s = {1, 2, 3, 4}
print(len(s), min(s), max(s), sum(s))  # 4, 1, 4, 10

a, b = {1, 2, 3}, {3, 4, 5}
print(a.union(b))         # Union → {1, 2, 3, 4, 5}
print(a.intersection(b))  # Intersection → {3}
print(a.difference(b))    # Difference → {1, 2}
print(a.symmetric_difference(b)) # Symmetric difference → {1, 2, 4, 5}

# Set Comprehensions
squares = {x**2 for x in range(5)}
print(squares)

# 4️⃣. Dictionaries – Key-value pairs.
d = {"name": "Alice", "age": 25}
d["city"] = "Delhi"         # Add/update key
print(d)                    # {'name': 'Alice', 'age': 25, 'city': 'Delhi'}
print(d.get("name"))      # Get value → Alice
print(d.keys())           # All keys  → like column names in a table -> (['name', 'age', 'city']) 
print(d.values())         # All values  → actual data for those keys -> (['Alice', 25, 'Delhi'])
print(d.items())          # All key-value pairs
d.update({"age": 26})     # Update multiple keys
d.pop("city")             # Remove key → 'Delhi'
d.popitem()               # Remove last inserted (Python 3.7+)
print("name" in d)        # Check key existence
print(len(d))             # Length → 1
copy_d = d.copy()         # Shallow copy
d.clear()                 # Remove all

# Dict Comprehensions
squared_dict = {x: x**2 for x in range(5)}
print(squared_dict)

# 5️⃣. Nested Structures – Collections inside collections.
data = {
    "students": [
        {"name": "Anil", "marks": 90},
        {"name": "Ravi", "marks": 85}
    ],
    "teachers": {
        "math": {"name": "Mr. Sharma", "experience": 10},
        "science": {"name": "Ms. Gupta", "experience": 8}
    }
}

# Access nested data
print(data["students"][0]["name"])           # Anil
print(data["students"][1]["marks"])          # 85
print(data["teachers"]["math"]["name"])      # Mr. Sharma

# Modify nested data
data["students"][0]["marks"] = 95
data["teachers"]["science"]["experience"] += 1
print(data)
```

## 2. String Methods & Functions (Advanced)
```python
# String Methods
text = "hello world"

# 1️⃣ Case Conversion
print(text.upper())        # HELLO WORLD
print(text.lower())        # hello world
print(text.title())        # Hello World
print(text.capitalize())   # Hello world
print(text.swapcase())     # HELLO WORLD → hello world / vice versa

# 2️⃣ Search & Find
print(text.find("world"))  # 6 → first occurrence index (or -1 if not found)
print(text.rfind("o"))     # 7 → last occurrence index
print(text.index("world")) # 6 → like find(), but error if not found
print(text.count("l"))     # 3 → number of occurrences

# 3️⃣ Replace & Remove
print(text.replace("world", "Python")) # hello Python
print(text.strip())       # Removes whitespace from both ends
print("   hi   ".strip()) # "hi"
print("   hi   ".lstrip())# "hi   "
print("   hi   ".rstrip())# "   hi"

# 4️⃣ Splitting & Joining
print(text.split())       # ['hello', 'world'] → split by space
print("a,b,c".split(",")) # ['a', 'b', 'c'] → split by comma
print("line1\nline2".splitlines()) # ['line1', 'line2']
print("-".join(["2025", "08", "12"])) # 2025-08-12

# 5️⃣ Checking String Contents (Return True/False)
print("123".isdigit())    # True
print("abc".isalpha())    # True
print("abc123".isalnum()) # True
print("hello".islower())  # True
print("HELLO".isupper())  # True
print("Hello World".istitle()) # True
print("   ".isspace())    # True
print("if".isidentifier())# True (valid Python variable name)
print(text.startswith("he")) # True
print(text.endswith("ld"))   # True

# 6️⃣ Alignment
print("hi".center(10, "-")) # ----hi----
print("hi".ljust(10, "*"))  # hi********
print("hi".rjust(10, "*"))  # ********hi
print("42".zfill(5))        # 00042

# 7️⃣ Encoding & Decoding
print("hello".encode())             # b'hello'
print(b'hello'.decode())            # hello

# String Functions
# 8️⃣ String Formatting
name = "Anil"
age = 25

print(f"My name is {name} and I am {age} years old.")        # f-string
print("My name is {} and I am {} years old.".format(name, age))  # format()

print("Name: {n}, Age: {a}".format(n=name, a=age))           # named format
print("Value: {:.2f}".format(3.14159))                       # 2 decimal places
print("%s is %d years old" % (name, age))                    # old-style formatting

```

## 3. Functions – Defining, Calling, and Advanced Usage
```python
# 1️⃣ Basic Function Definition & Call
def greet(name):
    return f"Hello, {name}!"
print(greet("Anil"))  # Hello, Anil!

# 2️⃣ Parameters & Return Values
def add(a, b):
    return a + b
print(add(3, 4))  # 7

# 3️⃣ Default Arguments
def intro(name, age=18):
    print(f"{name} is {age} years old.")
intro("Anil")        # Anil is 18 years old.
intro("Anil", 25)    # Anil is 25 years old.

# 4️⃣ Keyword Arguments
def profile(name, city):
    print(f"{name} lives in {city}.")
profile(city="Delhi", name="Anil")

# 5️⃣ Variable-length Arguments (*args, **kwargs)
def show_args(*args):   # args → tuple
    print(args)
show_args(1, 2, 3)      # (1, 2, 3)

def show_kwargs(**kwargs):  # kwargs → dict
    print(kwargs)
show_kwargs(name="Anil", age=25)  # {'name': 'Anil', 'age': 25}

# 6️⃣ *args and **kwargs Together
def mix_args(*args, **kwargs):
    print("Args:", args)
    print("Kwargs:", kwargs)
mix_args(1, 2, 3, name="Anil", age=25)

# 7️⃣ Lambda Functions (Anonymous Functions)
square = lambda x: x * x
print(square(5))  # 25

# 8️⃣ Functions Returning Multiple Values
def calc(a, b):
    return a + b, a - b
sum_, diff = calc(5, 3)
print(sum_, diff)  # 8 2

# 9️⃣ Scope – local, global, nonlocal
x = 10
def outer():
    global x
    x = 20
outer()
print(x)  # 20

# Nonlocal example
def outer_fn():
    y = 5
    def inner_fn():
        nonlocal y
        y += 1
        return y
    return inner_fn()
print(outer_fn())  # 6

# 🔟 Function Annotations (Hints)
def multiply(a: int, b: int) -> int:
    return a * b
print(multiply(3, 4))  # 12

# 1️⃣1️⃣ Nested Functions
def main_func():
    def helper():
        return "I'm inside!"
    return helper()
print(main_func())  # I'm inside!

# 1️⃣2️⃣ Passing Functions as Arguments
def apply_fn(fn, value):
    return fn(value)
print(apply_fn(lambda x: x**3, 2))  # 8

# 1️⃣3️⃣ Recursive Functions
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n-1)
print(factorial(5))  # 120
```

## 4. Modules & Packages – Importing, Creating, and Using
```python
# 1️⃣ Importing Entire Module
import math
print(math.sqrt(16))  # 4.0

# 2️⃣ Import Specific Function/Class
from math import sqrt
print(sqrt(25))  # 5.0

# 3️⃣ Import with Alias
import math as m
print(m.pi)  # 3.141592653589793

# 4️⃣ Import Multiple Items
from math import sin, cos
print(sin(0), cos(0))  # 0.0 1.0

# 5️⃣ Import All (⚠️ Not Recommended - pollutes namespace)
from math import *

# 6️⃣ Standard Library Examples
import random
print(random.randint(1, 10))  # Random integer

import datetime
print(datetime.date.today())  # Current date

# 7️⃣ Creating Your Own Module
# 📄 mymodule.py
# def hello():
#     print("Hello from module!")

# 📄 main.py
# import mymodule
# mymodule.hello()  # Hello from module!

# 8️⃣ Using from ... import for Your Module
# from mymodule import hello
# hello()

# 9️⃣ Packages – Folder with __init__.py
# 📁 mypackage/
# ├── __init__.py
# ├── module1.py
# └── module2.py
# Then in another file:
# from mypackage import module1
# module1.function_name()

# 🔟 The __name__ Variable
# 📄 script.py
# def run():
#     print("Running script!")

# if __name__ == "__main__":
#     run()
# → Ensures code runs only when executed directly, not when imported
```

## 5. File Handling – Reading, Writing, and Managing Files in Python
```python
# `with` statement (context manager)
# 1️⃣ Writing to a file (overwrite mode)
with open("example.txt", "w") as f:
    f.write("Hello File!")  # Overwrites existing content

# 2️⃣ Reading the entire file
with open("example.txt", "r") as f:
    content = f.read()
    print(content)  # Output: Hello File!

# 3️⃣ Reading line by line
with open("example.txt", "r") as f:
    for line in f:
        print(line.strip())

# 4️⃣ Reading all lines into a list
with open("example.txt", "r") as f:
    lines = f.readlines()
    print(lines)  # ['Hello File!\n']

# 5️⃣ Appending to a file
with open("example.txt", "a") as f:
    f.write("\nAppending a new line.")

# 6️⃣ Writing multiple lines
with open("example.txt", "w") as f:
    f.writelines(["Line 1\n", "Line 2\n"])

# 7️⃣ File modes:
# "r" – Read (default)
# "w" – Write (overwrite)
# "a" – Append
# "r+" – Read & Write
# "b" – Binary mode (e.g., "rb", "wb")

# 8️⃣ Reading/Writing binary files
with open("image.jpg", "rb") as f:
    img_data = f.read()

with open("copy.jpg", "wb") as f:
    f.write(img_data)

# 9️⃣ Checking if file exists before opening
import os
if os.path.exists("example.txt"):
    print("File exists!")
else:
    print("File not found!")

# 🔟 Deleting a file
os.remove("example.txt")
```

## 6. Exception Handling – try, except, else, finally, raise, custom exceptions
```python
# 1️⃣ Basic try-except
try:
    num = int("abc")
except ValueError:
    print("Invalid number!")  # Invalid number!

# 2️⃣ Multiple except blocks
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
except ValueError:
    print("Invalid value!")

# 3️⃣ Multiple exceptions in one except
try:
    x = int("abc")
except (ValueError, TypeError):
    print("Invalid data type or value!")

# 4️⃣ try-except-else (else runs if no exception)
try:
    num = int("42")
except ValueError:
    print("Invalid number!")
else:
    print("Conversion successful!")  # Conversion successful!

# 5️⃣ try-finally (finally always runs)
try:
    f = open("test.txt", "w")
    f.write("Hello")
finally:
    f.close()  # Always executes

# 6️⃣ try-except-finally
try:
    num = int("abc")
except ValueError:
    print("Invalid number!")
finally:
    print("Done.")  # Done.

# 7️⃣ Raising exceptions manually
def check_age(age):
    if age < 18:
        raise ValueError("Too young!")
check_age(20)  # Works fine, no exception

# 8️⃣ Raising built-in exceptions with custom messages
raise ZeroDivisionError("You tried to divide by zero!")

# 9️⃣ Creating custom exceptions
class MyError(Exception):
    """Custom exception for demonstration."""
    pass

# Example usage
try:
    raise MyError("Something went wrong!")
except MyError as e:
    print(f"Caught custom error: {e}")

# 🔟 Exception chaining (useful for debugging)
try:
    int("abc")
except ValueError as e:
    raise RuntimeError("Failed to parse integer") from e
```

## 7.  Comprehensions – Pythonic One-Liners for Creating Collections
```python
# List, Tuple, Set, Dict Comprehensions
# 1️⃣ List Comprehension – Create a list from an iterable
nums = [x**2 for x in range(5)]
print(nums)    #  [0, 1, 4, 9, 16]

# 2️⃣ Tuple Comprehension – Uses generator expression inside tuple()
tuple_comp = tuple(x**2 for x in range(5))
print(tuple_comp)  #  (0, 1, 4, 9, 16)

# 3️⃣ Set Comprehension – Automatically removes duplicates
unique = {x for x in [1, 2, 2, 3]}
print(unique)  #  {1, 2, 3}

# 4️⃣ Dictionary Comprehension – Key:Value pairs
squares = {x: x**2 for x in range(3)}
print(squares)  # {0: 0, 1: 1, 2: 4}

# 5️⃣ Conditional Comprehensions – Filtering inside comprehension
even_nums = [x for x in range(10) if x % 2 == 0]
print(even_nums)  # [0, 2, 4, 6, 8]

# 6️⃣ Conditional Expressions – Value selection within comprehension
num_types = ["even" if x % 2 == 0 else "odd" for x in range(5)]
print(num_types)  # ['even', 'odd', 'even', 'odd', 'even']

# 7️⃣ Nested Comprehensions – Flattening lists
matrix = [[1, 2], [3, 4], [5, 6]]
flat = [num for row in matrix for num in row]
print(flat)   # [1, 2, 3, 4, 5, 6]
```
---
---
# 3. 📚 Advanced – Deep Python
At this stage, you focus on powerful features and patterns.

## 1. Object-Oriented Programming (OOP)
```Python
# `__init__` Constructor --> is a special method (a dunder method) in Python classes. It runs automatically when you create an object from a class. It is mainly used to initialize (set) the object’s attributes.
class Student:
    def __init__(self, name, roll_no): # Attributes (instance variables)
        self.name = name
        self.roll_no = roll_no

# Creating an object calls __init__
s1 = Student("Ravi", 101)
s2 = Student("Anil", 102)

print(s1.name, s1.roll_no)  # Ravi 101
print(s2.name, s2.roll_no)  # Anil 102


# Class & Object --> A class is a blueprint; objects are instances created from it.
class Person:
    def __init__(self, name, age):     # Constructor
        self.name = name
        self.age = age

    def greet(self):                   # Instance method
        return f"Hello, my name is {self.name}."

p1 = Person("Anil", 25)
print(p1.greet())  # Hello, my name is Anil.

# Inheritance --> One class (child) can inherit methods/attributes from another (parent).
class Student(Person):
    def __init__(self, name, age, grade):
        super().__init__(name, age)     # Call parent constructor
        self.grade = grade

    def greet(self):  # Method overriding
        return f"I am {self.name}, a student in grade {self.grade}."

s1 = Student("Ravi", 20, "A")
print(s1.greet())    # I am Ravi, a student in grade A.

# Multiple Inheritance --> A class can inherit from more than one parent class.
class A:
    def method_a(self): print("Method A")
class B:
    def method_b(self): print("Method B")
class C(A, B): pass

c = C()
c.method_a()  # Method A
c.method_b()  # Method B

# Encapsulation --> Restricting access to data using _protected and __private naming.
class Demo:
    def __init__(self):
        self._protected = "Protected"
        self.__private = "Private"

d = Demo()
print(d._protected)      # Accessible, but should be treated as protected
# print(d.__private)     # Error – Name mangling
print(d._Demo__private)  # Access via mangled name

# Class & Static methods
# @classmethod works with the class (cls).
# @staticmethod doesn’t depend on instance/class data.

class MyClass:
    count = 0

    @classmethod
    def increment(cls):
        cls.count += 1

    @staticmethod
    def hello():
        print("Hello from static method!")

MyClass.increment()
print(MyClass.count)  # 1
MyClass.hello()

# @property --> Allows you to access a method as if it were an attribute.
class Circle:
    def __init__(self, radius):
        self._radius = radius

    @property
    def area(self):
        return 3.14 * self._radius**2

c = Circle(5)
print(c.area)  # 78.5 (no parentheses)

# Magic/Dunder Methods --> Special methods like __len__, __str__ customize object behavior.
class MyList:
    def __init__(self, items):
        self.items = items
    def __len__(self):
        return len(self.items)
    def __str__(self):
        return f"MyList({self.items})"

ml = MyList([1, 2, 3])
print(len(ml))  # 3
print(ml)       # MyList([1, 2, 3])
```
## 2. Iterators & Generators
```python
# Iterator --> Object with __iter__() & __next__() that returns values one at a time.
class Counter:
    def __init__(self, low, high):
        self.current = low
        self.high = high
    def __iter__(self):
        return self
    def __next__(self):
        if self.current > self.high:
            raise StopIteration
        val = self.current
        self.current += 1
        return val

for num in Counter(1, 3):
    print(num)   # 1 2 3

# Generator --> Function with `yield` keyword — returns values lazily, remembers state.
def count_up_to(n):
    count = 1
    while count <= n:
        yield count
        count += 1

for num in count_up_to(3):
    print(num)  # 1 2 3

# Generator expression --> Like list comprehension but with () — more memory efficient.
gen_exp = (x**2 for x in range(5))
print(list(gen_exp))  # [0, 1, 4, 9, 16]

```
 ## 3. Decorators
 ```python
 # Function decorator --> A function that modifies another function’s behavior.
def my_decorator(func):
    def wrapper():
        print("Before function")
        func()
        print("After function")
    return wrapper

@my_decorator       # is syntactic sugar for: say_hello = my_decorator(say_hello)
def say_hello():
    print("Hello!")
say_hello()

# Output: Before function runs
#         Hello!
#         After function runs


# Chaining Multiple Decorators --> Applying multiple decorators to one function.
def uppercase_decorator(func):
    def wrapper():
        result = func()
        return result.upper()
    return wrapper

def exclamation_decorator(func):
    def wrapper():
        result = func()
        return result + "!!!"
    return wrapper

@uppercase_decorator
@exclamation_decorator
def say_message():
    return "hello world"

print(say_message())

# Output: HELLO WORLD!!!

#🔹 Order matters:
First exclamation_decorator runs,
Then uppercase_decorator.
```
## 4. Context Managers
```python
# Using `with` statement --> Ensures resources (like files) are closed automatically
with open("file.txt", "w") as f:
    f.write("Hello Context Manager!")

# Creating custom context managers (__enter__, __exit__) --> Define __enter__ and __exit__ to control setup/cleanup.
class MyContext:
    def __enter__(self):
        print("Enter")
        return self
    def __exit__(self, exc_type, exc_val, exc_tb):
        print("Exit")

with MyContext() as mc:
    print("Inside block")
```
## 5. Functional Programming
```python
# map, filter, reduce

from functools import reduce
nums = [1, 2, 3, 4]
print(list(map(lambda x: x*2, nums)))       # [2, 4, 6, 8]
print(list(filter(lambda x: x%2==0, nums))) # [2, 4]
print(reduce(lambda a, b: a+b, nums))       # 10


# Closures --> Inner function remembers variables from outer function.
def outer(x):
    def inner(y):
        return x + y
    return inner

add5 = outer(5)
print(add5(10))  # 15

# Partial functions --> Pre-fill some arguments for a function.
from functools import partial
def power(base, exponent):
    return base ** exponent

square = partial(power, exponent=2)
print(square(5))  # 25

```
## 6. Error Logging
```python
# `logging` module --> Use logging to display messages with different severity levels.
import logging
logging.basicConfig(level=logging.INFO)
logging.info("This is an info message")
logging.warning("This is a warning")
logging.error("This is an error")
```
## 7. Type Hints
```python
# `typing` module basics --> Provide expected data types for clarity and error prevention.
from typing import List, Dict

def greet(name: str) -> str:
    return f"Hello, {name}"

def total(numbers: List[int]) -> int:
    return sum(numbers)

def get_user() -> Dict[str, str]:
    return {"name": "Anil", "city": "Delhi"}
```
