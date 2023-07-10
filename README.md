# 19-Unsupervised_Machine_Learning
# Instructions
1. Rename the Crypto_Clustering_starter_code.ipynb file as Crypto_Clustering.ipynb.
2. Load the crypto_market_data.csv into a DataFrame.
3. Get the summary statistics and plot the data to see what the data looks like before proceeding.
4. Prepare the Data using the StandardScaler() module from scikit-learn to normalize the data from the CSV file and create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
5. Find the Best Value for k Using the Original Scaled DataFrame, using the elbow method to find the best value for k
6. Cluster Cryptocurrencies with K-means Using the Original Scaled Data, clustering the cryptocurrencies for the best value for k on the original scaled data
7. Optimize Clusters with Principal Component Analysis, using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.
8. Find the Best Value for k Using the PCA Data using the elbow method
9. Cluster Cryptocurrencies with K-means Using the PCA Data

# Tools
- Python
- sklearn
