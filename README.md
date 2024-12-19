# Clustering and Classification Project

## Project Overview
This project focuses on clustering and classifying customer shopping behavior using the `shopping_behavior_updated.csv` dataset. The goal is to segment customers into clusters and build a predictive model to determine whether customers will use a promo code for their purchase.

## Steps and Methodology

### 1. **Data Preprocessing**
- Cleaned the dataset to handle missing values, outliers, and inconsistencies.
- Normalized numerical features to ensure uniform scaling.
- Encoded categorical variables where necessary.

### 2. **Exploratory Data Analysis (EDA)**
- Conducted EDA to understand data distributions, correlations, and patterns.
- Visualized key insights using histograms.

### 3. **Optimal Number of Clusters**
- Used the Silhouette Score to determine the optimal number of clusters.
- For simplicity, the presence of 2 clusters was assumed.

### 4. **Clustering Techniques**
#### **K-Means Clustering**
- Applied K-Means clustering on a PCA-transformed version of the dataset to reduce dimensionality and improve clustering performance.

#### **Hierarchical Clustering**
- Performed Agglomerative Clustering to visualize cluster formation.
- Plotted the dendrogram to assess hierarchical relationships.

#### **Visualization**
- Plotted clusters for Agglomerative Clustering and K-Means to understand customer segmentation.

### 5. **Comparison of Clustering Algorithms**
- Compared K-Means and Agglomerative Clustering based on cluster compactness and interpretability.
- **Cluster Interpretations:**
  - **Cluster 0:** Represents customers with minimal likelihood of using promo codes.
  - **Cluster 1:** Represents customers highly likely to use promo codes.

### 6. **Classification Model**
#### **Objective:** Predict whether a customer's purchase will use a promo code.

#### **Decision Tree Classification**
- Built a Decision Tree Classifier to predict promo code usage.
- Evaluated model performance using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

### 7. **Results and Insights**
- Clustering provided meaningful segmentation of customer behavior.
- The Decision Tree model achieved strong performance in predicting promo code usage.
- The combination of clustering and classification offers actionable insights for targeted marketing strategies.

