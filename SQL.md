# Structured query language|SQL
Structured query language (SQL) is a programming language for storing and processing information in a relational database.
# Table of contents
- [What is a database ?]()

## What is a database ?
- Database is any collection of related information and can be stored in different ways (paper, your mind, a computer, powerpoint,...)
- Computer are great for storing databases
- Database Management Systems (DBMS) make it easy to create, maintain, and secure a database.
- RDBMS Relational Database Management System (mySQL, Oracle, postgreSQL, mariaDB, etc).
- NRDBMS Non-Relational Database Management System (mongoDB, dynamoDB, apache cassandra, firebase, etc.)
- DBMS allow you to perform the C.R.U.D operations, and other administrative tasks (handles security, backups,importing and exporting data, concurrency, interact with software applications).
- Two types of Database, Relational & Non-relational
- Relational databases use SQL and store data in tables with rows and columns.
- Non-relational databases store data using other data structures, such as document(Json,Blob,Xml,etc.), graphs, key-value stores, flexible tables. 
- When the database's structure become more and more complex, it becomes more difficult to get the specific pieces of information, so we need database queries. Queries are requests made to the database management system for specific information. Ex: a google search is a query.

## Table and keys
Table is a combination of columns and rows
- Column present a single attribute of an object (the score of a student)
- Row present an individual object that has many attributes ( A student has ID, weight, height, major, score, etc.)

Primary keys is a special column which uniquely defines the row in database.
- Surrogate key is a primary key that has no mapping to the real world (sdtID: 0, 1, 2, 3,...)
- Natural key is a primary key that has a mapping or has a purpose in the real world (SSN Social Security Number)
Foreign key is an attribute that help us link a database table to another database table (branch_id) and it stores the primary key of a row in another databas table, define the relationship between two tables.
Composite key is the combination of more than one attribute to define the relationship.
![image](https://github.com/HaColab2k/Data-analyst-/assets/127838132/bb8db9a1-ca8b-4d9b-a689-79fb56022c87)
=> How much product the clien has bought from the employee

## SQL Basics
SQL is actually a hybrid language. it contains four types of languages.
- Data Query Language (DQL)
  + Used to query the database for information.
  + Get information that already stored there.
- Data Defination Language (DDL)
  + Used for defining database schemas.
- Data Control Language (DCL)
  + Used to controlling acces to the data in the database.
  + User & permissions management.
- Data Manipulation Language (DML)
  + Used for inserting, updating and deleting data from the database
A query is a set of instructions given to the RDBMS that tells RDBMS what information you want it to retrieve for you.
