# Spotify_Prediction

The aim of this project is to develop a model that predicts the popularity metric from a scale of 0
to 100 (0 being least popular to 100 being most popular) for unreleased or new music using
regression. 

Package Requirements - 
- Python. - 3.10.5
- numpy - 1.22.4
- matplotlib - 3.5.2
- sklearn - 1.1.1 
- pandas - 1.4.2
- xgboost - 1.5.1
- shap - 0.40.0

For this project, data has been collected from seven genres of music 
- Alternative
- Blues
- Hip-Hop
- Indie Alternative
- Metal
- Popular 
- Rock

Most features in the dataset focus on the quality of music through audio features which are defined below:
- Danceability refers to how suitable a track is for dancing based on a combination of musical
elements including tempo, rhythm stability, and overall regularity. A value of 0.0 is least
danceable and 1.0 is most danceable. 
- Energy is a measure from 0.0 to 1.0 and represents a measure of intensity and activity. Energetic tracks feel fast and loud. 
- Key is the estimated overall key of the track. The mapping starts at 0 = C, 1 = C♯/D♭, 2 = D, and so on. 
- Loudness refers to the overall loudness of a track in decibels (dB). 
- Mode indicates the modality (major or minor) of a track. Major is represented by 1 and minor is 0. 
- Speechiness detects the presence of spoken words in a track. 
- Acousticness is a confidence measure where 1.0 represents high confidence the track is acoustic 
- Instrumentalness predicts whether a track contains no vocals. The closer the instrumentalness: value is to 1.0, the greater likelihood the track contains no vocal content.
- Liveness detects the presence of an audience in the recording. A value above 0.8 provides strong likelihood that the track is live. 
- Valence is a measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy,
cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry). 
- Tempo is the overall estimated tempo of a track in beats per minute (BPM). 
- Time Signature refers to an estimated overall time signature of a track. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure). 
- Duration in milliseconds is the duration of the track in milliseconds. 
- Explicit refers to whether a song contains explicit lyrics 
- release_date refers to the date of release of the track 
- The remaining features in the dataset are identification features such as Artist and Track names, URI, Track URL, Genres and Playlists.
