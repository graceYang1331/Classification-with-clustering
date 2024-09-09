# Business use case
Determine which new customers are likely to churn, or which marketing strategies are needed for different customers, based on their purchases.

# Data
Open source retail customers data, contains purchasing history, with items and orders. 

# Target
Using historical customer purchasing data to predict new customer's shopping behavious, i.e predicting new customer's segmentation based on first 3 or less orders. 

# Clustering
## Product clustering
Use word tokens to do product description encoding, and segment the products.
## Customer clustering
Apply k means clustering on customers, including features derived from product segments, and assign a cluster to each customers. Use the cluster as a target lable for classification.

