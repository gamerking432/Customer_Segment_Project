# Customer Segmentation using KMeans

## 📌 Overview

This project performs **customer segmentation** using the KMeans clustering algorithm. It groups customers based on their **Annual Income** and **Spending Score** to identify distinct customer categories (tiers).

The goal is to understand customer behavior patterns and visualize how different groups are formed using unsupervised machine learning.

---

## ⚙️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

---

## 🧠 How It Works

1. **Data Loading**

   * The dataset is loaded using Pandas.

2. **Feature Selection**

   * Two features are selected:

     * Annual Income
     * Spending Score

3. **Data Scaling**

   * The data is standardized using `StandardScaler` to improve clustering performance.

4. **Model Training**

   * KMeans clustering is applied with 4 clusters.
   * Each data point is assigned to a cluster.

5. **Inverse Transformation**

   * Scaled data is converted back to original values for better visualization.

6. **Visualization**

   * A scatter plot is created to display:

     * Customer clusters (Tier 1 to Tier 4)
     * Cluster centroids (highlighted with 'X')

---

## 📊 Output

* Customers are divided into 4 distinct clusters (tiers)
* Each cluster represents a group with similar income and spending behavior
* Centroids indicate the center of each cluster

---

## 🎯 Key Concepts

* Unsupervised Learning
* KMeans Clustering
* Data Standardization
* Data Visualization

---

## 🚀 Use Cases

* Customer behavior analysis
* Targeted marketing
* Business decision-making
* Market segmentation

---

## ⚠️ Notes

* The model uses only two features, so clustering is based on limited information
* Results may vary depending on dataset quality and feature selection
* Scaling is necessary for accurate clustering

---

## 📁 Dataset

The project uses a CSV file:

```
customer_segment.csv
```

Make sure column names match:

* Annual_Income
* Spending_Score

---

## 📌 Conclusion

This project demonstrates how machine learning can be used to group customers into meaningful segments. It provides a simple but effective way to visualize patterns in customer data.
