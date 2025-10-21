#  Food Ordering App (Python)

##  Overview
This project is a simple food ordering application built with Python.  
It allows users to view a menu, select food items, place orders, and calculate the total bill.  
I created this project to practice basic Python concepts such as lists, functions, loops, and user input.

##  Objectives
- Learn how to build an interactive Python program.  
- Practice handling user input and performing calculations.  
- Display and manage menu items dynamically.  
- Simulate a basic food ordering experience in the terminal.

## Tools & Technologies
- **Language:** Python  
- **Environment:** VS Code / IDLE / Jupyter Notebook (any Python IDE)  
- **Concepts Practiced:** Functions, Loops, Conditional Statements, Lists, Dictionaries, Input & Output

##  Features
- Displays a list of available food items with prices.  
- Allows users to choose multiple items.  
- Automatically calculates the total order amount.  
- Option to place another order or exit the app.

## Sample Code Snippet
```python
menu = {"Burger": 3000, "Pizza": 6500, "Noodles": 1300}

print("Welcome to the Food App!")
for item, price in menu.items():
    print(f"{item}: ₦{price}")

order = input("What would you like to order? ")
if order in menu:
    print(f"Your total is {menu[order]}")
else:
    print("Sorry, item not available.")
