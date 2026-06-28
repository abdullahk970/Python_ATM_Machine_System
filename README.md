# 🏧 Python ATM Machine System (Beginner → OOP Implementation)

> A console-based **ATM simulation project in Python** demonstrating procedural programming, multi-user system design, and Object-Oriented Programming (OOP) concepts.

This project includes **three implementations**:

1. 🧾 Simple ATM (basic logic)
2. 👥 Multi-User ATM System (dictionary-based accounts)
3. 🧠 OOP-Based ATM System (class-based design)

---

# 🚀 Overview

This ATM system simulates real-world banking operations such as:

* PIN authentication
* Balance inquiry
* Cash deposit
* Cash withdrawal
* Multi-user account handling
* Secure login attempts (account lock after 3 failures)

It is designed as a **learning project** to demonstrate progression from basic Python logic to advanced OOP design.

---

# ✨ Features

## 🔐 Authentication System

* PIN-based login
* Maximum 3 attempts allowed
* Account lock after failed attempts

## 💰 Banking Operations

* Check balance
* Deposit money
* Withdraw money
* Real-time balance updates

## 👥 Multi-User Support

* Multiple accounts using dictionary storage
* Individual balances per user
* Secure account isolation

## 🧠 OOP Version Features

* Encapsulation using class
* Clean method-based architecture
* Reusable functions
* Structured program flow

---

# 🏗️ Tech Stack

* Python 3
* Core Python (No external libraries)
* OOP Concepts (Classes, Methods)
* Control Structures (loops, conditions)
* Dictionaries (for multi-user system)

---

# 📂 Project Structure

```text id="atm-structure"
ATM-System/
│
├── simple_atm.py        # Basic ATM logic (single user)
├── multi_user_atm.py    # Dictionary-based multi-user ATM
├── oop_atm.py           # Object-Oriented ATM system
└── README.md
```

---

# 🧾 1. Simple ATM (Basic Version)

### Features:

* Single user system
* PIN authentication
* Basic banking operations

### Flow:

```text id="simple-flow"
Enter PIN
   ↓
Login Success
   ↓
Menu (Check / Deposit / Withdraw / Exit)
   ↓
Balance Update
```

---

# 👥 2. Multi-User ATM System

### Features:

* Multiple accounts support
* Account number + PIN login
* Individual balances stored in dictionary

### Example Accounts:

```python id="accounts"
{
    "1102": {"PIN": "1234", "balance": 20000},
    "1103": {"PIN": "2345", "balance": 30000},
    "1104": {"PIN": "3456", "balance": 40000}
}
```

### Improvements:

* Prevents unauthorized access
* Maintains separate user data
* More realistic banking simulation

---

# 🧠 3. OOP ATM System

### Features:

* Class-based design (`Simple_ATM`)
* Encapsulation of data (PIN, Balance, Attempts)
* Modular functions for each operation

---

## 🧱 Class Structure

### `__init__`

Initializes:

* PIN
* Balance
* Login attempts

---

### 🔐 `login()`

* Validates PIN
* Locks account after 3 failed attempts
* Calls initial menu on success

---

### 📋 `show_menu()`

Provides options:

* Check Balance
* Deposit Money
* Withdraw Money
* Exit

---

### 💰 `check_balance()`

Displays current balance

---

### ➕ `deposit()`

Adds money to account

---

### ➖ `withdraw()`

Deducts money from account

---

# 🔄 Program Flow (OOP Version)

```text id="oop-flow"
Start
  ↓
Login (PIN check)
  ↓
Menu Selection
  ↓
Operation Execution
  ↓
Balance Update
  ↓
Loop until Exit
```

---

# 📊 Key Highlights

* 🧠 Demonstrates OOP principles (Encapsulation)
* 🔐 Secure PIN authentication system
* 👥 Multi-user account simulation
* 💰 Real-time balance updates
* 🔁 Loop-based menu system
* 🧱 Clean modular design progression

---

# 📈 Learning Outcomes

After building this project, you will understand:

* Python control flow (loops, conditions)
* Dictionary-based data modeling
* Function-based modular design
* Object-Oriented Programming fundamentals
* Real-world banking logic simulation

---

# 🔮 Future Improvements

* 🗄️ Database integration (SQLite / MySQL)
* 🌐 GUI version using Tkinter or PyQt
* 🔐 Password hashing (security upgrade)
* 📊 Transaction history tracking
* 🏦 Interest calculation system
* 📱 Web version using Flask/Django

---

# 🤝 Contributing

1. Fork repository
2. Create feature branch
3. Commit changes
4. Push branch
5. Open Pull Request

---

# 👨‍💻 Author

**Muhammad Abdullah Khan**

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
