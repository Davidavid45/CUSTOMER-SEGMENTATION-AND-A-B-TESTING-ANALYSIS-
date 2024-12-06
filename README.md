# Customer Segmentation and A/B Testing Analysis

## Overview

This project focuses on customer segmentation and A/B testing to better understand customer behavior and determine the effectiveness of targeted marketing campaigns. Using unsupervised learning techniques and statistical analysis, we identified distinct customer groups and measured the impact of a promotional discount.

### Objective

The primary goal is to segment customers based on purchasing behavior and evaluate the effect of a 10% discount on different customer segments to optimize engagement and sales.

## Methodology

Data Preparation & Feature Engineering: Prepared the data by cleaning missing values and engineered key features like average order value, total orders, and purchase recency.

Principal Component Analysis (PCA): Applied PCA for dimensionality reduction, simplifying the feature space for clustering.

K-Means Clustering: Used the elbow method to determine the optimal number of clusters and segmented customers into 4 distinct groups.

A/B Testing: Conducted A/B testing to compare the effect of a 10% discount on specific segments, analyzing metrics like average order value and total orders.

## Key Insights

High Value, Frequent Shoppers were highly responsive to discounts, leading to a statistically significant increase in order value and total orders.

Low Value, Dormant Shoppers did not show significant improvement, suggesting a different approach might be more suitable for re-engagement.

Technologies Used

Python: Data processing, clustering (using scikit-learn), A/B testing (using scipy).

Tableau: Visualizations to present the distribution of customer segments, average order values, and total orders.

Repository Structure

notebooks/: Contains the Jupyter notebooks used for data preparation, clustering, and A/B testing analysis.

reports/: Includes the project report detailing the methodology, results, and recommendations.

visualizations/: Tableau visualizations used to summarize insights.

Results

Increased Engagement: High-value shoppers showed a significant response to discounts, driving higher average order values.

Actionable Insights: Provided recommendations for targeted promotions for different customer segments to maximize ROI.

How to Run

Clone the repository.

Run the Jupyter notebook in the notebooks/ folder to replicate the clustering and A/B testing analysis.

Check the Tableau files in visualizations/ for interactive insights.
