# Processed Datasets

This folder contains the datasets generated after applying the data cleaning and preprocessing workflow to the original logistics dataset.

## Files

### `cleaned_logistics_data.csv`

This is the primary cleaned dataset generated after:

- Data type validation
- Timestamp conversion
- Duplicate checking
- Missing-value checking
- Data consistency validation

The original dataset contained no missing values and no duplicate records, so no unnecessary imputation or record deletion was performed.

### `normalized_logistics_data.csv`

This dataset contains the cleaned data with numerical variables transformed using Min-Max normalization.

## Normalization Method

The following formula was used:

```text
X_normalized = (X - X_min) / (X_max - X_min)
