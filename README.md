## Spotify-Recommendation-System
### Project Overview
- This project analyzes Spotify song data and builds a recommendation system to suggest songs based on user listening behavior.

### Dataset
-  The dataset contains the number of songs heard by each user. Each record represents the number of times a user has listened to a particular song.

### Approach
Our approach involves the following steps:
- Importing necessary libraries for data processing and model building.
- Apply NMF to factorize the feature matrix into two non-negative matrices.
- Cluster songs based on their latent factors obtained from NMF.
- Generate recommendations based on the clustering results and user listening behavior.

### Results:
The system successfully recommend songs based on user listening behavior.

### Technologies Used:
Python, pandas, scikit-learn, Jupyter Notebook.

### Skills Demonstrated:
Clustering, Dimensionality reduction.
