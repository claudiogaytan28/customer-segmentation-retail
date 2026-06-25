# Customer Segmentation in Retail Transactions

Identifying customer behavior patterns in retail transaction data using
clustering, in order to generate actionable, business-oriented insights.

## Problem

Retail companies often treat every customer the same way, even though
purchasing behavior varies widely across their customer base. Not every
customer responds to promotions in the same way, generates the same value,
or buys with the same frequency. This project answers a simple but
high-impact question: **what types of customers exist within this retail
business, based on their actual purchasing behavior?**

## Approach

1. Data cleaning
2. Customer-level feature engineering (transactions, spend, discount and
   promotion usage)
3. Feature scaling
4. KMeans clustering (k selected via the elbow method)
5. PCA for visualization
6. Cluster interpretation

## Key findings

- **Average ticket size is stable across all segments (~$52)** — the real
  differentiator between customers is purchase frequency, not basket size.
- **Five distinct customer profiles emerged**, ranging from infrequent,
  discount-driven buyers to highly loyal, high-frequency customers who
  account for disproportionately more revenue.
- **Business implication:** retention and purchase frequency — not average
  ticket size — are the most promising levers for increasing customer value.

## Tools

Python · pandas · scikit-learn · matplotlib

## Notebook

[View full notebook →](./01_customer_segmentation.ipynb)
