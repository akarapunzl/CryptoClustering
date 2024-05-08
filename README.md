Utilized Python and unsupervised learning techniques to analyze cryptocurrency data and predict the impact of 24-hour and 7-day price changes.

Prepared the data by loading the cryptocurrency market data into a DataFrame and normalized it using StandardScaler(). Identified the optimal number of clusters (k) using the elbow method and applied K-means clustering to group the cryptocurrencies based on the original scaled data.

Optimized the clustering process using Principal Component Analysis (PCA) to reduce the dimensionality of the data while preserving its variance. Determined the total explained variance of the three principal components and found the best value for k using the PCA-transformed data.

Clustered the cryptocurrencies using the PCA data and visualized the results using scatter plots. Analyzed the impact of using fewer features on clustering accuracy and gain insights into the behavior of cryptocurrencies in response to price changes over different time periods.
