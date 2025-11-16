# 🎓 University Academic Database Management System

A secure and user-friendly **Database Management System** built with **Python (Tkinter GUI)** and **MySQL** for managing university academic records.  
This project allows users to efficiently handle student, faculty, course, and department data — all within an intuitive graphical interface.

---

## 🚀 Features

- 🧑‍🎓 **Student Management:** Add, update, view, and delete student details.  
- 🧑‍🏫 **Faculty Management:** Maintain faculty records with relational data links.  
- 📚 **Course & Department Handling:** Manage course offerings and their assigned departments.  
- 🧩 **Tkinter GUI:** A simple and responsive interface for easy navigation.  
- 🔐 **Data Security:**  
  - Parameterized SQL queries used to prevent SQL Injection.  
  - Input validation to prevent data manipulation.  
- 💾 **MySQL Database Integration:** All records are securely stored and retrieved using MySQL.

---

## 🛠️ Tech Stack

| Component | Technology |
|------------|-------------|
| Frontend | Python (Tkinter) |
| Backend | MySQL |
| Database Connector | `mysql-connector-python` |
| Language | Python 3.x |

---

## ⚙️ Setup Instructions

### 1. Clone this Repository
```bash
2. Install Dependencies

Make sure Python is installed, then run:
pip install mysql-connector-python

3. Setup MySQL Database

Open your MySQL terminal or Workbench.

Create a database:
CREATE DATABASE university_db;


Import the provided .sql file (if included) or create required tables manually.

4. Run the Application
python university_db_gui.py
 GUI Overview
The interface includes:


Left Panel: Displays list of tables or categories (e.g., Students, Faculty, Courses).


Center Panel: Shows data records from the selected table.


Bottom Section: Buttons for Add, Edit, Delete, and Refresh.



🖼️ You can add screenshots here later for better visualization.


🔒 Security Measures


Sensitive database operations are handled using parameterized queries to prevent SQL Injection.


Proper input validation ensures data integrity.


User inputs are sanitized before database interaction.



📂 Project Structure
Uni_academic_DB_Python/
│
├── university_db_gui.py       # Main Python GUI file
├── db_config.sql              # Database schema (if applicable)
├── README.md                  # Project documentation
└── requirements.txt           # Dependencies list


🧑‍💻 Author
Bonita Batool
B.S. Artificial Intelligence
University Project — Database Management System in Python

🪪 License
This project is open-source and available under the MIT License.
Feel free to use, modify, and improve it.

⭐ If you like this project, don’t forget to star the repository!

---
cd Uni_academic_DB_Python
