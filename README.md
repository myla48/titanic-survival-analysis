# Titanic Survival Analysis & Custom Dataset

## 📌 Project Overview
This project consists of two parts:
1. Creating a custom dataset using Python and pandas.
2. Analyzing the Titanic dataset to understand survival patterns.

---

## 🔹 Part 1: Custom Dataset
A dataset was created using a Python dictionary with the following features:
- Name
- Age
- Grade
- Gender
- Score

The dataset contains:
- 15 rows
- 5 columns
- Custom index (S1 to S15)

This demonstrates basic DataFrame creation using pandas.

---

## 🔹 Part 2: Titanic Dataset Analysis

### 📊 Data Exploration
- Used `.head()`, `.info()`, `.describe()`
- Identified missing values in Age, Embarked, and Cabin

---

### 🧹 Data Cleaning
- Filled missing **Age** values using median
- Filled missing **Embarked** values using mode
- Dropped **Cabin** column due to many missing values
- Removed duplicate rows

---

### 📈 Data Analysis
Performed analysis using `groupby()`:
- Survival rate by gender
- Survival rate by class
- Average age per class
- Survival rate by age group

---

### 🔍 Filtering
- Female passengers who survived
- Children who survived
- First class passengers who survived

---

### 💡 Key Insights
- Females had a significantly higher survival rate than males due to evacuation priority.
- First class passengers had higher survival rates due to better access to lifeboats.
- Children were more likely to survive compared to adults.
- The highest survival group was females in first class.

---

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib (for visualization)

---

## 📁 Files
- `Titanic_Part1_Part2.ipynb` — Main notebook
- `Titanic-Dataset.csv` — Dataset

---

## 🎯 Conclusion
This project demonstrates data cleaning, analysis, and extracting meaningful insights from real-world data.

---

## 👤 Author
Ruhama Zerihun
