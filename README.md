# IFQ564
Data structures and algorithms 

This project is a C# console application developed to manage the inventory of a not-for-profit Tool Library. The application provides a menu-driven interface for managing tools, recording tool rentals, and updating inventory in a structured and efficient way. It uses only built-in C# features and basic data structures and algorithms taught in this unit, without any third-party libraries.

The goal of this application is to solve a real-world problem using:
Core data structures and algorithms covered in class
Efficient inventory tracking
User input handling and structured data management

Functional Requirements
The system includes the following functionality:

✅ Display Tools by Type
View tools under any of the 9 predefined categories
Displays tool name, description, and quantity
Sorted alphabetically by tool name

✅ Add New Tools
If a tool already exists, update its quantity
If it is a new tool, input name, description, and quantity

✅ Lend Tools to a Person
Record the full name and phone number of the borrower
One or more tools can be borrowed from multiple categories
Tool availability is updated in real-time

✅ Return Tools
Return one or more tools at a time
Updates the inventory and removes the borrower record

✅ Command-Line Menu
Simple user interface for navigating and interacting with the system

🗂️ Tool Categories
Gardening tools
Flooring tools
Fencing tools
Measuring tools
Cleaning tools
Painting tools
Electronic tools
Electricity tools
Automotive tools

Tools are treated as identical if they have the same name, regardless of how many exist.

📦 Data Structures Used
Arrays / Lists – to store tools and borrower data
Dictionaries or nested lists – to manage tool categories and quick access
Sorting algorithm – to list tools alphabetically by name
Basic input validation – to ensure consistent, safe data entry
All data structures used conform to those taught in the unit — no external libraries are used.

🛠️ Technologies
C#
.NET Console Application
Visual Studio (recommended for development)
