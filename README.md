# spotify-song-recommender
In this project, I used the SpotiPy API and clustering to create an algorithm to recommend new songs based on the previously chosen.

In this project, I built a Spotify recommendation engine providing rock and metal songs suggestions based on a song query.

The project divides in three parts:

Web scraping from the top100 songs from a website called Billboard. Specifically retrieving the title and artist of those hits. This information will later on be useful as the recommandation engine will advice a user to listen to a random current hit song in the top 100 if the query has been another hit song.
By using the Spotify API Wrapper, I downloaded a set of 5k rock and metal songs and their audio features (e.g. Danceability, Loudness...). Those audio features are constructed by Spotify.
I build, trhough the usage of an unsupervised machine learning model, a recommendation engine which will receive an input (a title of any songs currently on Spotify) and will advice either a top 100 song (if the input song was in the top 100 of Billboard), or a rock song similar in terms of audio features of the song the user imputed.
