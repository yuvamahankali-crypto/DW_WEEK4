Aim:
Demonstrate performing clustering of datasets.To perform clustering on a given dataset using unsupervised learning techniques (such as K-Means, Hierarchical) in order to group the data into meaningful clusters based on similarities and patterns without prior class labels.
To Perform the clustering of datasets we have to follow these steps:
•	Loading Dataset
•	Open Weka Explorer → Preprocess panel.
•	Load a dataset such as iris.arff or weather.numeric.arff.
•	Weka displays the number of attributes and instances.
•	Numeric datasets (like Iris) are best for clustering.


2.	Running k-Means Clustering
•	Go to the Cluster panel in Weka Explorer.
•	Select SimpleKMeans from the clustering algorithms.

 
•	Choose different values of k (e.g., 2, 3, 4) to test clustering.

•	Run the algorithm to generate cluster assignments.
•	Output includes cluster centroids, number of instances per cluster, and Sum of Squared Errors (SSE).

After Changing the values(numClusters:5):

 
•	Run the algorithm to generate cluster assignments.
•	Output includes cluster centroids, number of instances per cluster, and Sum of Squared Errors (SSE).

•	Studying Cluster Results
•	For iris dataset, k=2 often matches the 3 flower species.
•	he output shows centroids, which represent the mean values of attributes percluster.
•	SSE measures how compact clusters are (lower is better).
•	Misclassifications happen if clusters overlap in attribute space.
•	Comparing clusters with the actual class attribute shows clustering accuracy.

 

 



4.	Exploring Other Clustering Techniques
•	Weka provides other clustering algorithms like EM (Expectation- Maximization), Hierarchical clustering, and COBWEB.
•	EM automatically determines the number of clusters based on probability distribution.
•	Hierarchical clustering builds a tree (dendrogram) of nested clusters.
•	Different algorithms may produce different cluster structures.
•	Comparing results helps understand which algorithm suits the dataset.
 
 
Before Changing the values(numClusters:2):



 
After Changing the values(numClusters:4):



5.	Visualizing Clusters & Insights
•	Open the Visualize panel in Weka.
•	Select attributes on X and Y axes to view scatter plots of clusters.
•	Clusters are shown in different colors for clear separation.
•	Well-separated datasets (like Iris) show clear clusters.
•	Visualization confirms if chosen k correctly matches natural grouping.
 
 


