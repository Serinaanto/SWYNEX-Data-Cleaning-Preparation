# Data Cleaning and Preparation – Netflix Dataset

## Project Overview
This project focuses on cleaning and preparing the Netflix Movies and TV Shows dataset using Python and Pandas. The objective is to identify and handle missing values, duplicate records, incorrect data types, and inconsistent text values.

## Dataset
- **Dataset:** Netflix Movies and TV Shows
- **Source:** [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Original records:** 8,807 rows
- **Columns:** 12

## Tools and Technologies
- Python
- Pandas
- Google Colab

## Data Cleaning Operations

### 1. Missing Values
- Identified missing values in director, cast, country, date_added, rating, and duration.
- Replaced missing values in director, cast, country, and rating with "Unknown".
- Retained missing date_added and duration values because the actual information was unavailable.

### 2. Duplicate Records
- Checked for completely duplicated rows.
- No duplicate records were found.

### 3. Data Type Correction
- Converted the date_added column from text to datetime format.
- Kept release_year as an integer.
- Retained other columns in their appropriate formats.

### 4. Inconsistent Values
- Removed unnecessary leading and trailing spaces from text columns.
- Standardized the capitalization of the type column to use "Movie" and "TV Show".

## Final Results
- Original dataset: 8,807 rows and 12 columns.
- No completely duplicated rows were found.
- Missing values in four columns were handled.
- 10 missing date_added values and 3 missing duration values were retained.
- Date format was corrected.
- Text values were standardized.

## Repository Files
- `netflix_titles.csv` – Original dataset.
- `cleaned_netflix.csv` – Cleaned dataset.
- `data_cleaning.ipynb` – Python notebook containing the cleaning process.

## Conclusion
The Netflix dataset was inspected, cleaned, and prepared using Python and Pandas. The cleaned dataset is more consistent and suitable for further data analysis.
