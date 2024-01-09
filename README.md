# Spotify Song Recommendation System (2022)

Content Based Filtering Spotify Song Recommendation System using KMeans Clustering and Euclidean Distance.

## Objective 

Create a song recommendation system that accepts a Spoitify URL from a user, extracts the song's audio features, and uses them to recommend 10 songs with similar audio features (Danceability, Valence, Energy, Tempo, Loudness, Speechiness, Instrumentalness, Liveness, Acousticness, Key, Mode, Duration, Time Signature).

## Implementation

This content-based filtering song recommendation system uses KMeans Clustering and Euclidian Distance to find the similarity between the audio features of the input song and each of the songs in the dataset. The KMeans algorithm will be used to to group the songs in the dataset into similar clusters and assign the input song to its correct cluster. Once the songs are in clusters, the euclidian distance will be calculated between the audio features of the input song and cluster songs to find the 10 songs nearest (most similar to) the input song. The 10 nearest songs will be recommended to the user.