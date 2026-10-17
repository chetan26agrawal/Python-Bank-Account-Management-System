# 🏦 Python Bank Account Management System

A menu-driven bank account management system built using Python. This project demonstrates account management, financial transactions, file handling, exception handling, and transaction reporting.

## ✨ Features

- 🆕 Create new bank accounts
- 👤 View account details
- 💰 Deposit money into an account
- 💸 Withdraw money with balance validation
- 🔄 Transfer funds between accounts
- 🧾 View transaction history
- 📊 Generate transaction summary statistics using NumPy
- 💾 Save and load account data using Pickle
- 📁 Append transaction records to a file
- 🛡️ Validate user input and handle common errors
- 🖥️ Interactive command-line menu

## 🛠️ Technologies Used

- 🐍 Python
- 🔢 NumPy
- 💾 Pickle
- 📂 File Handling
- 📓 Jupyter Notebook

## 📂 Project Structure

```text
Python-Bank-Account-Management-System/
├── Python_Bank_Account_Management_System.ipynb
├── README.md
├── bank_accounts.pkl
└── transaction_history.txt
```

The account data and transaction history files are generated when the program runs and saves data.

## ⚙️ Installation

### 1. Install Python

Download Python from https://www.python.org/downloads/

### 2. Install the required libraries

Open your terminal or command prompt and run:

```bash
pip install numpy notebook
```

### 3. Run the Jupyter Notebook

Open the project notebook:

```bash
jupyter notebook
```

Then open `Python_Bank_Account_Management_System.ipynb` and run its cells in order.

## 📋 Available Operations

| Option | Operation |
|---|---|
| 1 | Open a new account |
| 2 | View account details |
| 3 | Deposit money |
| 4 | Withdraw money |
| 5 | Transfer funds |
| 6 | View transaction history and statistics |
| 7 | Save data and exit |

*Menu options may depend on the implementation in the notebook.*

## 📊 Transaction Reports

The project uses NumPy to calculate transaction statistics, including:

- Total deposits
- Total withdrawals
- Average transaction amount
- Transaction counts

Transaction history includes dates, transaction types, and amounts, according to the records maintained by the program.

## 🧠 Python Concepts Demonstrated

- Variables and data structures
- Functions
- Conditional statements
- Loops
- Input validation and exception handling
- File reading and writing
- Pickle serialization
- Date and time handling
- NumPy calculations

## ⚠️ Limitations

This project is intended for educational purposes and is not suitable for real banking or financial transactions. It does not provide production-grade security or authentication.

**Security note:** Only load trusted Pickle files because loading an untrusted Pickle file can execute malicious code.

## 🚀 Future Improvements

- 🔐 Add secure user authentication
- 🗄️ Use SQLite for persistent storage
- 🧪 Add unit tests
- 💵 Use Decimal for more precise currency calculations
- 📄 Export account statements to CSV
- 🎨 Build a graphical user interface

## 👩‍💻 Project Purpose

Created as a Python assignment to practise programming fundamentals, account management, transaction processing, file handling, and reporting.

---

⭐ If you find this project useful, consider giving the repository a star!
