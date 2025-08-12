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

### **Lists** – Ordered, mutable collections.
```python
nums = [10, 20, 30]
nums.append(40)      # Add element
nums.pop()           # Remove last
print(nums[1:])      # [20, 30]
```


# 📚 Intermediate Python Topics with Examples
This section covers **Core Python Skills** you’ll need to work with **collections, functions, and error handling** effectively.

## 1. Data Structures
```python
# Lists – Ordered, mutable collections.
nums = [10, 20, 30]
nums.append(40)      # Add element
nums.pop()           # Remove last
print(nums[1:])      # [20, 30]

# Tuples – Ordered, immutable collections.
coords = (10, 20)
print(coords[0])     # 10

# Sets – Unordered, unique items.
my_set = {1, 2, 2, 3}
print(my_set)        # {1, 2, 3}

# Dictionaries – Key-value pairs.
person = {"name": "Alice", "age": 25}
person["city"] = "Delhi"
print(person)        # {'name': 'Alice', 'age': 25, 'city': 'Delhi'}

# Nested Structures – Collections inside collections.
data = {"students": [{"name": "Anil", "marks": 90}]}
print(data["students"][0]["name"])  # Anil
```

## 2. Strings (Advanced)
```python
# String Methods
text = "hello world"
print(text.upper())         # HELLO WORLD
print(text.replace("world", "Python"))  # hello Python

# String Formatting
name = "Anil"
age = 25
print(f"My name is {name} and I am {age} years old.")
```

## 3. Functions
```python
# Defining & Calling Functions
def greet(name):
    return f"Hello, {name}!"
print(greet("Anil"))

# Parameters & Return Values
def add(a, b):
    return a + b
print(add(3, 4))  # 7

# Default, Keyword, Variable-length Arguments
def intro(name, age=18):
    print(f"{name} is {age} years old.")
intro("Anil")
intro("Anil", 25)

def show_args(*args, **kwargs):
    print(args)
    print(kwargs)
show_args(1, 2, 3, name="Anil", age=25)

# Lambda Functions
square = lambda x: x * x
print(square(5))  # 25

# Scope (local, global, nonlocal)
x = 10
def outer():
    global x
    x = 20
outer()
print(x)  # 20
```

## 4. Modules & Packages
```python
# Importing
import math
from math import sqrt
print(sqrt(16))  # 4.0

# Creating Your Own Module
# mymodule.py
# def hello():
#     print("Hello from module!")
# main.py
# import mymodule
# mymodule.hello()
```

## 5. File Handling
```python
# Opening, Reading, Writing
with open("example.txt", "w") as f:
    f.write("Hello File!")

with open("example.txt", "r") as f:
    print(f.read())
```

## 6. Exception Handling
```python
# try, except, else, finally
try:
    num = int("abc")
except ValueError:
    print("Invalid number!")
else:
    print("Conversion successful!")
finally:
    print("Done.")

# Raising Exceptions
def check_age(age):
    if age < 18:
        raise ValueError("Too young!")
check_age(20)

# Custom Exceptions
class MyError(Exception):
    pass
# raise MyError("Something went wrong!")
```

## 7. Comprehensions
```
# List, Set, Dict Comprehensions
nums = [x**2 for x in range(5)]
print(nums)  # [0, 1, 4, 9, 16]

unique = {x for x in [1, 2, 2, 3]}
print(unique)  # {1, 2, 3}

squares = {x: x**2 for x in range(3)}
print(squares)  # {0: 0, 1: 1, 2: 4}

# Conditional Comprehensions
even_nums = [x for x in range(10) if x % 2 == 0]
print(even_nums)  # [0, 2, 4, 6, 8]
