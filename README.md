# CapstoneLoanDefaultPredictionAssignment

# Loan Default Prediction Model

## Project Overview

Machine learning model to predict loan defaults within 2 years, achieving 86% AUC and generating $20.4M improvement over baseline approach.

### Business Problem
Banks lose millions from defaults while missing revenue by rejecting good customers. This model helps make better lending decisions.

### Results
- **Best Model:** Random Forest with 85.9% AUC and 90% accuracy
- **Business Impact:** $20.3M profit vs -$150K baseline
- **Key Finding:** Payment history is the strongest predictor of default

## Dataset
- **Source:** "Give Me Some Credit" from Kaggle
- **Size:** 150,000 borrowers with 10 features
- **Target:** Default within 2 years (6.7% default rate)

## Methodology
1. **EDA:** Identified class imbalance, missing data, and outliers
2. **Preprocessing:** Fixed data quality issues, filled missing values, feature engineering
3. **Modeling:** Logistic Regression and Random Forest with SMOTE for class balance
4. **Evaluation:** Used AUC-ROC, confusion matrices, and cost-benefit analysis

## Key Findings
- Payment history features show 8-15x difference between defaulters and non-defaulters
- Younger borrowers and lower income correlate with higher default risk
- Random Forest outperforms Logistic Regression (86% vs 83% AUC)
- Model generates $6.5M more profit than Logistic Regression

## Files
- `loan_default_notebook.ipynb` - Main analysis notebook
- `loan_default_random_forest_pipeline.pkl` - Trained model
- `cs-training.csv` - Training data

## Author
Pierre Hunter  
Data Science Capstone - October 2025
