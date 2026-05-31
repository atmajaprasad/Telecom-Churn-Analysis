# Telecom Customer Churn Analysis
Exploratory data analysis and predictive modelling on a telecom dataset to identify the key drivers of customer churn and build a model to predict at-risk customers.

## 📌 Objective
Analyze customer behavior in a telecom company to identify key factors driving churn and help improve customer retention.

## 📊 Tools & Technologies
- Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn
- Jupyter Notebook

## 📁 Dataset
- Source: IBM Telco Customer Churn Dataset (Kaggle)
- Size: 7,043 rows × 21 columns
- Target variable: Churn (Yes / No)
- Overall churn rate: ~26.5%

## 🔍 Key Analysis Steps
- #1 Churn Predictor: Contract type — month-to-month customers churn at 38% higher rate
- Statistical Validation: Chi-square test confirmed contract type is a significant churn driver (p < 0.05)
- Model Accuracy: Logistic Regression — 80% accuracy, 59.9% F1-score
- Top Insight: Customers on month-to-month contracts with no tech support and fibre internet had the highest churn probability


## ✅ Insights
- Customers on **month-to-month contracts** churn more than long-term users
- **Tenure** plays a significant role — newer users are more likely to churn
- **Senior citizens** have a slightly higher churn tendency

## Visuals

- Feature Correlation Heatmap
<img width="1406" height="1184" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/72f2f190-177b-4cdd-924a-a03c9eba72fc" />

- Churn Rate by Contract Type
<img width="545" height="393" alt="image" src="https://github.com/user-attachments/assets/b3cc0b40-329c-40bc-8ce8-0dce10c557cf" />

- Confusion Matrix
<img width="714" height="581" alt="confusion_matrix" src="https://github.com/user-attachments/assets/05786f67-f9ce-4fd5-a412-9d4ba197e7a4" />


This is part of my Data Analytics portfolio.  
Feel free to explore the notebook and visuals to understand the analysis workflow.

## Author : Atmaja A Prasad
---
