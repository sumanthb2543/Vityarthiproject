# Finance Tracking

# Overview of the project 
This code implements a simple command-line expense tracker using two classes:
Expense, which stores individual expense details (date, description, amount), 
and ExpenseTracker, which manages a list of expenses and provides functions to add
, remove, display, and total them. The main() function creates an interactive menu 
that allows the user to perform these actions in a loop until they choose to exit.

# Features
This expense tracker provides core features such as adding new expenses with a date, 
description, and amount; removing an expense by its index; viewing a formatted list of all recorded expenses;
and calculating the total amount spent. It also includes an interactive menu-driven interface that lets users 
perform these actions repeatedly until they choose to exit.

# Technological/tools used
This program is built entirely using Python, relying on fundamental language features such as classes, object-oriented programming, 
lists for data storage, string formatting, and basic input/output for user interaction. It does not use any external libraries or frameworks—only Python’s
built-in capabilities to create a simple, console-based expense tracking tool.

#  Steps to install and run the project
To install and run this project, you simply need to have Python installed on your computer; no additional libraries are required.
Save the code in a file—for example, expense_tracker.py—and open a terminal or command prompt in the folder where the file is located. 
Then run the program using the command python expense_tracker.py (or python3 expense_tracker.py depending on your setup). 
The script will start immediately and display the interactive menu, allowing you to add, view, remove, and total expenses.

# Instructions for testing
To test the project, first run the script and interact with the menu by adding several expenses with different dates,
descriptions, and amounts to confirm that they are stored and displayed correctly. 
Next, test the removal feature by deleting an existing expense and checking that the list updates as expected,
as well as attempting to remove an invalid index to verify error handling. You should also view the expenses list after multiple operations
to ensure consistency, and finally use the total-expenses 
option to confirm that the sum of all recorded amounts is calculated accurately.

# Screenshots
Main menu

adding the expense

Expense tracker

showing monthly or yearly expense 
 
