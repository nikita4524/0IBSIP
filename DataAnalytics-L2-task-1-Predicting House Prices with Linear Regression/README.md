# House Price Prediction with Linear Regression

##  Objective
Build and evaluate a linear regression model that predicts house prices based on features such as area, number of rooms, amenities, and furnishing status.  
This project demonstrates end-to-end skills: data cleaning, feature engineering, model training, evaluation, and interpretation.

---

## Dataset
- **Source:** [Housing Price Prediction – Kaggle](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)  
- **File:** `Housing.csv`  
- **Features:**
  - `Price` (target variable)
  - `Area`, `Bedrooms`, `Bathrooms`, `Stories`, `Parking`
  - `Mainroad`, `Guestroom`, `Basement`, `Hot water heating`, `Airconditioning`, `Prefarea`, `Furnishing status`

---

## Tech Stack
- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  
- Jupyter Notebook  

---

##  Workflow Checklist
- [x] Load dataset and perform EDA (null check, descriptive stats, target distribution)  
- [x] Feature selection discussion (markdown cell)  
- [x] Handle missing values and encode categorical features (One-Hot Encoding)  
- [x] Correlation heatmap  
- [x] Train/test split (80/20)  
- [x] Train Linear Regression model  
- [x] Evaluate with MSE, RMSE, R²  
- [x] Scatter plot (actual vs predicted)  
- [x] Residual plot (random distribution check)  
- [x] Coefficient analysis (feature impact)  
- [x] (Bonus) Compare Ridge & Lasso models  

---

## Results
 MSE: 1754318687330.6643
RMSE: 1324506.9600914388
R² Score: 0.6529242642153184 

###  Key Insights
1. **Area** and **furnishing status** are the strongest predictors of price.  
2. Amenities like **parking, air conditioning, preferred area** significantly increase value.  
3. Ridge/Lasso regularization improves model stability and reduces overfitting.  

---

##  Visuals
- Distribution of house prices  
- Correlation heatmap  
- Actual vs Predicted scatter plot  
- Residual plot  

---

##  Conclusion
This project shows how linear regression can be applied to real estate pricing.  
Future improvements could include:
- Feature scaling and polynomial regression  
- Cross-validation for more robust evaluation  
- Ensemble models (Random Forest, Gradient Boosting) for comparison  

---
