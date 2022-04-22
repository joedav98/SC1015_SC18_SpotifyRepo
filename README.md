# **SC1015 Mini-Project**[Readme.md]

## **Introduction**
---------
**This is a mini-project for SC1015 (Intro To Data Science & AI) which will be focusing on Spotify & Billboard
Songs.**  


## Problem Defintion 
--------------
* To find out whether a song can be considered a hit based on its **audio features**. 
 
* Which **Models** would be **best** used for this prediction ? 

![Spotify Logo](https://i.pinimg.com/originals/49/fd/2a/49fd2a48daacf595d3916bf21d4222c8.png)

## **File Directory**
--------
* [**Data Processing** ](https://github.com/joedav98/SC1015_SC18_SpotifyRepo/blob/main/spotify_data_preparation.ipynb "spotify_data_preparation.ipynb")
  * Data Collection 
  * Data Preparation
* [**EDA**](https://github.com/joedav98/SC1015_SC18_SpotifyRepo/blob/main/spotify_eda.ipynb "spotify_eda.ipynb")
  * Exploring Trend of Audio Features
  * Audio Feature Correlation
* [**Machine Learning**](https://github.com/joedav98/SC1015_SC18_SpotifyRepo/blob/main/spotify_machine_learning.ipynb"spotify_machine_learning.ipynb")
  * Performance Metrics
  * Supervised Learning Models
  * Evaluation


## [**Datasets**](https://github.com/joedav98/SC1015_SC18_SpotifyRepo/tree/main/data)
-----
* **Hit Songs**
* **Non - Hit Songs**
* **Spotify Songs**

## **Libraries**
--------
* Pandas
* Matplot
* Seaborn
* Numpy
* Plotly

## **Audio Features** 
----------
* **Track** - The Spotify ID for the track.
  
* **Artist** - The Spotify ID of the artist.
  
* **Danceability** - Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. 
  
* **Energy** - Represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy.
  
* **Loudness** - Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). 
  
* **Speechiness** - Presence of spoken words in a track
  
* **Acousticness** - Whether the track is acoustic.
  
* **Liveness** - Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. 
  
* **Valence** - Musical positiveness conveyed by a track.
* **Tempo** - The overall estimated tempo of a track in beats per minute (BPM). 
  
* **Duration_ms** - The track length in milliseconds.
  
* **Year** - The year the song was released in. 
  
* **Weeks-on-board** - Number of weeks the song was on the Bill Board.
  
* **Charted** - Whether a song is a hit or non-hit.


## **Machine Learning Models**
---------------------
* Logistic Regression
* Multi-Variate Linear Regression
* Random Forest
* Decision Tree
* K-Neighbors
* Support Vector Classification
* Guassian Naive Bayes 

## **Contributions**
----------
* **Joel**
  * Data Processing
  * EDA
 
* **Neo Wei**
  * EDA
  
* **Joseph**
  * Machine Learning

## **References**
---------
* [Spotify Audio Features](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features)
* [Machine Learning Models](https://scikit-learn.org/stable/)
* [Data Sets](https://www.kaggle.com/)

