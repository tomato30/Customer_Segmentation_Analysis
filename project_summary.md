Project Summary: Customer Segmentation using RFM and K-Means

Objective

The objective of this project is to segment e-commerce customers based on their purchasing behavior using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering. This helps businesses understand different types of customers and apply targeted marketing strategies.

Dataset

The project uses the Online Retail dataset containing over 500,000 e-commerce transactions including customer purchases, invoice details, and product information.

Key Steps

1. Data Cleaning
   
   - Removed missing CustomerID values
   - Removed product returns (negative quantity)

2. Feature Engineering
   
   - Created TotalPrice column
   - Generated RFM metrics for each customer

3. Feature Scaling
   
   - Applied StandardScaler to normalize Recency, Frequency, and Monetary features

4. Clustering
   
   - Used K-Means clustering for customer segmentation
   - Determined optimal clusters using the Elbow Method

5. Visualization
   
   - Customer distribution across segments
   - Scatter plot showing customer segments

Results

The model segmented customers into four groups:

- VIP Customers – High frequency and high spending customers
- Loyal Customers – Frequent buyers with moderate spending
- Potential Customers – Occasional buyers who may become loyal
- Lost Customers – Customers who have not purchased recently

Business Impact

Customer segmentation helps businesses:

- Improve targeted marketing campaigns
- Increase customer retention
- Identify high-value customers
- Optimize marketing budget

Tools & Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
