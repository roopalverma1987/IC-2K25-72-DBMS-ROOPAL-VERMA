# MySQL DBMS Assignment 2

## MCA – MySQL SELECT Queries

This repository contains **Assignment 2** for DBMS. The assignment focuses on MySQL `SELECT` queries, aliases, filtering, sorting, aggregate functions, string functions, calculations, and salary-related queries.

## Topics Covered

* `SELECT`
* Column aliases using `AS`
* `DISTINCT`
* `ORDER BY`
* Aggregate functions:

  * `SUM()`
  * `MAX()`
  * `MIN()`
  * `AVG()`
  * `COUNT()`
* String functions:

  * `UPPER()`
  * `SUBSTRING()`
  * `CONCAT()`
  * `TRIM()`
  * `LENGTH()`
* `REGEXP`
* `LIMIT`
* Arithmetic calculations
* Monthly salary calculation using `ROUND()`

## Database Details

**Database Name:** `assignment2_db`

**Table Name:** `employees`

The `employees` table contains the following fields:

* `employee_id`
* `first_name`
* `last_name`
* `email`
* `phone_number`
* `hire_date`
* `job_id`
* `salary`
* `department_id`

## Assignment Questions

The assignment contains **19 SQL queries** covering:

1. Displaying employee names using aliases
2. Finding unique department IDs
3. Sorting employee records by first name
4. Calculating PF as 15% of salary
5. Sorting employees by salary
6. Calculating total salary
7. Finding maximum and minimum salary
8. Finding average salary and number of employees
9. Counting employees
10. Counting available jobs
11. Displaying first names in uppercase
12. Extracting the first three characters of first names
13. Performing an arithmetic calculation
14. Combining first name and last name
15. Removing spaces using `TRIM()`
16. Finding the length of employee names
17. Checking first names for numbers using `REGEXP`
18. Selecting the first 10 records
19. Calculating monthly salary from annual salary

## Files

* `assignment2.sql` – SQL queries for the assignment
* `Q1.png` to `Q19.png` – Screenshots of query outputs

## Sample Data

The assignment uses sample employee data with Indian names for practicing the SQL queries.

## SQL Environment

The queries were executed using **MySQL Command Line Client**.

## Conclusion

This assignment provides practical practice with MySQL `SELECT` queries and commonly used SQL functions. It helps in understanding how to retrieve, sort, calculate, and format data from a database.
