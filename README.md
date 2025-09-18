# 🎓 Student Performance Prediction

## 📌 Objective
The goal of this project is to *predict student final grades* using multiple regression.  
We analyze which factors (study hours, attendance, sleep, past scores) affect performance the most.

---

## 📊 Dataset
The dataset contains the following features:
- *Study_Hours* → Hours spent studying daily
- *Attendance* → Percentage of classes attended
- *Sleep_Hours* → Average sleep hours
- *Past_Score* → Previous exam score
- *Final_Grade* → Final marks (Target variable)

---

## ⚙ Steps
1. *Dataset Preparation* – Collected data of students (study hours, attendance, etc.)
2. *Model Training* – Applied *Multiple Linear Regression* to predict final grade.
3. *Factor Analysis* – Checked coefficients to find the most important factors.

---

## 🧮 Results
- Predicted final grade for a sample student (7 hours study, 85% attendance, 6 sleep, 70 past score) → ~76-78 marks.
- *Most important factors:*
  - Study Hours ✅
  - Attendance ✅
- *Less important:*
  - Past Score (moderate effect)
  - Sleep Hours (slight negative effect if too much)

---

## 🚀 Technologies Used
- Python 🐍
- Pandas
- Scikit-Learn

---

## 📂 Files
- student_performance.ipynb → Jupyter Notebook / Colab code
- student_performance.py → Python script
- README.md → Project documentation
