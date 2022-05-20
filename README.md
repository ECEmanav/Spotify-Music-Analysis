# Spotify-Music-Analysis
I have been using the Spotify app for the past year to listen to my favorite artists and get new song recommendations. Recently, I learned that the app classifies the tracks according to a system of audio features, and that it stores them in a database easily accessible through its API. So, I thought: can we use this database to understand the tracks in it better? That is, can we discover any trends based on subgroups of music divided on things like popularity or year it has been released? Let’s begin:

Audio Features:
According to the Spotify website, all of their songs are given a score in each of the following categories (taken from the Spotify API documentation, https://developer.spotify.com/documentation/web-api/reference/):
Mood: Danceability, Valence, Energy, Tempo
Properties: Loudness, Speechiness, Instrumentalness
Context: Liveness, Acousticness
The data I will be using comes from this Kaggle dataset: https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks?select=tracks.csv.
