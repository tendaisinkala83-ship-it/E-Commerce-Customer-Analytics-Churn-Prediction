# E-Commerce-Customer-Analytics-Churn-Prediction

## Project Overview

This project analyzes customer purchasing behaviour within  an e-commerce  marketplace to uncover revenue drivers, customer retention patterns, and churn risk. Using Python-based analytics and machine learning techniques, the project progresses from exploratory analysis to customer segmentation and predictive modeling. The objective is to simulate a real-world analytics workflow to support data-driven business decisions.
___
## Business Objectives 

- Analyze overall revenue performance and customer purchasing trends
- Measure customer retention using repeat purchase behaviour
- Segment customers using RFM (Recency, Frequency, Monetary) analysis
- Identify high-value and at-risk customer groups
- Predict customer churn using machine learning
___
## Tools & Technologies

- **Python**
- **Pandas & NumPy**
- **Matplotlib**
- **Scikit-learn**
- **Jupyter Notebook**
- **Kaggle Dataset**
___
## Project Structure
```
ecommerce-customer-analytics/
    notebooks/
        01_data_cleaning.ipynb
        02_revenue_kpi_analysis.ipynb
        03_rfm_segmentation.ipynb
        04_churn_prediction.ipynb
    outputs/
        cleaned_master_dataset.csv
        rfm_dataset.csv
        modeling.dataset.csv

     README.md
```
___

## Key Analysis Steps

### 1. Data Cleaning & Preparation
- Merged multiple relational datasets
- Handled missing values
- Converted timestamps
- Engineered order-level revenue features

___

### 2. Revenue & KPI Analysis
- Total Revenue
- Total Orders
- Average Order Value (AOV)
- Repeat Customer Rate
  
This analysis provides insight into overall marketplace performance and customer purchasing behaviour.

___

### 3. Customer Segmentation (RFM Analysis)

Customers were segmented based on:
- **Recency**- Time since last purchase
- **Frequency**- Number of purchases
- **Monetary Value**- Total spending

Segments identified:
- Loyal Customers
- New Customers
- Standard Customers
- At-Risk Customers

Revenue contribution by segment highlights the disproportionate impact of high-value customers.
___

### 4. Churn Prediction (Machine Learrning)

A Random Forest classification  model was developed to predict customer chrun risk.

**Churn Definition:**
Customers inactive for more than 90 days were labled as churned.

Model Inputs:
- Recency
- Frequency
- Monetary Value

Outputs:
- Customer chrun probability
- Feature importance analysis

___

## Key Insights

- A small proportion of customers generates a large share of revenue.
- Customer inactivity (recency) is the strongest predictor of churn.
- Retention strategies targeting at-risk customers can significantly improve lifetime value.

___

## Business Impact

This project demonstrates how analytics can support:

- Customer retention strategy
- Marketing prioritization
- Revenue optimization
- Predictive decision-making

___

## Dataset

Brazilian E-Commerce Public Dataset by Olist
Avaliable on Kaggle.

___

## Author 
 **Tendai Sinkala**
 Data Analyst | Healthcare & Business Analytics
 sinkalat99@gmail.com

## Future Improvements

- Customer lifetime value prediction
- Marketing response modeling
- Interactive dashboard deployment
- Real-time churn monitoring
 
