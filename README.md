# Cryptocurrency Market Analysis with K-means Clustering

## Overview
This project aims to analyze cryptocurrency market data using K-means clustering. The analysis involves preprocessing the data, determining the optimal number of clusters (k), and clustering cryptocurrencies based on their price change percentages. Both original data and Principal Component Analysis (PCA) transformed data are used for clustering to compare the results.

## Technologies Used
* Python
* Pandas
* hvPlot
* Scikit-learn (KMeans, PCA, StandardScaler)

## Project Structure
### Importing Libraries
* Pandas: For data manipulation and analysis.
* hvPlot: For interactive plotting.
* Scikit-learn: For K-means clustering, PCA, and data preprocessing.
### Data Loading and Preprocessing
* Load Data: Load cryptocurrency market data from a CSV file.
* Data Scaling: Use StandardScaler to normalize the price change percentage columns.
* PCA Transformation: Reduce dimensionality using PCA for feature extraction.
### Exploratory Data Analysis
* Elbow Method: Determine the optimal number of clusters (k) using the Elbow method.
* Cluster Analysis: Cluster cryptocurrencies based on their price change percentages.
* PCA Analysis: Perform clustering using PCA-transformed data to compare results.

## Data Analysis Steps
1.  Data Loading and Preprocessing: Loaded cryptocurrency market data and normalize the data using StandardScaler.
2. Determine Optimal k: Used the Elbow method to identify the optimal number of clusters (k) for both original and PCA-transformed data.
3. Clustering: Cluster cryptocurrencies using K-means based on the optimal k value and compared clustering results between original and PCA-transformed data.

## How to Use
1. Setup Environment: Install the required libraries using pip install pandas hvplot scikit-learn.
2. Data: Place the crypto_market_data.csv file in a folder named Resources.
3. Run the Code: Execute the Python script in a Jupyter Notebook or any Python environment.
4. Visualization: View the interactive plots to analyze clustering results.

## Conclusion
This project demonstrates how K-means clustering can be applied to analyze cryptocurrency market data. By clustering cryptocurrencies based on their price change percentages, we can gain insights into market trends and identify potential investment opportunities. The use of PCA also provides a way to reduce dimensionality and improve clustering performance.

## Repository Organization
1. Crypto_Clustering --> Contains python script for the crypto currency data anaylsis for this assignment 
2. Resources folder --> Contains the csv file from which the data was acquired

## Credits: 
https://hvplot.holoviz.org/ --> Used resource to draw composite graphs
