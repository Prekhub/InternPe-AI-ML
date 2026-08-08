# Week 2: Used Car Price Predictor (Quikr Analysis)

## Overview
Built a Machine Learning regression model to predict the resale price of used cars based on historical listing data from Quikr.

## Key Features & Workflow
- **Data Cleaning & Formatting:** Cleaned messy text entries in vehicle names, removed non-numeric entries, formatted price and mileage columns, and handled missing values.
- **Outlier Removal:** Filtered out extreme price outliers to improve model stability and generalizability.
- **Feature Engineering:** Extracted brand names, model years, total kilometers driven, and fuel type for predictive modeling.
- **Pipeline & Model Building:** Created a machine learning pipeline using `ColumnTransformer` and `OneHotEncoder` for categorical features, paired with a Linear Regression estimator.
- **Evaluation:** Split the dataset into training and test sets to evaluate performance and ensure reliable price estimation.

## Project Structure
- `Quikr_Analysis.ipynb`: Main Jupyter Notebook with complete EDA, data cleaning, pipeline construction, and evaluation.
- `quikr_car.csv`: Raw dataset containing car listing attributes.