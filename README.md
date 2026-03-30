# Data-Quality-Assessment-Preprocessing-on-IoT-dataset-for-Intrusion-Detection-Systems
This project focuses on assessing data quality and applying preprocessing techniques to prepare the dataset for machine learning tasks. The goal is to ensure that the data is clean, consistent, and suitable for analysis.

# 📊 Dataset
The dataset used in this project is related to **IoT dataset for Intrusion Detection Systems**

# Task 1: Data Quality Issues

Several data quality issues were identified:

Missing values in some columns
Duplicate records
Inconsistent data types

These issues were handled to improve the reliability of the dataset.

# Task 2: Handling Missing Values

Missing values were handled using:

Median for numerical features (to reduce the impact of outliers)
Mode for categorical features (to keep the most frequent values)

This approach ensures that the dataset remains balanced and meaningful.

# Task 3: Outlier Detection & Handling

Outliers were detected using the Interquartile Range (IQR) method.
Values outside the acceptable range were removed to improve model performance and reduce noise in the data.

# Task 4: Normalization

Two normalization techniques were applied:

Min-Max Scaling: Rescales values between 0 and 1
Z-score Standardization: Centers data around the mean with unit variance

These methods help improve the performance of machine learning algorithms.

# Task 5: PCA (Principal Component Analysis)

PCA was applied after analyzing the correlation between numerical features.
It helps reduce dimensionality while preserving important information in the dataset.

# Tools Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
