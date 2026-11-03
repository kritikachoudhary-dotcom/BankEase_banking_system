# BankEase – Banking Transaction Management System

**A DBMS Mini Project using Oracle SQL and PL/SQL**

## 1. Project Overview

BankEase is a database-based Banking Transaction Management System developed using Oracle SQL and PL/SQL. It demonstrates basic banking operations such as depositing money, withdrawing money, transferring funds, checking account balances, and maintaining transaction records.

The project aims to demonstrate how database management concepts can be used to manage banking information efficiently.

## 2. Project Objectives

- To manage customer and account information.
- To perform basic banking transactions.
- To maintain accurate account balances.
- To store transaction details in a database.
- To understand the practical implementation of SQL and PL/SQL.

## 3. Features

- **Customer Management:** Stores customer details such as name, email, phone number, and city.
- **Account Management:** Maintains account numbers, account types, balances, and account status.
- **Deposit Money:** Adds money to a customer's account.
- **Withdraw Money:** Withdraws money after checking the available balance.
- **Fund Transfer:** Transfers money between two accounts.
- **Balance Enquiry:** Displays the current account balance.
- **Transaction History:** Maintains records of deposits, withdrawals, and transfers.

## 4. Technologies Used

| Technology | Purpose |
|---|---|
| Oracle Database | Database management |
| SQL | Creating tables and managing records |
| PL/SQL | Implementing banking operations |
| OneCompiler | Online SQL execution environment |
| GitHub | Project hosting and version control |

## 5. Database Tables

The project uses the following tables:

| Table Name | Description |
|---|---|
| BE_CUSTOMERS | Stores customer information |
| BE_ACCOUNTS | Stores bank account information |
| BE_TRANSACTIONS | Stores transaction records |

## 6. Project Structure

```text
BankEase-Banking-System/
│
├── README.md
└── BankEase.sql
```

## 7. How to Run the Project

1. Open [OneCompiler](https://onecompiler.com/oracle).
2. Select Oracle as the programming environment.
3. Open the `BankEase.sql` file from this repository.
4. Copy the SQL and PL/SQL code.
5. Paste the code into the OneCompiler editor.
6. Click the **Run** button.
7. View the banking operations and database output.

**Note:** Run the complete setup script only once in a fresh database environment to avoid duplicate table and record errors.

## 8. Sample Banking Operations

The project demonstrates the following operations:

| Operation | Example |
|---|---|
| Deposit | ₹2,000 |
| Withdrawal | ₹1,000 |
| Fund Transfer | ₹500 |
| Balance Enquiry | Displays current balance |
| Transaction History | Displays transaction records |

## 9. Learning Outcomes

Through this project, I learned:

- How to create and manage database tables.
- How to use SQL commands for database operations.
- How to implement procedures using PL/SQL.
- How to perform deposit, withdrawal, and fund transfer operations.
- How to maintain transaction records.
- How to execute and demonstrate database projects using an online compiler.

## 10. Future Enhancements

- Add a user-friendly graphical interface.
- Implement customer login and authentication.
- Add account creation and deletion.
- Generate downloadable transaction statements.
- Improve transaction security and validation.

## 11. Author

**Project:** BankEase – Banking Transaction Management System  
**Project Type:** MCA DBMS Mini Project  
**Database:** Oracle  
**Programming Language:** SQL and PL/SQL

---

*This project was developed for academic and educational purposes as part of database management system learning.*
