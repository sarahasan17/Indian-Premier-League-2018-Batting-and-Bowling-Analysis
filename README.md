# Indian Premier League 2018 Batting and Bowling Analysis using Clustering(Unsupervised Learning)
Analyzing batting and bowling data from the Indian Premier League (IPL) 2018 season using unsupervised machine learning techniques like hierarchical clustering and k-means clustering can provide valuable insights into the performance of different players in the tournament. This approach can help in categorizing players into clusters based on their performance, identifying key trends, and making informed decisions for team composition and strategy. Here's a detailed explanation of how this analysis can be carried out:

**Data Collection:**
Collecting Data: Gather comprehensive data for all the players who participated in IPL 2018, including their batting and bowling statistics. The key metrics for batting can include runs scored and strike rate, while for bowling, it can include the number of wickets taken and economy rate.

**Data Preprocessing:**
Data Cleaning: Ensure that the collected data is clean and consistent, handling missing values and outliers appropriately.

**Clustering Algorithms:**
Hierarchical Clustering: Hierarchical clustering is an agglomerative approach that starts with each data point as its own cluster and then gradually merges clusters based on similarity. You can use a distance metric like Euclidean distance to measure the similarity between players. Hierarchical clustering results in a dendrogram, which can be cut at a certain height to create a specific number of clusters.

K-Means Clustering: K-means clustering is a partitioning method that groups data points into k clusters based on their similarity. In this case, you would choose k=5 since you want to create five clusters. The algorithm iteratively assigns data points to clusters and updates the cluster centroids until convergence.

**Cluster Interpretation and Visualization:**
Interpretation: Once you have clustered the players using both hierarchical and k-means clustering, you can analyze the characteristics of each cluster. For example, Cluster 1 might consist of top-order aggressive batsmen, Cluster 2 could be composed of spin bowlers, and Cluster 3 may have all-rounders with a balanced performance in both batting and bowling.
Visualization: To visualize the clusters, you can create scatter plots or other visualizations. You can use the players' strike rates and the number of wickets taken as axes in a scatter plot. Each data point represents a player, and the color of the point can represent the cluster it belongs to. This will provide a clear visual representation of how players are grouped based on their performance.

**Insights and Decision Making:**
Insights: Analyze the clusters to identify insights such as which clusters contain the best performers in batting, bowling, or all-round skills. This can help team management and selectors make decisions regarding player selections and strategies for future tournaments.
Further Analysis: You can also perform additional analysis within each cluster to identify standout players and their specific strengths and weaknesses.

By applying hierarchical and k-means clustering to IPL 2018 batting and bowling data, you can gain a deeper understanding of player performance, identify player roles within a team, and make data-driven decisions to improve team strategies and player selections in future IPL tournaments.
