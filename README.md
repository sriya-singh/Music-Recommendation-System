# Music Recommendation System

The objective of this project is to explore and analyze Spotify data to gain insights into music genres, songs, and artists, and to build a recommendation system based on user preferences. The project involves several steps: data collection, exploratory data analysis (EDA), clustering genres and songs, and finally, building the recommendation system.

Initially, data is collected from various sources including Spotify's API and CSV files containing information about songs, genres, years, and artists. Exploratory data analysis (EDA) is then performed to understand the distribution and trends in the data. This includes visualizations such as count of songs by decade, trends of sound features over decades, and analysis of top genres and artists.

Next, clustering techniques such as K-Means and t-SNE are applied to group similar genres and songs together. K-Means clustering is used to cluster genres based on their features, while t-SNE is used to visualize these clusters in a two-dimensional space. Similarly, songs are clustered using K-Means based on their audio features, and PCA is used for dimensionality reduction to visualize these clusters.

Finally, a recommendation system is built leveraging the insights gained from the clustering analysis. The system takes as input a list of songs that the user has listened to and recommends similar songs based on their features. This is achieved by calculating the mean feature vector of the input songs and finding the nearest neighbors in the feature space using cosine distances. The system then recommends songs that are closest to the input songs but not already included in the user's list.

In summary, this project aims to provide music enthusiasts with a deeper understanding of music genres, trends, and artists, and to offer personalized recommendations based on their preferences and listening history. Through the combination of data analysis, visualization, and machine learning techniques, the project achieves its objective of exploring Spotify data and building an effective recommendation system for music lovers.

## Dataset

The Spotify dataset used for training TuneSuggest is sourced from Kaggle, provided by [Vatsal Mavani](https://www.kaggle.com/vatsalmavani). This dataset contains a comprehensive collection of tracks from Spotify, including audio features such as valence, energy, tempo, and more.

- **Dataset Source**: [Spotify Dataset 1921-2020, 160k+ Tracks](https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset)

