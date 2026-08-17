# Retail Sales SQL Analysis

## 📊 Project Overview

This project analyzes retail sales data using **Microsoft SQL Server** to identify sales trends, customer behavior, category performance, and transaction patterns.

The project covers the complete SQL data analysis workflow, including **database creation, data loading, data exploration, data cleaning, aggregation, window functions, date/time analysis, and business-oriented SQL queries**.

The objective is to transform raw retail transaction data into meaningful business insights that can support sales and customer-related decisions.

---

## 🛠️ Tools & Technologies

* **SQL Server**
* **SQL Server Management Studio (SSMS)**
* **SQL**
* CSV Dataset

### SQL Concepts Used

* `SELECT`
* `WHERE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* Aggregate Functions
* `COUNT()`
* `SUM()`
* `AVG()`
* `COUNT(DISTINCT)`
* `CASE WHEN`
* Date & Time Functions
* `YEAR()`
* `MONTH()`
* `DATEPART()`
* Common Table Expressions (CTEs)
* Window Functions
* `RANK()`
* Data Cleaning
* Data Filtering
* Subqueries

---

## 📁 Dataset

The dataset contains retail transaction-level information, including:

| Column         | Description                   |
| -------------- | ----------------------------- |
| transaction_id | Unique transaction identifier |
| sale_date      | Date of sale                  |
| sale_time      | Time of sale                  |
| customer_id    | Unique customer identifier    |
| gender         | Customer gender               |
| age            | Customer age                  |
| category       | Product category              |
| quantity       | Quantity purchased            |
| price_per_unit | Price per unit                |
| cogs           | Cost of goods sold            |
| total_sale     | Total transaction value       |

---

## 🔍 Project Workflow

### 1. Database & Table Creation

Created a `retail_sales` table in SQL Server to store the transaction data.

### 2. Data Loading

Imported the CSV dataset into SQL Server using `BULK INSERT`.

### 3. Data Exploration

Performed initial exploration to understand:

* Total number of transactions
* Number of unique customers
* Available product categories
* Dataset structure

### 4. Data Cleaning

Checked the dataset for missing values in important columns such as:

* Sale date
* Sale time
* Gender
* Age
* Category
* Quantity
* Price per unit
* COGS
* Total sales

Rows containing missing critical values were removed where appropriate.

---

## 📈 Business Questions & SQL Analysis

The project answers the following business questions:

### Q1. Sales on a Specific Date

Retrieved all transactions made on **November 5, 2022**.

### Q2. High-Quantity Clothing Sales

Identified clothing transactions where the quantity sold was greater than 10 during November 2022.

### Q3. Sales by Category

Calculated total sales for each product category to identify category-level performance.

### Q4. Average Customer Age — Beauty Category

Calculated the average age of customers who purchased products from the Beauty category.

### Q5. High-Value Transactions

Identified transactions where total sales exceeded **1000**.

### Q6. Transactions by Gender and Category

Analyzed the number of transactions across different genders and product categories.

### Q7. Best-Selling Month

Calculated monthly average sales and identified the best-performing month for each year using the `RANK()` window function.

### Q8. Top 5 Customers

Identified the top 5 customers based on their total purchase value.

### Q9. Unique Customers by Category

Calculated the number of unique customers purchasing from each product category.

### Q10. Sales by Time of Day

Classified transactions into:

* Morning
* Afternoon
* Evening

and analyzed the number of orders in each shift.

---

## 💡 Key Insights

The analysis can be used to identify:

* Which product categories generate the highest sales
* Which months perform best
* The highest-value customers
* Customer purchasing patterns
* Category preferences by gender
* High-value transactions
* Unique customer reach by category
* The busiest time periods during the day

> **Note:** Add your actual numerical findings here after running the SQL queries. Avoid adding estimated numbers.

Example:

* **Top-performing category:** `[Category]`
* **Highest-sales month:** `[Month, Year]`
* **Top customer:** `[Customer ID]`
* **Highest number of orders:** `[Shift]`
* **Category with highest unique customers:** `[Category]`

---

## 📂 Project Files

```text
Retail-Sales-SQL-Analysis/
│
├── README.md
│
├── SQL/
│   └── retail_sales_analysis.sql
│
├── Dataset/
│   └── retail_sales.csv
│
└── Screenshots/
    └── query_results.png
```

---

## 🚀 How to Run the Project

1. Install **Microsoft SQL Server** and **SQL Server Management Studio (SSMS)**.
2. Create a database for the project.
3. Open `retail_sales_analysis.sql`.
4. Create the `retail_sales` table.
5. Import the CSV dataset.
6. Run the data exploration and cleaning queries.
7. Execute the business analysis queries.
8. Review the results.

### Important

If using `BULK INSERT`, update the CSV file path in the SQL script:

```sql
FROM 'YOUR_FILE_PATH\retail_sales.csv'
```

---

## 🎯 Skills Demonstrated

This project demonstrates my ability to:

* Work with relational databases
* Clean and validate raw data
* Write analytical SQL queries
* Perform customer and sales analysis
* Use aggregate functions
* Analyze date and time-based trends
* Use CTEs and window functions
* Translate business questions into SQL queries
* Generate actionable insights from transactional data

---

## 👨‍💻 Author

**Harish Babu**

B.Tech Graduate | Aspiring Data Analyst

### Technical Skills

**SQL | Power BI | Microsoft Excel | Python**

---

⭐ If you find this project useful, feel free to explore the SQL queries and analysis.
