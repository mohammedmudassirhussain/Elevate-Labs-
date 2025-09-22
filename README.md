# Elevate-Labs-
# 📊 Netflix Titles Dataset Cleaning

This project focuses on cleaning and preparing the **Netflix Titles Dataset** (`netflix_titles.csv`) for analysis.  
The cleaning process involves handling missing values, removing duplicates, standardizing formats, and generating a summary report.  

---

## 🚀 Features
- Load raw dataset (`netflix_titles.csv`)  
- Identify and handle missing values  
  - Fill `director`, `cast`, `country`, `listed_in`, `description` with `"Unknown"`  
  - Fill `rating` with most frequent value (`TV-MA`)  
- Remove duplicate records  
- Standardize text formatting (trim spaces, fix casing, unify country names)  
- Convert `date_added` column to proper **datetime format (YYYY-MM-DD)**  
- Ensure numeric columns (`release_year`) are valid integers  
- Clean column names (lowercase, underscores)  
- Save **cleaned dataset** (`netflix_titles_cleaned.csv`)  
- Generate a **summary report** (`netflix_data_cleaning_report.txt`)  

---

## 📂 Files
- **`netflix_titles.csv`** → Raw input dataset  
- **`netflix_titles_cleaned.csv`** → Cleaned dataset (output)  
- **`netflix_data_cleaning_report.txt`** → Summary report of the cleaning process  
- **`clean_netflix.py`** → Python script used for cleaning  

---

## ⚙️ Requirements
Make sure Python (≥3.8) is installed.  

Install dependencies:
```bash
pip install pandas numpy
