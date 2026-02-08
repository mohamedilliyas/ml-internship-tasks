# Task 2: Customer Segmentation (Mall Customers)

## Objective
Group mall customers into meaningful segments using **K-Means clustering** based on **Annual Income** and **Spending Score**.

## Dataset
- **Source**: [Mall Customer Segmentation Data (Kaggle)](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Key features used**: Annual Income (k$), Spending Score (1-100)

## What I did
- Exploratory Data Analysis
- Feature scaling (StandardScaler)
- Determined optimal number of clusters using **Elbow Method** and **Silhouette Score**
- Applied K-Means clustering (k=5)
- Visualized customer segments
- Analyzed average income & spending per cluster

## Results
- Found **5 distinct customer groups**
- Clear visual separation in 2D scatter plot
- Identified high-value customers, careful spenders, etc.

## How to run
```bash
pip install -r requirements.txt
jupyter notebook Task2_Customer_Segmentation.ipynb