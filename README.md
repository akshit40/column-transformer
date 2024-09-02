# column-transformer
# COVID-19 Dataset Preprocessing

This repository provides a Jupyter notebook that demonstrates how to preprocess a dataset containing COVID-19 related features for machine learning. The preprocessing steps include handling missing data, encoding categorical features, and preparing the data for model training.

## Features

- **Data Loading**: Loads the dataset from a CSV file.
- **Data Analysis**: Provides basic analysis of missing data.
- **Data Preprocessing**:
  - **SimpleImputer**: Imputes missing values in the `fever` column.
  - **OrdinalEncoder**: Encodes the `cough` column, which contains ordinal categories.
  - **OneHotEncoder**: One-hot encodes the `gender` and `city` columns.
  - **Column Concatenation**: Concatenates the processed columns into a final dataset ready for machine learning.
- **ColumnTransformer**: Demonstrates the use of `ColumnTransformer` to streamline preprocessing.

## Requirements

The following Python libraries are required to run the notebook:

- `numpy`
- `pandas`
- `scikit-learn`

You can install these libraries using `pip`:

```bash
pip install numpy pandas scikit-learn
