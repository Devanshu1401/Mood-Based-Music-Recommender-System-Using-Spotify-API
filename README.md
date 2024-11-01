# Mood-Based-Music-Recommender-System-Using-Spotify-API

## Goal

Developed a music recommendation system based on content-based filtering leveraging the Spotify Web API, aimed at suggesting songs based on the user's mood and search suggestions.

## Tech Stack

### Languages & Libraries
- Python, Numpy, Pandas, Matplotlib, Plotly, Scikit-Learn, Jupyter Notebook, Spotipy, Tkinter

### Models Used
- K-Means Clustering

## Dataset

Utilized a Kaggle dataset containing 160,000 Spotify songs with attributes like acousticness, genre, valence, and danceability to train the K-means clustering model.

## Project

- Performed exploratory data analysis on the Spotify dataset, visualizing feature variations across genres and years.
- Pre-processed data by standardizing features and employed K-means clustering with four clusters based on song attributes.
- Developed a function to locate songs absent from the dataset via Spotipy API, assigning them clusters for recommendations.
- Generated mood-based recommendations by accessing Spotify's mood-based playlists and using cosine similarity.
- Built a Tkinter GUI for user convenience, allowing selection between mood-based or suggestion-based recommendations and input of song names or moods.


## Learning & Improvements
- Understanding applications of clustering algorithms to recommendation systems was interesting.
- Manually verified recommendations, showcasing relevance to user inputs; however, algorithm reliability needs further verification.
- Optimizing system time complexity is crucial to prevent performance slowdowns. 
