# ZEOTAP-ASSIGNMENT
Assignment for the company Zeotap.

---

## Overview

This project uses a simulated eCommerce transactions dataset to derive business insights, build predictive models, and segment customers. The objective is to showcase skills in data analysis, machine learning, and generating actionable insights.

---

## Dataset Description

The dataset consists of three files:

1. **Customers.csv**
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Continent where the customer resides.
   - `SignupDate`: Date when the customer signed up.

2. **Products.csv**
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price in USD.

3. **Transactions.csv**
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.
   - `Price`: Price of the product sold.

---

## Tasks

### Task 1: Exploratory Data Analysis (EDA)
- **Objective**: Derive meaningful business insights from the dataset.
- **Deliverables**:
  - A Jupyter Notebook containing the EDA code.
  - A PDF report summarizing the insights.

### Task 2: Lookalike Model
- **Objective**: Build a model that recommends 3 similar customers for a given user based on profile and transaction history.
- **Deliverables**:
  - A Jupyter Notebook explaining the model development.
  - A `Lookalike.csv` file containing recommendations for customers C0001–C0020.

### Task 3: Customer Segmentation / Clustering
- **Objective**: Perform customer segmentation using clustering techniques and evaluate clustering quality.
- **Deliverables**:
  - A Jupyter Notebook with clustering code.
  - A PDF report summarizing:
    - The number of clusters formed.
    - DB Index value and other metrics.
    - Visualizations of clusters.

---

## Deliverables

- **Jupyter Notebooks**:
  - `EDA.ipynb`: Exploratory Data Analysis.
  - `Lookalike.ipynb`: Lookalike Model implementation.
  - `Clustering.ipynb`: Customer Segmentation/Clustering.

- **Reports**:
  - `EDA_Report.pdf`: Summary of business insights.
  - `Clustering_Report.pdf`: Clustering results and metrics.

- **CSV Files**:
  - `Lookalike.csv`: Recommendations for similar customers.

---
