# Credit Card Analysis: Feature Selection & Clustering

This repository demonstrates a data science workflow on credit card datasets, divided into two main phases: Feature Selection and Clustering Analysis.

## 📂 Project Structure

The project is split into two notebooks:

1. **[Feature_creditcard.ipynb](./Feature_creditcard.ipynb) (Feature Engineering)**
   * Focuses on **Domain Understanding** and data exploration.
   * Performs feature selection to identify the most relevant variables for modeling.
   * Prepares the cleaned dataset for further analysis.

2. **[Cluster_creditcard.ipynb](./Cluster_creditcard.ipynb) (Clustering Analysis)**
   * Implements **Unsupervised Learning** to find patterns in the data.
   * **Techniques used:** * Data Normalization (StandardScaler)
     * Dimensionality Reduction (PCA)
     * K-Means Clustering
   * **Evaluation:** Uses the Elbow Method and Silhouette Score to determine the optimal number of clusters.

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## 🚀 How to Use
1. Start with `Feature_creditcard.ipynb` to understand the feature selection process.
2. Follow up with `Cluster_creditcard.ipynb` to see how those features are used to group the data into meaningful clusters.

---
*Developed as part of a Machine Learning study on data-driven insights.*
