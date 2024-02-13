# CryptoClustering

## Data: 
  * Loaded the csv file into DataFrame "crypto_market_data.csv".

## Prepare the data
  * Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
  * Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame

## Find the Best Value for k Using the Original Scaled DataFrame
  * Use the elbow method to find the best value for k
  * Clusterd Cryptocurrencies with K-means Using the Original Scaled Data
  * Create a scatter plot using hvPlot

## Optimize Clusters with Principal Component Analysis
  * Using the original scaled DataFrame, performed a PCA and reduce the features to three principal components.
  * Create a new DataFrame with the PCA data and set the "coin_id" index
  * Found the Best Value for k Using the PCA Data
  * Clusterd Cryptocurrencies with K-means Using the PCA Data
  * Create a scatter plot using hvPlot by setting x-axis as "price_change_percentage_24h" and the y-axis as "price_change_percentage_7d".

