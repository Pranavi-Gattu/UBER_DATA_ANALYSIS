****UBER DATA ANALYSIS****

Dataset: Data of Uber rides of 6 months (April - September) in the year 2014 are used.

Visualization: "DataVisualization.ipynb" performs the visualization of the data.

Analysis:
-> Initially, the file "Creating_dataset_for_FIM.ipynb" has to be executed to create the text file used for Frequent Itemset Mining.
-> Next "FIM_using_pyspark.ipynb" is to be executed to generate the frequent itemsets and association rules which is done using pyspark.
-> The other files can be executed in any order.
---> "KNN.ipynb" analyses the data using the K-Nearest Neighbours algorithm.
---> "DensityClustering.ipynb" performs DBSCAN over the data.
---> "KMeansClustering_using_pyspark.ipynb" performs KMeans clustering over the data using pyspark modules.
