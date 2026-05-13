# Employee Turnover Prediction using XGBoost

## Project Overview

Employee turnover is one of the major challenges faced by organizations because it affects productivity, hiring costs, and overall business performance.

This project uses Machine Learning and Data Analysis techniques to predict whether an employee is likely to leave the company based on factors such as satisfaction level, workload, promotions, salary, and working hours.

The project was built using Python, Exploratory Data Analysis (EDA), and XGBoost Classification to generate actionable HR insights.

---

# Business Problem

The HR department wants to identify:
- Why employees leave the company
- Which employees are at high risk of attrition
- The major factors affecting employee retention

The goal is to help organizations make data-driven HR decisions and improve employee satisfaction.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

# Project Workflow

## 1. Data Collection
- Imported employee dataset containing HR-related information.

## 2. Data Cleaning
- Checked missing values
- Removed inconsistencies
- Converted categorical variables into numerical format

## 3. Exploratory Data Analysis (EDA)
Performed visualization and analysis on:
- Employee satisfaction
- Monthly working hours
- Salary levels
- Promotion history
- Number of projects

## 4. Feature Engineering
- Prepared features for machine learning models
- Split dataset into training and testing sets

## 5. Machine Learning Model
Implemented:
- XGBoost Classifier

## 6. Model Evaluation
Evaluated model performance using:
- Accuracy Score
- Classification Report
- Confusion Matrix

---

# Key Insights

- Employees with low satisfaction levels were more likely to leave.
- Excessive workload increased attrition risk.
- Employees with low salaries had higher turnover rates.
- Lack of promotions contributed to employee dissatisfaction.
- Work-life balance strongly impacted retention.

---

# Business Recommendations

- Improve employee work-life balance
- Conduct regular employee satisfaction surveys
- Reduce excessive workloads
- Provide career growth opportunities
- Improve compensation strategies

---

# Results

The XGBoost model successfully identified important factors contributing to employee attrition and provided meaningful HR insights for decision-making.

---

# Project Structure

```bash
Employee-Turnover-Prediction/
│
├── data/
├── notebooks/
├── images/
├── Employee_Turnover_XGBoost_Professional.ipynb
├── README.md
└── requirements.txt
```
