ATM System
Overview
This ATM (Automated Teller Machine) System is a simple Java console application that simulates basic ATM functionality. It allows users to check their account balance, withdraw money, and deposit money after authenticating with a PIN.
Features

PIN Authentication: Secure access through PIN verification
Balance Inquiry: Check current account balance
Cash Withdrawal: Withdraw funds with insufficient balance validation
Cash Deposit: Add funds to the account
User-friendly Menu: Simple interface for navigating between operations

How It Works

The system prompts the user to enter their PIN
After successful authentication, users can:

Check their current balance
Withdraw money (with validation to prevent overdrafts)
Deposit money
Exit the system


After each operation, the system returns to the main menu for additional transactions

Technical Implementation

Object-Oriented Design: Encapsulates ATM operations within a class
Constructor Initialization: Sets initial PIN and balance values
Input Validation: Prevents invalid PIN entries and insufficient fund withdrawals
Recursive Menu Navigation: Returns to main menu after each operation
Scanner Integration: Processes user input for all operations

How to Run

Compile the Java file:
javac ATM.java

Run the compiled program:
java ATM

When prompted, enter the PIN (default is 1234)
Use the menu options to perform various banking operations

Default Settings

Default PIN: 1234
Initial Balance: $0.00

Future Enhancements

Multiple user accounts with different PINs
Transaction history logging
Time-based session timeouts
Fund transfer between accounts
Receipt generation functionality
GUI implementation

Requirements

Java Development Kit (JDK) 8 or higher
Command-line interface or IDE for Java development


© Manish Rejintal | https://github.com/rejintal/ATM-meachine-Project
