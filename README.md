# ❤️ Heart Disease Analysis – using Python

---

## 📌 Project Overview

Heart Disease is one of the leading causes of death globally.  
This project performs Exploratory Data Analysis (EDA) on a structured healthcare dataset to identify patterns, correlations, and major risk factors associated with heart disease.

The goal is to derive meaningful insights from patient medical records and understand which attributes contribute most to heart disease.

---

## 🎯 Project Objective

- Analyze patient health data to identify risk indicators
- Understand the relationship between medical attributes and heart disease
- Generate business/health insights from the dataset
- Prepare the dataset for predictive modeling in the future

---

## 🏢 Business Problem Statement

Healthcare institutions need data-driven insights to:

- Identify high-risk patients early
- Improve preventive healthcare strategies
- Support clinical decision-making
- Reduce cardiovascular-related mortality rates

By analyzing historical patient data, we can uncover trends that assist in risk-based patient segmentation.

---

## 📊 Dataset Information

- **Total Rows:** 1025  
- **Total Columns:** 14  
- **Dataset Type:** Structured Healthcare Dataset  
- **Target Variable:** `target`  
  - `0` → No Heart Disease  
  - `1` → Heart Disease  

### 📁 Feature Description

| Feature     | Description |
|-------------|-------------|
| age         | Age of the patient |
| sex         | Gender (0 = Female, 1 = Male) |
| cp          | Chest pain type (4 categories) |
| trestbps    | Resting blood pressure |
| chol        | Serum cholesterol |
| fbs         | Fasting blood sugar |
| restecg     | Resting ECG results |
| thalach     | Maximum heart rate achieved |
| exang       | Exercise induced angina |
| oldpeak     | ST depression |
| slope       | Slope of peak exercise ST segment |
| ca          | Number of major vessels |
| thal        | Thalassemia |
| target      | Heart disease presence |

---

## 🔄 Project Workflow

### 1️⃣ Importing Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn

### 2️⃣ Data Gathering
- Loaded dataset using `pd.read_csv()`

### 3️⃣ Data Understanding
- Displayed top 5 rows (`head()`)
- Displayed last 5 rows (`tail()`)
- Checked dataset shape
- Checked data types
- Used `.info()` and `.describe()` for statistical summary

### 4️⃣ Data Cleaning
- Checked for null values → No missing values found
- Checked for duplicate records,found duplicate values and removed them
- Verified dataset integrity

### 5️⃣ Exploratory Data Analysis (EDA)

Performed the following analyses:

- Heart disease distribution
- Gender distribution
- Gender vs Heart Disease comparison
- Age distribution analysis
- Chest pain type distribution
- Chest pain vs target analysis
- Fasting blood sugar vs target analysis
- Resting blood pressure comparison (Gender-wise)
- Correlation matrix visualization

---

## 📈 Key Business Insights

### 🔹 Heart Disease Distribution
- 164 patients have heart disease
- 138 patients do not have heart disease
- Dataset is relatively balanced

### 🔹 Gender Insights
- Males have higher representation in the dataset
- Heart disease occurrence is higher among males compared to females

### 🔹 Age Factor
- Majority of patients fall between 40–60 years
- Higher heart disease cases observed in middle-aged individuals

### 🔹 Chest Pain Type
- Asymptomatic chest pain shows strong association with heart disease
- Chest pain type is one of the strongest indicators

### 🔹 Correlation Insights
- `cp` (Chest Pain Type) shows strong positive correlation with target
- `thalach` (Max Heart Rate) shows negative correlation with heart disease
- `oldpeak` shows positive association with heart disease

---

## 🛠 Tools & Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Business Outcomes

This analysis helps:

- Identify high-risk demographic groups
- Understand critical medical indicators
- Support preventive healthcare strategies
- Prepare dataset for machine learning modeling

---

## 🧠 Conclusion

The EDA reveals that demographic factors (age, gender) and clinical attributes (chest pain type, max heart rate, oldpeak) play a significant role in identifying heart disease.

---

## 👩‍💻 Author

**Nandini Kumari**  
Data Analyst  
Skilled in Python, SQL, Power BI

---
