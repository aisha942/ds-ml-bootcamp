# Analysis of Student Study Habits and Academic Performance

## Introduction

Educational success is influenced by behavioral and lifestyle factors such as study time, sleep quality, attendance, and screen usage. Understanding how these habits relate to academic performance helps educators design better learning strategies and helps students improve outcomes.

This project presents a dataset collected through a real-world survey of students. The goal is to analyze patterns in student behavior and predict exam performance using machine learning techniques. The dataset intentionally contains small inconsistencies to reflect realistic data collection conditions, which is common in applied data science.

This study demonstrates the complete data science pipeline:

- Data collection
- Dataset description
- Quality assessment
- Exploratory analysis
- Machine learning modeling
- Interpretation of results

---

## Title & Collection Method

**Title:**  
Student Study Habits Dataset for Academic Performance Prediction

**Collection Method:**

A questionnaire was distributed to 52 students. Participants reported their daily study habits, sleep duration, screen time, attendance, and final exam score. Data was recorded manually into a spreadsheet.

The dataset reflects real-world imperfections such as:

- Missing values
- Self-reported estimates
- Rounding errors
- Inconsistent reporting

These imperfections are intentional and represent realistic data science challenges.

---

## Dataset Structure

- Total rows: **52 students**
- Total columns: **7 variables**
- Features (X): 6
- Label (y): 1 (Exam Score)

---

## Features & Label Description

| Variable | Description |
|---------|-------------|
| Age | Age of student (years) |
| Study_Hours | Average daily study time |
| Sleep_Hours | Average daily sleep time |
| Screen_Time | Daily device usage |
| Attendance | Attendance percentage |
| Gender | Categorical (M/F) |
| Exam_Score | Final exam score (label) |

---

## Sample Dataset Table

| Age | Study_Hours | Sleep_Hours | Screen_Time | Attendance | Gender | Exam_Score |
|-----|-------------|-------------|-------------|------------|--------|------------|
| 18 | 3 | 7 | 4 | 90 | F | 78 |
| 19 | 5 | 6 | 3 | 95 | M | 88 |
| 18 | 2 | 8 | 6 | 80 | F | 65 |
| 20 | 4 | 7 | 5 | 92 | M | 82 |
| 19 | 6 | 6 | 2 | 97 | F | 91 |

---


## Quality Issues

Because the dataset was collected manually, several real-world data issues exist:

- Self-reported values may contain bias
- Some rounding and estimation errors
- Slight imbalance in gender distribution
- Possible noise in behavior reporting
- Correlation overlap between variables

These issues require preprocessing before applying machine learning.

---


## Results Interpretation

The regression model suggests strong relationships between:

- Study hours
- Attendance
- Screen time

and exam performance.

Higher study time and attendance positively influence exam success, while excessive screen time shows a negative correlation.

---

## Use Case

This dataset can support:

- Academic performance prediction
- Student risk detection
- Personalized study planning
- Educational analytics systems





