# Task-1--Data-Analysis-Project-Using-Python-Internship

📘 Project Summary: Student Performance Data Analysis
🔍 Task Overview
The goal of this project is to analyze a student performance dataset to explore patterns related to final math grades (G3). The analysis includes data loading, cleaning, statistical exploration, answering key questions, and visualizing insights.

📊 Dataset Description
Source: student-mat.csv
Content: Demographic, social, and academic performance data of secondary school students.
Target Variable: G3 — Final math grade (ranging from 0 to 20).

🧾 Steps Taken
Data Loading and Inspection:

Used pandas to load the CSV file.
Displayed basic structure using .head(), .shape, .dtypes, and .describe().

Data Cleaning:

Checked and handled missing values (filled with median).
Removed duplicate entries to ensure data quality.

Data Exploration:

Verified data structure and summary statistics.
Checked distributions and potential data quality issues.

Data Analysis:

Average Final Grade (G3): Calculated using .mean().
High Scorers: Counted students scoring above 15 in G3.
Correlation: Checked relationship between studytime and G3.
Gender Comparison: Compared average G3 scores by gender.

Data Visualization:

Histogram: Showed distribution of G3 scores.
Scatter Plot: Visualized the relationship between study time and G3.
Bar Chart: Compared average grades between male and female students.

✅ Key Findings
Average Final Grade (G3): ~10.42

Students Scoring Above 15: 94 students

Correlation (Study Time vs G3): Slight positive (weak) correlation

Gender Performance: Male students slightly outperformed females on average
