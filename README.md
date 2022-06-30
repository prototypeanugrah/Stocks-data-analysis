# Stocks-data-analysis

The given dataset is the daily close of a major U.S. market index which includes the following features – Open,
Close, High, Low, Adj Close and daily Volume.

The assignment has been divided into 3 major sections –

Section 1 – To examine the daily volume data and identify the optimal number of clusters for the same.
  - Identified the optimal number of clusters (K = 3) using Elbow method on daily Volume data

Section 2 – To compute various fractional difference and perform clustering for the same.
  - Computed fractional differences
  - Implemented Gaussian Mixture Model (GMM) to cluster the dataset
  - Implemented PCA and TSNE dimensionality reduction methods

Section 3 – To compute the monthly returns for each month and model a Decision Tree to classify if investing in
any month can be a profitable strategy.
  - Computed monthly returns, previous month's Volume, High, Low prices
  - Used GridSearchCV for Hyperparameter Tuning
  - Implemented Decision Tree to clasify if investing in a month will be profitable

Visualization - 
  - Created yearly visuals to identify trends
  = Created monthly trend to make an investment decision i.e, which months are profitable to invest in.
