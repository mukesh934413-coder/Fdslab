DBMS Lab - SQL Programs and Answers

1. DDL Commands - Create, Alter, Truncate, and Drop

Aim: To create a database and perform table creation, alteration, truncation, and deletion using DDL commands.

lect the database

table

SQL Program:

Create a database CREATE DATABASE CollegeDB;

USE CollegeDB;

Create CREATE TABLE Student ( Student ID INT PRIMARY KEY, Name VARCHAR (50) Department VARCHAR (30), Age INT, Marks INT

Alter the table by adding a colum ALTER TABLE Student

ADD Email VARCHAR (100);

-- Display the table structure

DESC Studen

-- Remove all records from the table TRUNCATE TABLE Student

-- Delete the table completely

DROP TABLE Student;

Result: The database and table were created successfully. The table was altered, truncated, and dropped using DDL commands.# Fdslab
