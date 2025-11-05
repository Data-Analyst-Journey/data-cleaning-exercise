# 🧹 Data Cleaning Exercise - Dropna & Fillna

This exercise demonstrates how to handle missing data using **pandas** in Python.

---

## 📊 Overview
The dataset simulates a group of students with missing values in different columns, such as `subject` and `age`.

I practiced:
- Removing rows with missing subjects using `dropna(subset=['subject'])`
- Filling missing `age` values with the column mean using `fillna()`
- Understanding how `inplace=True` works
- Avoiding the `SettingWithCopyWarning` by using `.copy()` or assignment without `inplace`

---

## 🧠 Key Concepts Learned
- The difference between `view` and `copy` in pandas  
- When and why to use `.copy()` after filtering  
- How `dropna` and `fillna` affect DataFrames  
- Safe and clean ways to modify data

---

## 🧰 Tools & Libraries
- Python 3  
- Pandas  
- Jupyter Notebook  

---

## 📂 Files
| File | Description |
|------|--------------|
| `data_cleaning.ipynb` | Main notebook with all steps and explanations |
| `students_dirty.csv` | Example dataset containing missing values |

---

## 💬 Notes
This is part of my data analysis learning journey — practicing real-world data cleaning skills step by step before visualization.
