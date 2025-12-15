# Zopper – Device Insurance Attach Percentage Analysis

## Overview
This project analyzes monthly device insurance attach percentage data for Jumbo & Company retail stores.  
The objective is to evaluate performance across branches, months, and stores, categorize store performance levels, and predict January attach percentage at the store level.

## Dataset
- Monthly attach percentages from August to December
- Granularity: Branch-level and Store-level

## Analysis Performed
- Month-wise attach percentage trend analysis
- Branch-wise performance comparison
- Store-wise performance evaluation
- Store categorization:
  - High Performing (≥ 40%)
  - Medium Performing (25% – 40%)
  - Low Performing (< 25%)
- Heatmap visualization of store vs month performance

## Prediction
- Linear Regression model used
- January attach percentage predicted at store level
- Prediction based on historical month-wise trend per store

## Files Included
- `zopper_attach_percentage_analysis.ipynb` – Complete analysis notebook
- `Zopper_Data_Science_Assignment_Report.pdf` – Concise business report
- `Zopper_Final_Attach_Analysis.xlsx` – Final output with store category and January prediction

## Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Author
Sayeed Anwar
