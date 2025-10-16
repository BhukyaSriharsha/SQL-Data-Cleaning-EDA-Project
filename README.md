# 🔍 Layoffs 2022 – SQL Data Cleaning & EDA Project

<p align="center"> 
  <img src="https://img.shields.io/badge/Skill-SQL-blue?style=for-the-badge"/> 
  <img src="https://img.shields.io/badge/Tool-MySQL-orange?style=for-the-badge"/> 
  <img src="https://img.shields.io/badge/Category-Data%20Analytics-success?style=for-the-badge"/> 
</p>

---

## 📄 Overview

This project focuses on cleaning and analyzing a **global tech layoffs dataset** using **SQL**.  
The dataset was sourced from [Kaggle – Layoffs 2022](https://www.kaggle.com/datasets/swaptr/layoffs-2022).

It demonstrates **real-world data cleaning, transformation, and exploratory analysis** using SQL queries — replicating a typical **data analyst workflow**.

---

## 🧠 Project Structure

| Phase | Description |
|:------|:-------------|
| **1️⃣ Data Cleaning** | Removed duplicates, standardized values, handled NULLs, and fixed date formats. |
| **2️⃣ Exploratory Data Analysis (EDA)** | Found trends, outliers, and insights from cleaned data. |

---

## 🧰 Tools & Technologies

- **MySQL / SQL Workbench**  
- **Kaggle Dataset (Layoffs 2022)**  
- **Window Functions, CTEs, Joins, and Aggregations**

---

## 🧹 Data Cleaning Highlights

✅ Removed duplicate records using `ROW_NUMBER()` and **CTEs**  
✅ Standardized inconsistent values (e.g., `"CryptoCurrency"` → `"Crypto"`)  
✅ Replaced empty strings with `NULL` and filled missing industries  
✅ Converted `date` column to correct SQL **DATE** format  
✅ Removed incomplete rows (missing `total_laid_off` or `percentage_laid_off`)  
✅ Trimmed trailing punctuation (like `"United States."` → `"United States"`)  

---

## 📊 EDA (Exploratory Data Analysis) Highlights

📈 Identified **companies and countries** with the highest layoffs  
🏢 Found companies that laid off **100% of their workforce**  
📍 Analyzed layoffs by **industry, location, and company stage**  
📆 Studied **yearly & monthly layoff trends** using rolling totals  
🥇 Extracted **Top 3 companies with most layoffs each year** using window functions  

---

## 🚀 How to Run

### 1️⃣ Import the dataset
- Download [`layoffs.csv`](https://www.kaggle.com/datasets/swaptr/layoffs-2022) from Kaggle.  
- Import it into your SQL environment as:
  ```sql
  world_layoffs.layoffs
2️⃣ Run the Cleaning Script
Execute:

sql
Copy code
Portfolio Project - Data Cleaning.sql
to create a cleaned table:

sql
Copy code
layoffs_staging2
3️⃣ Run the EDA Script
Use:

sql
Copy code
Portfolio Project - EDA.sql
to explore insights and generate analytical outputs.

📁 Folder Structure
pgsql
Copy code
📦 layoffs-sql-project
┣ 📜 README.md
┣ 📄 Portfolio Project - Data Cleaning.sql
┣ 📄 Portfolio Project - EDA.sql
┗ 📊 layoffs.csv
📈 Sample Insights
Metric	Value
Most layoffs (Company)	Amazon
Top affected industry	Tech / FinTech
Country with highest layoffs	United States
Year with peak layoffs	2022

👤 Author
Bhukya Sriharsha
🎓 IIT (ISM) Dhanbad | Data Analyst | Python & SQL Enthusiast

📧 Email: sriharshabhukya@gmail.com

🔗 LinkedIn: [LinkedIn](https://www.linkedin.com/in/bhukya-sriharsha-a70362255/)
💻 GitHub: [github](https://github.com/BhukyaSriharsha)

🚀 This project demonstrates SQL data cleaning, analytics, and insights generation — a must-have skill for data analyst roles.
