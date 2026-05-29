# Bank Customer Churn Prediction

## Project Overview
Customer retention is a critical metric for financial institutions. This project aims to build a predictive model to identify bank customers who are likely to churn (close their accounts). By analyzing demographics, account information, and financial behaviors, the model helps the business proactively target at-risk customers with retention strategies.

## Tools & Technologies
- **Programming Language:** Python (Jupyter Notebook)
- **Data Manipulation & EDA:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, LightGBM, Random Forest
- **Techniques:** Data Preprocessing, Handling Imbalanced Data (SMOTE), Feature Engineering, Classification Modeling.

## Repository Structure
- `bankchurn.ipynb`: The main notebook containing the full workflow (Exploratory Data Analysis, Data Preprocessing, SMOTE implementation, Model Training, and Evaluation).
- `Churn_Modelling.csv`: The dataset containing 10,000 customer records with features such as age, credit score, balance, and the target variable `Exited`.

## Key Highlights & Methodology
1. **Exploratory Data Analysis (EDA):** Visualizing the relationships between customer attributes and churn rates to extract business insights.
2. **Handling Imbalanced Data:** Implementing **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the target class, ensuring the model does not become biased towards the majority class (retained customers).
3. **Model Evaluation:** Experimenting with multiple algorithms (Logistic Regression, Random Forest, Gradient Boosting/LGBM) and evaluating them based on Precision, Recall, F1-Score, and ROC-AUC metrics to select the most optimal model for business application.
