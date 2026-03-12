# PRODIGY_ML_02
"K-Means Clustering model to segment mall customers based on annual income and spending patterns (Task 02)."
# Task 02: Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project focuses on **Unsupervised Learning** by grouping customers of a retail mall based on their spending habits and annual income. The goal is to identify distinct customer segments to help businesses tailor their marketing strategies.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Scikit-Learn
* **Algorithm:** K-Means Clustering

## 📊 Key Steps
1. **Data Exploration:** Analyzed the Mall Customers dataset.
2. **Elbow Method:** Used WCSS (Within-Cluster Sum of Squares) to find the optimal number of clusters (**K=5**).
3. **Model Training:** Applied the K-Means algorithm to segment the data.
4. **Visualization:** Created a scatter plot to visualize the 5 distinct customer groups and their centroids.

## 🚀 Results
The model successfully identified 5 segments:
* **Target Customers:** High Income, High Spending Score.
* **Careful Spenders:** High Income, Low Spending Score.
* **Spendthrifts:** Low Income, High Spending Score.
* **Sensible:** Low Income, Low Spending Score.
* **Standard:** Average Income and Spending.
