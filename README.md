# Customer Segmentation using RFM & K-Means

## 📌 Overview

This project performs customer segmentation on retail transaction data using **RFM analysis** and **K-Means clustering**.

The goal is to identify meaningful customer groups based on their purchasing behavior and develop targeted marketing strategies for each segment.

## 📊 RFM Analysis

- **Recency** – How recently a customer made a purchase
- **Frequency** – How frequently a customer makes purchases
- **Monetary Value** – How much a customer spends

## 🔍 Workflow

1. Data cleaning and preprocessing
2. RFM feature engineering
3. Customer-level aggregation
4. Outlier detection using the IQR method
5. Feature scaling
6. Cluster selection using Elbow Method, Silhouette Score, and Gap Statistic
7. K-Means clustering with **4 clusters**
8. Cluster profiling and visualization
9. PCA visualization
10. Revenue contribution analysis
11. Business recommendations

## 👥 Customer Segments

The analysis identified four customer segments:

- **VIP / High-Value Customers**
- **Valuable / Active Customers**
- **Recent / Occasional Customers**
- **Inactive / At-Risk Customers**

## 💡 Key Insight

The identified segments show significant differences in customer behavior and revenue contribution, allowing businesses to apply targeted retention, engagement, upselling, and re-engagement strategies.

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🚀 How to Run

Clone the repository and open the Jupyter Notebook:

```bash
git clone https://github.com/shubhamstat10/customer-segmentation-rfm-kmeans
cd customer-segmentation-rfm-kmeans
jupyter notebook
