# **SC1015 Mini-Project**[Readme.md]

## **Introduction**
---------
**This is a mini-project for SC1015 (Intro To Data Science & AI) which will be focusing on Spotify & Billboard
Songs.**  


## Problem Defintion 
--------------   
Spotify is a digital music service that gives you access to millions of songs, and in 2021 has amassed 406 million active users, with 180 million premium subscribers.

Many would probably be familiar with the [Spotify](https://spotifycharts.com/regional) and [Billboard](https://www.billboard.com/charts/) Charts. These lists are constantly evolving, and songs are added and taken off every day. 

[Spotify's API](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features) also provides features for every song, with their integration of the echonest API

We want to find out if audio features can be used to predict a hit song, and if so, which models work best.

![Spotify Logo](https://i.pinimg.com/originals/49/fd/2a/49fd2a48daacf595d3916bf21d4222c8.png)

## **File Directory**
--------
* [**Data Processing** ](https://github.com/joedav98/SC1015_SC18_SpotifyRepo/blob/main/spotify_data_preparation.ipynb "spotify_data_preparation.ipynb")
  * Data Collection 
  * Data Preparation
* [**EDA**](https://github.com/joedav98/SC1015_SC18_SpotifyRepo/blob/main/spotify_eda.ipynb "spotify_eda.ipynb")
  * Exploring Trend of Audio Features
  * Audio Feature Correlation
* [**Machine Learning**](https://github.com/joedav98/SC1015_SC18_SpotifyRepo/blob/main/spotify_machine_learning.ipynb "spotify_machine_learning.ipynb")
  * Performance Metrics
  * Supervised Learning Models
  * Evaluation


## [**Datasets**](https://github.com/joedav98/SC1015_SC18_SpotifyRepo/tree/main/data)
-----
* **Non-Hit songs**
* **Hits songs**
* **Billboard Charts**
* **2020-2021 songs**

## **Libraries**
--------
* Pandas
* Matplotlib
* Seaborn
* Numpy
* SKlearn
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
  
* **Weeks-on-board** - Number of weeks the song was on the BillBoard.
  
* **Charted** - Whether a song is a hit or non-hit.


## **Machine Learning Models**
---------------------
* Multi-Variate Linear Regression
* Logistic Regression
* Decision Tree
* Random Forest Regressor
* Random Forest Classifier
* K-Nearest Neighbors Classifier
* Support Vector Machine Classifier
* Guassian Naive Bayes Classifier

## **Cross-Validation Methods**
* Grid Search Cross Validation (Random Forest Regressor)
* Random Search Cross Validation (Random Forest Classifier)
* Cross Validation Score (K-Nearest Neighbors Classifier)

## **Contributions**
----------
* **Joel David Lim Jianyi (U2120396F)**
  * Data Collection and Processing
  * EDA
 
* **Neo Wei (U2123800F)**
  * EDA
  
* **Joseph Chng (U2122493C)**
  * Machine Learning

## **References**
---------
* [Spotify Audio Features](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features)
* [Machine Learning Models](https://scikit-learn.org/stable/)
* [Non-Hits Data Set](https://www.kaggle.com/datasets/luckey01/test-data-set)
* [Hits Data Set](https://www.kaggle.com/datasets/theoverman/the-spotify-hit-predictor-dataset)
* [Charts Data Set](https://www.kaggle.com/datasets/dhruvildave/spotify-charts)
* [2020-2021 Data Set](https://www.kaggle.com/datasets/sashankpillai/spotify-top-200-charts-20202021)

