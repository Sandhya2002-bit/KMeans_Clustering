# 🛍️ Customer Segmentation using KMeans Clustering

## 📌 Overview
This project applies KMeans Clustering on customer data to segment them into distinct groups based on their **Annual Income** and **Spending Score**. This is a common unsupervised machine learning technique used in marketing to understand customer behavior and improve business strategy.

## 📂 Dataset
- Dataset Source: [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- Features Used:
  - `CustomerID`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

## 🧠 Techniques Used
- Exploratory Data Analysis (EDA)
- Feature Scaling using StandardScaler
- KMeans Clustering
- Elbow Method to find optimal number of clusters
- Cluster Profiling using `groupby`
- 2D & 3D Visualizations (Seaborn, Matplotlib)

## 🗂️ Project Structure
customer-segmentation/
│
├── customer_segmentation.ipynb # Jupyter Notebook with code & analysis
├── requirements.txt # Python dependencies
└── README.md # Project overview and instructions


## 🖼️ Visualizations
- Elbow Plot to choose number of clusters
- 2D scatter plots of clusters
- 3D plot (optional): Age vs Income vs Spending Score

## 📈 Cluster Summary
Each cluster is profiled based on average income, age, and spending:
- **Cluster 0**: Older customers with moderate income and low spending
- **Cluster 1**: Young customers with high spending — high-priority target
- **Cluster 2**: Mature, moderate spenders — stable group
- **Cluster 3**: Young, high-income, high spenders — premium segment

## ✅ Conclusion
Customer segmentation helps personalize marketing, improve customer engagement, and drive business growth.

## 🚀 Future Work
- Try other clustering algorithms (DBSCAN, Hierarchical)
- Include additional behavioral features
- Build an interactive dashboard for customer insights

---

## 🧪 How to Run
1. Clone this repository
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
