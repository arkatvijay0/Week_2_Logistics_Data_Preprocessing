# Week 2 - Logistics Data Collection, Cleaning and Preprocessing

## 📌 Project Overview

This project was completed as part of the Week 2 internship task focused on **Data Collection, Cleaning, and Preprocessing for Logistics Analysis**.

The objective of this project is to demonstrate a complete Python-based data preprocessing pipeline using a publicly available logistics and supply-chain dataset. The project focuses on understanding the dataset, identifying data-quality issues, performing cleaning and validation, detecting potential outliers, applying normalization techniques, and preparing the data for further analysis.

## 🎯 Objectives

- Collect and understand a publicly available logistics dataset
- Inspect the structure and characteristics of the data
- Identify missing values and duplicate records
- Validate and correct data types
- Convert timestamp information into a suitable datetime format
- Detect potential outliers using the IQR method
- Apply appropriate data-cleaning techniques
- Normalize numerical variables using Min-Max scaling
- Perform distribution and correlation analysis
- Generate visualizations to communicate preprocessing results
- Export cleaned and normalized datasets

## 📊 Dataset

The project uses a publicly available **Dynamic Supply Chain Logistics Dataset** from Kaggle.

Dataset source:

https://www.kaggle.com/dsv/9673933

The dataset contains **32,065 records and 26 columns** covering logistics and supply-chain-related operational information.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🔄 Data Preprocessing Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Understanding
     ↓
Missing Value Analysis
     ↓
Duplicate Detection
     ↓
Data Type Validation
     ↓
Timestamp Conversion
     ↓
Outlier Detection using IQR
     ↓
Data Cleaning
     ↓
Min-Max Normalization
     ↓
Correlation Analysis
     ↓
Visualization
     ↓
Final Dataset Verification
     ↓
Export Processed Data
```

## 🔍 Data Quality Analysis

The dataset was examined for:

- Missing values
- Duplicate records
- Incorrect data types
- Invalid numerical values
- Potential statistical outliers
- Variables with different numerical scales

The original dataset contained **no missing values and no duplicate records**, so no unnecessary deletion or imputation was performed.

## 📈 Outlier Detection

Potential outliers were identified using the **Interquartile Range (IQR)** method.

The IQR method uses:

```text
IQR = Q3 - Q1

Lower Bound = Q1 - 1.5 × IQR

Upper Bound = Q3 + 1.5 × IQR
```

Potential outliers were investigated rather than automatically removed because extreme logistics observations may represent genuine operational events.

## 📏 Normalization

Min-Max normalization was applied to numerical variables.

Formula:

```text
X_normalized = (X - X_min) / (X_max - X_min)
```

This transforms numerical variables to a common scale, generally between 0 and 1.

## 📊 Visualizations

The project includes visualizations for:

- Missing values
- Duplicate records
- Potential outliers
- Boxplots
- Numerical distributions
- Before vs. after normalization
- Correlation between numerical logistics variables

## 📁 Repository Structure

```text
future_ds_03/
│
├── README.md
│
├── dataset/
│   └── dynamic_supply_chain_logistics_dataset.csv
│
├── notebook/
│   └── Week_2_Logistics_Preprocessing.ipynb
│
├── output/
│   ├── cleaned_logistics_data.csv
│   └── normalized_logistics_data.csv
│
├── report/
│   └── Week_2_Logistics_Data_Preprocessing_Report.docx
│
└── figures/
    ├── 01_missing_values.png
    ├── 02_duplicates.png
    ├── 03_outliers.png
    ├── 04_boxplot.png
    ├── 05_distributions.png
    ├── 06_normalization.png
    └── 07_correlation_heatmap.png
```

## 📄 Report

The detailed project report is available in the `report/` folder.

It includes:

- Dataset description
- Methodology
- Data-quality assessment
- Cleaning techniques
- Outlier detection
- Normalization
- Python code snippets
- Visualizations
- Results
- Reflection
- Conclusion

## 💡 Key Learning Outcomes

This project provided practical experience in:

- Data collection and dataset understanding
- Data quality assessment
- Data cleaning using Pandas
- Missing-value analysis
- Duplicate detection
- Outlier detection using IQR
- Timestamp preprocessing
- Numerical normalization
- Data visualization
- Correlation analysis
- Documentation of a reproducible preprocessing workflow

## 👨‍💻 Project Author

**Vijay Kumar A G**

M.Tech – Data Science

This project was completed as part of an internship task.
