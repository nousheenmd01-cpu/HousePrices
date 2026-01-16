# Task 2: Data Cleaning & Missing Value Handling

## Internship
AI & ML Internship

---

## Objective
The objective of this task is to perform data cleaning by identifying and handling missing values to improve data quality and prepare the dataset for machine learning modeling.

---

## Dataset
**House Prices – Advanced Regression Techniques**  
Source: Kaggle  
File used: `train.csv`

---

## Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  

---

## Steps Performed

### 1. Load Dataset & Identify Missing Values
- Loaded the dataset using Pandas
- Identified missing values using `.isnull().sum()`

### 2. Visualize Missing Data
- Plotted a bar chart to visualize missing values across columns

### 3. Handle Numerical Missing Values
- Identified numerical columns (`int64`, `float64`)
- Applied **median imputation** to handle missing values and reduce outlier impact

### 4. Handle Categorical Missing Values
- Identified categorical (`object`) columns
- Applied **mode imputation** for missing categorical data

### 5. Remove Columns with High Missing Values
- Removed columns having more than **50% missing data**

### 6. Validate Cleaned Dataset
- Verified no missing values remain
- Checked dataset structure using `.info()`

### 7. Compare Before vs After
- Confirmed dataset size and quality after cleaning
- Final dataset shape: **1460 rows × 81 columns**

---

## Final Output
- Cleaned dataset saved as `cleaned_house_prices.csv`
- Dataset is now free of missing values and ready for ML modeling

---

## Conclusion
The dataset was successfully cleaned by applying appropriate missing value handling techniques. Data quality was improved without unnecessary data loss, making the dataset suitable for further analysis and machine learning tasks.

---

