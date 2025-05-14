# 📊 MySQL Capstone Project

This repository contains the complete SQL capstone project developed using **MySQL Workbench**. It includes the database schema, data export, and a series of SQL queries for analysis. The project demonstrates proficiency in database design, data manipulation, and analytical querying using SQL.

---

## 📁 Project Structure

amazonsales_sales/
│
├── capstone_project.sql # SQL script including schema and data
├── ERD.png # Entity Relationship Diagram (if available)
├── queries.sql # SQL queries for analysis and reporting
├── report.pdf # (Optional) Project report or insights
└── README.md # Project documentation


---

## 🎯 Project Objective

The main goal of this capstone project is to perform in-depth analysis on a simulated Amazon sales dataset. Key objectives include:

- Designing and implementing a normalized relational database schema.
- Inserting and managing sample sales data.
- Writing complex SQL queries to derive insights.
- Performing aggregation, filtering, grouping, and joins.
- Generating reports for business decision-making.

---

## 🧰 Technologies Used

- **Database**: MySQL 8+
- **Tool**: MySQL Workbench
- **Languages**: SQL
- **Version Control**: Git, GitHub

---

## 🏁 Getting Started

### Prerequisites:
- Install [MySQL](https://dev.mysql.com/downloads/mysql/)
- Install [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
- Install [Git](https://git-scm.com/)

### Setup Instructions:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/mysql-capstone-project.git
   cd mysql-capstone-project

📈 Key Features
Normalized schema design.

Real-world Amazon sales data simulation.

Data cleansing and preparation.

Complex SQL queries with JOIN, GROUP BY, HAVING, CASE, CTE, etc.

Performance-optimized queries for reporting.

📊 Sample Queries

-- Top 5 Selling Products
SELECT product_name, SUM(quantity_ordered) AS total_sold
FROM sales
GROUP BY product_name
ORDER BY total_sold DESC
LIMIT 5;

📃 License
This project is submitted as part of a capstone academic requirement. All code and documentation are intended for educational use only.

💬 Feedback
Feel free to fork, open issues, or submit pull requests if you'd like to contribute or suggest improvements!


