 #Student Performance Prediction using Logistic Regression

This project is part of my internship work, where I implemented a **Logistic Regression model** to predict whether a student will **pass or fail** based on their academic performance data.

---

## Project Overview

The goal of this project is to analyze student performance data and build a machine learning model that can **classify students as Pass (1) or Fail (0)**.  
The model uses numerical features such as study hours, attendance, assignment scores, etc., to make predictions.

---

## Dataset

- **File:** `student_performance.csv`  
- **Description:** Contains student performance metrics and a target column named `Pass` indicating the final result (1 = Pass, 0 = Fail).  
- **Example Columns:**
  - `StudyHours`
  - `Attendance`
  - `AssignmentScore`
  - `Participation`
  - `Pass` (target)

---

## Model and Workflow

1. **Import Libraries:** pandas, scikit-learn  
2. **Load Dataset:** Read CSV file and explore data structure  
3. **Preprocessing:** Split data into features (`X`) and target (`y`)  
4. **Train-Test Split:** 80% training and 20% testing data  
5. **Model Training:** Logistic Regression  
6. **Evaluation:** Accuracy, confusion matrix, and classification report  
7. **Prediction:** Predict pass/fail for a new student input

