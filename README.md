# README

## Cryptocurrency Clustering Analysis

This project aims to cluster various cryptocurrencies based on their market data. By applying clustering algorithms and optimization techniques, the project provides insights into the similarities and differences between different cryptocurrencies.

### Files Included:

1. `crypto_market_data.csv` - Contains market data for various cryptocurrencies over different time frames.
2. `Crypto_Clustering.ipynb` - A Jupyter notebook detailing the clustering analysis and optimization techniques.

## File Descriptions:

### 1. `crypto_market_data.csv`:

- Lists various cryptocurrencies with their price change percentages over different time frames like 24 hours, 7 days, 14 days, 30 days, 60 days, 200 days, and 1 year.

### 2. `Crypto_Clustering.ipynb`:

- **Data Preparation**: Initial steps to prepare the cryptocurrency market data for clustering.
- **K-means Clustering with Original Data**: Determines the optimal number of clusters and performs clustering on the original data.
- **Optimization with PCA**: Uses Principal Component Analysis to reduce the dimensionality of the data and explains the variance captured.
- **K-means Clustering with PCA Data**: Determines the optimal number of clusters for the PCA-transformed data and performs clustering.
- **Visualization & Comparison**: Provides visual comparisons of the clustering results with and without PCA.

Throughout the notebook, several questions are posed and answered, offering further insights into the analysis.

## How to Use:

1. **Jupyter Notebook**:
   - Open `Crypto_Clustering.ipynb` in Jupyter Notebook or Jupyter Lab.
   - Ensure all dependencies, especially required Python packages, are installed.
   - Run the cells in sequence to perform the clustering analysis.

2. **CSV Data**:
   - The `crypto_market_data.csv` file can be imported into any data processing or analysis tool for further exploration or used as a data source for other projects.

## Notes:

- Ensure that the notebook and CSV file are in the same directory for the analysis to work correctly.
- The analysis and results are based on the current structure and content of the `crypto_market_data.csv` file. Adjustments may be needed if the dataset changes in the future.
