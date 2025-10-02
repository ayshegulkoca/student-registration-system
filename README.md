# Student Registration System

A simple yet powerful **Student Registration System** built with **Python** and **MySQL**. This project provides a **menu-driven interface** to manage student data — from creating tables to adding, updating, deleting, and displaying student records.

## Features
- Create and manage a student records table  
- Add new student records (roll number, name, stream, total, grade, class)  
- Update student details  
- Delete student records  
- Display all records in the database  
- Sort students by total score in descending order  
- View table schema and list of tables  
- Menu-driven command-line interface  

## Getting Started
### Prerequisites
- Python 3.x  
- MySQL Server  
- MySQL Connector for Python  

Install the connector via pip:

```bash
pip install mysql-connector-python
```

### Installation
Clone the repository:

```bash
git clone https://github.com/ayshegulkoca/student-registration-system.git
cd student-registration-system
```

Run the script:

```bash
python "Student Registration System.py"
```

## Usage
When you run the script, you will see a menu like this:

```
*********** STUDENT REGISTRATION SYSTEM *************
1: Show databases
2: Create a table
3: Show tables
4: Display table structure
5: Add a student record
6: Update a student record
7: Delete a student record
8: Display all student records
9: Sort students by total (descending)
10: Quit
```

Follow the prompts to perform CRUD operations and view student data.

## Project Structure
```
student-registration-system/
├── Images/                # Student images
├── Student Registration System.py
├── Student_data.xlsx
└── README.md
```

## How It Works
- Connects to a MySQL database
- Allows Create, Read, Update, Delete (CRUD) operations
- Supports sorting by total marks
- Provides a simple menu-driven interface

## Possible Improvements
- Add error handling and input validation
- Use a configuration file for database credentials
- Build a GUI (Tkinter or web-based)
- Implement search and filter functions
- Add export to CSV/Excel functionality
- Use an ORM (e.g., SQLAlchemy) for scalability

## Contributing
Contributions are welcome:

1. Fork the repository
2. Create a branch (git checkout -b feature/my-feature)
3. Commit your changes (git commit -m "Add feature")
4. Push the branch and open a Pull Request
