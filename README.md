# Customer-Segmentation-using-Clustering-Algorithms

This repository contains customer segmentation projects using two popular unsupervised machine learning algorithms:

- K-Means Clustering
- Agglomerative Hierarchical Clustering

The objective is to group mall customers based on their purchasing behavior and annual income, helping businesses identify distinct customer segments for targeted marketing strategies.

---

## Dataset

The dataset used is the **Mall Customers Dataset**, which contains information about customers visiting a shopping mall.

### Features

| Feature | Description |
|----------|-------------|
| CustomerID | Unique customer identifier |
| Gender | Male/Female |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1-100) | Score assigned based on customer spending behavior |

---

## Project Files

### 1. Mall_Customers_Clustering_using_K_Means.ipynb

This notebook performs:

- Data preprocessing
- Feature selection
- Elbow Method for optimal cluster selection
- K-Means clustering implementation
- Cluster visualization
- Customer segmentation analysis

### Techniques Used

- K-Means Clustering
- Elbow Method
- Data Visualization using Matplotlib

---

### 2. Mall_Customers_using_Agglomerative_Clustering.ipynb

This notebook performs:

- Data preprocessing
- Hierarchical clustering
- Dendrogram generation
- Agglomerative clustering implementation
- Cluster visualization
- Customer segmentation analysis

### Techniques Used

- Agglomerative Hierarchical Clustering
- Dendrogram Analysis
- Data Visualization using Matplotlib and SciPy

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- SciPy
- Jupyter Notebook

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Anshif912/Mall-Customers-Clustering.git
```

Move into the project directory:

```bash
cd Mall-Customers-Clustering
```

Install required packages:

```bash
pip install numpy pandas matplotlib scikit-learn scipy
```

---

## Results

The clustering algorithms successfully segment customers into different groups based on income and spending patterns.

Example customer segments include:

- High Income – High Spending
- High Income – Low Spending
- Low Income – High Spending
- Low Income – Low Spending
- Average Customers

These insights can help businesses develop personalized marketing strategies and improve customer engagement.

---

## Visualizations

The project includes:

- Elbow Method Graph
- Cluster Scatter Plots
- Dendrogram
- Hierarchical Cluster Visualization

---

## Learning Outcomes

Through this project, the following concepts are explored:

- Unsupervised Machine Learning
- Customer Segmentation
- K-Means Clustering
- Hierarchical Clustering
- Dendrogram Interpretation
- Data Visualization

---

## Author

**Anshif H**

Machine Learning and Data Science Enthusiast

---
