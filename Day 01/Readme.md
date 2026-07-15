# 🧮 Day 01: Simple Calculator

A beginner-friendly Python project that performs basic arithmetic operations with three numbers based on user input.

![Python Version](https://img.shields.io/badge/Language-Python-blue?style=for-the-badge&logo=python&logoColor=white)
![Project Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge&logo=checkmarx&logoColor=white)
![Challenge Day](https://img.shields.io/badge/Challenge-Day%2001%20%2F%2030-orange?style=for-the-badge)

---

## 📝 Project Overview

This program takes three numbers as floating-point inputs from the user, asks for a specific arithmetic operation (`add`, `sub`, `mul`, `div`), and processes the numbers accordingly. It handles basic string matching to accept word commands (e.g., "Add", "Addition") as well as operators (e.g., "+"). It also includes basic error handling to prevent division by zero.

---

## 🧠 Concepts Practiced

By building this project, I practiced and applied the following fundamental Python building blocks:
- 📥 **`input()` Function:** Taking dynamic data from the console.
- 🔢 **Type Casting (`float`):** Converting string inputs into numbers to allow mathematical operations.
- 🔀 **Conditional Statements (`if-elif-else`):** Directing program flow based on user choices.
- 🤝 **Logical Operators (`or`, `!=`):** Evaluation of multiple target strings and checking boundary conditions.

---

## ⚙️ How It Works

1. Run the script `main.py`.
2. Enter three numbers when prompted.
3. Type the keyword or symbol for the operation you want to run.
4. The calculator displays the computed result or alerts you if the operation or input is invalid.

### 💻 Code Preview

```python
# Quick snippet of the main calculation logic
if Operator == "Add" or Operator == "Addition" or Operator == "+":
    print(a + b + c)
elif Operator == "Div" or Operator == "Division" or Operator == "/":
    if b != 0:
        print(a / b / c)
    else:
        print("Syntax Error")
```

## *🚀 Sample Input & Output:*
```
Enter First Number: 10
Enter Second Number: 5
Enter Third Number: 2
Enter operation (add/sub/mul/div): mul

Output: 100.0
```
## 📺 Watch the Short

See this code in action! Check out the quick breakdown and live demo on my YouTube Shorts:  
👉 **[App Hacks HQ - Day 01 Short](YOUR_YOUTUBE_SHORTS_LINK_HERE)**
