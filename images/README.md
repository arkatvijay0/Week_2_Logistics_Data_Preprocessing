# Project Visualizations

This folder contains the visualizations generated during the Week 2 logistics data collection, cleaning, and preprocessing workflow.

## Included Visualizations

### `01_missing_values.png`
Shows the number of missing values identified across the dataset columns. The analysis confirmed that the dataset contained no missing values.

### `02_duplicates.png`
Shows the comparison between unique and duplicate records. The dataset contained no duplicate records.

### `03_outliers.png`
Shows the number of potential statistical outliers detected for numerical variables using the Interquartile Range (IQR) method.

### `04_boxplot.png`
Provides a boxplot-based visualization of selected numerical logistics variables and helps identify their spread and potential outliers.

### `05_distributions.png`
Shows the distributions of selected numerical logistics variables and helps understand their range, frequency, spread, and possible skewness.

### `06_normalization.png`
Compares the distribution of a selected numerical variable before and after applying Min-Max normalization.

### `07_correlation_heatmap.png`
Shows the correlation relationships between numerical logistics variables and helps identify the strength and direction of their linear relationships.

## Purpose

These visualizations support the data-quality assessment, preprocessing analysis, and findings presented in the project report.

The graphs were generated using Python libraries including **Matplotlib** and **Seaborn** and are also available in the Jupyter Notebook.

## Visualization Workflow

```text
Raw Dataset
     ↓
Data Quality Analysis
     ↓
Outlier Detection
     ↓
Data Cleaning
     ↓
Normalization
     ↓
Statistical Analysis
     ↓
Visualization
```

## Usage

The images can be referenced in the project report and used to visually communicate the results of the logistics data preprocessing process.
