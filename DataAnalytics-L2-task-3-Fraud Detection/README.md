# Fraud Detection

##  Objective
Build a machine learning pipeline to detect fraudulent financial transactions from a heavily imbalanced dataset.  
The core challenge is handling class imbalance effectively while ensuring the model prioritizes recall (catching fraud) over accuracy.

---

##  Dataset
- **Source:** Custom Fraud Dataset (10 features, target = `is_fraud`)  
- **Features:**
  - transaction_id  
  - amount  
  - transaction_hour  
  - merchant_category  
  - foreign_transaction  
  - location_mismatch  
  - device_trust_score  
  - velocity_last_24h  
  - cardholder_age  
- **Target:** `is_fraud` (0 = legitimate, 1 = fraud)

---

##  Tech Stack
- Python  
- pandas, numpy  
- scikit-learn (Logistic Regression, Random Forest)  
- imbalanced-learn (SMOTE)  
- matplotlib, seaborn  
- Jupyter Notebook  

---

## Workflow Checklist
- [x] Load dataset and analyse class imbalance (fraud % vs non-fraud)  
- [x] EDA: transaction amount distribution; fraud vs non-fraud by time of day  
- [x] Markdown: explain why accuracy is misleading for imbalanced datasets  
- [x] Handle imbalance: SMOTE oversampling + class_weight='balanced'  
- [x] Train/test split with stratification  
- [x] Train Logistic Regression + Random Forest  
- [x] Evaluate using Precision, Recall, F1, ROC-AUC (not just accuracy)  
- [x] Explain Recall vs Precision trade-off for fraud detection  
- [x] Feature importance analysis (coefficients / Random Forest importances)  
- [x] Scalability discussion: handling millions of transactions/hour  

---



###  Key Insights
1. Fraud cases are <1% of transactions → extreme imbalance.  
2. Accuracy is misleading; Recall and ROC-AUC are better indicators.  
3. Random Forest captures non-linear patterns and achieves higher recall.  
4. Logistic Regression is lightweight and scalable for real-time detection.  

---

## Visuals
- Fraud vs Non-Fraud distribution  
- Transaction amount boxplot  
- Fraud by hour histogram  
- ROC curves for both models  
- Random Forest feature importance chart  

---

##  Conclusion
- **Recall matters most**: catching fraud is more important than avoiding false alarms.  
- Random Forest is best for accuracy and interpretability.  
- Logistic Regression is ideal for scalability in high-throughput systems.  
- For deployment at scale (e.g., 1M transactions/hour), integrate with streaming frameworks like Apache Kafka or Spark Streaming.  

---
