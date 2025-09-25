# 💰 Personal Expense Tracker (Python CLI)

A command-line based **Personal Expense Tracker** built with Python.  
This project helps you **record, view, and analyze** your daily financial transactions.  
It uses **CSV for persistent storage**, **pandas for data processing**, and **matplotlib for visualizing income/expenses over time**.  

---

## 🚀 Features
- Add new transactions (date, amount, category, description)
- Store and retrieve transactions from a CSV file
- View transactions within a custom date range
- Generate summaries of **total income, expenses, and net savings**
- Visualize income and expenses over time using matplotlib
- User-friendly command-line interface

---

## 🛠️ Installation

Make sure you have **Python 3.x** installed.  
Install required dependencies:

```bash
pip install pandas matplotlib
```

Menu Options:

- Add a new transaction
- View transactions and summary within a date range
- Exit

If you choose option 2, you’ll also get an option to plot transactions 📊.

📌 Future Improvements

- Add categories with auto-suggestions
- Export reports to Excel/PDF
- Build a simple Streamlit/Django UI
- Add monthly/weekly summaries
