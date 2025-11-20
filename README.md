Unsupervised Machine Learning – Project Summary

For this project, I worked with a dataset of 5,000 Spotify tracks and applied unsupervised learning techniques to group songs with similar musical characteristics.

My Approach

🧹 Data Preparation
I began by cleaning the dataset, removing duplicates and filling in missing information to ensure reliable results.

🎛️ Feature Selection
I selected key audio features — such as danceability, valence, loudness, energy, and acousticness — to represent each song’s musical profile.

📊 Clustering
K-Means was the main algorithm used to cluster the songs. The goal was to group tracks with similar patterns in their audio features.

🔻 Dimensionality Reduction
To streamline the clustering process and improve interpretability, I applied PCA to reduce the feature space while keeping most of the variance.

📏 Scaling
I standardized the numerical features using MinMaxScaler so that variables with larger ranges didn’t dominate the clustering.

🔍 Finding the Right Number of Clusters
I tested different cluster counts and used both the Elbow Method (Inertia) and Silhouette Score to identify the most suitable number of clusters.

🎶 Playlist Generation
Once clustering was complete, I created playlists by selecting songs closest to the cluster centroids — essentially choosing the most representative tracks from each group.
