# 📊 SQL Practice Notebook

This project contains a Jupyter Notebook focused on learning and practicing SQL queries. It covers fundamental to intermediate SQL concepts with examples and explanations.

---

## 🚀 Features

- Basic SQL queries (SELECT, WHERE, ORDER BY)
- Data filtering and sorting
- Aggregate functions (COUNT, SUM, AVG)
- Joins (INNER, LEFT, RIGHT)
- Grouping and conditions (GROUP BY, HAVING)
- Hands-on query examples

---

## 🛠️ Tech Stack

- Python (Jupyter Notebook)
- SQL
- SQLite / MySQL (depending on your setup)

---

## 📂 Project Structure


sql_1).ipynb   # Main notebook with SQL queries and examples


---

## ▶️ How to Run

1. Clone the repository:
bash
git clone https://github.com/your-username/sql-notebook.git


2. Open Jupyter Notebook:
bash
jupyter notebook


3. Open the file:

sql_1).ipynb


4. Run cells step by step to see outputs.

---

## 📸 Sample Queries

sql
SELECT * FROM users;

SELECT name, age 
FROM users 
WHERE age > 18;

SELECT COUNT(*) 
FROM users;


---

## 🎯 Purpose

This notebook is created for:
- Learning SQL from basics
- Practicing queries
- Preparing for exams or interviews

---

## 📌 Future Improvements

- Add advanced queries (Subqueries, Indexing)
- Connect with real datasets
- Build mini SQL projects

---

## 🤝 Contributing

Feel free to fork this repo and add more SQL examples or improvements.

---

## 📄 License

This project is open-source and available under the MIT License.






# Database Schema Diagram

## Schema Diagram

```
+-------------------+
|      STUDENTS     |
+-------------------+
| id (PK)           |
| name              |
| age               |
| email             |
+-------------------+
          |
          | FK
          v
+-------------------+
|    ENROLLMENT     |
+-------------------+
| enroll_id (PK)    |
| student_id (FK)   |
| course_id (FK)    |
+-------------------+
          |
          | FK
          v
+-------------------+
|      COURSES      |
+-------------------+
| course_id (PK)    |
| course_name       |
| duration          |
+-------------------+
```

## Tables Description

### Students Table
- id → Primary Key
- name → Student Name
- age → Student Age
- email → Student Email

### Courses Table
- course_id → Primary Key
- course_name → Course Name
- duration → Course Duration

### Enrollment Table
- enroll_id → Primary Key
- student_id → Foreign Key
- course_id → Foreign Key
