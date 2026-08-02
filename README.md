# 🏧 Python ATM Machine System

> A console-based ATM simulation in Python, built in three progressive stages — from basic procedural logic to a multi-user system to a full Object-Oriented design.

![Python](https://img.shields.io/badge/Python-3.x-blue) ![License](https://img.shields.io/badge/License-MIT-yellow)


## 🚀 Overview

This project simulates real-world banking operations through three implementations of increasing complexity, showing progression from basic scripting to OOP design:

1. **Simple ATM** — single-user, procedural logic
2. **Multi-User ATM** — dictionary-based account storage
3. **OOP ATM** — class-based design with encapsulation

## ✨ Features

- PIN-based authentication with a 3-attempt lockout
- Balance inquiry, deposit, and withdrawal
- Multi-user account support (dictionary-based)
- Class-based encapsulation in the OOP version

## 🏗️ Tech Stack

- Python 3 (standard library only — no external dependencies)
- Object-Oriented Programming (classes, encapsulation)
- Dictionaries for multi-user account storage

## 📂 Project Structure

```
Python_ATM_Machine_System/
│
├── Question1        # Basic single-user ATM logic
├── Question2   # Dictionary-based multi-user ATM
├── Question           # Object-oriented ATM system
└── README.md
```

## ⚙️ Installation & Usage

```bash
git clone https://github.com/abdullahk970/Python_ATM_Machine_System.git
cd Python_ATM_Machine_System

# Run any version:
python simple_atm.py
python multi_user_atm.py
python oop_atm.py
```

No external dependencies required.

## 🧱 OOP Version — Class Structure

- `__init__` — initializes PIN, balance, and login attempts
- `login()` — validates PIN, locks account after 3 failed attempts
- `show_menu()` — displays available operations
- `check_balance()`, `deposit()`, `withdraw()` — core banking operations

## 📈 What This Project Demonstrates

- Python control flow (loops, conditionals)
- Dictionary-based data modeling
- Function-based modular design
- Object-Oriented Programming fundamentals (encapsulation, class design)

## 🔮 Possible Future Improvements

- Database integration (SQLite)
- Transaction history tracking
- Password hashing for stored PINs
- GUI version (Tkinter)

## 👨‍💻 Author

**Muhammad Abdullah Khan**
