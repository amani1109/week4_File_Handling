A menu-driven Personal Finance Tracker built using Python that allows users to record expenses, categorize them, save data to files, and generate monthly financial reports.
This project serves as a capstone application combining core Python concepts from Weeks 1–4, including file handling, data validation, modular logic, and error handling.

 ## Features

 Add and store expenses with validation
 Support for multiple expense categories
 Persistent storage using JSON
 Backup and restore functionality
 Export expenses to CSV
 Search and filter expenses
 Monthly expense reports
 Category-wise breakdown with text visualization
 User-friendly command-line menu system

##  Technologies Used

Python 3
JSON (data persistence)
CSV (data export)
Standard Python libraries only (no external dependencies)

## Project Structure
finance_tracker.py
data/
├── expenses.json        # Automatically created
├── backup/
│   └── expenses_backup.json
└── exports/
    └── expenses.csv


All required folders are automatically created when the program runs.

## How to Run the Project
1️ Clone or Download the Project
git clone <your-repo-url>
cd <project-folder>

2️ Run the Application
python finance_tracker.py

## Menu Options
1. Add Expense
2. View Expenses
3. Search Expenses
4. Monthly Report
5. Export CSV
6. Backup Data
7. Restore Backup
0. Exit

## Expense Data Format

Each expense contains:
Date (YYYY-MM-DD)
Amount (positive number)
Category
Food
Transport
Rent
Utilities
Entertainment
Health
Education
Other

## Description

## Sample Output
Category Breakdown:
Food            $120.00 ████████████
Transport       $45.00  ████
Entertainment   $60.00  █████

## Data Persistence

Expenses are saved automatically to data/expenses.json
Backup copies are stored in data/backup/
CSV exports are saved in data/exports/
