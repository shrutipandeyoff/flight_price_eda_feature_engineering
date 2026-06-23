# flight_price_eda_feature_engineering
End-to-end Exploratory Data Analysis (EDA) and Feature Engineering on a Flight Price dataset using Python, Pandas, and Scikit-Learn.

# Flight Price Dataset: EDA & Feature Engineering

This project demonstrates a complete Exploratory Data Analysis (EDA) and Feature Engineering workflow on a Flight Price dataset. The objective is to transform raw flight data into a machine-learning-ready dataset by cleaning, preprocessing, and engineering meaningful features.

## Overview

The project focuses on understanding the structure of airline pricing data and applying feature engineering techniques to prepare the dataset for predictive modeling.

Key tasks include:

- Data cleaning and preprocessing
- Missing value treatment
- Date and time feature extraction
- Flight duration transformation
- Categorical variable encoding
- Feature creation and optimization
- Dataset preparation for machine learning

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- OpenPyXL
- Jupyter Notebook

## Feature Engineering Performed

### Date Features
- Extracted Day, Month, and Year from journey dates

### Time Features
- Extracted departure hours and minutes
- Extracted arrival hours and minutes

### Duration Features
- Converted duration into total minutes
- Handled inconsistent duration formats

### Missing Value Handling
- Identified and treated missing values
- Processed missing stop information

### Categorical Encoding
- Applied One-Hot Encoding on:
  - Airline
  - Source
  - Destination
  - Additional Information

### Data Optimization
- Removed redundant columns
- Prepared a machine-learning-ready dataset

## Outcome

Successfully transformed the raw flight dataset into a structured numerical dataset suitable for predictive analytics and machine learning applications.
