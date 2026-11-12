# Home Credit Default Risk – Data Analysis

Exploratory analysis of Home Credit loan data to identify client characteristics linked to loan default, and to propose credit policy recommendations.

## Data
Source: [Home Credit Default Risk – Kaggle](https://www.kaggle.com/competitions/home-credit-default-risk)

- `application_train.csv` – loan applications with client info and `TARGET` (1 = payment difficulties, 0 = repaid on time)
- `bureau.csv` – client's previous credits from other institutions (Credit Bureau)

## Contents
`Default Risk.ipynb`
1. Read data, check missing values, identify feature types
2. EDA: default rate by loan type, age, education, occupation, and bureau credit history
3. Conclusion and policy recommendations

## Tools
Python, pandas, numpy, matplotlib, seaborn, scipy, scikit-learn

## How to run
Download the data from Kaggle, update the file paths in the notebook (default: `/kaggle/input/home-credit-default-risk/`), then run all cells.
