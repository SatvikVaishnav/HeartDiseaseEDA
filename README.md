# 🫀 Heart Disease Dataset - Exploratory Data Analysis (EDA)

This project provides an in-depth **Exploratory Data Analysis (EDA)** on the Heart Disease dataset. The goal is to understand the distribution of features, handle missing data, detect outliers, and identify relationships between key health indicators and the presence of heart disease.

---

## 📊 Dataset Overview

The dataset contains **clinical records** of patients, with attributes such as:

- **Age**
- **Sex**
- **Resting Blood Pressure**
- **Cholesterol**
- **Chest Pain Type**
- **Maximum Heart Rate Achieved**
- **Exercise-Induced Angina**
- **ST Depression (Oldpeak)**
- **Slope of ST Segment (ST_Slope)**
- **Fasting Blood Sugar**
- **Resting ECG Results**
- **Target Variable**: `HeartDisease` (0 = No, 1 = Yes)

Dataset Source: *Available on Kaggle / UCI Repository*

---

## 📌 Key Objectives

- Explore feature distributions using histograms and count plots.
- Detect and handle **missing values** using **Iterative Imputer**.
- Perform **univariate**, **bivariate**, and **multivariate** analysis.
- Generate insights using **box plots**, **heatmaps**, and **pairplots**.
- Create new features via **binning** (e.g., Age Groups, BMI Categories).

---

## 🧪 Steps Performed

1. **Data Loading & Inspection**  
2. **Missing Value Handling** (Iterative Imputer, Mode Imputation)  
3. **Data Visualization**  
   - Histograms & Count Plots  
   - Heatmap of Feature Correlations  
   - Pairplot of Key Features  
4. **Feature Engineering**  
   - Age Grouping  
   - BMI Classification  
5. **Multivariate Analysis**

---

## 📈 Visual Insights

- Chest pain type and ST segment slope are strong indicators of heart disease.
- Age group and cholesterol also influence the presence of heart disease.
- Pairplots and heatmaps reveal underlying relationships.

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

<pre> ## 📁 Project Structure ``` 📦 HeartDisease-EDA ┣ 📊 heart_disease_eda.ipynb ┣ 📄 README.md ┗ 📂 dataset/ ``` </pre>
---

## 💡 Conclusion

This EDA helps identify major risk factors and patterns in the heart disease dataset, setting a strong foundation for building predictive models.

---

## 📌 Future Work

- Train machine learning models (e.g., Logistic Regression, Random Forest)
- Evaluate model performance (Accuracy, ROC, Precision-Recall)
- Use feature selection and scaling techniques

---

## 📬 Contact

**Satvik Vaishnav**  
📧 vaishnavsatvik2@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/satvik-vaishnav-462822266)  
🔗 [GitHub](https://github.com/SatvikVaishnav)
