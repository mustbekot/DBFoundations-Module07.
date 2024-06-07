
# Module07 Website

---
[Google Homepage](https://www.google.com "Google's Homepage")  
[GitHub Webpage Code CheatSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

There is much information on the Internet about the Markdown language, but you should find all you need for this course on this one webpage: [GitHub Markdown Help](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).

Important: Learning to use Markdown and Jekyll could well be the topic of a complete course, but in this course, you do NOT need to know much about Markdown programming. Please use only the basics shown in this module instead of more advanced features, and do not worry about getting the format perfect!

---

## Assignment 7 - SQL User-Defined Functions

### Introduction

This document provides an overview of SQL User-Defined Functions (UDFs), explaining their
usage and the differences between Scalar, Inline, and Multi-Statement Functions.
Understanding these UDFs is essential for efficient and modular SQL code management.

### When to Use a SQL UDF

SQL UDFs encapsulate reusable logic for use within queries, promoting code reusability,
modularity, and consistency. They are ideal for abstracting complex calculations, ensuring
consistent logic application, and optimizing performance.

### Differences Between Scalar, Inline, and Multi-Statement Functions

#### Scalar Functions

Scalar functions return a single value of a specified data type and are used for calculations or
operations that produce one result. They are suitable for mathematical operations, string
manipulations, and date calculations.

#### Inline Table-Valued Functions (Inline TVFs)

Inline TVFs return a table and are defined using a single SELECT statement, making them
efficient and similar to views. They are used to return a set of rows based on input parameters.

#### Multi-Statement Table-Valued Functions (Multi-Statement TVFs)

Multi-Statement TVFs return a table constructed through multiple BEGIN...END statements,
suitable for more complex logic. They can be less performant due to the overhead of managing
the table variable and complex operations.

### Summary

SQL UDFs, including Scalar, Inline TVFs, and Multi-Statement TVFs, enable reusable and
efficient SQL code. Each type serves different scenarios: Scalar for single values, Inline TVFs
for table results with simple logic, and Multi-Statement TVFs for complex logic returning tables.
Understanding their use enhances SQL code efficiency and maintainability.
