# Feature Engineering Practice

## Overview

This repository contains a hands-on implementation of basic feature engineering and data preprocessing techniques using Python. It is designed for learning and understanding how raw data is prepared before applying machine learning models.

---

## Topics Covered

* Handling missing values
* Encoding categorical data (Label, Ordinal, One Hot Encoding)
* Feature scaling (Standardization & MinMax Scaling)
* Log transformation
* Data cleaning and correlation analysis
* One-Hot Encoding using pandas (`pd.get_dummies()`)

---

## Notebooks Included

* feature_engineering_practice.ipynb
  Covers fundamental feature engineering steps such as missing value handling, encoding, scaling, and transformations.

* scaling_visualization.ipynb
  Demonstrates feature scaling techniques with visualization (before vs after scaling).

* standard_vs_minmax_scaling.ipynb
  Compares StandardScaler and MinMaxScaler.

* categorical_encoding_practice.ipynb
  Covers categorical encoding techniques including Label Encoding, Ordinal Encoding, and One Hot Encoding.

* Feature(Ordinal_Encoding).ipynb
  Extended notebook with practical dataset including:

  * One-Hot Encoding using `pd.get_dummies()`
  * Encoding categorical features like Fuel Type and Transmission
  * Boolean to numeric conversion (0/1)
  * Data cleaning by removing unnecessary columns
  * Handling errors in correlation computation
  * Correlation analysis with target variable (Price)
  * Final preprocessing flow including encoding and dataset preparation

---

## Steps Performed

1. Created a sample dataset
2. Handled missing values using mean
3. Encoded categorical columns using different encoding techniques
4. Applied StandardScaler and MinMaxScaler for feature scaling
5. Performed log transformation on numerical data
6. Visualized data before and after preprocessing
7. Applied One-Hot Encoding using pandas (`pd.get_dummies()`)
8. Converted boolean values into numeric format
9. Removed unnecessary columns (Brand, Model)
10. Fixed correlation errors by selecting numeric data
11. Performed correlation analysis to understand feature impact on Price
12. Finalized dataset after encoding for machine learning use

---

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Key Learnings

* Importance of preprocessing in machine learning
* Difference between raw and scaled data
* When and why to use feature scaling
* Understanding different encoding techniques
* Handling categorical data in real datasets
* Practical use of One-Hot Encoding with pandas
* Importance of cleaning data before analysis
* Fixing errors related to non-numeric data
* Understanding feature relationships using correlation

---

## How to Run

1. Open the notebooks in Jupyter Notebook or Google Colab
2. Run all cells sequentially
3. Observe outputs and visualizations

---

## Purpose

This project is created for practice and to build a strong foundation in feature engineering concepts used in real-world machine learning workflows.

---

## Note

This is a beginner-level practice project focused on understanding core concepts while gradually improving towards real dataset handling and analysis.
