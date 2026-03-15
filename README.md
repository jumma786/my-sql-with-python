# Python MySQL Data Analysis Project

## Project Overview
This project demonstrates how to connect Python with MySQL and perform database operations such as creating databases, running queries, and extracting data for analysis.

The notebook uses Python to establish a connection with MySQL Workbench and execute SQL commands programmatically.

## Problem Statement
Database operations are commonly performed using SQL tools. However, integrating databases with Python allows analysts to automate queries, manipulate data, and perform analysis more efficiently.

This project shows how Python can interact with MySQL databases to perform data operations.

## Technologies Used

- Python
- MySQL
- mysql-connector-python
- Pandas

## Features

- Connect Python to MySQL database
- Create databases using Python
- Execute SQL queries
- Extract data into Pandas DataFrames
- Automate database operations

## Example Code

```python
import mysql.connector
import pandas as pd

connection = mysql.connector.connect(
    host="localhost",
    user="root",
    password="yourpassword"
)
