🫀 Heart Disease Dataset - Exploratory Data Analysis (EDA)
This project provides an in-depth Exploratory Data Analysis (EDA) on the Heart Disease dataset. The goal is to understand the distribution of features, handle missing data, detect outliers, and identify relationships between key health indicators and the presence of heart disease.

📊 Dataset Overview
The dataset contains clinical records of patients, with attributes such as:

Age

Sex

Resting Blood Pressure

Cholesterol

Chest Pain Type

Maximum Heart Rate Achieved

Exercise-Induced Angina

ST Depression (Oldpeak)

Slope of ST Segment (ST_Slope)

Fasting Blood Sugar

Resting ECG Results

Target Variable: HeartDisease (0 = No, 1 = Yes)

Dataset Source: [Available on Kaggle / UCI Repository]

📌 Key Objectives
Explore feature distributions using histograms and count plots.

Detect and handle missing values using Iterative Imputer.

Perform univariate, bivariate, and multivariate analysis.

Generate insights using box plots, heatmaps, and pairplots.

Create new features via binning (e.g., Age Groups, BMI Categories).

🧪 Steps Performed
Data Loading & Inspection
Loaded the dataset, inspected data types, shape, and missing values.

Missing Value Handling
Used IterativeImputer with RandomForestRegressor to fill missing numerical values, and mode for categorical values.

Data Visualization

Histograms for numerical feature distributions

Count plots for categorical variables

Correlation heatmap

Pairplots of key features

Multivariate analysis (e.g., Chest Pain Type vs ST Slope vs Heart Disease)

Feature Engineering

Binning Age into categories: Young, Adult, Middle-aged, Senior

BMI classification: Underweight, Normal, Overweight, Obese (if applicable)

📈 Visual Insights
Chest pain type and ST segment slope are strong indicators of heart disease.

Certain age groups and cholesterol levels show higher heart disease prevalence.

Correlation heatmap helps identify relationships between numeric features.

🛠️ Tools & Libraries Used
Python 🐍

Pandas & NumPy

Seaborn & Matplotlib

Scikit-learn (for imputation)

📁 Project Structure
bash
Copy
Edit
📦 HeartDisease-EDA
 ┣ 📊 heart_disease_eda.ipynb      # Jupyter notebook with full analysis
 ┣ 📄 README.md                    # Project summary and explanation
 ┗ 📂 dataset                     # (Optional) Place your dataset here
💡 Conclusion
This EDA helps in uncovering critical patterns that may influence the likelihood of heart disease. These insights can support predictive modeling and healthcare decision-making.

📌 Future Work
Apply classification models (e.g., Logistic Regression, Random Forest)

Evaluate model performance using ROC-AUC, Precision-Recall

Feature selection and dimensionality reduction

📬 Contact
Satvik Vaishnav
📧 vaishnavsatvik2@gmail.com
🔗 LinkedIn | GitHub

