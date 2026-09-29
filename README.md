# 🏦 Bank Account Management System

A simple **Bank Account Management System** developed using Python and Object-Oriented Programming (OOP) concepts. This project simulates basic banking operations such as deposits, withdrawals, balance inquiries and interest calculation, with OTP-based verification for withdrawals.

## 📌 Project Overview

The Bank Account Management System is a Python-based mini project designed to demonstrate the practical implementation of OOP concepts. It allows users to deposit money, withdraw funds after OTP verification, check their account balance and calculate interest.

The project uses Python's built-in `random` module to generate a four-digit OTP for withdrawal verification.

## ✨ Features

* 🏦 **Account Creation:** Create a bank account with an account holder's name and initial balance.
* 💰 **Deposit Money:** Deposit money into the account.
* 💸 **Withdraw Money:** Withdraw money after OTP verification.
* 🔐 **OTP Verification:** Generate a random four-digit OTP to verify withdrawals.
* 📊 **Balance Inquiry:** Check the current account balance.
* 📈 **Interest Calculation:** Calculate interest at a fixed rate of 5%.
* 🛡️ **Encapsulation:** Demonstrate public, protected and private attributes and methods.

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Concepts:** Object-Oriented Programming (OOP)
* **Module:** `random`
* **Input/Output:** Python's built-in `input()` and `print()` functions

## 📂 Project Structure

```text
Bank-Account-Management/
│
├── bank_account.py
└── README.md
```

## 🚀 How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/your-username/Bank-Account-Management.git
```

**Step 2: Navigate to the project directory**

```bash
cd Bank-Account-Management
```

**Step 3: Run the Python program**

```bash
python bank_account.py
```

**Step 4: Enter the OTP**

When you attempt to withdraw money, the program generates a four-digit OTP. Enter the displayed OTP to complete the withdrawal.

## 💻 Example Output

```text
Account holder: Suresh
Account type (protected): Saving
Deposited 2000
generated otp= 4821
enter a otp value4821
Withdrew 3000
Interest: 450.0
Balance: 9000
```

*Note: The OTP is randomly generated, so the value may differ each time.*

## 📚 Concepts Covered

| Concept                | Description                                                |
| ---------------------- | ---------------------------------------------------------- |
| Classes and Objects    | Creating and using the `BankAccount` class.                |
| Constructor            | Initializing account details using `__init__()`.           |
| Encapsulation          | Using public, protected and private attributes.            |
| Methods                | Implementing deposit, withdrawal and balance methods.      |
| Return Statements      | Returning the account balance and OTP verification result. |
| Conditional Statements | Checking OTP validity and available balance.               |
| `self` Keyword         | Accessing instance attributes and methods.                 |
| F-Strings              | Formatting transaction messages.                           |
| Dynamic Input          | Accepting OTP from the user.                               |
| Random Module          | Generating a four-digit OTP.                               |
| Interest Calculation   | Calculating interest at a fixed 5% rate.                   |

## 🔍 How It Works

1. An account is created with the account holder's name and initial balance.
2. The user can deposit money into the account.
3. When the user requests a withdrawal, the system generates a four-digit OTP.
4. The user enters the OTP for verification.
5. If the OTP is correct and sufficient funds are available, the withdrawal is completed.
6. The system calculates interest at a fixed rate of 5%.
7. The user can check the updated account balance.

## 🎯 Learning Objectives

* Understand the fundamentals of Python classes and objects.
* Learn how constructors initialize object attributes.
* Apply encapsulation using public, protected and private members.
* Understand how methods interact with object data.
* Implement basic transaction logic using conditional statements.
* Explore random OTP generation and user input handling.

## 🔮 Future Enhancements

* Add PIN-based authentication.
* Implement transaction history.
* Add multiple bank accounts.
* Introduce a graphical user interface (GUI).
* Store account information in a database.
* Add input validation and improved transaction security.

## ⚠️ Limitations

* This is an educational project, not a real banking application.
* The OTP is displayed in the terminal and is not sent to a registered mobile number.
* Deposits currently do not include input validation.
* Account information is not permanently stored.
* The current implementation does not include secure authentication.

## 👨‍💻 Author

**G. Akshay Vardhan**
**k.Abhiram Reddy**

B.Tech – Data Science

GitHub: [Your GitHub Profile](https://github.com/akshayvardhan2023)

---

⭐ If you find this project useful, feel free to star the repository!
