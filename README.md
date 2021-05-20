# Spotify-recommender

This repository consists a tutorial code for Spotipy. Spotipy is a lightweight Python library for the Spotify Web API. With Spotipy you get full access to all of the music data provided by the Spotify platform. 
The second code is the spotify recommender system which works completely based on the user's taste. Data used can be found here (https://drive.google.com/file/d/1Lpa-N5VueMyDmhMns8uIaWM7K0HYFbF-/view?usp=sharing). First kmeans clustering is done on the data and songs are divided into 20 clusters. After that two types of reccomendations are possible, one based on users current playing queue i.e current mood and second based on user's most streamed tracks i.e basic taste. It takes data from user using the spotipy and then calculates the cluster center of the input data. After that recommendation is made based on the cosine similarity, the spotify's original algorithm uses manhattan distance so you can change one line of code and do that also. But I think cosine similarity will work better. Finally based on the recommendations a playlist is created for the user. add_to_queue can also be used if the user has premium account.

Also the notebooks wont work on colab as an initial redirection is required for authorisation. 

I haven't made any web app for this project because I didnt want to get into the networking and auth areas, but if you want to colab with me on it, reach out on bhuvanaggarwal9@gmail.com

<p align=center> Made with :heart: by Bhuvan Aggarwal </p>
