# # TradeGuardian AI: Supply Chain Risk Analytics Platform

TradeGuardian-AI is a machine learning project I built to analyze supply chain operations and predict late delivery risks using historical transaction data.

The project combines data cleaning, feature engineering, predictive modeling, customer segmentation, and business intelligence to generate insights that can help improve supply chain performance and business decision-making.

---

# Problem Statement

Late deliveries directly impact customer satisfaction, increase operational costs, and reduce overall supply chain efficiency.

This project focuses on using historical supply chain transaction data to:

- Predict late delivery risk
- Analyze delivery performance
- Identify valuable customer segments
- Measure customer health
- Generate actionable business insights

---

# Dataset

**Dataset:** DataCo Supply Chain Dataset

- **180,519** Orders
- **20,652** Customers
- **164** Countries
- **118** Products
- **53** Original Features
- **60+** Engineered Features

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

# Project Workflow

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

### Best Performing Model

**Random Forest**

### Model Performance

| Metric | Score |
|----------|--------|
| Accuracy | **82.99%** |
| ROC-AUC | **92.61%** |

---

# Feature Engineering

Some of the custom features created during feature engineering include:

- Shipping Delay
- Delivery Performance Score
- Supplier Risk Score
- Customer Lifetime Value
- Customer Health Score
- Shipping Efficiency
- Order Value Segment
- Product Popularity
- Country Sales Rank

These engineered features helped improve the predictive performance of the machine learning models while also providing meaningful business insights.

---

# Customer Segmentation

Customers were segmented using **K-Means Clustering** into five business-oriented personas:

- 🏆 VIP Customers
- 💎 Loyal Customers
- 🚨 High-Risk Customers
- 🌱 New / Stable Customers
- 💸 Loss-Making Customers

These customer groups can help businesses prioritize customer engagement, improve retention strategies, and identify customers requiring operational attention.

---

# Key Business Insights

Some interesting observations from the analysis were:

- Shipping Mode has the strongest influence on delivery risk.
- Certain countries and regions experience significantly higher delivery delays.
- Customer segmentation helps distinguish high-value customers from loss-making customer groups.
- Customer Health Score provides a quick overview of customer quality based on profitability, purchasing behavior, and delivery performance.
- Feature engineering contributed significantly to improving model performance.

---

# Current Limitations

This project represents **Version 1.0**, and there are several areas that can be expanded in future versions.

- Sales forecasting is based on only **34 complete monthly observations**, so it demonstrates the forecasting workflow rather than production-grade forecasting.
- Customer Health Score is calculated using engineered business metrics and quantile-based segmentation.
- The project is currently developed and executed in **Google Colab**.
- The prediction model is trained offline and does not support real-time inference.
- The project uses the publicly available **DataCo Supply Chain Dataset** rather than live operational data.

---

# Planned Enhancements (Version 2.0)

I plan to extend this project by adding:

### AI Features

- AI-powered Supply Chain Assistant
- Natural Language Querying
- LLM-based Business Insights
- Explainable AI Dashboard

### Business Intelligence

- Streamlit Dashboard
- Executive KPI Dashboard
- Procurement Risk Dashboard
- Customer Analytics Dashboard

### Backend

- FastAPI REST APIs
- Real-Time Prediction APIs
- Batch Prediction Service

### Deployment

- Docker Containerization
- Cloud Deployment
- CI/CD Pipeline

### Data Engineering

- Live Data Integration
- Automated ETL Pipeline
- Real-Time Monitoring

---

# What I Learned

Building this project gave me hands-on experience with the complete machine learning workflow, from preparing raw data to building predictive models and interpreting business insights.

Some of the key learnings include:

- Data Cleaning and Preprocessing
- Feature Engineering
- Machine Learning Model Development
- Customer Segmentation
- Business Intelligence
- Model Evaluation
- Data Visualization
- Translating analytical results into business recommendations

This project also reinforced that building a machine learning model is only one part of solving a business problem. Understanding the data, creating meaningful features, and presenting actionable insights are equally important.

---

# Future Scope

I plan to continue improving TradeGuardian-AI by adding interactive dashboards, REST APIs, and AI-powered insights so that it evolves from a machine learning notebook into a production-style analytics application.

---

# Author

**Mayur Gaikwad**

Thank you for taking the time to explore this project. Feedback and suggestions are always welcome.
