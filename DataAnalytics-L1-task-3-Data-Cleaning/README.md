# Task 3 – Data Cleaning (Titanic Dataset)

## Objective
Perform professional-level data cleaning on the Titanic dataset to prepare it for analysis and machine learning. The goal is to handle missing values, remove duplicates, standardise categorical variables, detect outliers, and correct data types.

## Dataset
- **File:** `titanic_cleaned_dataset.csv`
- **Columns:**
  - Unnamed: 0 (index column)
  - PassengerId
  - Survived
  - Pclass
  - Name
  - Sex
  - Age
  - Siblings
  - Parents
  - Fare
  - Embarked
- **Source:** [Cleaned Titanic Dataset – Kaggle](https://www.kaggle.com/datasets/almusheer/cleaned-titanic-dataset)

## Tech Stack
Python, pandas, numpy, matplotlib, seaborn, Jupyter Notebook

## Workflow
1. Load dataset and inspect structure
2. Generate data quality report (nulls, duplicates, dtypes)
3. Handle missing values:
   - Age → median imputation
   - Embarked → mode imputation
4. Remove duplicate rows
5. Standardise categorical values (Sex, Embarked)
6. Detect and cap outliers in Fare using IQR method
7. Correct data types (PassengerId → string, Survived → categorical, Fare → float)
8. Compare before vs after cleaning with summary table
9. Save cleaned dataset

## Outputs
- Data quality report table
- Heatmap of missing values
- Outlier detection (Fare boxplot)
- Before vs After summary table
- Cleaned dataset file (`cleaned_titanic.csv`)

## Insights
- Missing values in Age and Embarked handled appropriately
- Cabin column dropped due to excessive missingness (not present in cleaned dataset)
- Fare outliers capped to reduce skew
- Dataset ready for machine learning and exploratory analysis

## Deliverables
- Notebook (`Task3_DataCleaning.ipynb`)
- Dataset (`titanic_cleaned_dataset.csv`)
- Cleaned dataset (`cleaned_titanic.csv`)
- README.md (this file)
