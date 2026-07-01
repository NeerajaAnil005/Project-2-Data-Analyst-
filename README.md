# HR Analytics – Predict Employee Attrition

## Project Overview

Employee attrition is one of the major challenges faced by organizations. High attrition leads to increased recruitment costs, reduced productivity, and loss of experienced employees. This project uses data analytics and machine learning to identify the factors influencing employee attrition and predict whether an employee is likely to leave the organization.

The project includes Exploratory Data Analysis (EDA), predictive modeling using Logistic Regression (or Decision Tree), SHAP analysis for model explainability, and an interactive Power BI dashboard for visualization.

---

## Objective

* Analyze employee data to identify the major causes of attrition.
* Perform Exploratory Data Analysis (EDA).
* Build a machine learning classification model to predict employee attrition.
* Explain model predictions using SHAP values.
* Create an interactive Power BI dashboard for HR insights.
* Provide recommendations to reduce employee attrition.

---

## Dataset

**Dataset:** IBM HR Analytics Employee Attrition Dataset

The dataset contains employee information such as:

* Age
* Department
* Gender
* Job Role
* Monthly Income
* Marital Status
* OverTime
* Years at Company
* Years Since Last Promotion
* Job Satisfaction
* Work-Life Balance
* Attrition (Target Variable)

---

## Tools and Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SHAP
* Power BI Desktop

---

## Project Workflow

### 1. Data Collection

* Import the HR Analytics dataset.
* Load the data using Pandas.

### 2. Data Preprocessing

* Check for missing values.
* Encode categorical variables.
* Prepare the dataset for machine learning.

### 3. Exploratory Data Analysis (EDA)

Performed visual analysis on:

* Department-wise attrition
* Job Role vs Attrition
* Gender vs Attrition
* Monthly Income vs Attrition
* Overtime vs Attrition
* Promotion vs Attrition
* Age Distribution
* Correlation Heatmap

### 4. Machine Learning Model

* Split the dataset into training and testing sets (80:20).
* Train a Logistic Regression (or Decision Tree) model.
* Predict employee attrition.

### 5. Model Evaluation

Evaluate the model using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score

### 6. SHAP Analysis

* Explain model predictions.
* Identify the most influential features affecting employee attrition.

### 7. Power BI Dashboard

The dashboard includes:

* Total Employees
* Employees Left
* Average Age
* Average Monthly Income
* Department-wise Attrition
* Job Role Analysis
* Overtime Analysis
* Income Analysis
* Interactive slicers for Department, Gender, Job Role, and Marital Status

---

## Project Structure

```text
HR-Analytics-Employee-Attrition/
│
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── HR_Analytics.ipynb
├── HR_Cleaned.csv
├── HR_Attrition.pbix
├── Dashboard.pdf
├── Model_Report.pdf
├── Attrition_Prevention.pdf
├── README.md
└── screenshots/
```

---

## Results

The analysis helps identify important factors contributing to employee attrition, such as:

* Excessive overtime
* Lower monthly income
* Limited promotion opportunities
* Job role and department differences
* Years at the company
* Employee satisfaction and work-life balance

The machine learning model predicts employee attrition, while SHAP analysis explains which features most influence each prediction.

---

## Recommendations

* Improve promotion opportunities.
* Review compensation for lower salary bands.
* Reduce excessive overtime.
* Encourage a healthy work-life balance.
* Conduct regular employee engagement surveys.
* Offer learning and career development programs.
* Recognize employee achievements.
* Implement targeted retention strategies for high-risk groups.

---

## Future Enhancements

* Train advanced models such as Random Forest and XGBoost.
* Deploy the model as a web application using Streamlit or Flask.
* Connect the dashboard to a live HR database.
* Automate monthly attrition reporting.
* Include employee satisfaction survey data for improved prediction accuracy.

---

## Conclusion

This project demonstrates how data analytics, machine learning, and business intelligence can help organizations understand employee attrition, predict future resignations, and support data-driven HR decisions. The combination of Python, SHAP, and Power BI provides both predictive capability and actionable business insights.

---
