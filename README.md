# Cryptocurrencies
# Challenge
Cryptocurrencies Analysis using Unsupervised Machine Learning
In this repo I demonstrate techniques of Unsupervised Machine Learning to perform analysis of cryptocurrencies for a mock business proposal.  

In a mock scenario where an investment bank wishes to offer new cryptocurrencies for its customers and we are tasked to present a report of how the cryptocurrencies are trading on the market and how cryptocurrencies could be grouped toward creating classification for developing a new investment product.  

Since we have no known output, unsupervised machine learning is suited for the task.  We will be able to group cryptocurrencies and provide data visualizations to share our findings.  

## Journey of Data Analysis <font size="2"> (High level Jupter cells explanation) </font>
* Load libraries and dependencies
* Load raw CSV file
* Identify data types
* Prep and transform data column from object to float
* Clean data
  * Remove non active cryptocurrencies
  * Remove cryptocurrencies that doesn't have an algorithm
  * Remove Trading status column
  * Remove any incomplete Data cryptocurrencies
  * Remove any cryptocurrencies that hasn't been mined
* Extract Coin Name out and hold separately
* Use get_dummies method to distinguish algorithms into own feature
* Scale data for proper weight
* Use Principle Component Analysis (PCA) to thin down meaningful components
* Use elbow curve to best K value for K-means method
* Apply K-means model and obtain our classification
* Examine the data by 3d and 2d graphs, tables.  
