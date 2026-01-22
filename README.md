# Task1-Train
This project demonstrates a complete data cleaning workflow using a Kaggle dataset in Excel/Google Sheets. It includes handling missing values, validating duplicates, standardizing text, fixing date and numeric formats, adding Data_Quality_Notes, and exporting clean data as XLSX and CSV for analysis.

1]------Dataset

Source: Kaggle

Format: CSV (converted to XLSX for cleaning)

Rows: ~9,800

Domain: Retail / Sales Data


2]------Data Cleaning Process

Imported the CSV dataset and ensured correct column headers and delimiter separation.

Used Freeze Panes and filters to explore the dataset efficiently.

Identified missing values using filters and conditional formatting.

Found 11 missing values in the Postal Code column and replaced them with the code 41550.

Checked for duplicate records after creating a backup sheet; no duplicates were found.

Standardized text columns using TRIM and PROPER to remove extra spaces and inconsistent casing.

Validated date columns by converting them to YYYY-MM-DD format.

Verified numeric columns and formatted Sales values as currency.

Created a separate Cleaned_Data sheet to keep raw and processed data separate.

Added a Data_Quality_Notes column to document data issues and cleaning decisions.

3]------Key Results

Missing values handled and documented

No duplicate records present

Text, date, and numeric formats standardized

Total Sales Amount: 2,261,536.78

4]------Final Output

Cleaned_dataset.xlsx

cleaned_dataset.csv

5]------Tools & Skills

Tools: Excel / Google Sheets
Skills: Data Cleaning, Data Validation, Data Quality Checks, Attention to Detail, Analyst Workflow

6]------Conclusion

This project highlights a real-world data cleaning pipeline and reflects essential skills required for an entry-level Data Analyst role. It ensures data quality, consistency, and readiness for further analysis.
