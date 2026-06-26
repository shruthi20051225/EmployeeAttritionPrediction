# Employee Attrition Prediction using Machine Learning

## 📌 Project Overview

Employee attrition is a major challenge for organizations, leading to increased recruitment costs, training expenses, and reduced productivity. This project uses Machine Learning to predict whether an employee is likely to leave the company based on various HR-related factors.

The project analyzes employee information such as salary, job role, work-life balance, years at the company, job satisfaction, and other workplace attributes to identify patterns associated with employee turnover.

---

## 🎯 Objectives

- Analyze employee attrition patterns.
- Clean and preprocess HR data.
- Perform Exploratory Data Analysis (EDA).
- Build and compare multiple Machine Learning classification models.
- Identify the key factors influencing employee attrition.
- Provide business recommendations for HR teams.

---

## 📂 Dataset

**Dataset:** IBM HR Analytics Employee Attrition Dataset

- Total Records: **1,470**
- Target Variable: **Attrition (Yes/No)**

Dataset Source:
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

---

## 📊 Project Workflow

### Task 1 – Data Loading & Exploration
- Loaded the dataset
- Explored dataset structure
- Checked missing values
- Calculated employee attrition rate
- Identified numerical and categorical features

### Task 2 – Data Cleaning & Preprocessing
- Removed unnecessary columns
- Converted Attrition (Yes/No) into numerical values
- Applied One-Hot Encoding
- Standardized numerical features using StandardScaler

### Task 3 – Exploratory Data Analysis
- Attrition by Department
- Attrition by Job Role
- Monthly Income vs Attrition
- Work-Life Balance vs Attrition
- Years at Company vs Attrition

### Task 4 – Model Building
Three classification models were trained:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

### Task 5 – Model Evaluation

Models were evaluated using:

- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

### Task 6 – Visualizations

The project includes:

- Attrition Rate by Department
- Attrition Rate by Job Role
- Monthly Income vs Attrition
- Work-Life Balance vs Attrition
- Years at Company vs Attrition
- Confusion Matrix
- Feature Importance
- ROC Curve Comparison

---

## 📈 Key Findings

- Employees with lower salaries were more likely to leave the organization.
- Poor work-life balance was associated with higher attrition.
- Employees with fewer years at the company showed higher turnover.
- Certain departments and job roles experienced higher attrition rates.
- Employee attrition is influenced by multiple workplace factors rather than salary alone.

---

## 💡 Business Recommendations

- Focus retention programs on new employees during their first few years.
- Improve work-life balance through flexible work policies.
- Monitor departments and job roles with higher turnover.
- Provide career growth opportunities and regular employee engagement initiatives.

---

## 📁 Project Structure

```
EmployeeAttritionPrediction/
│
├── analysis.ipynb
├── README.md
├── summary.docx
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
└── charts/
    ├── attrition_department.png
    ├── attrition_jobrole.png
    ├── income_vs_attrition.png
    ├── worklife_vs_attrition.png
    ├── years_company_attrition.png
    ├── confusion_matrix.png
    ├── feature_importance.png
    └── roc_curve.png
```

---

## 🚀 Future Improvements

- Apply advanced techniques for handling class imbalance (e.g., SMOTE).
- Perform hyperparameter tuning to improve model performance.
- Deploy the model as a web application using Streamlit or Flask.
- Integrate real-time HR data for continuous attrition monitoring.

---

## 👩‍💻 Author

**Shruthi Meena R**

GitHub: https://github.com/shruthi20051225
