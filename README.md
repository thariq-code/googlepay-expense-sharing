# Google Pay Expense Sharing System

## Project Description

This project is a simple Expense Sharing Application developed using Python in Jupyter Notebook.
The system helps friends manage shared expenses for accommodation, food, travel, and other group activities similar to the Google Pay expense sharing feature.

The application allows users to:

* Add shared expenses
* Split expenses equally among friends
* Calculate balances
* Display settlement amounts
* Suggest payment transactions between users

---

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* PrettyTable

---

## Libraries Required

Install the following libraries before running the project:

```python
pip install numpy prettytable
```

---

## Features

* Add expenses with payer details
* Split expenses equally among multiple users
* Automatically calculate shared amounts
* Track balances between friends
* Display final settlements in table format
* Suggest payment transactions for settling debts

---

## Project Structure

* `GooglePay_Expense_Sharing.ipynb` → Main Jupyter Notebook file
* `README.md` → Project documentation
* `Screenshots` → Output screenshots of the project

---

## How to Run the Project

1. Open Jupyter Notebook
2. Open the file:
   `GooglePay_Expense_Sharing.ipynb`
3. Run all cells
4. View the final settlements and suggested transactions

---

## Sample Output

### Final Settlements

| Friend | Settlement              |
| ------ | ----------------------- |
| Thariq | Should Receive ₹950.00  |
| Arsath | Owes ₹50.00             |
| Tj     | Owes ₹850.00            |
| Arsh   | Owes ₹50.00             |

### Suggested Transactions

* Arsath should pay ₹50 to Thariq
* Tj should pay ₹850 to Thariq
* Arsh should pay ₹50 to Thariq

---

## Business Use Case

This application can be used by friends, roommates, or travel groups to manage and settle shared expenses easily without manual calculations.

---

## Conclusion

The Google Pay Expense Sharing System simplifies expense management by automatically calculating balances and settlements among users. The project demonstrates the use of Python, NumPy, and PrettyTable for implementing a real-time expense-sharing solution.
