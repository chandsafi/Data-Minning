Module-Data-Mining
Welcome to the Module-Data-Mining repository! This repository contains SQL query files that demonstrate essential data mining techniques, including querying and manipulating data from databases. The repository includes two main files: Sakiladb_Queries and DML_Queries, which contain a variety of SQL queries for different use cases.

Repository Contents
1. Sakiladb_Queries.sql
This file contains queries run against the popular Sakila database, which is widely used for SQL learning and practice. The queries in this file are designed to perform tasks such as filtering data, using wildcards, and combining multiple conditions.

Key examples include:

Query 01: Selecting the actor_id from the actor table where actor_id = 58.
Query 02: Selecting movie names where the title starts with the letter "P".
Query 03: Selecting movies that were released in 2006.
Query 04: Retrieving the password assigned to user "MIKE".
Query 05: Retrieving actors whose first names do not end with "T".
Query 06: Selecting actors whose IDs are between 50 and 150 or whose names start with "A".
Query 08: Displaying customer names in the format lastname, first letter of first name.
Query 10: Concatenating first and last names of customers and displaying them with their address_id.
2. DML_Queries.sql
This file demonstrates basic Data Manipulation Language (DML) queries using SQL. It includes creating tables, inserting data, and performing operations such as retrieving, filtering, and aggregating employee data.

Key queries include:

Creating Tables: Departments and Employees tables.
Inserting Data: Inserting department names and employee records into their respective tables.
Basic Retrieval: Querying employee names and hire dates.
Filtering Data: Selecting employees hired after a specific date.
Aggregation: Counting the number of employees in each department.
Date Functions: Finding the earliest and latest hire dates.
Joins and Subqueries: Finding employees who do not belong to any department.
Usage
You can run these SQL queries in any relational database management system (RDBMS) that supports SQL. If you're working with the Sakila database, ensure it's set up properly in your RDBMS before running the queries from Sakiladb_Queries.sql.

Steps to Run Queries:
Clone this repository:
Open your preferred SQL client (e.g., MySQL Workbench, PostgreSQL, etc.).
Import or paste the queries from the respective .sql files.
Execute the queries in your database environment to view results.
Requirements
SQL-compatible database (MySQL, PostgreSQL, etc.).
Sakila database (for Sakiladb_Queries.sql).
