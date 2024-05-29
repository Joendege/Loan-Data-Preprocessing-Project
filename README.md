# Loan-Data-Preprocessing-Project


### Project Overview

This data cleaning project aims to clean and preprocess a loan data file in NumPy Package and then pass the dataset to data scientist team to measure and predict probability of default. The data set will be cleaned and preprocessed purely using NumPy Package, all the categorical variables will be quantifiable, that is the text columns will be converted to numerical then save the preprocessed file.

### Data Sources
The primary data source for this project is "loan_data.csv" file containing a detailed record of each loan given by the bank

### Tools
- Jupyter Notebook- Data Cleaning, Preprocessing and Formatting [Download Here](https://www.anaconda.com/)

### Data Cleaning and Preprocessing
The data cleaning and preprocessing stage I performed the following tasks:
1. Data Loading and Inspection
2. Data Splitting
3. Data Cleaning and Formatting
4. Handling missing values
5. Removing irrevant columns
6. Adding new columns
7. Merging and Ordering the data
8. Extracting the preprocessed data file

### Limitations 
On the categorical variables all missing data I had to fill them with the worst case scenario, in instances where the categorical varaible had two possible outcomes I had to fill them with dummy variables with the missing values filled with the worst case that is zero. On the numerical variables also the missing values I had to fill them also with the maximum values in the respective columns for loan_amount, intrest_rate, installment and total_payment columns. The funded amount column is the only i had to fill the missing value with the minimum amount in the column.

### References
- [Numpy Documentation](https://numpy.org/doc/stable/reference/generated/)
