# 🧠 Diabetes Data Analysis Project

## 📋 Project Overview
This project focuses on analyzing a diabetes-related dataset to uncover insights about health risks and lifestyle factors contributing to diabetes.  
The analysis includes **data cleaning, exploration, and visualization** to identify major health patterns and risk contributors.

---

## 📂 Project Structure
```
DIABETES DATA ANALYSIS PROJECT/
│
├── data/
│ ├── raw/
│ │ └── diabetes_dataset.csv
│ └── cleaned/
│ └── diabetes_dataset_cleaned.csv
│
├── visualizations/
│ ├── univariate/
│ │ ├── age_distribution.png
│ │ ├── Blood Glucose Level Distribution.png
│ │ ├── BMI Distribution.png
│ │ ├── gender_distribution.png
│ │ ├── heart_disease_distribution.png
│ │ ├── hyper_tension_distribution.png
│ │ └── smoking_distribution.png
│ │
│ ├── bivariate/
│ │ ├── Age vs Diabetes.png
│ │ ├── BMI vs Diabetes.png
│ │ └── Hypertension vs Diabetes & Heart Disease.png
│ │
│ └── multivariate/
│ ├── Combined Effect Age, BMI, and BP on Diabetes.png
│ ├── Correlation Heatmap of Numerical Features.png
│ ├── Diabetes Count by Race.png
│ └── pair_plot.png
│
├── DA_Final_Project.ipynb
├── diabetes_dataset.csv
└── insights.md
└── README.md
```

---

## ⚙️ Steps in the Analysis

### 1. **Data Cleaning**
- Removed duplicates and missing values.  
- Standardized column names for consistency.  
- Exported the cleaned dataset to:
  ```
  data/cleaned/diabetes_dataset_cleaned.csv
  ```

### 2. **Exploratory Data Analysis (EDA)**
- Analyzed relationships between **BMI**, **Age**, and **Diabetes Risk**.  
- Visualized lifestyle factors such as **Physical Activity**, **Smoking**, and **Alcohol Consumption**.  
- Identified patterns of high-risk groups.

### 3. **Insights**
- Higher **BMI** and **lack of exercise** are strong predictors of diabetes.  
- **Smokers** and **alcohol consumers** show higher diabetes risk levels.  
- Preventive factors include **healthy diet** and **regular physical activity**.  
- Middle-aged and older individuals (40+) have a significantly higher chance of diabetes.

---

## 🧰 Tools & Libraries Used
- **Python 3.9+**
- **Pandas** — Data cleaning & manipulation  
- **Matplotlib / Seaborn** — Visualization  
- **NumPy** — Numerical operations  
- **Jupyter Notebook** — For analysis workflow  

