# Python-beginner-project
"A modular Python-based Banking System featuring secure account management, transaction tracking, and data persistence."
 ICB Bank — Python Banking System
A fully modular, real-world banking simulation built with pure Python — no frameworks, no shortcuts.
🚀 Key Features

Multi-File Architecture — Each module has one job, connected through clean imports
Secure Authentication — Login system with attempt limits and account locking
Full Transaction System — Deposit, Withdraw, Transfer and Toll Tax payment
Daily Security Limits — 50,000 PKR daily transaction limit with auto-reset
PIN Protection — 4-digit PIN with wrong attempt tracking and 24-hour lockout
Account Settings — Change name, password and PIN with edit limits
Account Freeze — Permanently delete account across all data files
Data Persistence — All data saved in JSON files, survives app restarts
EasyPaisa-style Transfer — Send money directly to another account holder

📂 Project Structure
ICB_Bank/
├── ICB.py              ← Master engine, entry point
├── Bankinfo.py         ← Signup, login and bank registration
├── account_setup.py    ← Account type selection and creation
├── transaction.py      ← Deposit, withdraw, transfer, toll tax
├── dashboard.py        ← User interface and menu system
├── settings.py         ← Name, password and PIN management
├── security.py         ← Daily limits, PIN lock, account status
└── data/
    ├── signupinfo.json
    ├── bankdata.json
    ├── Autofill_Account_data.json
    ├── Balance.json
    ├── Settingdata.json
    └── Security.json
