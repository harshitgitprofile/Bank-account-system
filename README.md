🏦 Bank Management System — C Language
A console-based Bank Management System built in C language by Harshit. This program allows users to manage customer bank accounts — from creating accounts to deposits, withdrawals, and interest calculations — with all data saved using file handling.

📋 Features
FeatureDescription🔐 Password LoginSecure login required before accessing the system➕ Create New AccountAdd a new customer with full details (name, DOB, address, citizenship, phone, account type, amount)✏️ Update Account InfoEdit customer address or phone number by account number💸 TransactionsDeposit or withdraw money from an existing account🔍 Check Account DetailsSearch account by Account Number or Name — shows full info + interest❌ Remove AccountDelete an existing customer account from records📋 View Customer ListDisplay all customers with account no., name, address, and phone💾 File HandlingAll records saved in record.dat — data persists after program closes

🏦 Account Types & Interest Rates
Account TypeInterest RateDurationSaving8% per monthMonthlyCurrent0%No interestFixed19%1 YearFixed211%2 YearsFixed313%3 Years

🛠️ Tech Stack

Language: C
Platform: Windows (uses windows.h, system("cls"), system("color"))
Compiler: GCC / MinGW
Concepts Used:

Structures (struct) for account & date data
File Handling (fopen, fscanf, fprintf, fclose)
Functions & Modular Programming
goto statements for menu navigation
Simple Interest calculation logic
String comparison (strcmp, strcmpi)
Console-based Menu driven UI




🖥️ Program Flow
Start → Password Login
│
└── Main Menu
        ├── 1. Create New Account
        ├── 2. Update Account Info (Address / Phone)
        ├── 3. Transactions (Deposit / Withdraw)
        ├── 4. Check Account Details (by Acc No. or Name)
        ├── 5. Remove Account
        ├── 6. View All Customers
        └── 7. Exit

🚀 How to Run
Prerequisites

Windows OS (required — uses windows.h)
GCC / MinGW compiler installed

Option 1 — Run the .exe directly
Double-click bank_management_system.exe
Option 2 — Compile & Run from Source

Clone the repository

bash   git clone https://github.com/harshitgitprofile/BANK-MANAGEMENT-SYSTEM.git
   cd BANK-MANAGEMENT-SYSTEM

Compile

bash   gcc bank_management_system.c -o bank_management_system

Run

bash   bank_management_system.exe

⚠️ Make sure record.dat is in the same folder as the .exe or it will be created automatically on first run.


📁 Project Structure
📁 Bank-Management-System/
├── bank_management_system.c    # Full source code
├── bank_management_system.exe  # Compiled executable (Windows)
├── record.dat                  # Data file (auto-created on first run)
└── README.md                   # Project documentation

💡 Concepts Learned

✅ Struct-based data modeling (Account, Date)
✅ File handling for persistent storage (record.dat)
✅ Password-protected login system
✅ Menu-driven console application
✅ Simple Interest formula implementation
✅ Record search by account number and name
✅ Update and delete records using temp file technique

HARSHIT PANCHAL
GitHub

