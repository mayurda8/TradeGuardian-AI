# TradeGuardian-AI
AI-powered Supply Chain Risk Analytics Platform using Machine Learning, Customer Segmentation, Business Intelligence, and Predictive Analytics.

# TradeGuardian-AI

TradeGuardian-AI is an end-to-end machine learning project that analyzes supply chain operations and predicts late delivery risks. Along with predictive modeling, the project includes customer segmentation, business KPIs, and operational insights to support better decision-making.

The objective of this project was not just to build a prediction model, but to understand how machine learning can be applied to solve real business problems in supply chain and logistics.

---

# Problem Statement

Late deliveries impact customer satisfaction, increase operational costs, and reduce overall supply chain efficiency.

Using historical supply chain transaction data, this project focuses on:

- Predicting late delivery risk
- Understanding delivery performance
- Identifying valuable customer segments
- Measuring customer health
- Generating business insights from operational data

---

# Dataset

**Dataset:** DataCo Supply Chain Dataset

- 180,519 Orders
- 20,652 Customers
- 164 Countries
- 118 Products
- 53 Original Features
- 60+ Engineered Features

---

# Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest
- XGBoost
- LightGBM
- K-Means Clustering
- Plotly
- Matplotlib
- Google Colab

---

# Workflow

```
Raw Dataset
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis
      ↓
Business KPI Generation
      ↓
Machine Learning
      ↓
Customer Segmentation
      ↓
Business Insights
```

---

# Machine Learning

### Target Variable

Late Delivery Risk

### Models Evaluated

- Logistic Regression
- Random Forest
- XGBoost
- LightGBM

### Best Model

Random Forest

### Performance

| Metric | Value |
|---------|-------|
| Accuracy | **82.99%** |
| ROC-AUC | **92.61%** |

---

# Feature Engineering

Some of the engineered features include:

- Shipping Delay
- Delivery Performance Score
- Supplier Risk Score
- Customer Lifetime Value
- Customer Health Score
- Shipping Efficiency
- Order Value Segment
- Product Popularity
- Country Sales Rank

---

# Customer Segmentation

Customers were grouped using **K-Means Clustering** into five business-oriented personas.

- VIP Customers
- Loyal Customers
- High-Risk Customers
- New / Stable Customers
- Loss-Making Customers

These segments help identify customers requiring retention strategies, operational improvements, or profitability reviews.

---

# Key Business Insights

Some insights generated from this project include:

- Shipping Mode has the highest impact on delivery risk.
- Certain geographical regions contribute more to delivery delays.
- Customer segmentation helps identify high-value and loss-making customers.
- Customer Health Score provides a quick view of customer quality based on profitability, delivery performance, and purchasing behavior.
- Feature engineering significantly improved model performance.

---

# Current Limitations

This project represents **Version 1.0**.

Some components have intentionally been kept simple and can be improved further.

- Sales forecasting is based on only 34 complete monthly observations, so it demonstrates the forecasting workflow rather than production-grade forecasting.
- Customer Health Score is calculated using engineered business metrics and quantile-based segmentation.
- The project currently runs in Google Colab.
- The prediction model is trained offline and does not support real-time inference.
- The project uses a publicly available dataset instead of live operational data.

---

# Planned Enhancements (Version 2.0)

The next version of this project will include:

- Streamlit Dashboard
- FastAPI REST APIs
- AI Supply Chain Copilot
- Natural Language Querying
- Docker Deployment
- Cloud Hosting
- Real-Time Prediction API
- Automated Model Retraining

---

# What I Learned

Working on this project helped me gain practical experience in:

- Data Cleaning
- Feature Engineering
- Machine Learning
- Customer Segmentation
- Business Intelligence
- Model Evaluation
- Data Visualization
- Translating analytical results into business insights

More importantly, it reinforced that building a machine learning model is only one part of solving a business problem. Understanding the data, engineering meaningful features, and presenting actionable insights are equally important.

---

# Future Scope

My goal is to expand TradeGuardian-AI into a complete AI-powered supply chain analytics platform by integrating conversational AI, interactive dashboards, and cloud deployment.

---

# Author

**Mayur Gaikwad**

Business Analyst | Data Analyst | AI & Machine Learning Enthusiast

# 👨‍💻 Author

**Mayur Gaikwad**


