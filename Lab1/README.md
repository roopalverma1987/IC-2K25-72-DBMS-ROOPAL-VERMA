# DBMS Lab 1 - Assignment 1

## Student Information

- **Name:** Roopal Verma
- **Roll No:** IC-2K25-72
- **Subject:** Database Management System (DBMS)
- **Lab:** Lab 1
- **Assignment:** Assignment 1

---

## 1. Problem Statement

The objective of this assignment is to practice SQL statements for creating tables and applying different constraints in MySQL.

The assignment contains 20 questions covering:

- Creating tables
- Creating tables if they already exist
- Creating duplicate table structures
- Copying table structure and data
- NULL constraints
- CHECK constraints
- UNIQUE constraints
- PRIMARY KEY constraints
- AUTO_INCREMENT
- Composite UNIQUE constraints
- Foreign key constraints
- Composite foreign keys
- InnoDB storage engine
- ON UPDATE and ON DELETE actions

The questions use tables such as `countries`, `jobs`, `job_histry`, `job_history`, `departments`, and `employees`.

---

## 2. Approach / Algorithm

1. Open MySQL Command Line Client.
2. Create the required tables using `CREATE TABLE`.
3. Define appropriate columns and data types.
4. Apply required constraints such as:
   - PRIMARY KEY
   - UNIQUE
   - NULL
   - CHECK
   - FOREIGN KEY
   - AUTO_INCREMENT
5. Use `IF NOT EXISTS` wherever required.
6. Create relationships between tables using foreign keys.
7. Use the InnoDB engine where specified.
8. Apply required `ON DELETE` and `ON UPDATE` actions.
9. Execute the SQL statements in MySQL.
10. Verify the table structure and output.
11. Save the SQL source code and screenshots of the program output.

---

## 3. Time & Space Complexity Analysis

### Time Complexity

Most `CREATE TABLE` operations take approximately:

**O(1)**

Constraint creation and table definition are handled by the database management system.

Operations involving insertion, searching, or checking constraints may depend on the number of records and indexes.

### Space Complexity

The space required depends on:

- Number of tables
- Number of columns
- Number of records
- Indexes
- Constraints

Therefore, the overall storage requirement depends on the size of the created database tables.

---

## 4. Sample Input / Output

### Sample Input

```sql
CREATE TABLE countries (
    country_id INT,
    country_name VARCHAR(50),
    region_id INT
);
