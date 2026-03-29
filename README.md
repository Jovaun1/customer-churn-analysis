# Customer Churn Analysis & Prediction

## 📌 Overview
This project analyzes customer churn behavior and builds a machine learning model to predict which customers are likely to leave.

It combines exploratory data analysis and predictive modeling to identify key churn drivers and quantify the financial impact of customer loss.

---

## ⚡ Quick Insight
High-value customers generate the most revenue, and even a small churn rate in this group represents significant financial risk.

---

## 🎯 Business Objective
Customer churn directly impacts revenue and growth. This project aims to:

- Understand why customers leave
- Identify high-risk customers
- Quantify revenue impact of churn
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
- Low-value customers churn more frequently
- High-value customers generate the majority of revenue
- Losing high-value customers results in significant financial loss

---

## 💰 Revenue Analysis (Business Impact)
- Customers were segmented into **Low, Medium, and High value** based on total revenue
- High-value customers contribute the largest share of total revenue
- Total revenue at risk from churned customers:

👉 **$2.8M+ in lost revenue**

This highlights the importance of prioritizing retention for high-value customers.

---

## 🤖 Model
A Random Forest Classifier was used to predict customer churn.

### Model Performance:
- Accuracy: ~79%
- Precision (Churn): 0.60
- Recall (Churn): 0.51 → improved using threshold tuning

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

This enables businesses to prioritize retention efforts effectively.

---

## 💡 Business Impact
This solution enables:

- Early identification of high-risk customers
- Focus on **high-value customer retention**
- Reduction in revenue loss due to churn
- Improved customer lifetime value (CLV)

---

## 📁 Project Structure
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Customer segmentation
- Revenue impact analysis
- Machine learning model
- Churn prediction system

---

## 🔮 Future Improvements
- Hyperparameter tuning
- Additional models (Logistic Regression, XGBoost)
- Real-time prediction system
- Dashboard integration (Power BI / Streamlit)

---

## 🧠 Conclusion
This project demonstrates how data analysis and machine learning can be used not only to predict churn, but to quantify its financial impact.

By combining customer segmentation, revenue analysis, and predictive modeling, businesses can make smarter decisions and protect their most valuable customers.
