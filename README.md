# Customer Churn Analysis & Prediction

## 📌 Overview
This project analyzes customer churn behavior and builds a machine learning model to predict which customers are likely to leave.

The goal is to identify key drivers of churn and provide actionable insights to help businesses reduce customer loss and improve retention.

---

## 🎯 Business Objective
Customer churn directly impacts revenue and growth. This project aims to:

- Understand why customers leave
- Identify high-risk customers
- Enable data-driven retention strategies

---

## 🛠️ Tools Used
- Python
- Pandas
- Seaborn & Matplotlib
- Scikit-learn

---

## 🔍 Key Insights
- Month-to-month customers have the highest churn (~43%)
- Electronic check users show the highest churn (~45%)
- High-paying customers are more likely to churn
- Fiber optic customers have higher churn rates
- New customers (low tenure) are at highest risk

---

## 🤖 Model
A Random Forest Classifier was used to predict customer churn.

### Model Performance:
- Accuracy: ~79%
- Improved recall by adjusting prediction threshold

---

## ⚡ Model Improvement
The prediction threshold was adjusted from **0.5 to 0.3** to improve recall.

This allows the model to:
- Identify more at-risk customers
- Reduce missed churn cases
- Support proactive retention strategies

---

## 📊 Churn Prediction System
The model provides:
- Churn prediction (Yes / No)
- Probability of churn
- Risk classification (High / Medium / Low)

This enables businesses to focus on customers most likely to leave.

---

## 💡 Business Impact
This solution enables:

- Early identification of high-risk customers
- Targeted retention campaigns
- Reduced customer loss
- Improved customer lifetime value

---

## 📁 Project Structure
- Data cleaning and preprocessing
- Exploratory data analysis
- Feature engineering
- Machine learning model
- Churn prediction system

---

## 🔮 Future Improvements
- Hyperparameter tuning
- Additional models (Logistic Regression, XGBoost)
- Dashboard integration (Power BI / Streamlit)

---

## 🧠 Conclusion
This project demonstrates how data analysis and machine learning can be used to understand customer behavior and reduce churn.

By combining insights with predictive modeling, businesses can make more effective, data-driven decisions.
