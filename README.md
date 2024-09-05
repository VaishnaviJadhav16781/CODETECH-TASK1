TASK-1
Name: Vaishnavi Jadhav
Company: CodeTech IT Solutions PVT LTD
ID:CTO8DS6391
Domain: Python Programming
Duration: August 5th to September 5th
Mentor: Neela Santosh Kumar
OVERVIEW OF THE PROJECT:
PROJECT: Creating a Python program that acts as a basic calculator
Project Objective:
Build a simple calculator that can perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The user will be able to input two numbers and select the desired operation. The program will then display the result of the operation.

Core Features:
User Input:

Prompt the user to input two numbers.
Ask the user to choose an operation (e.g., addition, subtraction, multiplication, division).
Arithmetic Operations:

Implement functions to handle the four basic arithmetic operations:
Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
Display Results:

Perform the chosen operation on the two numbers.
Display the result to the user.
Error Handling:

Ensure the user inputs valid numbers.
Handle division by zero gracefully.
Program Loop:

Allow the user to perform multiple calculations until they choose to exit the program.
Extensions:
Add more operations: Include operations like exponentiation, modulus, etc.
Graphical Interface: Use a library like Tkinter to create a GUI for the calculator.
Enhance error handling: Handle more edge cases like invalid input (non-numeric).
Learning Outcomes:
Working with functions and modular programming.
Handling user input and validating it.
Using loops and conditional statements for program control.
Basic error handling techniques.
![Screenshot 2024-09-05 135531](https://github.com/user-attachments/assets/5aec97fb-4890-4076-a052-fff7f4ba3c2d)



TASK-2
Project Objective:
The main goal of this project is to create a system that streamlines library management by allowing administrators (librarians) to manage library resources and users to access and manage borrowed items.

Key Features:
Adding New Items:

The system supports the addition of different types of library items like Books, Magazines, and DVDs.
Each item has attributes like title, author, and category (Book, Magazine, or DVD).
These items can be added to the library's collection, allowing them to be available for checkout.
Checkout and Return Functionality:

Users can check out items, after which the item is marked as "checked out" and assigned a due date.
When returning items, the system calculates whether they are returned past their due date and applies overdue fines (e.g., $1 per day late).
Overdue Fines Management:

If an item is returned after the due date, a fine is calculated based on the number of overdue days.
The system notifies users of the fine amount and resets the status of the item to "available" once returned.
Search Functionality:

Users can search for items in the library by title, author, or category.
This feature allows users to easily locate the resources they need.
Display All Items:

Librarians or users can view the current status of all items in the library.
Items will either be displayed as "available" or "checked out" with the associated due date.
Technological Concepts Involved:
Object-Oriented Programming (OOP):

The system uses object-oriented principles to represent each library item (books, magazines, DVDs) as an object with attributes and behaviors.
Classes such as LibraryItem, Book, Magazine, and DVD encapsulate the properties and methods related to each item type.
Inheritance and Class Hierarchy:

The base class LibraryItem is inherited by subclasses such as Book, Magazine, and DVD. This allows for code reuse and makes the program easy to extend.
The Library class manages the collection of all items and their interactions (adding, searching, checking out, and returning).
Date and Time Handling:

The program uses the datetime module to handle due dates and calculate overdue periods.
Due dates are set automatically upon checkout (typically 14 days), and fines are applied based on how late the item is returned.
Error Handling and Validation:

The system handles various user inputs, such as invalid choices and incorrect item titles, by providing informative error messages.
It ensures that users can’t check out items that are already borrowed or return items that haven’t been checked out.
Program Control with Loops and Conditionals:

The system is designed to allow continuous user interaction until the user chooses to exit.
A while loop ensures that users can repeatedly perform operations (e.g., checking out or returning items).
Implementation Breakdown:
1. Library Items:
Each library item (book, magazine, DVD) has properties such as title, author, and category. It also has a status that indicates whether it’s available or checked out.
The check_out() and return_item() methods update the item's status, set due dates, and calculate overdue fines.
2. Library Management:
The Library class maintains a collection of all library items and provides methods to:
Add new items.
Search for items.
Check out and return items.
Display all items and their current status.
3. User Interface (CLI-based):
The system operates through a command-line interface where users can choose options from a menu (e.g., add items, check out, return, search, display).
The program keeps running until the user chooses to exit.
Extensions and Future Enhancements:
While this project provides basic functionality for library management, it can be extended in the future with additional features such as:

User Management: Track which users have borrowed items and integrate a system of user accounts.
Reservation System: Allow users to reserve items that are currently checked out.
Inventory Reports: Provide summaries of library statistics, such as most popular items, overdue reports, etc.
Graphical User Interface (GUI): Improve usability by building a graphical interface using libraries like Tkinter or PyQt.
Learning Outcomes:
Mastering OOP Concepts: By designing a system with classes, objects, inheritance, and methods, developers strengthen their understanding of object-oriented programming.
Working with Dates: Handling real-world time-based constraints (due dates and overdue fines) builds experience in using Python’s datetime module.
Error Handling and Data Validation: Ensuring the system behaves correctly under various conditions (invalid inputs, items already checked out, overdue items) reinforces good coding practices.
Developing Interactive CLI Applications: The project involves creating a menu-driven system that users can interact with, helping to understand program flow and user input handling.
Conclusion:
The Library Management System project is a great introduction to real-world software development problems. It combines core concepts like object-oriented programming, data management, and error handling in a way that mimics an actual system used in libraries, making it an excellent learning experience for beginner to intermediate Python programmers.
![Screenshot 2024-09-05 175505](https://github.com/user-attachments/assets/60e6e6aa-3943-48bb-bbbb-aa113457bf2f)


