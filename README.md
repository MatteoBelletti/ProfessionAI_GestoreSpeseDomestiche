# ProfessionAI Household Expense Manager
Welcome to the ProfessionAI Household Expense Manager! This project is part of the curriculum for the Data Science Master program offered by ProfessionAI. The goal of this project is to develop a simple but effective expense tracking application using Python, with data persistence achieved through CSV file storage.

## Project Overview
The ProfessionAI Household Expense Manager is designed to help users monitor their daily financial transactions, generate monthly reports, and identify the most significant expenses. The system aims to provide a transparent financial overview, supporting users in making informed decisions to improve personal and family budget management.

## Features
### Transaction Recording
- Register a new expense by entering the date (DD/MM/YYYY), a short description, and the amount
- All transactions are immediately saved to a CSV file for real-time tracking

### Monthly Report
- Generate a summary of all transactions grouped by year and month
- Provides a clear view of spending trends over time

### Top 10 Transactions
- Display the ten highest expenses sorted by amount in descending order
- Helps identify the most impactful spending categories at a glance

### User-Friendly Interface
- Simple and intuitive interactive menu for easy operation
- Clear prompts and input validation for each field

## Technologies Used
- Python: programming language used for development
- CSV: lightweight file format for data persistence
- Google Colab: cloud-based notebook environment for running the application
- Standard library modules: `csv`, `os`, `datetime`

## Getting Started
To get started with the ProfessionAI Household Expense Manager, follow these steps:

1. Open the notebook in Google Colab by navigating to the repository and clicking **Open in Colab**, or upload `GestoreSpeseDomestiche.ipynb` directly at [colab.research.google.com](https://colab.research.google.com).
2. Run each cell in order from top to bottom.
3. The last cell of Section 5 launches the interactive menu.
4. The cells in Section 6 are optional and demonstrate the application with pre-loaded sample data.

## Usage
Once the application is running, the interactive menu offers the following options:

- **[1] Aggiungi una transazione**: record a new expense with date, description, and amount.
- **[2] Report Mensile**: display all transactions sorted and grouped by year and month.
- **[3] Top 10 Transazioni**: display the ten largest expenses by amount.
- **[0] Esci**: exit the application.

## License
This project is licensed under the MIT License.

## Acknowledgements
Special thanks to ProfessionAI for providing the opportunity to work on this project and develop practical skills in data science and software development.
