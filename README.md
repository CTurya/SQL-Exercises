# SQL Functions and Query Operations

## Overview

This repository contains a collection of SQL exercises that introduce essential SQL functions and query operations used for data analysis and database management. The exercises focus on performing calculations, manipulating dates, combining data from multiple tables, handling missing values, and merging query results.

These concepts form the foundation of writing efficient SQL queries for reporting, business intelligence, and data analytics.

---

## Learning Objectives

After completing these exercises, you should be able to:

* Use aggregate functions to summarize data.
* Apply SQL operators to filter and compare data.
* Manipulate and format dates using date functions.
* Retrieve related data using different types of joins.
* Handle NULL values effectively.
* Combine the results of multiple queries using `UNION` and `UNION ALL`.

---

# Exercises Covered

## Exercise 2 – SQL Aggregates and Operators

### Description

This exercise introduces aggregate functions used to summarize data and SQL operators used to filter and compare records.

### Topics Covered

### Aggregate Functions

* `COUNT()`
* `SUM()`
* `AVG()`
* `MIN()`
* `MAX()`

### SQL Operators

* Arithmetic Operators (`+`, `-`, `*`, `/`)
* Comparison Operators (`=`, `>`, `<`, `>=`, `<=`, `<>`)
* Logical Operators (`AND`, `OR`, `NOT`)
* `BETWEEN`
* `IN`
* `LIKE`

### Learning Outcomes

* Calculate totals and averages.
* Count records.
* Identify minimum and maximum values.
* Filter records using conditions.
* Combine multiple conditions in SQL queries.

---

## Exercise 3 – Date Functions

### Description

This exercise focuses on working with date and time values in SQL.

### Topics Covered

* Current date and time
* Extracting date components
* Date arithmetic
* Formatting dates
* Calculating date differences

### Common Functions

* `CURRENT_DATE`
* `CURRENT_TIMESTAMP`
* `NOW()`
* `YEAR()`
* `MONTH()`
* `DAY()`
* `DATEDIFF()`
* `DATEADD()` *(SQL Server)*

### Learning Outcomes

* Retrieve the current system date.
* Extract year, month, and day values.
* Calculate the difference between dates.
* Perform date calculations for reporting and analysis.

---

## Exercise 4 – Joins

### Description

This exercise introduces SQL joins, which combine related data from multiple tables based on common fields.

### Types of Joins Covered

### INNER JOIN

Returns matching records from both tables.

### LEFT JOIN

Returns all records from the left table and matching records from the right table.

### RIGHT JOIN

Returns all records from the right table and matching records from the left table.

### FULL OUTER JOIN *(where supported)*

Returns all matching and non-matching records from both tables.

### Learning Outcomes

* Combine data from multiple tables.
* Understand relationships between tables.
* Retrieve complete datasets using appropriate join types.
* Analyze relational data effectively.

---

## Exercise 5 – NULL Functions

### Description

This exercise focuses on handling missing or unknown values stored as `NULL`.

### Topics Covered

* Understanding NULL values
* Replacing NULL values
* Comparing NULL values

### Common Functions

* `COALESCE()`
* `IFNULL()` *(MySQL)*
* `ISNULL()` *(SQL Server)*
* `NULLIF()`

### Learning Outcomes

* Detect missing values.
* Replace NULL values with default values.
* Prevent NULL values from affecting calculations.
* Improve data quality and query reliability.

---

## Exercise 6 – UNION / UNION ALL

### Description

This exercise demonstrates how to combine the results of two or more `SELECT` statements.

### UNION

* Combines query results.
* Removes duplicate rows.
* Requires the same number of columns with compatible data types.

### UNION ALL

* Combines query results.
* Includes duplicate rows.
* Generally performs faster than `UNION` because duplicates are not removed.

### Learning Outcomes

* Merge data from multiple queries.
* Understand the difference between `UNION` and `UNION ALL`.
* Choose the appropriate operation based on reporting requirements.

---

# Skills Developed

By completing these exercises, you will develop the ability to:

* Summarize data using aggregate functions.
* Filter records using SQL operators.
* Work with date and time values.
* Retrieve related information using joins.
* Handle missing data using NULL functions.
* Combine datasets using `UNION` and `UNION ALL`.
* Write efficient and readable SQL queries.

---

# Prerequisites

Before attempting these exercises, you should be familiar with:

* Basic SQL syntax
* `SELECT` statements
* `FROM` clause
* `WHERE` clause
* `ORDER BY`
* Basic database concepts

---

# Applications

The SQL techniques covered in these exercises are commonly used in:

* Data Analytics
* Business Intelligence
* Database Administration
* Financial Reporting
* Sales and Marketing Analysis
* Inventory Management
* Customer Relationship Management (CRM)

---

# Conclusion

These exercises provide practical experience with fundamental SQL functions and query operations that are widely used in relational databases. Mastering aggregates, operators, date functions, joins, NULL handling, and query unions enables you to retrieve, manipulate, and analyze data effectively, forming a strong foundation for advanced SQL and data analytics.

---
