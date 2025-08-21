# CosmiCodeInternship_CustomerSegmentation
# 🛍️ Customer Segmentation using Machine Learning  

## 📌 Project Overview  
Organizations often face challenges in identifying the right customer segments, which leads to **ineffective marketing strategies, low engagement, and missed revenue opportunities**.  

This project applies **unsupervised machine learning algorithms** to segment customers based on **Annual Income** and **Spending Score**, providing valuable insights to optimize business strategies.  

We primarily use **K-Means Clustering** and compare it with **DBSCAN (Density-Based Clustering)** to identify unique customer groups and spending patterns.  

---

## 🎯 Problem Statement  
Businesses struggle to determine the correct target audience due to **poor segmentation**. This project addresses the issue by:  
- Segmenting customers into meaningful clusters.  
- Identifying **high-value vs. low-value** customer groups.  
- Providing insights for **targeted marketing and personalized strategies**.  

---

## 🎯 Objectives  
- Perform **Exploratory Data Analysis (EDA)** on `Mall_Customers.csv`.  
- Apply **K-Means clustering** with optimal cluster detection (using the **Elbow Method**).  
- Compare results with **DBSCAN** to detect non-linear patterns and outliers.  
- Visualize customer segments through **scatter plots, pair plots, and heatmaps**.  
- Calculate **average expenditure per cluster** for business insights.  

---

## 🛠️ Tools & Technologies  
- **IDE/Notebook:** VS Code, Jupyter Notebook  
- **Language:** Python  

### 📚 Libraries Used  
- **Pandas** → Data handling  
- **Matplotlib & Seaborn** → Data visualization  
- **Scikit-learn** → Clustering algorithms (K-Means, DBSCAN), scaling  

---

## 📂 Dataset  
Dataset: **`Mall_Customers.csv`** (Kaggle)  

**Attributes:**  
- `CustomerID` → Unique identifier  
- `Gender` → Male / Female  
- `Age` → Age of customer  
- `Annual Income (k$)` → Annual income in thousands  
- `Spending Score (1-100)` → Assigned score based on customer spending behavior  

> **Note:** We primarily utilize **Annual Income** and **Spending Score** for clustering.  

---

## 🔑 Key Features  

### 🔎 Exploratory Data Analysis (EDA)  
- Dataset structure & summary statistics  
- Correlation Heatmap for attribute relationships  

### ⚡ Feature Selection & Scaling  
- Selected **Annual Income** & **Spending Score**  
- Standardized data with **StandardScaler()**  

### 📊 Customer Segmentation with K-Means  
- Used **Elbow Method** to find the optimal number of clusters (**6**)  
- Divided customers into recognizable groups  
- Visualized results with **scatter plots**  

### 🔍 Customer Segmentation with DBSCAN  
- Detected **non-linear clusters** and **outliers**  
- Compared clustering results with K-Means  

### 📈 Cluster Analysis & Insights  
- Calculated **average income per cluster**  
- Identified customer profiles like:  
  - High-income, high-spending customers  
  - Low-income, low-spending customers  

### 🎨 Visualizations  
- **Heatmaps** for correlations  
- **Scatter plots** for K-Means & DBSCAN clusters  
- **Pair plots** for multi-variable visualization  

---

## 🚀 Steps & Workflow  

1. **Import Libraries**  
2. **Load Dataset**  
3. **Perform EDA** → Dataset info, summary stats, correlations  
4. **Feature Selection & Scaling**  
5. **Apply K-Means Algorithm** → Optimal cluster detection (Elbow Method)  
6. **Cluster Visualization** → Scatter plots  
7. **Apply DBSCAN Algorithm** → Outlier detection  
8. **Calculate Average per Cluster**  
9. **Pair Plot Visualization**  

---

## 📊 Sample Outputs  

- 📌 **Correlation Heatmap**  
- 📌 **K-Means Cluster Scatter Plot**  
- 📌 **Optimal Cluster Visualization (Elbow Method)**  
- 📌 **DBSCAN Cluster Plot**  
- 📌 **Pair Plot of Customer Segments**  

---

## 📢 Insights & Business Use Cases  
✔️ Helps businesses design **targeted marketing campaigns**.  
✔️ Identifies **high-value customers** for premium services.  
✔️ Detects **low-engagement customers** for retention strategies.  
✔️ Provides data-driven insights for **personalized offers**.  

---

## 📎 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/Malaika23-ntu-cs-1291/customer-segmentation.git
   cd customer-segmentation
2.Install dependencies:

pip install pandas matplotlib seaborn scikit-learn



3.Run the Jupyter Notebook:

jupyter notebook


4.Open Customer_Segmentation.ipynb and execute cells.
