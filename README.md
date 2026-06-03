# Task 2

This repository contains `Project 2.ipynb`, a Jupyter Notebook focused on exploratory data analysis for an order dataset.

## What Was Done

The notebook performs an exploratory analysis of 1,200 orders, including:

- Loading and previewing the cleaned analytics dataset.
- Calculating basic descriptive statistics.
- Visualizing distributions for key numeric fields.
- Reviewing revenue trends and monthly patterns.
- Detecting outliers using the IQR method.
- Comparing product revenue performance.
- Reviewing order status patterns.
- Analyzing referral sources by revenue.
- Summarizing key business observations from the analysis.

## Main Findings

- The average order value is higher than the median, showing that a small number of high-value orders increase the mean.
- Quantity is tightly distributed, generally ranging from 1 to 5 items per order.
- `TotalPrice` contains the clearest outliers, with several high-value orders above the IQR upper bound.
- Chair, Printer, and Laptop generate the highest total revenue in the dataset.
- June 2024 is the strongest revenue month in the analyzed data.
- Cancelled and Returned orders are slightly more common than Delivered orders.
- Instagram and Email are the strongest referral sources by total revenue.

## How to Run

Open `Project 2.ipynb` in Jupyter Notebook, JupyterLab, or VS Code and run the cells in order.

The notebook expects a local CSV file named `Cleaned_Data_Analytics_Dataset.csv`.

