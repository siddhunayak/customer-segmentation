# Customer Segmentation using K-Means Clustering

# Shopping Customer Segmentation

## Problem Statement
Understand the Target Customers for the marketing team to plan a strategy.
Understand the Target Customers for the marketing team to plan a strategy.

## Objective
### Market Segmentation
Divide the mall target market into approachable groups.

Create subsets of a market based on demographic and behavioral criteria to better understand the target for marketing activities.

## The Approach
1. Perform a quick EDA (Exploratory Data Analysis).
2. Use the K-Means Clustering Algorithm to create our segments.
3. Use Summary Statistics on the clusters.
4. Visualize.

## Objective
### Market Segmentation
Divide your mall target market into approachable groups. Create subsets of a market based on demographic and behavioral criteria to better understand the target for marketing activities.

## Context
The stakeholders want to identify the most important shopping groups based on income, age, and the mall shopping score. They also want to identify the ideal number of groups with a label for each.

## Overview
This project performs customer segmentation using K-Means clustering on the Mall Customers dataset. The goal is to group customers based on their spending behavior and annual income.

## Dataset
The dataset used is `Mall_Customers.csv`, which contains the following attributes:
- `CustomerID`: Unique ID for each customer
- `Gender`: Male or Female
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income in thousands of dollars
- `Spending Score (1-100)`: Score assigned based on customer behavior

## Project Structure
```
├── Clustering.csv                  # Final dataset with cluster labels
├── clustering_bivariate.png         # Cluster visualization plot
├── Mall_Customers.csv               # Original dataset
├── mall clustering project.py             # Python script for clustering
├── README.md                        # Project documentation
```

## Dependencies
Ensure you have the following Python libraries installed before running the script:
```sh
pip install pandas numpy seaborn matplotlib scikit-learn
```

## Analysis
### Target Cluster
Target group would be **Cluster 1**, which has a high Spending Score and high income.

- **54% of Cluster 1 shoppers are women.** We should look for ways to attract these customers using a marketing campaign targeting popular items in this cluster.  
- **Cluster 2 presents an interesting opportunity** to market to the customers for sales events on popular items.






