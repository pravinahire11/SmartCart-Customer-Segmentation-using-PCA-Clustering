# SmartCart-Customer-Segmentation-using-PCA-Clustering

## Project Overview

This project performs customer segmentation using machine learning clustering techniques to identify different customer groups based on their demographics, income, spending, and purchasing behavior.

## Objectives

- Clean and preprocess customer data
- Create meaningful customer features
- Reduce dimensionality using PCA
- Identify the optimal number of clusters
- Apply K-Means and Agglomerative Clustering
- Analyze and characterize customer segments

## Dataset Features

The dataset contains customer demographic, household, purchasing, and campaign-response information, including:

- Demographics: Year_Birth, Education, Marital_Status, Income
- Household: Kidhome, Teenhome
- Customer information: Dt_Customer, Recency
- Product spending: MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds
- Purchase behavior: NumDealsPurchases, NumWebPurchases, NumCatalogPurchases, NumStorePurchases
- Engagement: NumWebVisitsMonth
- Campaign/Feedback: Complain, Response
- ID: Unique customer identifier

## Methodology

1. Data Loading
2. Missing Value Handling
3. Feature Engineering
4. Outlier Treatment
5. Categorical Encoding
6. Feature Scaling
7. PCA for Dimensionality Reduction
8. Optimal K Selection using:
   - Elbow Method
   - Silhouette Score
9. Customer Clustering using:
   - K-Means Clustering
   - Agglomerative Clustering
10. Cluster Characterization and Visualization

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- PCA
- K-Means Clustering
- Agglomerative Clustering

## Project Structure

```text
smartcart-customer-segmentation/
│
├──  README.md
├── smartcart_customers.csv
└── smartcart.ipynb
