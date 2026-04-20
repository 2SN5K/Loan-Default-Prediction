# Loan-Default-Prediction 
ML project to predict loan default risk using Machine Learning

## Project Overview
This project aims to predict whether a customer will default on a loan using machine learning techniques. The model helps identify high-risk and low-risk customers for better lending decisions.

---

## Dataset
The dataset includes customer details such as:
- Age
- Income
- Employment Length
- Loan Amount
- Interest Rate
- Credit History

---

##  Models Used
- Logistic Regression
- Decision Tree
- Random Forest (Best Model)

---

##  Objective
To classify customers into:
- Low Risk (0)
- High Risk (1)

---

## Model Performance
- Logistic Regression: 83.7%
- Decision Tree: 88.5%
- Random Forest: 93.0% (Best)

---

## Prediction Results
- Low Risk Customers (0): 5450
- High Risk Customers (1): 1067

👉 This shows that most customers are low risk, but a significant number of customers are likely to default.

---

##  Key Insights
- Loan percent income is the most important factor affecting default risk
- Customers with higher loan burden compared to income are more likely to default
- Lower income increases default probability
- Higher interest rates lead to higher risk
- Loan grade and home ownership also influence default behavior

---

##  Business Insight
The bank faces risk when loans are issued to customers with high loan-to-income ratios and low income levels.

However, the Random Forest model helps identify 1067 high-risk customers in advance, enabling the bank to:
- Reduce financial loss
- Make better loan approval decisions
- Monitor risky customers effectively

---

##  Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

##  Conclusion
Random Forest achieved the highest accuracy of 93% and was used to classify customers into risk categories. The model successfully identified high-risk customers and can be used as a decision-support tool for banks.

---

## 🔗 Project Files
(https://colab.research.google.com/drive/19YKoGOP37OXM6w_G7EY72AnzMjGBBmaF?usp=sharing)
