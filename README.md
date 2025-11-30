# sql-testing

![SQL](https://img.shields.io/badge/SQL-MySQL-blue)
![MySQL](https://img.shields.io/badge/Database-MySQL%208-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status: Completed](https://img.shields.io/badge/Status-Completed-brightgreen)

This project contains solutions to SQL tasks completed as part of a module in the **Kodilla "Automated Tester"** course focusing on **SQL**.
The exercises were performed using **MySQL**, focusing on understanding core database concepts, table operations, and CRUD queries.

The project was developed as part of the learning path for future **QA/Test Automation Engineers**.

---

## 📘 Description

The module covers the fundamentals of relational databases and SQL.  
Through practical exercises, you learn how to:

- understand database structure: tables, columns, primary keys  
- create tables  
- insert data  
- read data using `SELECT`  
- filter rows using `WHERE`  
- sort results using `ORDER BY`  
- update existing entries using `UPDATE`  
- delete records using `DELETE`  
- operate on conditions (`AND`, `OR`, `BETWEEN`, `LIKE`, `IN`)  
- work with numerical, textual, and date-based filters  
- understand database relations and data integrity basics  

Each task is saved as a separate `.txt` file containing SQL commands executed in MySQL.

---

## 📁 Project Structure
```
kodilla-sql/
├── Zadanie - lista zadań.txt
├── Zadanie - wyświetlanie zadań z listy.txt
├── Zadanie - modyfikacje zadań z listy.txt
├── README.md
└── LICENSE
```
---
## 🛠️ Getting Started

### Requirements

This project contains plain SQL exercises created during the SQL module of the Kodilla “Automated Tester” course.
To run SQL queries from this module, you need:

- **MySQL Server 8+**  
- **MySQL Command Line Client** *or* any GUI client (MySQL Workbench, DBeaver, DataGrip)

Note:  
- During installation of MySQL, an additional component — **MySQL Connector/J** — may be downloaded automatically.  
- It is used when connecting Java applications to a MySQL database via JDBC, but **it is not required for this module**, since all tasks were executed directly in MySQL console.

Since this module consists solely of SQL files, no build system (like Gradle or Maven) is required.

## Running the SQL Scripts
### 1. Start MySQL
```bash
mysql -u root -p
```
### 2. Create a database (optional)
```
CREATE DATABASE kodilla;
USE kodilla;
```
### 3. Execute SQL from tasks

Copy the SQL commands from the selected .txt file and paste them directly into the MySQL console.

Example:
```
SELECT * FROM tasks;
```

## Tasks Overview
- Zadanie – lista zadań - Creating a table to store a list of tasks and inserting example records.
- Zadanie – wyświetlanie zadań z listy - Reading data using SELECT, filtering with WHERE, sorting with ORDER BY.
- Zadanie – modyfikacje zadań z listy - Updating records with UPDATE, removing items with DELETE, modifying table content.
---
## Help

If MySQL does not start, try:
```
sudo service mysql start
```

To check available databases:
```
SHOW DATABASES;
```
---

## Authors

Created by:

**Joanna Kamińska**  
GitHub: https://github.com/joanna-kaminska-qa

---

## Version History

- **0.2** – README added, improved documentation
- **0.1** – Initial upload

---

## License

This project is licensed under the **MIT License**.  
See the `LICENSE` file for details.

---

## Acknowledgments
- Kodilla Automated Tester Java course
- MySQL official documentation
- SQL reference resources
