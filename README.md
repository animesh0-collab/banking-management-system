# Banking System Python

A terminal-based banking management system built in Python to safely simulate core banking operations.

## Features
* **Create Account:** Open a new bank account with a name and an initial deposit.
* **Deposit:** Add money to an existing account and record the transaction.
* **Withdraw:** Take money out safely (includes low-balance checks).
* **Check Balance:** View the account holder's name and current available balance.
* **Transaction History:** List all deposits and withdrawals in chronological order.
* **Input Validation:** Rejects letters, special characters, and unknown account numbers without crashing.

## How to Run
1. Open the project in Google Colab.
2. Go to the top menu and select **Runtime > Run all** (or press Shift + Enter to run individual cells).
3. Interact with the system using the text prompts provided in the terminal output cell.

## Sample Output
```text
--- Welcome to the Banking System ---
1. Create account
2. Deposit
3. Withdraw
4. Check balance
5. Transaction history
6. Exit

Enter your choice: 1
Enter your name: Deb
Enter opening deposit: 5000
Account created successfully! Your Account Number is: 1001

Enter your choice: 4
Enter account number: 1001
Account Holder: Deb
Current Balance: ₹5,000
