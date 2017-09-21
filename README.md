# Spotify - An Analysis of Your Music

If there is one thing I cannot live without, it’s not my phone or my laptop or my car – it’s   music. I love music and I love getting lost in it. I like to think that I have a diverse taste in   music. So my inspiration for this project is finding out why my music taste vary so   much. And yes, I am that person you see with her headphones always on. 

# Capstone Proposal
1.	What problem do you want to solve?
    - Why do you love the music that you love?
    - What attributes of a song do you identify with the most/least?
    - How do you compare to other listeners/top charts?
    - Create a predictive model on whether or not you will like a song.
2.	Who is your client and why do they care about this problem? In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?
    - Spotify users can gain insight on what they listen to and how they compare to others
    - Spotify users can use the model to test whether they will like a song or not
3.	What data are you going to use for this? How will you acquire this data?
    - Data: https://developer.spotify.com/web-api/get-audio-features/ Spotify’s API includes Audio Features for each Track. What I will be looking at is the 13 attributes that Spotify has for each
    Track: acousticness, danceability, duration, energy, instrumentalness, key, liveness, loudness, mode, speechiness, tempo, time_signature, and valence
    - There is a web app, <a href="http://sortyourmusic.playlistmachinery.com/index.html">Sort Your Music</a> by Echo Nest, that conveniently extracts the Audio Feature data from Spotify
    - For this project, I would need three playlists to create my predictive model: one playlist for songs I like, one playlist for songs I dislike, and one playlist for Today's top hits.
    - I will have approximately 1200 songs total: 500 liked songs and 500 disliked songs and 150 top hit songs.
4.	In brief, outline your approach to solving this problem (knowing this might change later).
    - STEP I - Getting the Data: I will need to pull the three playlists from my account. I will be using a web app, <a href="http://sortyourmusic.playlistmachinery.com/index.html">Sort Your Music</a>, to extract the Audio Feature data from Spotify.
    - STEP II - Exploratory Data Analysis: In this part, I will get to know the data and try to find out if there is a correlation or any patterns between each playlist.
    - STEP III - Predictive Model: In this part, I’ll attempt to build a model to predict whether or not I will like a song, based on the attributes of my liked and disliked songs.
5.	What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck
    - Code
    - Analyses, visualizations, model (in the form of a report and/or slide deck)

