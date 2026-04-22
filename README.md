# -
# 📚 Library-Management-System-SQL-Project (PostgreSQL)

## 📌 Project Overview
This project demonstrates the design and implementation of a **Library Management System using SQL**. It focuses on managing books, members, employees, and transactions such as book issuance and returns.

The project also showcases the use of **stored procedures, joins, and analytical queries** to solve real-world business problems.

---

## 🎯 Objectives
- Design a relational database for a library system  
- Perform CRUD operations (Create, Read, Update, Delete)  
- Implement stored procedures for automation  
- Use CTAS (Create Table As Select) for reporting  
- Write advanced SQL queries for insights  

---

## 🗂️ Database Details
- **Database Name:** `library_db`
- **Technology Used:** PostgreSQL

---

## 🧱 Tables Created
The database consists of the following tables:

- `branch` → Stores branch details  
- `employees` → Employee information  
- `members` → Library members data  
- `books` → Book inventory  
- `issued_status` → Book issue records  
- `return_status` → Book return records  

Each table is connected using **primary and foreign keys**.

---

## ⚙️ Key Features

### 🔹 1. CRUD Operations
- Insert new book records  
- Update member details  
- Delete issued records  
- Retrieve books issued by employees  

---

### 🔹 2. Stored Procedures

#### ✅ Issue Book
- Checks if a book is available  
- If available → issues the book  
- Updates book status automatically  

#### ✅ Return Book
- Records returned books  
- Updates status to available  

---

### 🔹 3. Advanced SQL Queries
- Members who issued multiple books  
- Books not yet returned  
- Overdue books (more than 30 days)  
- Employee-wise issue tracking  

---

### 🔹 4. Reporting using CTAS
- `book_issued_cnt` → Number of times each book is issued  
- `branch_reports` → Branch performance summary  
- `active_members` → Members active in last 2 months  

---

## 📊 Sample Insights
- Identify high-demand books  
- Track overdue returns  
- Analyze branch performance  
- Measure employee productivity  

---

## 🚀 How to Run the Project

1. Clone the repository:

   
2. Execute SQL files in order:
- database_setup.sql  
- data_insertion.sql  
- analysis_queries.sql  

3. Run stored procedures and queries to test functionality.

---

## 🛠️ Tools & Skills Used
- PostgreSQL  
- SQL (DDL, DML, Joins, Group By)  
- Stored Procedures  
- CTAS (Create Table As Select)  

---

## 📈 Project Highlights
- End-to-end database design  
- Real-world business logic implementation  
- Use of stored procedures for automation  
- Data analysis using SQL queries  

---

## 🧠 Learning Outcomes
- Improved SQL query writing skills  
- Understanding of relational database design  
- Hands-on experience with stored procedures  
- Ability to derive insights from data  

---

## 👤 Author
**Sharvil Bookshet**  
Data Analyst  
🔗 GitHub: https://github.com/Sharvil19



