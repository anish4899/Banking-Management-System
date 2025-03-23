# Banking-Management-System
This project is a Customer Account Banking Management System implemented in C. It provides a console-based interface for managing bank accounts with functionalities such as account creation, information updating, transactions, viewing account details, deleting accounts, and listing all customer accounts.
Features
Create New Account: Allows users to create a new bank account with personal and account-related details.

Update Account Information: Edit the address or phone number of an existing account.

Transactions: Deposit or withdraw money from a customer’s account (Fixed accounts are non-transactable).

View Account Details: Retrieve details of a customer using their account number or name.

Delete Account: Permanently remove a customer’s account from the records.

List All Accounts: View a list of all registered customers with basic details.

Interest Calculation: Automatic interest calculation for Fixed and Saving accounts.

Technologies Used
C Programming Language

File Handling (record.dat for storing account information)

Console-based UI (using stdio.h and stdlib.h)

Windows System Commands (system("cls") and system("color 9"))

How to Run
Clone the repository.

Compile the bank.c file using a C compiler (e.g., gcc bank.c -o bank.exe).

Run the compiled executable (./bank.exe or bank.exe).

