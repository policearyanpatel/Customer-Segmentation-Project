# Customer Intelligence & Segmentation Analysis

## End-to-End Customer Analytics and Customer Segmentation Project

### Project Overview

Customer Intelligence & Segmentation Analysis is a complete data analytics and machine learning project designed to identify meaningful customer segments from transactional and behavioral customer data.

The project combines data cleaning, exploratory data analysis, feature engineering, RFM analysis, customer segmentation using K-Means clustering, and interactive Power BI dashboards to transform raw customer data into actionable business insights.

The primary objective is to help organizations better understand customer behavior, improve customer retention, optimize marketing strategies, and increase customer lifetime value through data-driven decision making.



## Business Problem

Organizations often struggle to understand the differences between their customers. Treating every customer the same can lead to ineffective marketing campaigns, low retention rates, and missed revenue opportunities.

This project addresses these challenges by:

* Identifying high-value customers
* Detecting customers at risk of churn
* Understanding purchasing behavior
* Creating actionable customer segments
* Providing business recommendations for each segment

---
## Dataset

Due to GitHub file size limitations, the cleaned dataset (`cleaned_data.csv`) is not included in this repository.

The project can be reproduced using the original Online Retail dataset and the provided notebooks.

Available datasets:
- customer_features.csv
- segmented_customers.csv

## Dataset Description

The dataset contains customer-level transactional and behavioral information.

### Dataset Size

* Total Customers: 4,338

### Features Used

| Feature           | Description                         |
| ----------------- | ----------------------------------- |
| CustomerID        | Unique customer identifier          |
| Recency           | Days since last purchase            |
| Frequency         | Number of purchases made            |
| Monetary          | Total spending amount               |
| Product_Diversity | Number of unique products purchased |
| Tenure            | Customer relationship duration      |
| Avg_Order_Value   | Average spending per transaction    |
| Avg_Basket_Size   | Average value of items purchased    |

---

# Project Methodology

The project was developed through four major phases.

---

## Notebook 01: Data Cleaning & Preparation

### Objectives

Prepare a high-quality dataset suitable for analytics and machine learning.

### Activities Performed

* Missing value assessment
* Duplicate record detection
* Data type validation
* Data consistency checks
* Numerical feature validation
* Data quality verification

### Outcome

A clean and reliable dataset ready for analysis and modeling.

---

## Notebook 02: Exploratory Data Analysis (EDA)

### Objectives

Understand customer behavior and identify important patterns.

### Analysis Conducted

#### Recency Analysis

Examined customer activity levels and purchasing recency.

#### Frequency Analysis

Studied customer engagement and purchase behavior.

#### Monetary Analysis

Investigated customer spending patterns and revenue distribution.

#### Tenure Analysis

Analyzed customer lifecycle and relationship duration.

### Key Findings

* Most customers purchase infrequently.
* Revenue is concentrated among a smaller group of customers.
* Customer spending distribution is highly skewed.
* High-value customers significantly impact overall revenue.

---

## Notebook 03: Feature Engineering

Feature engineering was performed to create meaningful business-focused variables.

### RFM Analysis

#### Recency

Measures how recently a customer made a purchase.

#### Frequency

Measures how often a customer purchases.

#### Monetary

Measures total customer spending.

---

### Additional Features Created

#### Average Order Value

Average spending per transaction.

#### Average Basket Size

Average purchase value per order.

#### Product Diversity

Variety of products purchased by a customer.

#### Customer Tenure

Length of customer relationship.

### Outcome

These engineered features provided a richer representation of customer behavior and improved segmentation quality.

---

## Notebook 04: Customer Segmentation

### Feature Selection

The clustering model used:

* Recency
* Frequency
* Monetary
* Product Diversity
* Tenure
* Average Order Value
* Average Basket Size

### Feature Scaling

Features were standardized before clustering to ensure equal contribution.

### K-Means Clustering

K-Means clustering was applied to group customers with similar purchasing behaviors.

### Cluster Profiling

After clustering, each cluster was analyzed and assigned business-friendly names.

---

# Customer Segments Identified

## VIP Customers

### Characteristics

* Highest purchase frequency
* Highest customer value
* Strong loyalty
* High engagement

### Business Strategy

* Premium rewards
* Exclusive access programs
* Personalized engagement

---

## Loyal Customers

### Characteristics

* Consistent purchasing behavior
* Strong revenue contribution
* High retention levels

### Business Strategy

* Membership programs
* Cross-selling opportunities
* Referral campaigns

---

## Potential Loyalists

### Characteristics

* Largest customer segment
* Moderate engagement
* Strong growth potential

### Business Strategy

* Personalized promotions
* Loyalty enrollment campaigns
* Targeted marketing

---

## Dormant Customers

### Characteristics

* Low engagement
* High recency values
* Churn risk

### Business Strategy

* Win-back campaigns
* Reactivation discounts
* Personalized reminders

---

## Wholesale Buyers

### Characteristics

* Very high average order value
* Bulk purchasing behavior
* Lower purchase frequency

### Business Strategy

* Bulk discounts
* Dedicated account management
* Contract pricing

---

# Power BI Dashboard

An interactive four-page Power BI dashboard was developed to communicate insights.

---

## Page 1: Executive Summary

### KPIs

* Total Customers
* Total Revenue
* Average Customer Value
* Average Purchase Frequency

### Visualizations

* Revenue by Segment
* Customer Distribution by Segment

### Purpose

Provides a high-level overview of business performance.

---

## Page 2: Segment Analysis

### Visualizations

* Revenue Contribution by Segment
* Average Customer Value by Segment
* Purchase Frequency by Segment
* Segment Characteristics Table
* Segment Profitability Comparison

### Purpose

Supports strategic customer targeting and resource allocation.

---

## Page 3: Customer Behavior Analytics

### Visualizations

* Recency Distribution
* Frequency Distribution
* Monetary Distribution
* Tenure Distribution
* Frequency vs Monetary Scatter Plot
* Average Basket Size Analysis

### Purpose

Provides deeper insights into customer purchasing behavior.

---

## Page 4: Strategic Recommendations

### Visualizations

* Segment Recommendations Table
* Business Insights
* Customer Distribution by Segment
* Strategic Action Plans

### Purpose

Converts analytical findings into actionable business decisions.

---

# Business Impact

This project demonstrates how customer analytics can help organizations:

* Improve customer retention
* Increase customer lifetime value
* Reduce customer churn
* Optimize marketing campaigns
* Improve revenue generation
* Support data-driven decision making

---

# Tools & Technologies

### Programming & Analytics

* Python
* Pandas
* NumPy
* Scikit-Learn

### Data Visualization

* Matplotlib
* Seaborn

### Business Intelligence

* Power BI

### Development Environment

* VS Code
* Jupyter Notebook

---

# Future Improvements

Potential enhancements include:

* Customer churn prediction models
* Real-time customer segmentation
* Recommendation systems
* Streamlit deployment
* Automated customer scoring
* Advanced behavioral analytics

---

# Conclusion

This project successfully transformed raw customer transaction data into actionable business intelligence through data cleaning, exploratory analysis, feature engineering, customer segmentation, and interactive dashboard development.

The final solution provides a practical framework for identifying high-value customers, improving customer retention, optimizing marketing strategies, and supporting long-term business growth through data-driven decision making.

Project done by : Police Aryan Patel 