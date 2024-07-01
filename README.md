[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15353487&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

**1. Python Basics:**
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

What is Python?
Python is a high-level, interpreted programming language known for its simplicity and readability. It supports multiple programming paradigms and is widely used for web development, scientific computing, data analysis, artificial intelligence, and more.

Key Features:
-Easy-to-learn: Simple syntax that emphasizes readability and reduces the cost of -program maintenance.
-Interpreted: No need for compilation before execution, making development faster.
-Dynamic typing: Variables are not statically typed, which provides flexibility.
-Rich standard library: Extensive libraries and frameworks for various tasks.
-Cross-platform: Runs on Windows, macOS, Linux, and other platforms.

Use Cases examples:
-Web Development (Django, Flask)
-Data Analysis and Visualization (Pandas, Matplotlib)
-Machine Learning and AI (TensorFlow, PyTorch)
-Scripting and Automation

**2. Installing Python:**
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

Steps to Install (Windows)
-Download Python installer from python.org.
-Run the installer, 
-select "Add Python to PATH" during installation.

Verify Installation:
-Open a terminal or command prompt.
-Type python --version or python3 --version to check the installed version.

Set Up Virtual Environment:
-Install virtualenv using pip: pip install virtualenv.
-Create a virtual environment: virtualenv venv.
-Activate the virtual environment:
-Windows: venv\Scripts\activate
-macOS/Linux: source venv/bin/activate

**3. Python Syntax and Semantics:**
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

# Hello, World! program
print("Hello, World!")

Basic syntax elements: print() is a built-in function to output text.

**4. Data Types and Variables:**
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

Basic Data Types:
-int: Integer numbers (1, 2, 3)
-float: Floating-point numbers (3.14, 2.718)
-str: Strings ('hello', "world")
-bool: Boolean values (True, False)

Example Script:
# Variables of different data types
num = 10          # int
pi = 3.14159      # float
name = "John"     # str
is_student = True # bool

**5. Control Structures:**
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

# Example of if-else statement
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")

# Example of if-else statement
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")



**6. Functions in Python:**
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

Functions are blocks of organized, reusable code used to perform a single, related action.

# Function to add two numbers
def add_numbers(a, b):
    return a + b

# Calling the function
result = add_numbers(3, 5)
print("Sum:", result)

**7. Lists and Dictionaries:**
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

Lists vs. Dictionaries:
-Lists: Ordered collection of items accessed by index.
-Dictionaries: Unordered collection of key-value pairs.

# List of numbers
numbers = [1, 2, 3, 4, 5]

# Dictionary with key-value pairs
person = {'name': 'John', 'age': 30, 'city': 'New York'}

# Basic operations
print(numbers[0])        # Accessing list element
print(person['age'])     # Accessing dictionary value


**8. Exception Handling:**
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

this is the Handling errors gracefully during program execution.

# Example of try-except block
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Error: Division by zero")
finally:
    print("Execution completed")


**9. Modules and Packages:**
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

Modules: Python files containing functions and statements.
Packages: Directories of Python modules with __init__.py file.

# Importing math module
import math

# Using math module
print(math.sqrt(16))    # Square root function


**10.  File I/O:**
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

File Reading
# Reading from a file
with open('file.txt', 'r') as file:
    content = file.read()
    print(content)

File Writing
# Writing to a file
lines = ['Line 1\n', 'Line 2\n', 'Line 3\n']
with open('output.txt', 'w') as file:
    file.writelines(lines)

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


