# Budget Tracker

A simple command-line tool that helps you manage a shopping trip within a set budget.

## What it does

- Set a budget at the start
- Add items to a shopping list with their prices
- Calculates the total cost automatically
- Tells you if you're over or within budget

## How to run it

Make sure you have Python installed, then:
```
git clone https://github.com/yourname/budget-tracker
cd budget-tracker
python main.py
```

## Demo
```
Enter your budget: 50
Do you want to add items to your shopping list? (y/n): y
Enter the name of the item (or 'done' to finish): Apples
Enter the price of Apples: 3.99
Enter the name of the item (or 'done' to finish): Bread
Enter the price of Bread: 2.49
Enter the name of the item (or 'done' to finish): done

Total cost of your shopping list: $6.48
You are within your budget. Happy shopping!
```

## Requirements

- Python 3.x
- No external libraries needed

## What I learned from building this

This project uses core Python concepts including:

- **Variables & data types** — strings, floats, and booleans to store user input and prices
- **Conditionals** — `if/else` logic to compare total cost against the budget
- **Loops** — a `while` loop to keep adding items until the user is done
- **Lists & tuples** — storing each item and its price as a tuple inside a list
- **List comprehensions** — summing prices with a generator expression
- **User input & formatting** — `input()` for interaction, f-strings for clean output

I'm still early in learning Python and plan to keep improving and post more or improve this over time

