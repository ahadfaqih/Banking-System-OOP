# Banking System using Object-Oriented Programming

A Python-based banking system that demonstrates core Object-Oriented Programming (OOP) concepts through bank branches, customers, accounts, transactions, and money transfers.

## Project Overview

This project simulates a simple banking system using Python and OOP principles. It includes a head office that manages multiple branches, customers with current and savings accounts, transaction processing, account charges, and transfers between accounts.

## OOP Concepts Demonstrated

- Classes and Objects
- Inheritance
- Abstraction
- Polymorphism
- Method Overriding
- Object Relationships
- Static Methods
- Exception Handling

## Main Components

### HeadOffice
Manages the bank name, address, and registered branches.

### Branch
Stores branch information and manages customer accounts.

### Customer
Represents a bank customer and stores their accounts.

### Account
An abstract base class containing common account functionality such as deposits, withdrawals, balances, and transaction history.

### CurrentAccount
Inherits from `Account` and implements its own account charge calculation.

### SavingsAccount
Inherits from `Account` and calculates charges based on the account balance.

### Transaction
Represents a transfer of money between two accounts.

### BankService
Handles transfers between accounts and records transactions in both accounts.

## Features

- Create multiple bank branches
- Create customers and accounts
- Support current and savings accounts
- Deposit and withdraw money
- Transfer money between accounts
- Prevent invalid transfers
- Maintain transaction history
- Calculate account charges
- Display account and branch information

## Example Transactions

The demonstration performs two transfers:

- 300 from Customer 1's current account to Customer 2's savings account
- 500 from Customer 2's current account to Customer 1's savings account

Final account balances:

| Account | Balance |
|---|---:|
| C1-CA-1 | 700 |
| C1-SA-1 | 5500 |
| C2-CA-1 | 1500 |
| C2-SA-1 | 6300 |

## Technologies Used

- Python
- Object-Oriented Programming (OOP)
- Python `abc` module
- Google Colab / Jupyter Notebook

## Project File

`Banking_System_OOP.ipynb`

The notebook contains the complete implementation and a demonstration of the banking system.

## What I Learned

Through this project, I practiced designing a program using multiple interacting classes, implementing inheritance and abstraction, overriding methods in subclasses, validating banking operations, and modeling relationships between real-world entities using Object-Oriented Programming.
