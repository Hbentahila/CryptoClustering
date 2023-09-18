# CryptoClustering
Challenge Module 19

# Instructions

## Prepare the Data

 - Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
 - Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

## Find the Best Value for k Using the Original Scaled DataFrame

 - Use the elbow method to find the best value for k.

## Cluster Cryptocurrencies with K-means Using the Original Scaled Data

## Optimize Clusters with Principal Component Analysis

 - Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.

## Find the Best Value for k Using the PCA Data

 - Use the elbow method on the PCA data to find the best value for k.

## Cluster Cryptocurrencies with K-means Using the PCA Data

 -Cluster the cryptocurrencies for the best value for k on the PCA data.

## Answer the following question:

 - What is the impact of using fewer features to cluster the data using K-Means?

# Solution: 

 - Please refer to "Crypto_Clustering.ipynb" for the script including the Analysis
 - Results printed successfully on Jupyter Notebook
 - All requirements completed
 - Using the original data, the best value of k would be 4 as it's the point where the graph rapidly changes and starts moving almost parallel with X-axis. We might want to experiment on both K=3 and k=4 and consider the one witht the best results. 
 - PCA: About 90% of the total variance is condensed into the 3 PCA variables. The best value of k would still be 4 as it's the point where the graph rapidly changes and starts moving almost parallel with X-axis. We might want to experiment on both K=3 and k=4 and consider the one witht the best results.
 - In this case we have reduced the number of features from 7 to 3 and we were still able to get the same results. We can conclude that we can use less features and still get a similar performance to the original model