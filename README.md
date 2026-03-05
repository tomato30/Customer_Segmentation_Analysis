# Customer Segmentation using RFM Analysis and K-Means

## Project Overview

This project performs customer segmentation on an e-commerce dataset using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering.

The goal is to identify different types of customers so businesses can apply targeted marketing strategies and improve customer retention.

---

## Dataset

Online Retail Dataset containing real e-commerce transactions.

Features used:

* CustomerID
* InvoiceDate
* InvoiceNo
* Quantity
* UnitPrice

---

## Methodology

1. Data Cleaning

   * Removed missing CustomerID values
   * Removed returned orders (negative quantity)

2. Feature Engineering

   * Created TotalPrice
   * Calculated RFM metrics

3. Feature Scaling

   * StandardScaler applied to normalize features

4. Clustering

   * K-Means clustering applied
   * Optimal clusters chosen using Elbow Method

5. Customer Segmentation

![](/ClusterGroup.png)
   * VIP Customers --> Cluster 2
   * Loyal Customers --> Cluster 0
   * Potential Customers --> Cluster 3
   * Lost Customers --> Cluster 1

---

## Visualizations

### Customer distribution across segments
![](/customer_distribution.png)
### Customer segmentation scatter plot
![](/segmentation_scatter.png)

---

## Business Insights

* VIP customers generate the highest revenue.
* Loyal customers purchase frequently and can be nurtured into VIP customers.
* Potential customers require marketing engagement.
* Lost customers may need win-back campaigns.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

