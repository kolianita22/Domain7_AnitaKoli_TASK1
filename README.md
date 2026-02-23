## 📊 Student Performance Data Analysis Project
# 📌 Project Overview

This project analyzes the Student Performance Dataset (student-mat.csv) using Python.
The goal is to explore student academic performance and understand the relationship between study time, gender, and final grades.

The dataset contains information about students' demographic, social, and academic attributes.

# 📂 Dataset Information

File Name: student-mat.csv

Total Records: 395 students

Total Features: 33 columns

Important Columns Used:

G1 – First term grade

G2 – Second term grade

G3 – Final grade (Target Variable)

studytime – Weekly study time

sex – Gender of student (M/F)

# 🛠 Technologies Used

Python 🐍

Pandas

Matplotlib

Seaborn

Jupyter Notebook

## 📊 Project Steps
# 1️⃣ Data Loading

Loaded dataset using pandas.read_csv()

Used sep=';' because the dataset is semicolon-separated.

# 2️⃣ Data Exploration

Checked dataset size using .shape

Verified missing values using .isnull().sum()

Examined column data types using .dtypes

# 3️⃣ Data Cleaning

Removed duplicate records

Handled missing values (if any)

# 4️⃣ Data Analysis Questions
🔹 1. What is the average final grade (G3)?

Average G3 = 10.42

🔹 2. How many students scored above 15 in G3?

    40 students scored above 15

🔹 3. Is there a correlation between study time and final grade?

   Correlation = 0.098

   This indicates a very weak positive relationship

🔹 4. Which gender has a higher average final grade?

  Male students have a slightly higher average G3 than female students.

# 📈 Visualizations Created

Histogram of Final Grades (G3)

Scatter Plot: Study Time vs Final Grade

Bar Chart: Average Final Grade by Gender

🎯 Key Findings

Most students scored between 8 and 14.

Study time has very weak correlation with final grade.

Only about 10% of students scored above 15.

Gender difference exists but is small.

## 🚀 How to Run the Project

Install required libraries:

``` pip install pandas matplotlib seaborn```

Place student-mat.csv in your project folder.

Run the Python script or Jupyter Notebook.

## 📌 Conclusion

This project demonstrates basic data analysis techniques including:

Data cleaning

Exploratory data analysis (EDA)

Statistical insights

Data visualization

It serves as a beginner-friendly machine learning and data analysis project.
