# Diabetes-EDA-And-Hypothesis-Testing.
# 🩺 Diabetes Prediction & Statistical Analysis using Python

This project explores a real-world healthcare dataset to analyze and understand key indicators related to **diabetes diagnosis**. We perform **exploratory data analysis (EDA)**, **statistical hypothesis testing**, and **visualization** using Python libraries.

> 🔍 This analysis helps identify how health metrics like **BMI, HbA1c, glucose levels, age, and smoking history** relate to diabetes status.

---

## 📂 Dataset

- **Source:** [Kaggle - Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)
- **Features:**
  - `age`
  - `gender`
  - `bmi`
  - `hypertension`
  - `heart_disease`
  - `smoking_history`
  - `HbA1c_level`
  - `blood_glucose_level`
  - `diabetes` (Target: 1 = Positive, 0 = Negative)

---

## 📊 Project Workflow

### 1. **Data Loading & Cleaning**
- Load CSV using Pandas
- View structure: `.head()`, `.info()`, `.describe()`
- Handle missing values (drop or impute)

### 2. **Exploratory Data Analysis (EDA)**
- Mean values for key indicators
- Correlation matrix
- Group-wise comparisons based on diabetes status

### 3. **Data Visualization** (with Seaborn/Matplotlib)
- Histogram of BMI
- Boxplot of Glucose vs Diabetes
- Regression plot: HbA1c vs Glucose
- Correlation heatmap

### 4. **Hypothesis Testing**
#### 🔹 One-sample Z-Test (BMI)
> H0: Population mean BMI = 25  
> ✅ Result: Significant / Not Significant?

#### 🔹 Two-sample T-Test (Age vs Diabetes)
> H0: Mean age is equal in both diabetic and non-diabetic groups  
> ✅ Result: Significant / Not Significant?

#### 🔹 Chi-Square Test (Smoking History vs Diabetes)
> H0: Smoking history and diabetes status are independent  
> ✅ Result: Associated / Not Associated?

---

## 🛠️ Tools & Libraries

- Python 3
- Pandas
- NumPy
- Seaborn
- Matplotlib
- SciPy
- Statsmodels

---

## 📌 Key Insights

- BMI, HbA1c, and blood glucose are significantly higher in diabetic individuals.
- Age is a strong differentiator between diabetic and non-diabetic groups.
- Smoking history shows a statistically significant relationship with diabetes presence.

---


