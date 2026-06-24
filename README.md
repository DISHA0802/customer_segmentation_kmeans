
#  Customer Segmentation Using K-Means Clustering

## Project Overview

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their **Annual Income** and **Spending Score**.

Customer segmentation helps businesses understand customer behavior, identify target groups, and create personalized marketing strategies.

## Objectives

- Analyze customer purchasing behavior.
- Group customers into meaningful segments.
- Visualize customer clusters.
- Identify potential high-value customers.

## Dataset

**Dataset:** Mall Customer Segmentation Dataset

### Features

| Column | Description |
|----------|------------|
| CustomerID | Unique Customer ID |
| Gender | Male/Female |
| Age | Customer Age |
| Annual Income (k$) | Annual Income in Thousand Dollars |
| Spending Score (1-100) | Customer Spending Score |


##  Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn



## Project Workflow

### 1. Data Loading

- Upload dataset to Google Colab
- Load dataset using Pandas

### 2. Data Exploration

- Check shape of dataset
- View summary statistics
- Check missing values

### 3. Data Visualization

- Age vs Spending Score
- Customer behavior analysis

### 4. Feature Selection

Selected Features:

```python
Annual Income (k$)
Spending Score (1-100)
```

### 5. Elbow Method

Used to determine the optimal number of clusters.

### 6. K-Means Clustering

```python
KMeans(n_clusters=5)
```

### 7. Cluster Visualization

Visualized customer groups using scatter plots and cluster centroids.



##  Output

### Customer Segmentation Graph

The graph displays:

- Different customer segments
- Cluster centroids
- Spending behavior patterns

Example Segments:

- Premium Customers
- Budget Customers
- Average Customers
- Young High Spenders
- High Income Low Spenders

---

##  Elbow Method

The Elbow Method was used to determine the optimal number of clusters.

Optimal Value:

```text
K = 5
```



##  Results

The model successfully grouped customers into distinct segments based on spending habits and annual income.

These insights can help businesses:

- Improve customer targeting
- Design marketing campaigns
- Increase customer retention
- Optimize business strategies

## How to Run

### Google Colab

1. Open Google Colab
2. Upload `Mall_Customers.csv`
3. Run all notebook cells
4. View generated cluster visualizations

---

## Machine Learning Concepts Used

- Unsupervised Learning
- K-Means Clustering
- Elbow Method
- Data Visualization
- Customer Segmentation


