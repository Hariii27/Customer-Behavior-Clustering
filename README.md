# Customer-Behavior-Clustering
# 🛒 Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project focuses on segmenting customers into distinct groups based on their purchasing behavior using unsupervised machine learning. The goal is to identify meaningful customer segments that can help businesses optimize marketing strategies and improve customer engagement.

---

## 🎯 Problem Statement

Businesses often struggle to understand different types of customers due to the lack of labeled data. This project aims to group customers with similar behavior patterns without predefined labels using clustering techniques.

---

## 💡 Solution Approach

* Generated a synthetic dataset with clear behavioral patterns
* Selected key features influencing customer behavior
* Applied feature scaling to normalize data
* Used K-Means clustering to segment customers
* Determined optimal clusters using Elbow Method and Silhouette Score
* Interpreted clusters to derive business insights

---

## 📊 Dataset Description

The dataset includes the following features:

* `purchase_frequency` → Number of purchases made by a customer
* `avg_order_value` → Average spending per order
* `cart_abandonment_rate` → Percentage of abandoned carts

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 🧠 Machine Learning Workflow

1. Synthetic Data Generation (1500 records with clear patterns)
2. Data Exploration
3. Feature Scaling using StandardScaler
4. Clustering using K-Means
5. Optimal cluster selection (Elbow Method)
6. Model evaluation using Silhouette Score
7. Cluster interpretation

---

## 📈 Results

* Achieved a Silhouette Score of **~0.60**, indicating strong cluster separation
* Identified 3 distinct customer segments:

### 💎 High-Value Customers

* High purchase frequency
* High average order value
* Low cart abandonment

### ⚖️ Medium Customers

* Moderate purchase behavior
* Average spending

### ⚠️ Low-Engagement Customers

* Low purchase frequency
* Low spending
* High cart abandonment

---

## 📊 Visualization

* Scatter plot showing clear separation between clusters
* Elbow Method graph for optimal cluster selection

---

## 🔍 Key Learnings

* Importance of feature selection in clustering
* Impact of data distribution on model performance
* Difference between model accuracy and cluster quality
* Practical understanding of unsupervised learning

---

## ⚠️ Limitations

* Dataset is synthetic and not real-world data
* K-Means assumes spherical clusters
* Sensitive to feature scaling

---

## 🚀 Future Improvements

* Use real-world e-commerce datasets
* Apply advanced clustering algorithms (DBSCAN, Hierarchical Clustering)
* Integrate recommendation systems
* Build an interactive dashboard

---

## 🙌 Author

Hari Narayanan K
CSE Student | Aspiring ML & Cloud Engineer
