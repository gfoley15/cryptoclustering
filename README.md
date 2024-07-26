# cryptoclustering
This project involves clustering cryptocurrencies using K-means clustering with data preprocessing and Principal Component Analysis (PCA). It includes the following tasks:

1. **Prepare the Data:** Normalize data using StandardScaler and create a DataFrame with the scaled data.
2. **Find the Best Value for k:** Use the elbow method to determine the optimal number of clusters.
3. **Cluster Cryptocurrencies:** Apply K-means clustering to the original scaled data and visualize using hvPlot.
4. **Optimize Clusters with PCA:** Perform PCA, find the best k value on PCA data, and visualize the results.
5. **Analyze Impact:** Assess the impact of dimensionality reduction on clustering.

## Files

- `Resources/crypto_market_data.csv`: The CSV file containing cryptocurrency data.
- `Notebook/Crypto_Clustering_code.ipynb`: Jupyter notebook for data analysis and visualization.

## Sources
- https://matplotlib.org/stable/gallery/subplots_axes_and_figures/subplots_demo.html
- https://holoviz.org/tutorial/Composing_Plots.html
