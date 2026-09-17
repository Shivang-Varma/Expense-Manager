# Expense Manager

A console-based **Expense Manager** developed using Python for recording, managing, searching, and analyzing personal expenses. The project uses **CSV file handling** for data persistence.

## Features

* Add new expenses
* View all expenses
* Search expenses by name
* Delete expenses
* Calculate total expenses
* Calculate average expense
* Find the highest expense
* Calculate category-wise expenses
* Save expense data to CSV
* Load expense data from CSV
* Menu-driven console interface

## Technologies Used

* **Python**
* **CSV File Handling**
* **Lists & Dictionaries**
* **Functions**
* **Loops & Conditional Statements**
* **Exception Handling**

## Project Structure

```text
Expense-Manager/
│
├── expense_manager.py
├── README.md
└── .gitignore
```

> `expenses.csv` is generated when expense data is saved using the application.

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Expense-Manager.git
```

### 2. Open the Project Folder

```bash
cd Expense-Manager
```

### 3. Run the Program

```bash
python expense_manager.py
```

## Application Menu

```text
------ Expense Manager ------

1. Add Expense
2. View Expenses
3. Delete Expense
4. Category-wise Total
5. Total Expenses
6. Average
7. Search
8. Highest Expense
9. Save to CSV
10. Load from CSV
11. Exit
```

## Data Storage

Expense records are stored in memory using Python dictionaries and lists.

Each expense contains:

```text
Name
Amount
Category
```

Example:

```python
{
    "name": "Food",
    "amount": 250.0,
    "category": "Food"
}
```

The application uses Python's `csv` module to save and load expense records from `expenses.csv`.

## Learning Outcomes

This project helped in practicing:

* Python functions
* Lists and dictionaries
* Loops and conditional statements
* Searching and deleting data
* File handling
* CSV operations
* Exception handling
* Basic data analysis
* Menu-driven program design

## Future Improvements

* Add expense date and time
* Add expense IDs
* Add monthly expense analysis
* Add budget management
* Add MySQL database integration
* Add a graphical or web-based interface
* Add data visualization

## Author

**Shivang Varma**

Computer Engineering Student

