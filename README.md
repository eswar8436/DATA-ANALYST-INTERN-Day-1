
# Task 1: Data Cleaning and Preprocessing – Netflix Dataset

This project is part of a Data Analyst Internship assignment focused on cleaning and preprocessing real-world datasets using Python and Pandas.

## Dataset Used
- `netflix_titles_nov_2019.csv` (from Kaggle)

## Tasks Performed
- Handled **missing values** in `director`, `cast`, `country`, `date_added`
- Removed **duplicate rows**
- Standardized text in columns like `country`, `rating`
- Converted `date_added` to **datetime format**
- Renamed all columns to **lowercase with underscores**
- Verified and corrected **data types** (`release_year` as integer)

##  Summary of Cleaning
| Step                | Action Taken                          |
|---------------------|----------------------------------------|
| Missing Values       | Filled with mode or 'Unknown'          |
| Duplicates           | Checked and removed (if any)           |
| Text Standardization | Trimmed spaces, converted case         |
| Dates                | Converted `date_added` to datetime     |
| Column Names         | Lowercased and formatted               |
| Data Types           | Casted `release_year` to integer       |

## Files Included
- `netflix_titles_nov_2019.csv` - Raw dataset
- `netflix_cleaned.csv` - Cleaned dataset
- `netflix_cleaning_task1.ipynb` - Jupyter notebook with code
- `README.md` - This file


## Tools Used
- Python
- Pandas
- Jupyter Notebook
