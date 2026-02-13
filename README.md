# 📉 Telco Customer Churn Prediction

## 📌 Project Overview
The objective of this project is to identify customers of a telecom company who are likely to leave the service (Churn). 
This is a **Binary Classification** problem where we use machine learning to help the company save revenue.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **ML Framework:** Scikit-learn
* **Data Balancing:** SMOTE (Synthetic Minority Over-sampling Technique)

⚙️ Data Preprocessing & Modeling
We took the following steps to prepare the data for the model:

Data Cleaning: Converted TotalCharges to numeric and removed null values.

Encoding: Transformed categorical variables into numbers using One-Hot Encoding.

Scaling: Used StandardScaler so that the scale of features could be balanced.

Handling Imbalance (SMOTE): Since the number of churners was low (Imbalanced Data), we used SMOTE so that the model does not become biased only towards "No Churn".


## 📈 Model Performance
Using **Random Forest + SMOTE**, we achieved:
* **Recall (Class 1):** ~64% (Successfully identifying most churners)
* **Accuracy:** 76%
*   ![Confusion Matrix](https://github.com/anuskhattak/Customer-Churn-Prediction/blob/main/download%20(4).png?raw=true)

💡 Business Recommendations
Incentivize Month-to-month customers to switch to yearly plans.
![Payment Method vs Churn](https://github.com/anuskhattak/Customer-Churn-Prediction/blob/main/download%20(3).png?raw=true)

Monitor customers using Electronic Checks for early churn signs.
![Electronic Check Churn Analysis](https://github.com/anuskhattak/Customer-Churn-Prediction/blob/main/download%20(2).png?raw=true)

Offer loyalty rewards to high-paying customers to reduce risk.


  
