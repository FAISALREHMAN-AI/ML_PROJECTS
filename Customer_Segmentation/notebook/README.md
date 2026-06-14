# 🛒 Customer Segmentation Using K-Means

## 📌 Project Overview
This project is an Unsupervised Machine Learning tool built for retail businesses and shopping malls. Instead of predicting a specific target, this AI analyzes customer data (such as age, annual income, and spending scores) to discover hidden patterns. It automatically groups customers into distinct segments, allowing marketing teams to launch highly targeted ad campaigns and personalized discounts.

## 🚀 Key Features
* **Exploratory Data Analysis (EDA):** Visualized income and spending distributions to understand baseline customer demographics.
* **The Elbow Method:** Implemented a programmatic loop to calculate the Within-Cluster Sum of Squares (WCSS) to mathematically determine the optimal number of customer groups (k=5).
* **K-Means Clustering:** Trained the K-Means algorithm to assign every customer to one of the five targeted segments and plotted their centroids.

## 🛠️ Technologies Used
* **Programming Language:** Python
* **Data Handling:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (KMeans)

## 📊 Business Insights & Marketing Strategy
The K-Means algorithm successfully identified 5 distinct customer groups:
1. **Target Customers (High Income, High Spend):** Premium shoppers. Strategy: Market expensive, luxury brands directly to them.
2. **Careful Customers (High Income, Low Spend):** High-earning but frugal. Strategy: Offer promo codes and discount sales to incentivize purchasing.
3. **Careless Customers (Low Income, High Spend):** Trend-driven shoppers. Strategy: Showcase affordable, fast-fashion items.
4. **Standard Customers (Average Income, Average Spend):** The bulk of the mall's visitors. Strategy: Standard broad-marketing campaigns.
5. **Sensible Customers (Low Income, Low Spend):** Essential buyers.