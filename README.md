# Sales-Summary-Analysis-using-SQLite-and-Python

This project demonstrates how to generate a basic sales summary from a small SQLite database using Python, SQL, pandas, and matplotlib.

## 📊 Objective

- Create a simple SQLite database (`sales_data.db`) with randomly generated sales data
- Run SQL queries using Python to calculate:
  - Total quantity sold per product
  - Total revenue per product
- Display the results using `print()` and a bar chart with matplotlib

## 📂 Files Included

- `create_sales_db.py` – Script to generate the database and insert sample sales data
- `sales_summary.py` – Script to query the database and generate the sales chart
- `sales_data.db` – SQLite database file with 250 rows of sales data
- `sales_chart.png` – Bar chart showing revenue by product
- `Task7_Sales_Summary.ipynb` – (If using Jupyter) Full notebook with code, outputs, and chart

## 📌 Technologies Used

- Python 
- SQLite 
- pandas
- matplotlib

## 📝 How to Run

1. Run `create_sales_db.py` to generate the database:
    ```bash
    python create_sales_db.py
    ```

2. Run `sales_summary.py` to generate and save the sales summary chart:
    ```bash
    python sales_summary.py
    ```

Or open `Task7_Sales_Summary.ipynb` in Jupyter Notebook to view everything in one place.

## 📷 Example Output

![Sales Chart](sales_chart.png)

---

