Jiajun Yu
Aug 22, 2021
Foundations of Programming, SQL
Assignment 07
GITHUB Link: https://github.com/Jeanneuw/DBFoundations-Module07

# SQL UDF, Scalar, Inline, and Multi-Statement Functions

## Introduction
In this paper, I will go over the questions about SQL UDF, Scalar, Inline, and Multi-Statement Functions
 and will explain when we shall use those statements. 

## 1. Explain when you would use a SQL UDF.
Definition
SQL UDF statement means user defined function and which is UDF in short by using Transact-SQL.

### When to use a SQL UDF
A scalar valued UDF accepts parameters and can return a single atomic value. The main purpose is to use the objects stored in the database and avoid writing the same code over and over again. 
Store complex code in one structure
Match test input parameters
Don’t want to rewrite same code
Do the changes to the code in one place and reflect the change at every place the function is used
Need to calculate which will be repeated throughout the database


## 2. Explain the differences between Scalar, Inline, and Multi-Statement Functions.

### Similarities
Scalar, Inline, and Multi-Statement Functions are three types of user defined functions. The main purpose of using those statements is to improve maintainability and code readability.

### Difference
Scalar, Inline, and Multi-Statement Functions when we need to use them to return different values or results.
The Scalar UDF usually is used to return one single value from input value. It works on each record independently.  It always returns a single valued result. 
The Inline table valued function returns a variable of data type table with the value derived from one SELECT statement
The Multi-statement table valued function returns a table variable as result of function actions. It returns a table and the table structure will be returned.

## Summary
Overall, SQL UDF, Scalar, Inline, and Multi-Statement Functions are used to improve the maintainability and code readability of codes.
