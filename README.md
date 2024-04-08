# CryptoClustering
Module 11 Homework

## The Solution

Data Source: CryptoClustering/Resources/crypto_market_data.csv

Logic: Crypto_Clustering.ipynb

## Key Steps

1) Read Data and Prepare the Data using standard Scaler

2) Find Best Value of K using the Original Scaled DataFrame

3) Cluster Cryptocurrencies with K-means using the original Scaled Data

4) Optimize Clusters with Principal Component Analysis (PCA)

5) Find best values fpr k using the PCA Data

6) Cluster Cryptocurrencies with K-means using the PCA data

7) Determine the Weights of Each Feature on Each Principal Component

## Conclusion

Our original graph of using the "price_change_percentage_24h" and "price_change_percentage_7d" before applying PCA may be "good enough" to segment the data with 3 clusters, but the clustering results would have been slightly improved using 4 clusters and using a scatterplot between "price_change_percentage_7d" and "price_change_percentage_14d".

By using the PCA analysis, we can confirm that "price_change_percentage_7d" and "price_change_percentage_14d" provide the best separation amongst various cluster plots given the influence of these features on PCA compnents PCA3 and PCA2 respectively. Similar results can be achived using a plot betweeen "price_change_percentage_7d" and "price_change_percentage_200d" or between "price_change_percentage_7d" and "price_change_percentage_30d"

Please refer to the solution jupyter-notebook file for all the relevant charts.
