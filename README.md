# Bank Management System

A simple console-based bank management system built in Python (Jupyter Notebook). It lets a user look up an account by account number and then deposit, withdraw, check balance, or create a new account.

## Features

- Account lookup — enter an account number to pull up the matching record
- Deposit — add money to the selected account
- Withdraw — remove money, with a balance check to prevent overdrawing
- Check balance — print the current balance of the selected account
- Create new account — add a new customer with a randomly generated 7-digit account number

## Data structure

Accounts are stored in a simple in-memory list of lists:

```python
bank = [
    ['Aarav', 200000, 1234567],
    ['Tigmansh', 200000, 3456789]
]
```

Each account is `[name, balance, account_number]`.

## Requirements

- Python 3
- Jupyter Notebook (to run the `.ipynb` file), or adapt the code into a `.py` script

No external libraries are required beyond the standard library (`random` is used for generating new account numbers).

## How to run

1. Open `Bank_management.ipynb` in Jupyter Notebook / JupyterLab.
2. Run the first cell to initialize the `bank` list of accounts.
3. Run the second cell — you'll be prompted to:
   - Enter your account number
   - Choose a service (1–4)
   - Follow the additional prompts for deposit/withdraw/new account amounts

## Menu options

```
1) Deposit
2) Withdraw
3) Check balance
4) Create new account
```

## License

No license specified — add one if you plan to share or publish this project.
