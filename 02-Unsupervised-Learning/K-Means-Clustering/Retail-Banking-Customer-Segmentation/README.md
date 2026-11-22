# Retail Banking Customer Segmentation

## Project Overview

This project analyzes the credit card usage patterns of 8,950 customers to identify meaningful customer groups using unsupervised machine learning.

The goal is to understand differences in customer spending, cash-advance usage, outstanding balances, and repayment behavior.

## Dataset

- **Source:** [Credit Card Dataset for Clustering — Kaggle](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata)
- **Records:** 8,950 customers
- **Original columns:** 18

## Analysis

The project covers data cleaning, exploratory data analysis, feature selection, preprocessing, and customer segmentation using K-Means clustering.

Hierarchical Clustering and PCA will be explored in later stages.

## K-Means Results

Five customer segments were identified:

| Segment | Customers |
|---|---:|
| High Credit Users | 1,641 |
| Cash-Advance Users | 2,195 |
| Regular Purchasers | 2,491 |
| Low-Activity Customers | 1,338 |
| Frequent Full-Payment Customers | 1,285 |

These segments provide a starting point for understanding different customer behaviors and exploring relevant banking services.

## Project Files

- `notebooks/` — Jupyter notebooks containing the analysis
- `reports/` — Business analysis reports
- `docs/` — Technical explanations and revision material

## Project Status

K-Means clustering completed. Further clustering methods and dimensionality reduction will be added as the project progresses.
