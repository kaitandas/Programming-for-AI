# Programming-for-AI

# 🏏 IPL Player Statistics Data Cleaning Project

This project demonstrates **data preprocessing and cleaning techniques** in Python using the **IPL Player Statistics dataset**.  
It focuses on preparing raw cricket data for further analysis or visualization by handling duplicates, missing values, and formatting issues.

---

## 🚀 Features
- Load dataset using **Pandas**
- Perform **exploratory analysis** with `.info()` and `.describe()`
- Clean dataset by:
  - Removing duplicates
  - Handling missing values (`dropna`, `fillna`)
  - Replacing unwanted strings (e.g., `'nan--'`)
  - Stripping whitespaces from string columns
- Inspect unique values and ranges for better understanding of the data

---

## 📂 Project Structure
├── project.ipynb # Jupyter Notebook with full code
├── project-checkpoint.ipynb # Auto-saved checkpoint
└── IPL Player Stat.csv # Dataset used (not included in repo by default)

yaml
Copy code

---

## ⚙️ Requirements
Install dependencies before running the notebook:
```bash
pip install pandas jupyter
▶️ How to Run
Clone this repository

Place the dataset IPL Player Stat.csv in the same folder

Open the notebook:

bash
Copy code
jupyter notebook project.ipynb
Run all cells to see the data cleaning steps in action

📊 Sample Operations
Minimum & maximum runs in the dataset

Handling null values with .dropna() and .fillna()

Removing duplicates

String cleaning with .str.replace() and .str.strip()

🏷️ Technologies Used
Python 🐍

Pandas 📊

Jupyter Notebook 📓
