# 🚀 Feature Engineering Practice

## 📌 Overview

This repository contains hands-on practice of **feature engineering, data preprocessing, and transformation techniques** using Python and Scikit-learn.
It focuses on understanding how raw data is cleaned, transformed, encoded, scaled, and prepared for machine learning models.

The repository includes beginner-friendly practical notebooks covering preprocessing workflows commonly used in real-world ML pipelines.

---

## 🧠 Topics Covered

* Handling missing values
* Data cleaning and preprocessing
* Feature scaling

  * StandardScaler
  * MinMaxScaler
* Log transformation
* Power Transformation

  * PowerTransformer
  * Distribution normalization
  * Skewness reduction
* Encoding categorical data

  * Label Encoding
  * Ordinal Encoding
  * One-Hot Encoding
* Feature selection
* Correlation analysis
* Boolean to numeric conversion
* Binning and discretization
* Binarization techniques
* Data visualization for preprocessing
* Preparing datasets for ML models
* Handling date and time features
* Handling mixed variables
* Feature extraction from categorical-text data
* Missing value handling
* Missing data preprocessing
---

## 📂 Notebooks Included

### 🔹 feature_engineering_practice.ipynb

* Missing value handling
* Encoding techniques
* Feature scaling
* Log transformation

### 🔹 scaling_visualization.ipynb

* Visualization of scaling (before vs after)

### 🔹 standard_vs_minmax_scaling.ipynb

* Comparison of StandardScaler vs MinMaxScaler

### 🔹 categorical_encoding_practice.ipynb

* Label Encoding
* Ordinal Encoding
* One-Hot Encoding

### 🔹 Feature(Ordinal_Encoding).ipynb

* One-Hot Encoding using pandas
* Encoding Fuel Type & Transmission
* Boolean → numeric conversion
* Data cleaning (dropping unnecessary columns)
* Handling correlation errors
* Correlation analysis with target (Price)
* Final dataset preparation

### 🔹 PowerTransformer.ipynb

* Understanding skewed data
* Applying PowerTransformer
* Feature transformation techniques
* Normalizing numerical distributions
* Preparing transformed data for ML algorithms
* Comparing transformed vs original data
* Basic preprocessing workflow using sklearn

### 🔹 binning_practice.ipynb

* Understanding data binning
* Converting continuous data into categories
* Equal-width binning
* Equal-frequency binning
* Using pd.cut() and pd.qcut()
* Creating categorical ranges from numerical data
* Data preprocessing for ML workflows
* Visualization of binned data

### 🔹 Binarization.ipynb

* Understanding binarization techniques
* Converting numerical values into binary form
* Using sklearn Binarizer
* Applying ColumnTransformer
* Feature preprocessing workflow
* Preparing transformed data for machine learning
* Train-test split implementation
* Model training and evaluation
* Understanding threshold-based transformation

### 🔹 Handling_Mixed_Variable.ipynb

* Understanding mixed variables
* Separating categorical and numerical information
* Feature extraction from Cabin and Ticket columns
* Regex-based extraction techniques
* Handling text + number combined features
* Creating new categorical and numerical features
* Data preprocessing using pandas string methods
* Feature engineering workflow for mixed data types

### 🔹 Handling_Date_&_Time.ipynb

* Working with datetime data
* Extracting year, month, day, and week
* Extracting weekday and weekend information
* Semester feature creation
* Time feature extraction
* Datetime preprocessing using pandas
* Feature engineering from date and time columns
* Creating ML-ready temporal features

### 🔹 Handling_Missing_Values/

* Missing value preprocessing notebooks
* Null value analysis
* Imputation techniques
* Feature engineering with missing data
---

## ⚙️ Steps Performed

1. Created dataset
2. Handled missing values
3. Cleaned raw data
4. Applied encoding techniques
5. Performed feature scaling
6. Applied log transformation
7. Applied Power Transformation
8. Applied binning techniques
9. Applied binarization techniques
10. Visualized data changes
11. Applied One-Hot Encoding
12. Converted boolean values
13. Removed unnecessary columns
14. Fixed correlation issues
15. Analyzed feature relationships
16. Prepared final dataset for ML models
17. Extracted features from date and time columns
18. Handled mixed categorical and numerical variables
19. Created new engineered features from raw data

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Key Learnings

* Importance of preprocessing in ML
* Difference between raw vs scaled data
* Understanding skewed distributions
* Understanding data binning and discretization
* Understanding binarization preprocessing
* When to use scaling and encoding
* Importance of PowerTransformer in preprocessing
* Handling categorical data effectively
* Data cleaning before modeling
* Understanding feature relationships
* Building preprocessing workflows using sklearn
* Using ColumnTransformer in ML pipelines
* Working with datetime features
* Extracting useful information from mixed variables
* Creating engineered features from raw datasets

---

## ▶️ How to Run

1. Open notebooks in Jupyter Notebook / Google Colab
2. Install required libraries if needed
3. Run all cells sequentially
4. Observe outputs and visualizations

---

## 🎯 Purpose

This repository is created for **practice and learning purposes**, helping build a strong foundation in feature engineering and preprocessing techniques used in real-world Machine Learning workflows.

---

## 📝 Note

This is a **beginner-level practice repository** focused on learning core preprocessing concepts step-by-step before moving toward advanced machine learning projects and real-world datasets.
