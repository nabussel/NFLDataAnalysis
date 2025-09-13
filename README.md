# 🏈 NFL Combine Clustering Analysis (2008–2022)

This project applies **unsupervised machine learning** techniques to **NFL Combine data (2008–2022)** in order to identify performance-based player archetypes. By leveraging **K-means clustering** and **Principal Component Analysis (PCA)**, the analysis uncovers distinct groups of athletes based solely on **physical and athletic metrics** — without using position labels.

The goal is to demonstrate how machine learning can reveal **hidden patterns** in sports performance data, with potential applications in **scouting, player evaluation, and strategy development**.

---

## Key Findings
- **Optimal clustering at k = 2**, validated with both the **Elbow** and **Silhouette** methods  
- **Two distinct athletic archetypes emerged**:  
  - **Cluster 1:** Speed & agility profiles (e.g., WR, CB, S)  
  - **Cluster 2:** Size & strength profiles (e.g., TE, LB, QB)  
- **Strong alignment with real-world positions** despite position labels being excluded  
- **PCA and radar plots** provided clear interpretation of cluster separation  

---

## Tools & Technologies
- **Python**  
- **Pandas, NumPy** – data preprocessing  
- **Scikit-learn** – K-means clustering, PCA, feature scaling  
- **Matplotlib, Seaborn** – data visualization  

---

## Repository Contents
- `NFL_Combine_Clustering_Report.pdf` – Full project report with methodology, results, and visualizations  
- Source code notebooks and scripts for:
  - Data preprocessing  
  - Clustering and PCA  
  - Visualization (radar plots, PCA scatter plots, evaluation metrics)  

---

## Project Highlights
- Showcases the **power of unsupervised learning** in sports analytics  
- Provides a **data-driven approach** to grouping athletes without bias from position labels  
- Demonstrates end-to-end workflow: **data preparation → clustering → evaluation → visualization**  

