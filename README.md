
Our task is to perform an **entity resolution**, also known as record linkage, on Retailer A and Retailer B's datasets. 

Those Retailers have started working together and the goal is to identify which products in Retailer B's dataset are also products of Retailer A.

This would allow the marketing department to create more personalized product offering campaigns and product indexes.

The K-Means-DDB-03-RecordLinkage.ipynb and the DBSCAN-DDB-03-RecordLinkage.ipynb were uploaded using two different approaches. On the first one, we applied the K-means algorithm using the score value to cluster by both retailerA and RetailerB's products in order to analyze the gap prices between both them. Meanwhile on the second notebook, we imported the dataset (matches_df.xlsx) obtained after cleaning and applying the Entity Matching to visually analyze the obtained clusters.
