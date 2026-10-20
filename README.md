# Project Kick-off: Choose and Load the Dataset

## Project Overview

This project begins an employee data analysis workflow using Python, Pandas, and Jupyter Notebook. The goal is to inspect the dataset, check basic data quality, and define business questions related to employee attrition.

## Dataset

- **Name:** IBM HR Analytics Employee Attrition & Performance
- **Source:** [Kaggle dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Format:** CSV
- **Rows:** 1,470
- **Columns:** 35

The dataset is a fictional employee dataset intended for analytics practice.

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- VS Code
- Git and GitHub

## Project Structure

```text
Project-Kick-off-Choose-and-Load-the-Dataset/
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── notebooks/
│   └── employee_data_analysis.ipynb
├── README.md
└── .gitignore
```

## Initial Data Inspection

The notebook covers:

- Dataset shape
- Column information and data types using `info()`
- Descriptive statistics using `describe()`
- Missing-value counts using `isna().sum()`
- Duplicate-row counts using `duplicated().sum()`

## Business Questions

1. Which department has the highest employee attrition?
2. Does overtime have an association with employee attrition?
3. How does monthly income differ between employees who left and employees who stayed?
4. Which job roles have the highest employee attrition?
5. Is job satisfaction associated with employee attrition?

## How to Run

1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install the required packages: `python -m pip install pandas jupyter ipykernel`.
4. Download the CSV dataset from Kaggle and place it in the `data/` directory.
5. Open `notebooks/employee_data_analysis.ipynb` in VS Code.
6. Select the correct Python kernel and run the notebook cells.

## Project Status

Task 2 — Project setup, dataset loading, initial data inspection, and business question definition.
