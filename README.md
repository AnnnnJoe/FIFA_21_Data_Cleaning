# Data Cleaning - FIFA 21 Dataset
## What is Data Cleaning?
#### Data cleaning, also known as data cleansing, is the process of identifying and correcting errors, inconsistencies, and inaccuracies in a dataset to improve its quality, reliability, and usefulness for analysis or other purposes. Data cleaning is a crucial step in the data preparation pipeline and is essential for ensuring that the data accurately reflects the underlying reality it represents.
## About dataset:
#### The dataset utilized for this task is the FIFA 21 dataset, sourced from Kaggle. This dataset was acquired in its original form through web scraping from sofifa.com, encompassing comprehensive information about football players and their performance, up to the year 2021. Notably, the FIFA 21 dataset comprises 18,979 rows and 77 columns.
## Tools used:
#### Python, Numpy, Pandas, Jupyter Notebook.
## Tasks Completed:
1. **Data Exploration:**
      - Checked datatypes
      - Checked duplicates and missing values
      - Checked statistical summary of dataset
2. **Data Cleaning:**
      - Standardized 'Height' and 'Weight' columns to a single unit (cm and kg respectively) by removing suffixes and converting values to numeric datatype.
      - Split 'Joined' column into separate day, month, and year columns, converting month numbers to month names for improved readability.
      - Rectified datatype issues in 'Wage', 'Value', and 'Release Clause' columns by removing currency symbols and converting to numeric datatype.
      - Removed newline characters from 'Club' column values for consistency.
      - Grouped values in 'Contract' column into 'Contract', 'Loan', and 'Free' categories, creating a new 'Agreement' column.
      - Removed star symbols from columns 'W/F', 'SM', 'IR' representing ratings and converted to numeric datatype.
      - Handled missing values in 'Hits' column by treating them as 0.
      - Handled missing values in 'Loan End Date' column by replacing with 'No Loan'.
      - Dropped 'photoUrl' and 'playerUrl' columns to streamline data for analysis.
      - Enhanced readability by renaming columns.
3. **Exporting Data:**
      - Exported cleaned dataset to Excel format for further analysis and visualization.
