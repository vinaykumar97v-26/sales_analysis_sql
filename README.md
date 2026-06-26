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
SELECT * FROM Sales;

SELECT * FROM Sales
WHERE Category = 'Electronics';

SELECT Category, COUNT(*)
FROM Sales
GROUP BY Category;
```

## Learning Outcomes

* Database creation
* Data insertion
* Data filtering
* Aggregate functions
* SQL reporting queries
