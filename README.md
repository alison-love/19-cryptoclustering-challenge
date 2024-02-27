## Cryptocurrency Clustering Analysis

### Project Overview

This project applies unsupervised learning methods to a dataset of cryptocurrencies in order to uncover inherent groupings. By using K-Means clustering both on the original features and on the principal components obtained through PCA, we aim to identify patterns and relationships that are not immediately apparent.

### Features and Data

The dataset includes a variety of features related to cryptocurrency performance, such as price changes over 24 hours and 7 days. These features are used to understand the behavior of different cryptocurrencies in the market.

### Methodology

K-Means Clustering: We applied the K-Means algorithm to the preprocessed data to identify clusters based on the original features.
Principal Component Analysis (PCA): PCA was employed to reduce the dimensionality of the data, transforming the original features into principal components.
Cluster Analysis with PCA: K-Means clustering was then applied to the principal components to observe the impact of dimensionality reduction on the cluster structures.

### Results

The results were visualized using scatter plots, comparing the clusters formed from the original features with those formed after PCA. The visualizations demonstrate the impact of using fewer features (principal components) on the clarity and separation of the clusters.

### Conclusion

The project illustrates the power of dimensionality reduction in revealing more distinct clustering patterns. The PCA-transformed data led to potentially more meaningful clusters, although the trade-off is a less direct interpretability in terms of the original features.

### Dependencies

- Python 3
- Jupyter
- Pandas
- NumPy
- Matplotlib
- scikit-learn
