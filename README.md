# Sales Analysis SQL

A beginner SQL project built with SQLite to practice database design and data analysis.

## Tech Stack

* SQL
* SQLite
* DB Browser for SQLite
* Git & GitHub

## Features

* Create a sales database
* Insert sample sales data
* Filter records using `WHERE`
* Sort results using `ORDER BY`
* Summarize data using `SUM()`, `AVG()`, `COUNT()`
* Group data using `GROUP BY`

## Project Structure

```text
sales-analysis-sql/
├── README.md
├── sales_database.db
├── schema.sql
├── data.sql
├── queries.sql
└── screenshots/
```

## Sample Queries

```sql
-- Show all sales
SELECT * FROM Sales;

-- Show only Electronics
SELECT * FROM Sales
WHERE Category = 'Electronics';

-- Products costing more than 10000
SELECT Product, Price
FROM Sales
WHERE Price > 10000;

-- Total quantity sold
SELECT SUM(Quantity)
FROM Sales;

-- Average price
SELECT AVG(Price)
FROM Sales;

-- Number of products in each category
SELECT Category, COUNT(*)
FROM Sales
GROUP BY Category;

-- Highest price
SELECT MAX(Price)
FROM Sales;

-- Lowest price
SELECT MIN(Price)
FROM Sales;

-- Sort by price (highest first)
SELECT *
FROM Sales
ORDER BY Price DESC;
```

## Learning Outcomes

* Database creation
* Data insertion
* Data filtering
* Aggregate functions
* SQL reporting queries
