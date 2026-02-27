# Customer Segmentation using KMeans and DBSCAN

## 📊 Project Overview
This project performs customer segmentation on wholesale spending data using two clustering algorithms:
- KMeans
- DBSCAN

The objective is to analyze customer purchasing behavior across multiple product categories and compare clustering approaches.

---

## 📂 Dataset
The dataset contains annual spending for wholesale customers across six product categories:

- Fresh
- Milk
- Grocery
- Frozen
- Detergents_Paper
- Delicassen

Total records: 440 customers

---

## 🔍 Project Workflow

1. Exploratory Data Analysis (EDA)
2. Skewness detection and log transformation
3. Feature standardization
4. KMeans clustering
5. DBSCAN clustering
6. PCA visualization
7. Cluster profiling
8. Algorithm comparison

---

## 📈 Results

- KMeans produced stable clusters with moderate separation.
- DBSCAN detected density-based groups and identified noise points.
- Silhouette scores indicate overlapping but meaningful customer segments.

---

## 🧠 Key Insights

- Cluster 0: Grocery & Detergent-heavy customers
- Cluster 1: Fresh-product-focused customers
- Cluster 2: High-volume diversified buyers

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
