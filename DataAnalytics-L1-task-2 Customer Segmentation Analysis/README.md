# Task 2 – Customer Segmentation Analysis

## Objective
Apply clustering algorithms to segment an e-commerce company's customer base into distinct groups based on purchasing behaviour. The goal is to enable targeted marketing strategies by identifying customer segments using RFM (Recency, Frequency, Monetary) analysis.

## Dataset
- **File:** `retail_sales_dataset.csv`
- **Columns:**
  - Transaction ID
  - Date
  - Customer ID
  - Gender
  - Age
  - Product Category
  - Quantity
  - Price per Unit
  - Total Amount
- **Source:** Self-provided dataset for internship task

## Tech Stack
Python, pandas, numpy, scikit-learn (KMeans), matplotlib, seaborn, Jupyter Notebook

## Workflow
1. Load dataset and inspect structure; handle missing values and inconsistent data
2. Generate descriptive statistics: average purchase value, purchase frequency, customer lifetime value
3. Feature selection: build RFM features (Recency, Frequency, Monetary)
4. Normalise/standardise data using `StandardScaler`
5. Apply K-Means clustering; use Elbow Method to determine optimal number of clusters (K)
6. Visualise clusters using scatter plots (Recency vs Monetary, Frequency vs Monetary)
7. Profile each cluster: calculate mean feature values per cluster and describe customer type
8. Bar chart: number of customers per cluster
9. Insights: recommend marketing actions for each segment

## Outputs
- Elbow plot (optimal K)
- Scatter plots of clusters
- Bar chart of customers per cluster
- Cluster profile table

## Insights
- **Cluster 0 (High Frequency, High Monetary):** VIP customers → Offer loyalty rewards, exclusive deals
- **Cluster 1 (Low Recency, High Monetary):** Dormant big spenders → Send re-engagement campaigns
- **Cluster 2 (High Recency, Low Frequency):** New customers → Welcome offers, onboarding emails
- **Cluster 3 (Low Monetary, Low Frequency):** Bargain shoppers → Promote discounts, bundle deals

## Deliverables
- Notebook (`Task2_CustomerSegmentation.ipynb`)
- Dataset (`retail_sales_dataset.csv`)
- README.md (this file)
