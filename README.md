# 🛒 Retail Transaction Customer Segmentation Analysis

A machine learning project that segments retail customers based on their purchasing behavior using unsupervised learning (KMeans clustering). This analysis helps uncover hidden patterns in shopping habits and identifies key product preferences among customer groups.

---

## 📊 Project Overview

This project utilizes a retail transaction dataset containing:

- **Customer IDs**
- **Timestamps**
- **Product lists**

Each transaction details what products were bought by which customer on a given date. The goal is to group similar customers based on the types of products they purchase.

---

## 🧠 Key Concepts

- **Unsupervised Learning**: KMeans clustering is used to find natural groupings in customer behavior.
- **Dimensionality Reduction**: PCA (Principal Component Analysis) helps visualize high-dimensional product vectors.
- **Customer Profiling**: Analyze what kinds of products each customer group buys the most.

---

## 🧪 Techniques Used

| Task                         | Technique / Library        |
|------------------------------|----------------------------|
| Data Cleaning & Processing   | `pandas`, `numpy`          |
| Product Vectorization        | One-hot encoding           |
| Clustering                   | `KMeans` from `sklearn`    |
| Dimensionality Reduction     | `PCA`                      |
| Data Visualization           | `seaborn`, `matplotlib`    |

---

## 📂 Dataset

- Contains **30,000+** retail transactions
- Format: `CustomerID`, `Timestamp`, `Products`
- Product list is exploded into individual rows for vectorization

---

## 📈 Visualizations

- PCA scatter plot to visualize cluster distribution
- Bar charts showing top 10 products per customer cluster

---

## 🔍 Sample Insights

- **Cluster 0**: Health & Home — Yogurt, Detergent, Cereal, Lentils
- **Cluster 1**: Daily Essentials — Apple, Bread, Chips, Shampoo
- **Cluster 2-4**: Distinct product interests and shopping patterns

These insights can inform:
- Personalized marketing
- Inventory planning
- Customer loyalty programs

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/sahil007707/retail-customer-segmentation.git
cd retail-customer-segmentation

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
