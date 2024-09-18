# CryptoClustering
Module 19
This challenge dove into a dataframe about crypto currencies. With 2 parts:
Part 1:
Using the StandardScaler() from scikit-learn to normalize the data from a csv file. Transformed it to a dataframe and scaled the data with the "coin id" set as the index. Once the dataframe was scaled, it was plotted using the elbow method. The elbow method helped find a value for k. Furthermore, with the same scaled dataframe a scatter plot was created showing scatter to one side of the plot.

Part 2:
Using the scaled dataframe, the elbow method and the scatter plot were made again, this time using K-Means. The difference in the elbow method were not much different. However, in the scatter plot, it was more evident that the cluster of data was more precise. It shows that using K-Means gives you a more visual aspect of where the data is giving you the best value for k. 