# ProdigyInfoTech_Task2

# Customer Segmentation using K-means Clustering

## Objective

This project aims to create a K-means clustering algorithm to group customers of a retail store based on their purchase history. The dataset used is the [Mall_Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python), which includes features such as Customer ID, Gender, Age, Annual Income, and Spending Score.

## Overview

The provided Jupyter Notebook (`KmeansCLustering.ipynb`) demonstrates the process of customer segmentation using K-means clustering. The notebook is designed to be run in a Google Colab environment.

## Dataset

- **Mall_Customers.csv:** Contains the following features:
  1. Customer_id - Customer Id
  2. Gender - Gender of the Customer
  3. Age - Age of the Customer
  4. Annual Income (k$) - Customer's Annual Income
  5. Spending Score (1-100) - Customer's Spending Score

## Getting Started

1. Open the Jupyter Notebook in a Google Colab environment using [this link](https://colab.research.google.com/drive/16hK-TF_Pmc8jQGTU0P9xJWwXItFjC50G).

2. Run the cells in the notebook to execute the K-means clustering algorithm.

3. Adjust the optimal number of clusters based on the Elbow method graph generated in the notebook.

## Dependencies

Ensure you have the necessary libraries installed:

```bash
pip install pandas numpy matplotlib scikit-learn
```

Results
The notebook generates a 3D scatter plot visualizing the clusters based on the selected features. The number of clusters can be adjusted based on the Elbow method, providing insights into customer segmentation.
