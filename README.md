# Customer Segmentation using K-Means Clustering

## Project Overview

This project segments customers based on purchasing behaviour using the K-Means clustering algorithm. The customers are classified as Loyal Customers, Inactive Customers, Average Customers and VIP Customers. This helps to identify the different customer groups and derive business insights to employ targeted marketing strategies. 

---

## Features

- Data Cleaning
- Feature Selection
- Standardization
- Elbow Method
- K-Means Clustering
- Customer Segmentation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Dataset
This project uses the **Customer Segmentation : Clustering** dataset from Kaggle.

**Source:** https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis](https://www.kaggle.com/datasets/vishakhdapat/customer-segmentation-clustering

Customer Personality Analysis involves a thorough examination of a company's optimal customer profiles. This analysis facilitates a deeper understanding of customers, enabling businesses to tailor products to meet the distinct needs, behaviors, and concerns of various customer types.
The dataset contains:

- Id: Unique identifier for each individual in the dataset.
- Year_Birth: The birth year of the individual.
- Education: The highest level of education attained by the individual.
- Marital_Status: The marital status of the individual.
- Income: The annual income of the individual.
- Kidhome: The number of young children in the household.
- Teenhome: The number of teenagers in the household.
- Dt_Customer: The date when the customer was first enrolled or became a part of the company's database.
- Recency: The number of days since the last purchase or interaction.
- MntWines: The amount spent on wines.
- MntFruits: The amount spent on fruits.
- MntMeatProducts: The amount spent on meat products.
- MntFishProducts: The amount spent on fish products.
- MntSweetProducts: The amount spent on sweet products.
- MntGoldProds: The amount spent on gold products.
- NumDealsPurchases: The number of purchases made with a discount or as part of a deal.
- NumWebPurchases: The number of purchases made through the company's website.
- NumCatalogPurchases: The number of purchases made through catalogs.
- NumStorePurchases: The number of purchases made in physical stores.
- NumWebVisitsMonth: The number of visits to the company's website in a month.
- AcceptedCmp3: Binary indicator (1 or 0) whether the individual accepted the third marketing campaign.
- AcceptedCmp4: Binary indicator (1 or 0) whether the individual accepted the fourth marketing campaign.
- AcceptedCmp5: Binary indicator (1 or 0) whether the individual accepted the fifth marketing campaign.
- AcceptedCmp1: Binary indicator (1 or 0) whether the individual accepted the first marketing campaign.
- AcceptedCmp2: Binary indicator (1 or 0) whether the individual accepted the second marketing campaign.
- Complain: Binary indicator (1 or 0) whether the individual has made a complaint.
- Z_CostContact: A constant cost associated with contacting a customer.
- Z_Revenue: A constant revenue associated with a successful campaign response.
- Response: Binary indicator (1 or 0) whether the individual responded to the marketing campaign.

**Features used for RFM analysis**

- **Recency:** `Recency`
- **Frequency:** Sum of `NumDealsPurchases`, `NumWebPurchases`, `NumCatalogPurchases`, and `NumStorePurchases`
- **Monetary:** Total spending calculated as the sum of `MntWines`, `MntFruits`, `MntMeatProducts`, `MntFishProducts`, `MntSweetProducts`, and `MntGoldProds`
---

## Customer Segments

VIP Customers - High spending and frequent buyers
Loyal Customers - High spending moderately repeat customers 
Average Customers - Moderate purchasing behaviour 
Inactive Customers - Low spending and infrequent purchases 

---


## Author

**Reva Kulkarni**

