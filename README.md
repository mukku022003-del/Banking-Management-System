# Banking Management System (Java + Oracle SQL + JDBC)

A simple menu-driven banking system that connects Java with **Oracle Database** using **JDBC**.

## Features
- Create a new account
- View account details
- Deposit money
- Withdraw money with balance validation

## Tech Stack
- Java (Core)
- Oracle SQL (Database)
- JDBC (Connectivity)

## Setup
1. Install Oracle Database and create a table:
   ```sql
   CREATE TABLE accounts (
       acc_no NUMBER PRIMARY KEY,
       name VARCHAR2(50),
       balance NUMBER
   );
