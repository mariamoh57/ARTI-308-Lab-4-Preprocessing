# Data Quality Assessment & Preprocessing
## ARTI 308: Machine Learning - Lab 4

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### Project Overview
This repository contains the completion of Lab 4, focusing on preparing and cleaning data for machine learning models. The pipeline includes data quality assessment, missing value imputation, outlier handling, normalization, and dimensionality reduction.

### Dataset Note
Unlike previous projects, **no external CSV file is included in this repository**. The **Breast Cancer Wisconsin (Diagnostic)** dataset is dynamically loaded directly via the `scikit-learn` library (`sklearn.datasets.load_breast_cancer`). This advanced approach ensures complete reproducibility and eliminates the need for manual data file management.

### Tasks Performed
1. **Data Quality Assessment:** Identified missing values dynamically.
2. **Missing Value Strategy:** Applied **Mean Imputation** to the numerical features, as the mean effectively represents the central tendency for continuous variables.
3. **Outlier Detection & Handling:** Utilized the **Interquartile Range (IQR)** method to detect and cap outliers in specific features to prevent data loss.
4. **Normalization:** Applied both **Min-Max Scaling** and **Z-score Standardization** to ensure uniform feature scales for accurate model training.
5. **Dimensionality Reduction (PCA):** Verified feature correlation and successfully applied **Principal Component Analysis (PCA)** to reduce dimensions while retaining key variance.
