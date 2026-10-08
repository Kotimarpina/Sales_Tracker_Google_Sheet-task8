# Task 8 – Sales Tracker in Google Sheets

## 📊 Retail Sales Tracker

This project is part of my **Data Analytics Internship at Veda Technologies**.

For this task, I created a lightweight **Sales Tracker using Google Sheets** to organize retail transaction data and automatically calculate daily, weekly, and monthly sales totals.

The main focus of this task was to understand how a spreadsheet can be structured for continuous data entry while using formulas to automatically aggregate and summarize sales information.

---

## 🎯 Objective

The objective of this task was to:

- Structure raw retail transaction data in a spreadsheet
- Create a separate summary section for analysis
- Automatically calculate daily sales
- Automatically calculate weekly sales
- Automatically calculate monthly sales
- Use formulas for dynamic calculations
- Apply data validation to reduce incorrect entries
- Verify calculated totals through manual checks

---

## 🛠️ Tools Used

- Google Sheets
- Google Sheets Formulas
- SUMIFS
- Data Validation
- Basic Spreadsheet Formatting
- Charts

---

## 📂 Dataset

The project uses a **Retail Sales dataset** containing transaction-level information.

The dataset includes the following fields:

| Column | Description |
|---|---|
| Transaction ID | Unique identifier for each transaction |
| Date | Transaction date |
| Customer ID | Unique customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Product Category | Category of the purchased product |
| Quantity | Number of units purchased |
| Price per Unit | Price of one unit |
| Total Amount | Total value of the transaction |

---

## 📑 Spreadsheet Structure

The Google Sheets workbook is organized into separate sections for raw data and analysis.

### Raw_Data

The `Raw_Data` sheet contains the original transaction-level data.

```text
Transaction ID
Date
Customer ID
Gender
Age
Product Category
Quantity
Price per Unit
Total Amount
