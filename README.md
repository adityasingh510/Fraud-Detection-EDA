This repository contains an exploratory data analysis (EDA) project performed on two datasets: `application_data.csv` and `previous_application.csv`. The goal of this project is to clean, preprocess, and analyze the data to uncover patterns and insights.

## Dataset Overview

- **application_data.csv**: Contains 122 columns and includes information about loan applications.
- **previous_application.csv**: Contains 37 columns and includes historical data on previous loan applications.

## Steps Performed

1. **Data Loading & Inspection**:
   - Loaded both datasets using pandas.
   - Displayed the first few rows to understand the structure.

2. **Data Cleaning**:
   - Removed redundant columns (e.g., mobile, phone, email, and document flags).
   - Encoded categorical variables using one-hot and label encoding.
   - Handled missing values and identified columns with high null counts.

3. **Exploratory Data Analysis**:
   - Visualized distributions and relationships using matplotlib and seaborn.
   - Analyzed correlations and key metrics.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (for encoding)

## How to Run

1. Clone the repository.
2. Ensure the datasets are placed in the correct directory.
3. Run the Jupyter notebook `EDA Assignment (2).ipynb`.

## Results

The analysis provides insights into loan application trends, applicant demographics, and historical loan behavior, which can be used for further modeling or decision-making.
