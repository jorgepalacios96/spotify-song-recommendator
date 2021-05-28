# spotify-song-recommender
![spotipy logo](https://user-images.githubusercontent.com/79402322/120002527-37cc3080-bfd5-11eb-9bf2-0868e314e2f6.png)


In this project, I used the SpotiPy API and clustering to create an algorithm to recommend new songs based on a song query.

To perform the recommender, I followed the next steps: 

1. First, I used web scraping to get the top 100 song ranking from Billboard. If our initial song appears in this ranking, the recommender would choose another song from this list.

2. With the Spotify API Wrapper, I downloaded a dataset of 10000 songs from all type of genres so that the algorithm has a wide range of elements to search. Each song has associated some audio features (danceability, valence, energy, liveness, instrumentalness, tempo...) which represent its nature.

3. Through an unsupervised machine learning model, tha algorithm would take our input song and will recommend a another one based on the similarity with the audio features of another song.
