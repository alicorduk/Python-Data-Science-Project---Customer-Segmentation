# Customer Segmentation with K-Means

A complete customer segmentation workflow using **Pandas**, **Matplotlib/Seaborn**, **StandardScaler**, **K-Means**, and **PCA**.  
The goal is to segment customers based on demographics, spending behavior, and engagement, enabling data-driven marketing strategies.

---

## 📂 Dataset
Includes customer demographic, purchase, and campaign response data.  
Example source: [Kaggle – Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) (replace if different).

---

## ⚙️ Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Run the Project
```bash
jupyter notebook Customer_Segmentation_.ipynb
```
Run all cells to reproduce the results.

---

## 🛠 Tools & Technologies
- **Languages & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Machine Learning:** K-Means Clustering, PCA (Principal Component Analysis)  
- **Data Processing:** Feature Engineering, StandardScaler, Handling Missing Values  
- **Visualization:** Histograms, KDE plots, Boxplots, Heatmaps, Scatter Plots  
- **Model Selection:** Elbow Method  
- **Environment:** Jupyter Notebook  

---

## 🔬 Workflow
1. **Data Loading & Cleaning** – Drop missing values, fix data types.
2. **Feature Engineering** – Age, Total Spending, Customer Tenure, etc.
3. **EDA** – Visualize distributions, correlations, category relationships.
4. **Feature Scaling** – StandardScaler for clustering.
5. **Modeling** – K-Means clustering, Elbow method for `k`.
6. **Visualization** – PCA for cluster separation.
7. **Cluster Profiling** – Summarize characteristics per cluster.

---

## 📸 Visual Results

### Distributions
![Age Distribution](https://github.com/alicorduk/Python-Data-Science-Project---Customer-Segmentation/blob/main/Images/Age_Distribution.png)
![Income Distribution](https://github.com/alicorduk/Python-Data-Science-Project---Customer-Segmentation/blob/main/Images/Income_Distribution.png)

### Correlation & Relationships
![Correlation Matrix](https://github.com/alicorduk/Python-Data-Science-Project---Customer-Segmentation/blob/main/Images/Coreelation_Matrix.png)
![Education Income Level](https://github.com/alicorduk/Python-Data-Science-Project---Customer-Segmentation/blob/main/Images/Education%20Level%20%3A%20income.png)
![Average Income by Education & Marital Status](https://github.com/alicorduk/Python-Data-Science-Project---Customer-Segmentation/blob/main/Images/Heatmap.png)

### Model Selection
![Elbow Method](https://github.com/alicorduk/Python-Data-Science-Project---Customer-Segmentation/blob/main/Images/Elbow_Method.png)

### Final Clusters (PCA)
![Customer Segmentation PCA](https://github.com/alicorduk/Python-Data-Science-Project---Customer-Segmentation/blob/main/Images/Customer_Segmentation(PCA).png)

---

## 📈 Features Used
- Age
- Income
- Total Spending
- Number of Web Purchases
- Number of Store Purchases
- Number of Web Visits per Month
- Recency

---

## 🚀 Next Steps
- Build a Streamlit app for live predictions  
- Implement automated cluster naming  
- Deploy as API for integration with CRM tools  

---

