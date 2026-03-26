# Walmart Sales Data Analysis

## Project Overview

This project performs end-to-end data analysis on Walmart sales transaction data, covering data cleaning, exploratory analysis, and business insight extraction using Python and MySQL.

---

## Project Files

| File | Description |
|------|-------------|
| `Walmart.csv` | Raw, uncleaned sales transaction dataset |
| `walmart_clean_data.csv` | Cleaned and processed dataset ready for analysis |
| `data_cleaning.ipynb` | Jupyter notebook for data cleaning and preprocessing |
| `MySQL_Queries.sql` | SQL queries for business insight extraction |

---

## Dataset Description

The cleaned dataset contains the following columns:

| Column | Description |
|--------|-------------|
| `invoice_id` | Unique transaction identifier |
| `branch` | Walmart branch code (e.g., WALM003) |
| `city` | City where the branch is located |
| `category` | Product category (e.g., Health and beauty, Electronics) |
| `unit_price` | Price per unit of product |
| `quantity` | Number of units sold |
| `date` | Transaction date (DD/MM/YY) |
| `time` | Transaction time (HH:MM:SS) |
| `payment_method` | Payment type (Cash, Ewallet, Credit card) |
| `rating` | Customer satisfaction rating |
| `profit_margin` | Profit margin for the transaction |

Dataset size: ~9,970 transaction records

---

## Data Cleaning

The Jupyter notebook handles the following preprocessing steps:

- Removing duplicate records
- Handling missing and null values
- Standardizing date and time formats
- Fixing data types (e.g., converting `unit_price` from string to float)
- Deriving calculated columns as needed

---

## Tools and Technologies

- Python - Data cleaning and preprocessing
- Pandas - DataFrame operations
- Jupyter Notebook - Interactive analysis environment
- MySQL - Business insight queries using window functions, CTEs, and aggregations

---

## Key Insights

- Payment Methods: Ewallet, Cash, and Credit Card are the three payment options analyzed across all branches.
- Shift Analysis: Transactions are categorized into Morning (before 12:00), Afternoon (12:00 to 17:00), and Evening (after 17:00).
- Profitability: Total profit is calculated as unit_price x quantity x profit_margin.
- Revenue Trends: Year-over-year revenue change is tracked from 2022 to 2023 across branches.

---

## License

This project is for educational and portfolio purposes.
