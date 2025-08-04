# Netflix Data Cleaning Task

This project is part of a data preprocessing exercise focused on cleaning and preparing real-world datasets for analysis.

📄 Dataset
Source: Netflix Movies and TV Shows dataset from Kaggle  
(https://www.kaggle.com/datasets/shivamb/netflix-shows)

🔧 Cleaning and Preprocessing Steps

- ✅ Removed rows with non-English characters in text columns (e.g., é, ñ, 中)
- ✅ Kept the `description` column as-is, even if it contained special characters
- ✅ Renamed column headers to lowercase and removed spaces
- ✅ Handled missing values (especially in `cast` and `director`)
- ✅ Ensured date formats were standardized
- ✅ Verified data types (e.g., release year as integer, date added as date)
- ✅ Checked and confirmed there were no duplicate rows

🛠 Tools Used
- Microsoft Excel (for most data cleaning tasks)
- Python (used optionally for initial inspection)

📁 Files Included
netflix_titles_fully_cleaned.xlsx`: Cleaned version of the dataset

📌 Objective
This task demonstrates essential skills in data wrangling, a critical step before analysis or modeling.


