# netflix-data-cleaning

## Objective:
To clean and preprocess the Netflix dataset by handling missing values, removing duplicates, correcting inconsistent formats, and preparing the data for analysis.
---
## Tools Used:
- Python
- Pandas
- Jupyter Notebook
---
## Dataset Used:
**Netflix Movies and TV Shows** dataset from Kaggle  
It contains information about Netflix content such as title, director, cast, country, release year, rating, and date added.
---
## Summary of Changes:
- Removed duplicate rows.
- Handled missing values:
  - Filled 'director' and 'country' with 'Unknown'
  - Filled 'cast' and 'rating' with default values
  - Dropped rows missing 'date_added' or 'duration'
- Standardized text formatting (e.g., title case for 'type', capitalized 'rating')
- Converted 'date_added' column to datetime format
- Renamed all column headers to lowercase with underscores
- Ensured 'release_year' is an integer type
- Final cleaned dataset contains **[your_final_row_count]** rows and **[column_count]** columns.
---
##Files Included:
- `netflix_cleaning.ipynb` – Python notebook with all cleaning steps.
- `cleaned_netflix_titles.csv` – Final cleaned dataset.
- `README.md` – Summary of the work done.
---
## Output:

The cleaned dataset is ready for further analysis or visualization.  
It contains consistent, reliable, and structured data with:
- No duplicate rows
- Proper formatting
- No nulls in key columns

