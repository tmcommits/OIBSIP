
# Task 1 - Data Cleaning

## Objective

The objective of this project is to clean and preprocess raw data by handling missing values, removing unnecessary columns, and standardizing text data.

## Dataset Used

Titanic Dataset

## Steps Performed

* Loaded the dataset using Pandas
* Checked dataset structure using `df.info()`
* Identified missing values using `df.isnull().sum()`
* Filled missing values in Age column using mean
* Filled missing values in Embarked column using mode
* Removed Cabin column due to excessive missing values
* Checked for duplicate rows
* Standardized text values in Sex column
* Generated summary statistics using `df.describe()`
* Saved the cleaned dataset

## Tools Used

* Python
* Pandas
* NumPy
* Google Colab

## Output

A cleaned dataset named `cleaned_titanic.csv` was generated successfully.

## Conclusion

This project helped in understanding the importance of data cleaning and preprocessing before performing analysis or building machine learning models.
