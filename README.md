# Diabetes Prediction Analysis

## Project Overview
This project analyzes a **Diabetes Prediction dataset** to identify the key factors contributing to diabetes. Using **Exploratory Data Analysis (EDA), feature engineering, and risk scoring**, the project uncovers patterns, distributions, and relationships between medical and lifestyle factors and diabetes incidence.  

The analysis aims to:
- Understand dataset structure and quality
- Explore individual features and their distributions
- Examine relationships between risk factors and diabetes
- Build a **risk score** to quantify diabetes probability

---

## Dataset Information
The dataset is sourced from [Kaggle: Diabetes Prediction Dataset](https://www.kaggle.com/datasets). It contains the following columns:

| Column | Type | Description |
|--------|------|------------|
| `gender` | Categorical | Male / Female / Other |
| `age` | Numerical | Age of the patient |
| `hypertension` | Binary | 0 = No, 1 = Yes |
| `heart_disease` | Binary | 0 = No, 1 = Yes |
| `smoking_history` | Categorical | never, former, current, etc. |
| `bmi` | Numerical | Body Mass Index |
| `HbA1c_level` | Numerical | Average blood sugar over 3 months |
| `blood_glucose_level` | Numerical | Current blood sugar level |
| `diabetes` | Binary | Target variable: 0 = No, 1 = Yes |

---

## Project Steps / EDA

### 1. Data Cleaning
- Checked for missing values and duplicates
- Handled missing values using appropriate strategies
- Converted categorical features to numerical formats for analysis

### 2. Univariate Analysis
- Count plots for categorical features (gender, smoking history, diabetes, heart disease)

### 3. Bivariate Analysis
- Examined relationships between:
  - Age vs Diabetes
  - BMI vs Diabetes
  - Heart Disease vs Diabetes
  - Smoking History vs Diabetes
- Used **boxplots, and scatterplots** for insights

### 4. Multivariate / Advanced Analysis
- Created a **Risk Score** based on age, BMI, HbA1c, blood glucose, and heart disease



