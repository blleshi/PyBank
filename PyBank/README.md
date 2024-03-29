# Module 2: Python Challenge (PyBank Financial Analysis Report)
Completed by Brigilda Lleshi

## Overview
This Python script analyzes the financial records of a company to calculate key metrics such as total number of months, net total amount of Profit/Losses, average change in Profit/Losses, greatest increase in profits, and greatest decrease in losses over the entire period. The analysis is performed on a dataset provided in a CSV file.
## Dataset
The dataset budget_data.csv contains two columns: Date and Profit/Losses. Each row represents the financial data for a specific month.

## Analysis
The Python script performs the following analysis on the financial records:
1. Total number of months included in the dataset
2. Net total amount of Profit/Losses over the entire period
3. Average change in Profit/Losses over the entire period
4. Greatest increase in profits (date and amount) over the entire period
5. Greatest decrease in losses (date and amount) over the entire period

## Assumptions
1. The financial records are assumed to be accurate and consistent.
2. The dataset contains complete and valid data for each month.

## Complications
All recurring complications on running the code were with the CSV file path. After much troubleshooting, it was likely (although still unsure) that the previous issues were due to incorrect specification of the file path or the working directory. Therefore, in order to bypass these persistent errors, it was necessary to directly use the pull CSV path in order to perform the financial analysis. Despite re-running codeblocks on Jupyter Lab, errors were still occuring with the file path; however, generating the same code on one code block generated no issues until I started tampering with it out of curiosity because the codes inputted were correct and had no errors prior.

![Error Screenshot (for README)](https://github.com/blleshi/Python-Challenge/assets/161882522/ffb88ff0-f248-4f3e-9289-7424d563ab9c)

After realizing this glitch, the route through importing "pandas as pd" and reading the CSV file as a DataFrame seemed like a much cleaner approach.
