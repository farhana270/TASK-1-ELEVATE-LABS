# TASK-1-ELEVATE-LABS
# This project involves cleaning the Netflix Titles Dataset to prepare it for further analysis or visualization. The dataset originally contained duplicates, missing values, and inconsistent formats that needed to be addressed before use.

# What This Script Does
1. Loads the Raw Dataset: Reads the netflix_titles.csv file using pandas.
2. Cleans the Data:
Removes any duplicate rows.
Fills missing director, cast, and country values with "Unknown".
Drops rows missing critical fields like date_added, rating, or duration.
Fixes Formatting Issues:
Converts date_added to a proper datetime format.
Strips extra spaces from text fields (rating, type) for consistency.
Saves the Cleaned Dataset: Outputs a cleaned version as netflix_titles_cleaned.csv.
