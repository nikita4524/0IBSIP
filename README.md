# OIBSIP – Data Analytics Internship Projects

## 📌 Overview
This repository contains all tasks completed during the Oasis Infobyte Internship Program (OIBSIP) in Data Analytics.  
The projects demonstrate practical data analysis, cleaning, clustering, and machine learning techniques using Python and popular libraries.  
Together, they showcase end‑to‑end workflows: **EDA, clustering, professional data cleaning, regression, classification, and fraud detection**.

---

## ⚙️ Tech Stack
- Python  
- pandas, numpy  
- scikit-learn  
- imbalanced-learn (SMOTE)  
- matplotlib, seaborn  
- Jupyter Notebook  

---

## 📂 Tasks

### 🛒 Task 1 – Retail Sales Data Analysis (EDA)
- **Objective:** Perform exploratory data analysis on retail sales data to uncover customer demographics, product categories, and sales trends.  
- **Workflow Highlights:** Handle missing values, generate descriptive statistics, visualise trends, identify top customers and categories.  
- **Deliverables:** `Task1_EDA.ipynb`, dataset, README.md.  
- **Key Outputs:** Customer demographics charts, product category analysis, sales trend visualisations.

---

### 👥 Task 2 – Customer Segmentation Analysis
- **Objective:** Apply clustering (KMeans) to segment customers into groups using RFM (Recency, Frequency, Monetary) analysis.  
- **Workflow Highlights:** Build RFM features, standardise data, apply KMeans with Elbow Method, visualise clusters, profile segments.  
- **Deliverables:** `Task2_CustomerSegmentation.ipynb`, dataset, README.md.  
- **Key Outputs:** Elbow plot, scatter plots, cluster profile table, marketing insights.

---

### 🧹 Task 3 – Data Cleaning (Titanic Dataset)
- **Objective:** Demonstrate professional-level data cleaning by transforming a messy dataset into analysis-ready form.  
- **Workflow Highlights:** Data quality report, handle missing values, remove duplicates, standardise formats, detect/treat outliers, correct data types.  
- **Deliverables:** `Task3_DataCleaning.ipynb`, cleaned dataset, README.md.  
- **Key Outputs:** Missing value heatmap, outlier detection, before vs after summary table.

---

### 🏠 Task 4 – House Prices Prediction
- **Objective:** Predict house prices using regression models.  
- **Workflow Highlights:** Clean dataset, EDA, train/test split, train Linear Regression, Decision Tree, Random Forest, evaluate with RMSE & R².  
- **Deliverables:** `Task4_HousePrices.ipynb`, README.md.  
- **Key Outputs:** Random Forest achieved best R²; Area & Location strongest predictors.

---

### 🍷 Task 5 – Wine Quality Prediction
- **Objective:** Classify wine quality scores (3–8) using classification models.  
- **Workflow Highlights:** Load dataset with `sep=";"`, EDA, handle imbalance, feature engineering, train Random Forest, SGD, SVC, evaluate with accuracy & confusion matrix.  
- **Deliverables:** `Task5_WineQuality.ipynb`, README.md.  
- **Key Outputs:** Random Forest achieved highest accuracy; Alcohol, Volatile acidity, Sulphates key predictors.

---

### 💳 Task 6 – Fraud Detection
- **Objective:** Detect fraudulent transactions from a heavily imbalanced dataset, prioritising recall.  
- **Workflow Highlights:** Analyse imbalance, EDA (amounts, time-of-day), explain accuracy pitfalls, apply SMOTE + class_weight, train Logistic Regression & Random Forest, evaluate with Precision, Recall, F1, ROC-AUC, feature importance, scalability discussion.  
- **Deliverables:** `Task6_FraudDetection.ipynb`, README.md.  
- **Key Outputs:** Fraud <1%; Random Forest achieved higher recall & ROC-AUC; Logistic Regression lightweight & scalable.

---

## 🏁 Conclusion
- **EDA & Cleaning:** Retail Sales and Titanic tasks show strong data wrangling skills.  
- **Clustering:** Customer Segmentation demonstrates unsupervised learning with RFM features.  
- **Regression & Classification:** House Prices and Wine Quality tasks highlight supervised ML workflows.  
- **Fraud Detection:** Tackles extreme imbalance with SMOTE, focusing on recall for real-world deployment.  

Together, these tasks demonstrate practical data analytics, machine learning, and professional documentation skills.
