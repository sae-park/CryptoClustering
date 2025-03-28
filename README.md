# CryptoClustering

Clustered cryptocurrencies based on their market data using K-Means and Principal Component Analysis (PCA).

Loaded and Preprocessed Data:

Imported cryptocurrency market data from a CSV file.

Normalized the data using StandardScaler.

K-Means Clustering (Without PCA):

Applied K-Means clustering to the standardized dataset.

Used the Elbow Method to determine the optimal number of clusters.

Assigned cluster labels to cryptocurrencies and visualized the results in a scatter plot.

Dimensionality Reduction with PCA:

Reduced the dataset to three principal components using PCA.

Evaluated the explained variance of each component.

K-Means Clustering (With PCA Data):

Re-ran the Elbow Method on PCA-transformed data.

Clustered the cryptocurrencies again based on the reduced dimensions.

Compared clustering results before and after PCA using visualization.

Visualizations and Comparisons:

Plotted Elbow curves to analyze inertia.

Created scatter plots to visualize cluster distributions before and after PCA.
