# Project: MySQL Table Display Script

## Table of Contents

1. [Description](#description)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Setup](#setup)
5. [Usage](#usage)
6. [Example](#example)
7. [License](#license)
8. [Author](#author)

## Description

This Python script connects to a MySQL database, allows the user to input the name of a table, and then retrieves and displays the contents of that table in a neatly formatted table using the `PrettyTable` library.

## Features

- Connects to a MySQL database using `mysql.connector`.
- Fetches and displays the structure and contents of a specified table.
- Utilizes `PrettyTable` to format and print the table data.

## Requirements

- Python 3.x
- `mysql-connector-python` (for MySQL database connectivity)
- `prettytable` (for formatting table output)

You can install the required packages using:

```bash
pip install mysql-connector-python prettytable
```
## Usage

1. Run the script in your terminal.
2. When prompted, input the name of the table you wish to display.
3. The script will fetch and display the structure and contents of the specified table.

## Example

```text
Name of the table: employees
+----+------------+-----------+------------+
| ID | First Name | Last Name | Department |
+----+------------+-----------+------------+
|  1 | John       | Doe       | HR         |
|  2 | Jane       | Smith     | IT         |
+----+------------+-----------+------------+
```
