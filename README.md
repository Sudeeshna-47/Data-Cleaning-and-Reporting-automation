# Data Cleaning & Reporting Automation

## Project Overview

This project automates the process of data cleaning and reporting using Python. It identifies and handles missing values, removes duplicate records, standardizes inconsistent data, generates a cleaned dataset, creates an automated cleaning report, and produces visual summaries for data analysis.

## Objectives

* Automate data cleaning tasks using Python.
* Handle missing values and duplicate records.
* Standardize inconsistent text data.
* Generate an automated data cleaning report.
* Create visual summaries to support data analysis.

## Dataset

* **Dataset:** Sample Superstore Dataset (.xlsx)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* OpenPyXL

## Project Workflow

1. Load the dataset.
2. Explore the dataset using descriptive functions.
3. Detect and handle missing values.
4. Detect and remove duplicate records.
5. Standardize inconsistent text data.
6. Save the cleaned dataset.
7. Generate an automated cleaning report.
8. Create visual summaries.

## Visualizations

* Category-wise Sales (Bar Chart)
* Profit by Region (Bar Chart)
* Customer Segment Distribution (Pie Chart)

## Project Structure

```
Data-Cleaning-Reporting-Automation/
│
├── DataSet/
│   └── Sample - Superstore.xlsx
├── notebook/
│   └── data_cleaning_automation.ipynb
├── reports/
│   ├── cleaned_data.csv
│   └── cleaning_report.txt
├── images/
│   ├── category_sales.png
│   ├── profit_by_region.png
│   └── segment_distribution.png
├── requirements.txt
└── README.md
```

## Expected Outcome

This project demonstrates practical data preprocessing techniques by automating data cleaning tasks and generating reports with visual summaries. It improves data quality, reduces manual effort, and provides insights for decision-making.

## How to Run

1. Clone this repository.
2. Install the required libraries:

   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook.
4. Run all cells in `data_cleaning_automation.ipynb`.
5. The cleaned dataset, cleaning report, and visualizations will be generated automatically.

## Learning Outcomes

* Data Cleaning
* Missing Value Handling
* Duplicate Removal
* Data Standardization
* Report Automation
* Data Visualization
* Python for Data Analysis
