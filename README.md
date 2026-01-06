# Airbnb Data Cleaning Project

## Overview
This project focuses on cleaning and validating an Airbnb dataset.
The goal is to transform raw data into a clean, analysis-ready dataset.

## Dataset
- Rows (raw): 102,599
- Rows (cleaned): 102,050
- Columns (raw): 26
- Columns (cleaned): 19

## Cleaning Steps
- Removed irrelevant columns
- Handled missing values logically (no blind deletion)
- Converted data types correctly
- Normalized categorical values
- Removed duplicates
- Validated numeric ranges

## Validation Performed
- Missing value checks
- Data type checks
- Duplicate detection
- Logical range checks
- Distribution sanity checks

## Output
- `cleaned_data.csv` is ready for EDA and ML tasks

## Tools Used
- Python
- Pandas
- NumPy
