E-commerce Customer Segmentation (RFM & K-Means)

Project Overview

This project focuses on identifying distinct customer segments for a UK-based online retail store. By analyzing transactional data, the goal is to group customers based on their purchasing behavior using RFM Analysis (Recency, Frequency, Monetary) and Machine Learning (K-Means Clustering).

This allows the marketing team to target VIP clients, re-engage at-risk customers, and optimize promotional budgets.

Data Source

The dataset used is the official Online Retail Dataset from the UCI Machine Learning Repository, containing over 500,000 transactions.

Methodology

Data Cleaning: Handled missing Customer IDs, filtered out cancelled orders (negative quantities), and calculated the total revenue per transaction.

RFM Aggregation: Grouped the transactional data at the customer level to calculate:

Recency: Days since the last purchase.

Frequency: Total number of distinct orders.

Monetary: Total money spent by the customer.

Machine Learning (K-Means):

Applied log transformation and standardization (StandardScaler) to handle the right-skewed data.

Utilized the K-Means algorithm to automatically group customers into 4 distinct business segments.

Interactive Visualization: Deployed Plotly to create an interactive 3D scatter plot of the clusters.

Tech Stack

Python (Core logic)

pandas (Data manipulation and aggregation)

scikit-learn (Data preprocessing and K-Means clustering)

plotly (Interactive 3D data visualization)
