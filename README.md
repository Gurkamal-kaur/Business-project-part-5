# 📌 Project Title
Customer Lifetime Value Analysis & Future Spending Prediction

## 🛒 Business Problem
The company wants to increase revenue from existing customers rather than spending heavily on acquiring new ones. By analyzing customer behavior and predicting future spending, the business can design targeted strategies to:
- Identify high‑value customers for premium offers
- Re‑engage inactive buyers
- Maximize overall customer lifetime value (CLV)

## 📂 Dataset Source
Name: Customer Behavior & Future Spending Dataset  
Origin: Provided via Google Drive  
Accessed from: [Dataset Link](https://drive.google.com/file/d/1BIrMxVmcLTXwowxkQ1HqMw8U1eu6dCE7/view?usp=sharing)

## 📑 Dataset Description
Period: One year of customer activity  
Size: Several thousand rows  
Columns include:
- CustomerID (unique identifier)
- Age, Income (demographics)
- Website Visits, Active Days, App Sessions (engagement metrics)
- Previous Spending, Number of Orders, Average Order Value (purchase behavior)
- Return Rate, Cancellation Rate (risk indicators)
- Future Spending (target variable)
- Customer Value Score (derived measure of importance)

## 🛠️ Tools and Libraries Used
- Python (Google Colab / Jupyter Notebook)
- pandas, numpy → data cleaning & feature engineering
- matplotlib, seaborn → visualizations
- scikit‑learn → regression models (Linear Regression, Decision Tree, Random Forest)

## 🔎 Steps Performed
1. Business Problem Understanding  
2. Data Understanding  
3. Data Cleaning & Feature Engineering  
4. Exploratory Data Analysis (EDA)  
5. Customer Segmentation  
6. Future Spending Prediction  
7. Business Recommendations  

## 🧹 Data Cleaning Summary
- Removed duplicates and invalid entries
- Handled missing demographic and behavioral values
- Corrected data types
- Removed extreme outliers in spending and orders

## 🏗️ Feature Engineering Summary
- Recency = days since last purchase
- Frequency = number of orders
- Monetary = total spending
- Engagement Score = website visits + active days
- Spending Growth = change in spending over time

## 📊 EDA Insights
- Strong correlation between previous spending and future spending
- Customers with high orders and spending drive most revenue
- Inactive customers show long recency and low engagement
- Outliers exist in spending and order counts

## 🤖 Modeling Approach
- Standardized features for regression
- Applied Linear Regression, Decision Tree, Random Forest
- Compared performance using MAE, MSE, RMSE, R²
- Random Forest gave the most accurate predictions

## 🧩 Business Recommendations
- High Value Loyal → VIP programs, exclusive launches, thank‑you campaigns
- Inactive / At‑Risk → Reactivation discounts, win‑back emails
- Frequent Low‑Spend Buyers → Bundle deals, cross‑selling, tiered discounts
- Occasional Buyers → Seasonal promotions, free shipping vouchers
- Low Value / Low Engagement → Avoid costly offers, focus on low‑cost engagement

## ▶️ How to Run the Project
Clone the repository and install requirements:

```bash
git clone https://github.com/Gurkamal-kaur/business-project-part-5.git
cd business-project-part-5
pip install -r requirements.txt

