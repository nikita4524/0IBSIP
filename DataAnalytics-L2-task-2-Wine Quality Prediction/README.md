# Wine Quality Prediction

## Objective
Train and compare multiple classification models to predict wine quality scores (scale 3–8) based on physicochemical properties such as acidity, density, and alcohol content.  
This project demonstrates end-to-end skills: data exploration, handling class imbalance, feature engineering, model training, evaluation, and comparison.

---

## Dataset
  
- **Kaggle Mirror:** [Red Wine Quality Dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)  
- **Files:**
  - `winequality-red.csv` → 1,599 samples  
  -   
- **Features (11 physicochemical properties):**
  - Fixed acidity  
  - Volatile acidity  
  - Citric acid  
  - Residual sugar  
  - Chlorides  
  - Free sulfur dioxide  
  - Total sulfur dioxide  
  - Density  
  - pH  
  - Sulphates  
  - Alcohol  
- **Target:** `quality` (integer score 3–8)

---

##  Tech Stack
- Python  
- pandas, numpy  
- scikit-learn (RandomForestClassifier, SGDClassifier, SVC)  
- matplotlib, seaborn  
- Jupyter Notebook  

---

## Workflow Checklist
- [x] Load dataset and inspect structure; check class distribution of quality scores  
- [x] EDA: distribution plots for all chemical features; correlation heatmap  
- [x] Discuss class imbalance (markdown cell)  
- [x] Feature engineering: binary (good/bad) or 3-class grouping  
- [x] Train/test split with stratification  
- [x] Train 3 classifiers: Random Forest, SGD, SVC  
- [x] Evaluate each: accuracy, classification report, confusion matrix  
- [x] Feature importance chart (Random Forest)  
- [x] Comparison table of all models  
- [x] Conclusion: most suitable model for deployment  

---



### Key Insights
1. Quality scores are imbalanced (most wines rated 5–6).  
2. Alcohol, volatile acidity, and sulphates are strong predictors of wine quality.  
3. Random Forest outperforms SGD and SVC in accuracy and interpretability.  

---

## Visuals
- Distribution plots of features  
- Correlation heatmap  
- Confusion matrices  
- Random Forest feature importance chart  

---

##  Conclusion
Random Forest is the most suitable model for deployment due to its balance of accuracy, robustness, and interpretability.  
Future improvements could include:
- Hyperparameter tuning (GridSearchCV)  
- Resampling techniques (SMOTE) to address class imbalance  
- Testing ensemble methods (Gradient Boosting, XGBoost)  

---
