# Task 7 – Basic Sales Summary using SQLite and Python

## Objective
The objective of this task is to create a small SQLite database and use SQL queries
inside Python to generate a basic sales summary, including total quantity sold and
total revenue, and visualize the results using a bar chart.

## Tools Used
- Python
- SQLite (sqlite3)
- Pandas
- Matplotlib
- Jupyter Notebook

## Description of Work
- Created a SQLite database named `sales_data.db`
- Created a `sales` table with product, quantity, and price columns
- Inserted sample sales data into the table
- Used SQL queries with `GROUP BY` to calculate:
  - Total quantity sold per product
  - Total revenue per product
- Loaded SQL query results into a pandas DataFrame
- Displayed the results using print statements
- Created a bar chart to visualize revenue by product

## Files Included
- `Task-7.ipynb` – Jupyter Notebook containing the complete code and output
- `sales_data.db` – SQLite database file
- `sales_chart.png` – Bar chart showing revenue by product
- `README.md` – Task explanation and details

## Outcome
This task helped in understanding how to:
- Connect Python with a SQLite database
- Execute SQL queries inside Python
- Perform basic data aggregation
- Visualize data using matplotlib
