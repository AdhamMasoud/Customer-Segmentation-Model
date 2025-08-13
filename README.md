# Customer Segmentation Model

## Overview
This project demonstrates how to perform customer segmentation by combining RFM (Recency, Frequency, Monetary) analysis with clustering techniques such as K-Means. It helps businesses understand customer behavior and target marketing efforts more effectively.

---
## Features
Data preprocessing: Cleans and prepares transactional data.

RFM calculation: Computes Recency, Frequency, and Monetary features for each customer.

Data transformation: Applies scaling to normalize data.

Clustering: Uses K-Means to segment customers based on RFM scores.

Cluster evaluation: Employs metrics like Elbow Method and Silhouette Score to choose the optimal number of clusters.

Visualization: Provides insightful plots to interpret clusters and customer profiles.

Cluster profiling: Generates summaries of each cluster’s behavior for actionable insights.

---
## Dataset
The model is built and tested on the Superstore Dataset from the Kaggle.

The dataset contains detailed transactional data including invoice date, customer ID, and purchase amount.

Link to dataset: [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final?resource=download)

---
## Import libraries and load the dataset
![My Local Image](images/Capture.PNG)
---
## Preprocess the data
![My Local Image](images/Capture1.PNG)
---
## Creating boxplots for 'Quantity' and 'Sales' to identify outliers
![My Local Image](images/Capture3.PNG)
![My Local Image](images/newplot.png)
---
## Removing outliers
![My Local Image](images/Capture16.PNG)
![My Local Image](images/Capture17.PNG)
---
## Create boxplots after removing outliers
![My Local Image](images/newplot4.png)
---
## Creating RFM
![My Local Image](images/Capture7.PNG)
![My Local Image](images/Capture8.PNG)
---
## Plot RFM distributions
![My Local Image](images/Capture9.PNG)
![My Local Image](images/output.png)
---
## Standardize the data
![My Local Image](images/Capture10.PNG)
---
## Fit KMeans clustering for a range of k values and calculate inertia and silhouette scores
![My Local Image](images/Capture11.PNG)
![My Local Image](images/output1.png)
---
## Fit KMeans with the optimal number of clusters (k=3 in this case)
![My Local Image](images/Capture12.PNG)
---
## Assigning cluster names
![My Local Image](images/Capture13.PNG)
![My Local Image](images/Capture14.PNG)
---
## Creating a 3D scatter plot for RFM segmentation
![My Local Image](images/Capture15.PNG)
![My Local Image](images/newplot3.png)

---
## Summary

## 1. Platinum Customers 🏆

Behavior: Extremely loyal, frequent purchases, and the highest total spend.

Loyalty: Very high — short recency, high frequency, high monetary value.

Engagement Strategy:

Exclusive early access to new products.

VIP loyalty programs.

Personalized recommendations and premium support.

## 2. Gold Customers 🥇

Behavior: Regular buyers with good spending habits, but slightly less frequent or lower spend than Platinum.

Loyalty: High — moderate recency, good frequency, high monetary value.

Engagement Strategy:

Targeted upselling and cross-selling campaigns.

Seasonal discounts or bundle offers to encourage more frequent purchases.

Invitations to special promotions to encourage transition to Platinum tier.

## 3. Silver Customers 🥈

Behavior: Occasional buyers, moderate spend, may need reactivation campaigns.

Loyalty: Medium — longer recency, lower frequency, moderate monetary value.

Engagement Strategy:

Email reminders and personalized discount codes.

Incentives like free shipping to encourage more purchases.

Customer surveys to understand potential barriers to buying

---
## Reference

Unlocking Customer Segmentation Insights — Combining RFM Analysis with K-Means Clustering
[Customer Segmentation Insights](https://ishla.medium.com/unlocking-customer-segmentation-insights-combining-rfm-analysis-with-k-means-clustering-45bdc6bf8555)  


