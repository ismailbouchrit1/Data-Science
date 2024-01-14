![Image description](https://assets-global.website-files.com/63b7152f92a121295976e6ed/63c57b741af4d31e3b441d07_6104190348e0bc8e2ded440f_dataqualitydashboard.png)
# File Name: Data Quality Integrator.ipynb

# Description 
This Jupyter Notebook file contains code to integrate data quality checks on a dataset. It separates categorical and numeric columns, handles missing values, performs visualizations and predicts missing values.

# Usage
You can use this file to load a dataset, perform exploratory data analysis, identify data quality issues like missing values, separate variable types and predict missing values. 

# Functions used
The file contains the following key functions:

- `separate_columns()`: Separates categorical and numeric columns 
- `visualisation()`: Performs visualizations on categorical and numeric columns
- `regression()`: Performs regression on numeric target variable
- `classification()`: Performs classification on categorical target variable
- `prepare_datasets()`: Prepares training and prediction datasets

# Requirements
This file requires Python and the following libraries:
- Pandas 
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
