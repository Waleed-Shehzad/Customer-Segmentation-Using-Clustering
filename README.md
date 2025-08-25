# Customer Segmentation Using Clustering

This project applies unsupervised learning techniques to segment mall customers based on their demographics and spending patterns. The goal is to identify distinct customer groups that can help businesses develop targeted marketing strategies.

---

## 📊 Dataset
- **Source:** [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- **File Used:** `Mall_Customers.csv`  
- **Features:**
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🔧 Methodology
1. **Data Preprocessing**
   - Checked for missing values and duplicates.
   - Selected relevant features (`Age`, `Annual Income`, `Spending Score`).
   - Applied `StandardScaler` for normalization.

2. **Clustering**
   - Applied **K-Means clustering** with different values of `k`.
   - Used **Elbow Method** and **Silhouette Score** to find the optimal number of clusters.

3. **Dimensionality Reduction**
   - Applied **PCA** (2D) for visualization of clusters.

4. **Analysis**
   - Generated cluster profiles based on mean values of features.
   - Visualized cluster distribution.

---

## 📈 Visualizations
- Elbow Method graph
- Silhouette Score vs. k
- PCA-based 2D cluster scatter plot
- Cluster size bar chart

---

## 🛠️ Libraries Used
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

---

## 🚀 Results & Insights
- The model identifies **distinct customer groups** with varying age, income, and spending habits.
- Businesses can use this segmentation to tailor **personalized marketing campaigns**.

---
