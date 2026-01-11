# 📊 Databases and SQL for Data Science with Python — Final Assessment

This repository contains the **final assessment notebook** for the Coursera course  
**“Databases and SQL for Data Science with Python”** offered by **IBM**.

The project demonstrates the ability to use **SQL and Python together** to analyze
real-world datasets using a relational database.

---

## ✅ Project Overview

In this project, the following skills are demonstrated:

- Loading real-world datasets into a relational database
- Writing SQL queries to analyze data
- Using Python (Pandas & SQLite / DB2) to execute SQL
- Answering real data-science style questions using SQL

The notebook follows the official **IBM Coursera Final Assignment structure**.

---

## 📂 Datasets Used

This assessment uses three public datasets from the **`City of Chicago Open Data Portal`**:

| Dataset | Description |
|-------|------------|
| **Socioeconomic Indicators in Chicago** | Poverty, income, hardship index |
| **Chicago Public Schools** | School information and performance metrics |
| **Chicago Crime Data** | Reported crimes in Chicago |

These datasets are loaded into SQL tables and queried using    `SQL and Python`.

---

## 🛠 Tools & Technologies

- **Python**
- **SQLite** 
- **Pandas**
- **Jupyter Notebook**
- **ipython-sql**

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```
git clone https://github.com/zakiahmed85/Databases-and-SQL-for-Data-Science-python-IBM.git
cd Databases-and-SQL-for-Data-Science-python-IBM
```

## 2️⃣ Install Required Libraries

```
pip install pandas ipython-sql 
```
`sqlite3` is included with Python by default.

## 3️⃣ Run the Notebook

```
jupyter notebook "Databases & SQL With Python.ipynb"
```
You can also run the notebook using `VS Code` or `Google Colab`.

## 📌 Notebook Structure

The notebook is organized into the following sections:

### 🔹 1. Introduction & Setup
-   Import required Python libraries
-   Establish database connection

### 🔹 2. Load Datasets
-   Load CSV files into Pandas DataFrames
-   Create SQL tables
-   Insert data into the database

### 🔹 3. SQL Queries with Python
-   Execute SQL queries inside Python
-   Retrieve query results into Pandas DataFrames

### 🔹 4. Assignment Questions
-   Answer data analysis questions using SQL

---

# ❓ Typical Assessment Questions

The following are the types of questions you’ll answer in the notebook — these match the common assignment from the course.

### 📍 Basic SQL Queries

1. How many crimes are recorded in the CHICAGO_CRIME_DATA table?
2. ist community area names and numbers with per capita income below a threshold.

### 🔍 Intermediate SQL Questions

3. List all case numbers for crimes involving minors.
4. List all kidnapping crimes involving children.

### 🏫 Join & Aggregation

5. List the types of crimes that occurred at schools (without repetitions).
6. List school types with average safety score per type.

### 📊 Advanced Analysis

7. List the top 5 community areas with highest % households below poverty.
8. Which community area is most crime-prone?
9. Use a subquery to find the community area with the highest hardship index.
10. Find the community area with the most crimes using a subquery.

## 📌 How SQL and Python Work Together

Examples of how to run SQL inside Python:

### With SQLite
```
import sqlite3
conn = sqlite3.connect('FinalDB.db.db')
query = "select * from sqlite_master where type = 'table' " LIMIT 10;"
pd.read_sql(query, conn)
```
### With SQL Magic
```
%load_ext sql
%sql sqlite:///ChicagoDB.db
```
----
## ✨ Expected Skills Demonstrated

-   ✔ SQL querying and filtering
-   ✔ Joins between multiple tables
-   ✔ Aggregation and grouping
-   ✔ Subqueries and nested SQL
-   ✔ Python and Pandas for results visualization
---

## 📌 Conclusion

This assignment notebook helps practice real data science skills using SQL and Python in an interactive environment. Completing it shows proficiency in database concepts, querying, and data analysis — fundamentals for any data science role
 
### Author & Contact
### Jikiriya
Data Analyst

📧 Email:   zakkyzeeshan1931@gmail.com  

🔗 [LinkedIn](https://www.linkedin.com/in/zaki-ahmed85)