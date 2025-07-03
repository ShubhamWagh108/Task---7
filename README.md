# Task---7
# 📊 Sales Summary with Python, SQLite & SQL

This project demonstrates how to use SQL inside Python to extract basic sales insights and visualize them using matplotlib. It is designed for beginners who want to integrate SQL queries into Python and create simple business dashboards.

---

## 🔧 Tools & Technologies

- Python 3
- SQLite (via `sqlite3` – no installation needed)
- Pandas
- Matplotlib
- Jupyter Notebook / Python script (`.py`)

---

## 📁 Dataset

A simple in-memory dataset is inserted into a SQLite database (`sales_data.db`) with the following schema:

```sql
CREATE TABLE sales (
    id INTEGER PRIMARY KEY,
    product TEXT,
    quantity INTEGER,
    price REAL
);
