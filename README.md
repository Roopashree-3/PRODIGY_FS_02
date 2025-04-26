 Employee Management System

This is a simple **Employee Management System** built using **Python**, **Tkinter (CustomTkinter)**, and **SQLite3**.  
It allows you to **Add**, **Update**, **Delete**, and **View** employees easily.

---

## Features 

- Add New Employees
- Update Existing Employee Details
- Delete Employees
- View All Employees in a Table
- Interactive and Beautiful UI with **CustomTkinter**
- SQLite3 database for storing data

---

## Installation 

1. **Clone the repository** or **download the source code**.

2. **Install required libraries** if not already installed:
   ```bash
   pip install customtkinter
   ```

3. **Run the application**:
   ```bash
   python app.py
   ```

---

## Project Structure 

```
├── app.py           # Main application file (UI + Functionality)
├── database.py      # Database connection and queries (SQLite3)
├── Employee.db      # SQLite3 database file (auto-created)
├── README.md        # Project Documentation
```

---

## Usage 

- **Add Employee**: Enter ID, Name, Role, Gender, and Status → Click **Add Employee**.
- **Update Employee**: Select an employee from the table → Edit fields → Click **Update Employee**.
- **Delete Employee**: Select an employee → Click **Delete Employee**.
- **New Employee**: Click **New Employee** to clear the form and add fresh data.

---



---

## Requirements 

- Python 3.x
- customtkinter
- sqlite3 (comes pre-installed with Python)

---

## Notes

- **Employee.db** database will be automatically created on the first run.
- IDs must be **unique**. The app will show an error if you try to add a duplicate ID.

---

## License 

This project is free to use for educational or personal purposes.

