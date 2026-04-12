# 🌀 06_Functions_Recursion

Welcome to the **Functions and Recursion** section!  
In this section, you’ll learn how to write **modular, reusable, and organized** code using functions — the foundation of clean and efficient Python programming.  
You’ll also explore **recursion**, an advanced concept where functions call themselves to solve complex problems elegantly.

---

## 📘 Overview

You will learn:

- How to **define and call functions** in Python.  
- The use of **parameters** and **return values**.  
- The concept of **local vs global variables** inside functions.  
- What **recursion** is and how to apply it to repetitive problems.  
- How to structure real-world programs efficiently using functions.

---

## 🧩 Folder Structure

```

├── 06_Functions_Recursion/
│   ├── 01_functions_basics.py
│   ├── 02_return_and_parameters.py
│   ├── 03_global_variables_functions.py
│   ├── 04_recursion_basics.py
│   ├── practice_scripts/
│   └── README.md

```

---

## 📂 Files Description

| File Name | Description |
|------------|-------------|
| `01_functions_basics.py` | Introduces what functions are, how to define them using `def`, and how to call them. |
| `02_return_and_parameters.py` | Demonstrates how to use **parameters** and **return statements** to make functions flexible and reusable. |
| `03_global_variables_functions.py` | Explains the difference between **local** and **global** variables, and how to use the `global` keyword. |
| `04_recursion_basics.py` | Introduces **recursion** — when a function calls itself — with examples like factorial and Fibonacci series. |

---

## 🧠 Example Code

```python
# Basic Function Example
def greet():
    print("Hello, welcome to Python learning!")

greet()  # Calling the function


# Function with Parameters and Return Value
def add_numbers(a, b):
    return a + b

result = add_numbers(5, 3)
print("Sum:", result)


# Local vs Global Variables
x = 10  # Global variable

def change_value():
    global x  # Accessing global variable
    x = 20
    print("Inside function, x =", x)

change_value()
print("Outside function, x =", x)


# Recursion Example – Factorial Function
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n - 1)

print("Factorial of 5:", factorial(5))
```

---

## 🧩 Practice Exercises

The `practice_scripts/` folder includes beginner-to-intermediate problems designed to reinforce your understanding of **functions** and **recursion**.

### Example Challenges:

* Write a function that checks whether a number is prime.
* Create a function that calculates the area of different shapes (circle, square, rectangle).
* Write a recursive function to calculate the factorial of a number.
* Build a recursive function to print Fibonacci numbers.
* Write a function that reverses a string using both loops and recursion.

---

## 🚀 Next Section

**Next Section →** [07_File_IO](../07_File_IO/README.md)

---
