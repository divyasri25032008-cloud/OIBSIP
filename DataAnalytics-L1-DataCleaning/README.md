# Data Cleaning – Titanic Dataset

## Project Overview
This project focuses on cleaning and preprocessing the Titanic dataset using Python, Pandas and NumPy.

## Objectives
- Identify missing values and duplicate records.
- Handle missing data using appropriate strategies.
- Detect outliers using the IQR method.
- Correct data types.
- Compare data quality before and after cleaning.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Data Cleaning Process
1. Loaded and explored the Titanic dataset.
2. Identified missing values in Age, Cabin and Embarked.
3. Filled missing Age values using the median.
4. Removed Cabin due to a high percentage of missing values.
5. Filled missing Embarked values using the mode.
6. Checked for duplicate records.
7. Detected Age and Fare outliers using the IQR method and retained plausible observations.
8. Converted PassengerId to string.

## Results

| Metric | Before | After |
|---|---:|---:|
| Rows | 891 | 891 |
| Columns | 12 | 11 |
| Missing Values | 866 | 0 |
| Duplicate Rows | 0 | 0 |

## Project Files
- `Data_Cleaning.ipynb` – Complete data cleaning process.
- `Titanic_Cleaned.csv` – Final cleaned dataset.

## Conclusion
The Titanic dataset was successfully cleaned, resulting in 891 rows and 11 columns with no missing values or duplicate records. The cleaned dataset is ready for further analysis.
