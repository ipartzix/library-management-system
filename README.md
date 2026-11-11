Library Management System

A command-line Library Management System developed using Python and Object-Oriented Programming (OOP). The application provides basic library operations, including book categorization, member authentication, user profile management, and book issuing workflows.

The project focuses on modular Python development and practical implementation of fundamental OOP concepts.

Features

- Book Management: Represent books using dedicated classes with attributes such as book ID, title, and author.
- Book Categorization: Organize and display books based on predefined categories.
- Member Authentication: Implement basic account creation and login functionality.
- Profile Management: Allow users to create and update their profile information.
- Book Issuing: Issue books to authenticated users with automatically calculated due dates.
- Book Search: Includes a placeholder for future book availability search functionality.

Project Structure

library-management-system/
│
├── LICENSE
├── README.md
├── requirements.txt
├── .gitignore
│
└── src/
    ├── book.py
    ├── books_data.py
    ├── library.py
    ├── main.py
    └── member.py

Technologies & Concepts

Language: Python 3

Programming Concepts:

- Object-Oriented Programming (OOP)
- Classes and Objects
- Encapsulation
- Inheritance
- Method Overriding
- "super()" and Constructor Inheritance
- Python Dictionaries and List Comprehensions
- Date and Time Operations

Interface: Command-Line Interface (CLI)

Data Handling: In-memory Python data structures.

Getting Started

Prerequisites

- Python 3.8 or higher
- Git

Installation

1. Clone the repository:

git clone https://github.com/ipartzix/library-management-system.git

2. Navigate to the project directory:

cd library-management-system

3. Run the application:

python src/main.py

Dependencies

This project currently uses Python's standard library and does not require any external dependencies.

Current Scope

The current implementation provides foundational library operations through a command-line interface. Book availability verification, return processing, fine calculation, and persistent data storage are not yet fully implemented.

Future Enhancements

- Complete book return and availability management.
- Implement overdue tracking and fine calculation.
- Introduce persistent storage using SQLite.
- Add automated unit testing.
- Improve input validation and exception handling.

Author

Partha Paul

- GitHub: "@ipartzix" (https://github.com/ipartzix)
- LinkedIn: "ipartzix" (https://linkedin.com/in/ipartzix)

---

Developed as a Python project to strengthen practical understanding of Object-Oriented Programming and software development fundamentals.
