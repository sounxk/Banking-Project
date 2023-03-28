
Basic Banking System
====================

This C++ project covers the basic functionalities of a banking system, which include account opening, balance inquiry, deposit, withdrawal, account closure, and listing of all accounts.

Functionality
-------------

### Open an Account

To open an account, the user is prompted to provide their personal information, such as their name, address, and contact information. A unique account number is generated and assigned to the new account.

### Balance Enquiry

To inquire about an account's balance, the user enters their account number, and the system displays the current balance of that account.

### Deposit

To deposit money into an account, the user enters their account number and the amount they wish to deposit. The system updates the account balance accordingly.

### Withdrawal

To withdraw money from an account, the user enters their account number and the amount they wish to withdraw. The system verifies that the account has sufficient funds and updates the account balance accordingly.

### Close an Account

To close an account, the user enters their account number. The system verifies that the account has a zero balance and then removes the account from the system.

### Show All Accounts

To view a list of all accounts, the user selects this option from the main menu, and the system displays a table of all accounts, including their account number, name, and current balance.

Compilation and Execution
-------------------------

To compile and execute the project, follow these steps:

1.  Clone the repository to your local machine.
2.  Navigate to the project directory in your terminal.
3.  Run the following command to compile the project:


```
g++ -o bankingSystem bankingSystem.cpp
```
1.  Run the following command to execute the project:

```
./bankingSystem
```
Contributions
-------------

This project was developed by Sounak Ghosh. Contributions and improvements are welcome.
