# Raw Dataset

This folder contains the original dataset used for the Week 2 logistics data collection, cleaning, and preprocessing project.

## Dataset File

`dynamic_supply_chain_logistics_dataset.csv`

## Dataset Source

Kaggle – Logistics and Supply Chain Dataset

https://www.kaggle.com/dsv/9673933

## Dataset Description

The dataset contains logistics and supply-chain-related operational data that can be used for data-quality assessment, exploratory analysis, preprocessing, and further logistics analytics.

## Dataset Size

- Records: 32,065
- Columns: 26

## Purpose

The raw dataset serves as the starting point for the preprocessing workflow. It is retained in its original form and is not modified manually.

The dataset was loaded into Python using Pandas and subsequently analyzed for:

- Missing values
- Duplicate records
- Data types
- Invalid values
- Potential outliers
- Numerical variable distributions

## Data Integrity

The original dataset is preserved without modification to maintain reproducibility and allow comparison between the raw and processed data.

All cleaning and transformation operations were performed separately and the resulting datasets are stored in the `processed` folder.
