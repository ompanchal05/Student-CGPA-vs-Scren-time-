#  Student CGPA vs Screen Time Analysis

##  Project Overview
This project analyzes the relationship between **students' screen time and academic performance (CGPA)** using **Python for data analysis** and **Power BI for visualization**.

The purpose of this project is to understand how different types of screen usage such as **social media, gaming, and online study** affect students' academic performance.

This project demonstrates **data cleaning, exploratory data analysis (EDA), and dashboard creation**.

---

##  Project Objectives

- Analyze students' **daily screen usage patterns**
- Identify how **screen time impacts CGPA**
- Compare **social media, gaming, and study hours**
- Build an **interactive Power BI dashboard**
- Extract meaningful **insights from the dataset**

---

## Repository Structure

Student-CGPA-vs-Screen-time

- Student_Performance_2026.csv # Dataset
- Analysis.ipynb # Python Analysis Notebook
- README.md # Project Documentation
- LICENSE # MIT License
- .gitattributes

---

##  Dataset Description

The dataset contains student behavioral and academic data.

| Column Name | Description |
|-------------|-------------|
| student_ID | Unique student identifier |
| Age | Age of student |
| Gender | Male / Female |
| daily_screen_time_hours | Total daily screen time |
| social_media_hours | Time spent on social media |
| gaming_hours | Time spent gaming |
| online_study_hours | Online study time |
| offline_study_hours | Offline study time |
| sleep_hours | Daily sleep duration |
| previous_sem_CGPA | Previous semester CGPA |

---

##  Data Cleaning

Data preprocessing was done using **Python and Pandas**.

Cleaning steps:

- Loaded dataset using Pandas
- Checked dataset structure
- Identified missing values
- Removed duplicate records
- Verified data types
- Validated cleaned dataset

Example code:

```python
import pandas as pd

df = pd.read_csv("Student_Performance_2026.csv")

# Check missing values
df.isnull().sum()

# Remove duplicates
df = df.drop_duplicates()

# Dataset information
df.info()
