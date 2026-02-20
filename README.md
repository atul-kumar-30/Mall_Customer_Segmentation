# 🛍 Mall Customer Segmentation using K-Means & PCA

## 📌 Project Overview
This project applies **unsupervised machine learning** techniques to segment mall customers into distinct groups based on their demographic and spending behavior.

The goal is to identify meaningful customer clusters that can help businesses design targeted marketing strategies.

---

## 📊 Dataset
The dataset contains customer information including:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

Since there are no predefined labels, clustering techniques were used.

---

## 🧠 Methods Used

### 1️⃣ Data Preprocessing
- Selected relevant features (Age, Annual Income, Spending Score)
- Standardized the data using StandardScaler

### 2️⃣ K-Means Clustering
The Elbow Method was used to determine the optimal number of clusters.

K-Means minimizes the Within-Cluster Sum of Squares (WCSS):

WCSS = Σ Σ ||x - μ||²

Where:
- x = data point  
- μ = cluster centroid  

Optimal number of clusters selected: **K = 5**

### 3️⃣ PCA (Principal Component Analysis)
PCA was applied to reduce dimensionality and visualize clusters in 2D space.

---

## 📈 Results

Five distinct customer segments were identified:

1. High Income – High Spending (Premium Customers)
2. High Income – Low Spending (Careful Wealthy Customers)
3. Low Income – High Spending (Impulsive Buyers)
4. Low Income – Low Spending (Budget Customers)
5. Moderate Income – Moderate Spending (Average Customers)

Cluster visualization confirms clear separation between groups.

---

## 💡 Business Insights

- 🎯 Premium customers → Loyalty programs & luxury offers
- 💰 Careful wealthy customers → Personalized marketing
- 🛒 Impulsive buyers → Promotional campaigns
- 💸 Budget customers → Discounts & affordable options

Customer segmentation helps improve marketing efficiency and profitability.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 How to Run

1. Clone the repository:
