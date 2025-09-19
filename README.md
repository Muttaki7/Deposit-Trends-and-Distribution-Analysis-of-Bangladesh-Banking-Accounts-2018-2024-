# Deposit-Trends-and-Distribution-Analysis-of-Bangladesh-Banking-Accounts-2018-2024-
This project provides a detailed analysis of banking deposit trends in Bangladesh using publicly available data from data.gov.bd
. The analysis covers total deposits, deposit type distribution, quarterly and yearly trends, and key growth insights from 2018 to the 2024.
Dataset

Source: Bangladesh Bank – Deposits Amount Distributed by Types of Account

File: data-resource_2024_06_24_Table-15 Deposits Amount Distributed by Types of Account.csv

Content: Deposits by type (savings, current, fixed, etc.) across years and quarters.

Features

Data Cleaning and Preprocessing

Converts numeric columns safely.

Extracts Year and Quarter from messy CSV entries.

Removes non-standard rows (notes, provisional entries).

Creates ordered categorical columns for plotting.

Descriptive Analysis

Total rows, columns, years, and quarters.

Summary statistics for all deposit types.

Visualization

Total deposits by year (bar chart)

Boxplot and histogram of total deposits

Year-over-Year growth trend

Quarterly deposit trends

Top 5 deposit types by total amount

Correlation heatmap among deposit types

Distribution boxplots for all deposit types

Cumulative deposits over years

Export

Cleaned dataset saved as cleaned_deposits.csv.

Requirements

Python 3.x

Libraries:

pandas
matplotlib
seaborn


Install required packages:

pip install pandas matplotlib seaborn

Usage

Place the CSV dataset in the project folder.

Update the file_path variable in main.py to point to your CSV file:

file_path = r"C:\path\to\your\dataset.csv"


Run the analysis:

python main.py


Visualizations and cleaned dataset will be generated automatically.

Example Output

Total Deposits by Year: Bar chart

Quarterly Deposit Trend: Line chart

Top 5 Deposit Types: Bar chart

Correlation Heatmap: Heatmap

Cumulative Deposits: Line chart

(All charts are displayed during execution.)

Project Structure
├── main.py                # Main analysis script
├── data-resource.csv      # Original dataset
├── cleaned_deposits.csv   # Cleaned output dataset
└── README.md              # Project documentation

References

Bangladesh Open Data Portal

Bangladesh Bank Statistics Department

License

This project is licensed under the MIT License.

If you want, I can also create a GitHub-ready version with badges, screenshots of graphs, and setup instructions so it looks professional on your repo page.
