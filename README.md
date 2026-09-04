# Python-Loops-Control-Functions

This repository contains Python programs demonstrating **loops, control flow statements, and functions**.

# Python Assignment – While Loop, For Loop, and Function

## Project Overview

This project is part of a Python assignment focused on understanding basic programming concepts through practical examples.

The assignment includes three programs:

1. Number Guessing Game using a `while` loop
2. Multiplication Table Generator using a `for` loop
3. BMI Calculator using a function

The programs were developed and executed using **Jupyter Notebook / Google Colab**.

---

## Objectives

The main objectives of this assignment are:

* To understand `while` and `for` loops.
* To use `range()` and control statements.
* To understand the `break` statement.
* To create and use Python functions.
* To work with user input and output.
* To perform basic calculations using Python.

---

## Tools and Technologies

* **Programming Language:** Python
* **Development Environment:** Jupyter Notebook / Google Colab
* **Python Concepts:** Loops, Functions, Control Statements
* **Python Library:** Random

---

# Tasks Performed

## Task 1: Number Guessing Game

### Problem Statement

A simple number guessing game was created using a `while` loop. The program generates a random number between **1 and 10**, and the user gets a maximum of **3 attempts** to guess the correct number.

### Concepts Used

* `while` loop
* `if`, `elif`, and `else`
* `break`
* `random.randint()`
* User input

### How It Works

1. A random number between 1 and 10 is generated.
2. The user enters a guess.
3. The program checks whether the guess is in range.
4. It displays whether the guess is correct, too high, or too low.
5. `break` stops the loop when the correct number is guessed.
6. The game allows a maximum of 3 attempts.

### Example

```text
Enter the guess number between 1 to 10: 3
Too low, try again

Enter the guess number between 1 to 10: 6
Congrats! You guessed the correct number
```

---

# Task 2: Multiplication Table Generator

### Problem Statement

A Python program was created to generate a multiplication table from **1 to 10** for a number entered by the user.

### Concepts Used

* `for` loop
* `range()` function
* User input
* Arithmetic operations
* f-strings

### How It Works

1. The user enters a number.
2. The `for` loop runs from 1 to 10 using `range(1, 11)`.
3. The number is multiplied by the current value of `i`.
4. The result is displayed using an f-string.

### Example

For the input `6`, the program produces:

```text
multiplication table for 6

6 * 1 = 6
6 * 2 = 12
6 * 3 = 18
6 * 4 = 24
6 * 5 = 30
6 * 6 = 36
6 * 7 = 42
6 * 8 = 48
6 * 9 = 54
6 * 10 = 60
```

---

# Task 3: BMI Calculator

### Problem Statement

A BMI Calculator was developed using a Python function. The program calculates Body Mass Index based on the user's weight and height.

### BMI Formula

```text
BMI = Weight (kg) / Height (m)²
```

### Concepts Used

* Function creation
* Parameters and `return`
* User input
* Arithmetic operations

### Function Used

```python
def calculate_bmi(weight, height):
    return weight / (height ** 2)
```

### How It Works

1. The `calculate_bmi()` function is defined.
2. The user enters weight in kilograms.
3. The user enters height in meters.
4. The function calculates and returns the BMI.
5. The calculated BMI is displayed.

### Example

```text
Enter the weight in kg: 71
Enter the height in metre: 1.65

Your BMI is: 26.07897153351699
```

---

# Python Concepts Demonstrated

| Concept               | Application            |
| --------------------- | ---------------------- |
| While Loop            | Number Guessing Game   |
| For Loop              | Multiplication Table   |
| If / Elif / Else      | Guess Checking         |
| Break                 | Stop the Guessing Game |
| Range                 | Multiplication Table   |
| Functions             | BMI Calculation        |
| Random Module         | Secret Number          |
| User Input            | All Tasks              |
| Arithmetic Operations | Calculations           |

---

# Project Structure

```text
Python-Loops-Control-Functions/
│
├── Python_Assignment_3.ipynb
│
└── README.md
```

### File Description

**Python_Assignment_3.ipynb**
Contains the implementation and output of all three tasks.

**README.md**
Contains the project overview, objectives, task descriptions, concepts used, and project structure.

---

# Learning Outcomes

After completing this assignment, I gained practical knowledge of:

* Using `while` and `for` loops.
* Applying control statements and `break`.
* Using `range()` for iteration.
* Creating functions with parameters and `return`.
* Taking user input and displaying output.
* Performing basic calculations using Python.

---

# Conclusion

This assignment provided practical experience with fundamental Python programming concepts. The **Number Guessing Game** demonstrated `while` loops and control statements, the **Multiplication Table Generator** demonstrated `for` loops and `range()`, and the **BMI Calculator** demonstrated functions and calculations.

These tasks helped strengthen my **Python fundamentals and logical problem-solving skills** for further learning in **Data Analytics and Python**.

## Created By

**Suganya D**
*Aspiring Data Analyst*

