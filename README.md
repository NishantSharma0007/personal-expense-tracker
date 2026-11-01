# Personal Expense Tracker & Monthly Report Generator 💰

## 📌 Project Overview

Personal Expense Tracker is a Python-based command-line application designed to record, manage, and analyze personal expenses.

The application allows users to enter expense descriptions, categories, amounts, and dates. It generates transaction reference IDs, calculates total spending, summarizes expenses by category, and produces a monthly expense report.

The project demonstrates how to organize Python code into reusable modules and use built-in and external libraries.

## 🎯 Project Objectives

- Understand Python modules and packages.
- Learn different import techniques.
- Organize code into multiple Python files.
- Work with Python built-in libraries.
- Generate random transaction reference IDs.
- Calculate and summarize expenses.
- Generate date-based monthly reports.
- Install and use external packages with pip.

## ⚙️ Features

- Record personal expenses.
- Categorize expenses (Food, Travel, Study, Bills, Other).
- Enter custom transaction dates.
- Generate random transaction reference IDs.
- Validate positive expense amounts.
- Calculate total spending.
- Calculate category-wise expenses.
- Generate monthly expense reports.
- Display formatted expense tables.
- Check file paths using the os module.

## 🛠️ Technologies Used

- Python 3
- VS Code / PyCharm
- Command Line Interface (CLI)
- pip Package Manager

## 📚 Modules and Libraries Used

| Module / Package | Type | Purpose |
|---|---|---|
| datetime | Built-in | Manage dates and months |
| random | Built-in | Generate transaction IDs |
| math | Built-in | Rounding and calculations |
| os | Built-in | File paths and existence checks |
| tabulate | External | Display formatted tables |

## 📦 Installation

Install the external package:

```bash
python -m pip install tabulate
```

Or install all project dependencies:

```bash
python -m pip install -r requirements.txt
```

## 🚀 How to Run

1. Install Python 3.
2. Clone this repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

3. Open the project folder in VS Code or PyCharm.
4. Install the required dependencies.
5. Run the main program:

   ```bash
   python main.py
   ```

## 📊 Sample Output

```text
Expense Tracker

Enter description: Metro card recharge
Enter category: Travel
Enter amount: 500
Enter date (YYYY-MM-DD, blank for today): [Enter]

Reference ID: EXP-482731

----- MONTHLY EXPENSE REPORT -----

Date        Description          Category    Amount
2026-10-27  Metro card recharge  Travel      500.00

Total spending: ₹500.00
Travel total: ₹500.00
Report month: October 2026
```

## 📂 Project Structure

```text
personal-expense-tracker/
│
├── main.py
├── expense_utils.py
├── report_utils.py
├── requirements.txt
└── README.md
```

## 📋 Requirements

Add the following dependency to requirements.txt:

```text
tabulate
```

## 📌 Project Information

- **Project Type:** Python Mini-Project
- **Module:** Module 5 – Modules, Packages & Libraries
- **Difficulty:** Intermediate
- **Interface:** Command Line
- **External Package:** Tabulate

## 👨‍💻 Author

Created as part of Python Technical Training.

## 📜 License

This project is intended for educational and learning purposes.
