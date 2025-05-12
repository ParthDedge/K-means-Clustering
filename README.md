# 🌸 K-Means Clustering on the Iris Dataset

This repository showcases the implementation of **K-Means Clustering**, a popular unsupervised machine learning algorithm, using the **Iris dataset** — a classic benchmark dataset in machine learning and statistics.

---

## 📌 Project Objective

To apply K-Means Clustering on the Iris dataset and group the data points into clusters that ideally represent the three species of Iris flowers:  
- *Setosa*  
- *Versicolor*  
- *Virginica*

---

## 📊 Dataset Overview

The Iris dataset contains **150 samples**, with each sample having **4 features**:
- 🌿 Sepal Length  
- 🌿 Sepal Width  
- 🌸 Petal Length  
- 🌸 Petal Width

These features are used to cluster the samples into groups using the K-Means algorithm.

---

## 🔁 Workflow Summary

1. **Load the Data**  
   - Load the Iris dataset from Kaggle or a public dataset library such as `sklearn.datasets`.

2. **Preprocess the Data**  
   - Check for missing values and normalize features if necessary.

3. **Apply K-Means Clustering**  
   - Cluster the data using the `KMeans` algorithm from Scikit-learn.

4. **Determine the Optimal Number of Clusters**  
   - Use the **Elbow Method** to find the ideal number of clusters (typically 3 for the Iris dataset).

---

## 📐 Elbow Method Explained

The **Elbow Method** is used to determine the optimal number of clusters by plotting the **Within-Cluster Sum of Squares (WCSS)** for different values of *k*.

- 📉 As the number of clusters increases, WCSS decreases.
- 🧠 The "elbow" point on the graph indicates where additional clusters don't significantly reduce WCSS.
- ✅ This point suggests the ideal number of clusters for your dataset.

---

## 🧰 Tools and Libraries

- **Python**  
- **Pandas**, **NumPy**  
- **Matplotlib**, **Seaborn**  
- **Scikit-learn** (for KMeans and dataset loading)

---

## 📂 Files in This Repository

- `kmeans_iris_clustering.ipynb` – Jupyter Notebook with complete implementation
- `README.md` – Documentation for the project
