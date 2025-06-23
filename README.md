
# Task 1: Data Cleaning and Preprocessing

## 📊 Dataset:
**Netflix Movies and TV Shows Dataset**  
Source: [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 🎯 Objective:
To clean and prepare a raw dataset by handling:
- Missing values
- Duplicates
- Inconsistent formats
- Non-standard column names and types

---

## 🧹 Cleaning Summary:

### ✅ Performed Steps:
1. **Handled Missing Values**
   - Filled missing values in `director`, `cast`, `rating`, and `duration`
   - Used mode to fill missing `country` values
   - Dropped rows with null `date_added`

2. **Removed Duplicate Records**
   - Used `.drop_duplicates()` to clean repeated rows

3. **Converted Date Formats**
   - `date_added` column converted to `datetime` format

4. **Renamed and Cleaned Columns**
   - Column names standardized (lowercase, no spaces, underscores)
   - Trimmed and standardized text fields like `type` and `country`

5. **Verified Data Types**
   - Confirmed all column types are appropriate

---

## 💻 Tools Used:
- Google Colab
- Python
- Pandas

---

## 📁 Files in this Repository:
- `final_cleaned_netflix_titles.csv` — Cleaned dataset
- `task1_data_cleaning.ipynb` — Google Colab notebook
- `README.md` — This file

---

## ✅ Outcome:
The final cleaned dataset is now ready for further data analysis, visualization, or modeling.
