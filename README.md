The Expense Tracker is a Python project that models and manages financial expenses through the implementation of two classes: `Expense` and `ExpenseDatabase`. This project serves as an assessment of understanding object-oriented programming (OOP) concepts in Python, focusing on defining classes, utilizing class attributes and methods, and handling time-related functionalities.

## Classes Overview

### Expense Class

Represents an individual financial expense.

Attributes:
- `id`: A unique identifier generated as a UUID string.
- `title`: A string representing the title of the expense.
- `amount`: A float representing the amount of the expense.
- `created_at`: A timestamp indicating when the expense was created (UTC).
- `updated_at`: A timestamp indicating the last time the expense was updated (UTC).

Methods:
- `__init__`: Initializes the attributes.
- `update`: Allows updating the title and/or amount, updating the `updated_at` timestamp.
- `to_dict`: Returns a dictionary representation of the expense.

# ExpenseDB Class

Manages a collection of `Expense` objects.

Attributes:
- `expenses`: A list storing `Expense` instances.

Methods:
- `__init__`: Initializes the list.
- `add_expense`: Adds an expense.
- `remove_expense`: Removes an expense.
- `get_expense_by_id`: Retrieves an expense by ID.
- `get_expenses_by_title`: Retrieves expenses by title (returning a list).
- `to_dict`: Returns a list of dictionaries representing expenses.

# Getting Started

# Clone the Repository

To get a local copy of the project, you can use the following command:

```bash
git clone https://github.com/omogeworld/expense-tracker.git

Running the Code
Make sure you have Python installed on your machine. Navigate to the project directory and run the Jupyter Notebook:
cd expense-tracker
jupyter notebook

Open the notebook file (ExpenseTracker.ipynb) and execute each cell to interact with the implemented classes.

Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

This README provides clear instructions on cloning the repository and running the code using Jupyter Notebook. Additionally, it includes sections for contributing and licensing, which you can customize based on your project's needs.
