# ATM-Console-Application
A C++ CLI ATM System Simulation featuring client login verification, quick/normal cash withdrawals with balance validation, deposits, and real-time balance checking via local file storage.

# ATM System Simulation

A simple and interactive Command Line Interface (CLI) ATM Simulation system written in C++. This application emulates real-world ATM workflows, allowing validated bank clients to securely access their accounts and perform transactions directly through the console.

## 🚀 Features

- **Secure Client Login:** Validates client access using an Account Number and PIN Code.
- **Quick Withdraw:** A fast cash withdrawal feature with preset options (20, 50, 100, 200, 400, 600, 800, 1000).
- **Normal Withdraw:** Allows custom withdrawal amounts, with validation to ensure the amount is a multiple of 5.
- **Deposit Operations:** Enables adding positive funds to the account.
- **Balance Inquiry:** Real-time checking and displaying of the current account balance.
- **Persistent Data Sync:** Automatically updates and saves the client's new balances back to the central data file (`Clients.txt`).

## 🛠️ Built With

- **C++** (Standard Library, fstream, vector, iomanip)
