# Java Console Banking Application

## Project Overview
This project is a simple console-based banking application built in Java. It includes essential banking functionalities such as user registration, login, account management, transaction processing, statement generation, interest calculation, and balance checking. The objective is to practice handling user inputs, managing data structures, and performing basic calculations in a console application.

## Features

1. **User Registration & Login**
    - Users can register by creating a username and password.
    - Secure login functionality verifies user credentials before accessing accounts.

2. **Account Opening**
    - Logged-in users can open new bank accounts.
    - Accounts have unique account numbers and store details like account holder name, account type (savings/checking), and initial deposit amount.

3. **Transaction Processing**
    - Users can make deposits and withdrawals in each account.
    - Withdrawal validation prevents overdrafts (attempts to withdraw more than the current balance).
    - Each transaction is logged with a unique ID, date, type (deposit or withdrawal), and amount.

4. **Statement Generation**
    - Users can generate a statement showing their transaction history.
    - The statement includes details for each transaction, such as date, type, and amount.

5. **Interest Calculation**
    - For savings accounts, monthly interest is calculated and added to the account balance.
    - Interest is only added once per month, using a fixed interest rate.

6. **Balance Check**
    - Users can check the current balance for any of their accounts.

## Technologies Used
- **Java**: Core programming language for the application.
- **Console Input/Output**: For user interaction.
- **Data Structures**: Arrays or lists to store user and account data.
