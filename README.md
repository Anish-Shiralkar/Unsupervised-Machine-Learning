# Unsupervised-Machine-Learning
Skills gained: Dimensionality Reduction, Unsupervised ML algorithms, Clustering evaluation & interpretation

Languages & tools leveraged: Scikit learn (Unsupervised ML)


## Situation ##
I undertook a project to cluster a dataset of 5000 Spotify songs based on similar features. The goal was to explore the application of unsupervised machine learning in creating thematic playlists that enhance user experience by grouping similar songs together.

## Task ##
The aim was to use machine learning techniques to classify these songs into meaningful clusters, ultimately forming coherent playlists. The challenge was to achieve this with minimal human intervention while ensuring the playlists were logical and enjoyable.

## Action ##
1. Data Preparation: Collected and preprocessed the dataset, ensuring it included relevant audio features such as tempo, energy, danceability, and valence. I standardized the features using a Standard Scaler to normalize the data.

2. Dimensionality Reduction: Applied Principal Component Analysis (PCA) to reduce the dimensionality of the data, simplifying the dataset while retaining most of the variance. This step was crucial to enhance the performance and efficiency of the clustering algorithm.

3. Algorithm Implementation: Utilized the k-means clustering algorithm, experimenting with different values of k to determine the optimal number of clusters. After careful analysis, I settled on k=24, resulting in 24 distinct clusters.

4. Cluster Analysis: Examined the resulting clusters to identify common characteristics within each group. This involved analyzing the centroid of each cluster to understand the defining features of the songs within them.

5. Evaluation and Adjustment: Evaluated the cohesiveness of the playlists, noting that a few songs did not fit perfectly within their assigned clusters. This observation indicated that while the k-means algorithm was effective, it was not entirely sufficient for perfect playlist creation.

## Result ##
The k-means algorithm successfully clustered the 5000 songs into 24 thematic playlists. However, I identified some outliers that did not align well with their respective clusters. This highlighted the need for human intervention and auditory assessment to refine the playlists further. The project demonstrated the significant potential of machine learning in organizing music data but also underscored the irreplaceable value of human expertise in tasks requiring subjective judgment. This experience provided valuable insights into the interplay between algorithmic efficiency and human intuition in music curation.

