# Project-MMA831---Analyzing-Marketing-Campaign-effectiveness-for-Bank
A data science project analyzing the effectiveness of a Portuguese bank's marketing campaigns using classification models and customer segmentation techniques. In doing so, gaining insights regarding strategies that can be used to improve future marketing campaigns.

---
## Overview
The bank aimed to reduce inefficiencies in its telemarketing campaigns by predicting which customers are most likely to subscribe to a term deposit product.  
By leveraging machine learning techniques, our goal was to:
- Maximize subscription rate (conversion)
- Minimize customer fatigue from repeated outreach
- Optimize targeting strategy using explainable AI

---
## Repository Structure
```
├── EMC Bank Marketing_ver Final.ipynb  # Main notebook with code
├── bank-data-final.csv  # Bank marketing campaign data
├── MMA 831 - EMC Presentation_Final.pdf  # Project Report
├── README.md  # Summary of the project
```

---
## Tech Stack
- **Language**: Python (Jupyter Notebooks)
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost, lightgbm
- **Machine Learning**: Cross-Validatoin, Hyperparameter Tuning, Logistic Regression, Decision Tree, Random Forest, XGBoost, LightGBM
- **Evaluation Metrics**: Accuracy, ROC-AUC, F1 Score
- **Feature Engineering**: Label encoding, Categorizing numerical features, Standard scaling

---
## Features and Approach
- Performed exploratory data analysis (EDA) to identify key predictors (e.g., contact type, month, previous outcome)
- Performed Feature Engineering to imrpove the data for modeling
- Trained and compared multiple classification models using k-fold cross-validation
- Used GridSearchCV for hyperparameter tuning
- Calculated feature importance to gain insights
- Created actionable customer segments based on predictions

---
## Results
- Best Model = LightGBM
- Accuracy = 91%; F1 Score = 90%; ROC-AUC = 0.94
- Insights - Prior campaign outcome and call duration were most influential
- Recommendation - Focus future outreach on customers with positive historical interaction and optimize call timing

---
