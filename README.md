# Decorators-in-python

Python Decorator Examples
This repository contains simple and clear examples to help you understand Python decorators, including:

Basic decorator structure

Decorators with arguments

Function wrapping concepts

📂 Files
1. Decorators_.py
This file demonstrates a basic decorator. It shows how a decorator wraps a function to execute code before and after the original function.

Key Concepts:
Basic decorator syntax

Wrapper function

Decorating a simple say_hello() function

Output Example:

pgsql
Copy
Edit
before function call
hello !
after function call
2. decorators_with_args.py
This file demonstrates how to use decorators with arguments. It includes a repeat(n) decorator that executes a function multiple times.

Key Concepts:
Parameterized decorators

Nested function structure

Repeated function calls

Example Usage:

python
Copy
Edit
@repeat(7)
def say_hello(name):
    print(f"Hello {name}")
Output Example:

python-repl
Copy
Edit
Hello Suraj
Hello Suraj
... (7 times total)
🧠 Learning Goals
Understand the concept and usage of decorators.

Learn how to build decorators with arguments.

Practice wrapping functions to add behavior.

🚀 Getting Started
Clone this repo and run each file using:

bash
Copy
Edit
python Decorators_.py
python decorators_with_args.py
📚 References
Python Docs - Decorators

Real Python - Python Decorators

Feel free to fork, experiment, and expand these examples!
Happy coding! 🚀
