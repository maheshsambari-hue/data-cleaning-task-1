# 🧹 Data Cleaning and Preprocessing Task

## 📌 Objective
This project is part of a data cleaning assignment. The goal is to clean a raw dataset by identifying and fixing:
- Missing values
- Duplicate records
- Inconsistent data formats (text, date)
- Column naming issues
- Incorrect data types

---

## 📂 Dataset
**Chocolate Sales.csv** — A sample dataset with issues like:
- Null values in Name
- Duplicates
- Inconsistent date formats
- Inconsistent capitalization in text columns (like Country)

---

## 🛠 Tools Used 
- Excel (for spreadsheet-based cleaning)

---

## 🔧 Cleaning Steps
1. **Handled missing values**  
   → Filled with "Unknown" or average values for Age

2. **Removed duplicates**  
   → Duplicate rows based on all columns

3. **Standardized text**  
   → Country fields converted to consistent formats (e.g., 'India')

4. **Converted date formats**  
   → Standardized all dates to `dd-mm-yyyy`

5. **Renamed columns**  
   → Used lowercase and underscores (e.g., `sales_person`, `boxes_shipped`)

---

## 📁 Files Included
- `Chocolate Sales.csv` — Original raw dataset
- `cleaned_chocolate_sales_dataset.csv` — Final cleaned dataset
- `README.md` — This file

---

## ✅ Outcome
- A clean, structured dataset ready for data analysis or modeling
- Practice in handling real-world data issues
