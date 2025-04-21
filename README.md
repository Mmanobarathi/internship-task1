
# Task 1 - Internship
# Data Cleaning Task 
## Objective
To clean and prepare the Netflix titles dataset by handling null values, removing duplicates, standardizing formats, and ensuring data consistency using Python and Pandas.

## Tools Used
1.Python
2.Pandas
3.Jupyter Notebook

## Dataset
- Source file: `netflix_titles.csv`
- Description: Contains information about movies and TV shows available on Netflix.

## Data Cleaning Steps

1. **Loaded Dataset** using 'pandas.read_csv'.
2. **Explored Dataset** with '.info()', '.describe()', and '.isnull().sum()'.
3. **Removed Duplicates** using '.drop_duplicates()'.
4. **Handled Missing Values** by:
   - Dropping nulls in 'date_added'
   - Filling other columns with appropriate defaults
5. **Standardized Text** using '.str.strip().str.title()'.
6. **Converted Dates** with 'pd.to_datetime()'.
7. **Saved Cleaned Data** as 'netflix_titles_cleaned.csv'.

## Files in Repository

- 'task1 internship.ipynb' — Full notebook with data cleaning steps
-  'netflix_titles_cleaned.csv'. — Cleaned dataset
- 'README.md' — This file
