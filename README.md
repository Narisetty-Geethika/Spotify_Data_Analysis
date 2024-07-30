# <h1 align="center">  An Exploratory Data Analysis of Spotify Data

## Table of Contents

- [Project Overview](#project-overview)
- [Introduction](#introduction)
- [Audio Features](#audio-features)
- [Data Sources](#data-sources)
- [Prerequisites](#prerequisites)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Methadology](#methadology)
- [Summary of Analysis](#summary-of-analysis)
- [Conclusion](#conclusion)
  
  
## Project Overview
This project is an Exploratory Data Analysis (EDA) on the Spotify dataset. The dataset contains information about various songs, including their features such as danceability, energy, loudness, and more. Through this analysis, we aim to gain insights into the characteristics of the songs and explore any patterns or trends.

## Introduction

Spotify is a digital music streaming service that provides users access to over 82 million songs, podcasts and audio books. The app was developed by Daniel Ek and Martin Lorenzton in 2006. This app has become a family name over the years and boasts over 457 million subscribers as of 2022, rivaling SoundCloud and Apple Music.

![Banner](https://github.com/user-attachments/assets/097a127a-19ce-42ec-a5f0-1ea8b8a32acf)
 
Spotify measures the popularity of its' artists based on their monthly listeners and number of streams they receive on songs produced. These streams are then multipled by (0.003) and paid to artists as "Royalties", it is a modernized system of monetizing digital sales from traditional album sales (100 streams = 1 album). Ed Sheeran was Spotify's most streamed artist in 2019, however, the rank placements change rapidly depending on album relases, EP's, mixtapes and so forth!

Spotify is a perfect dataset to measure the popularity of songs against various music elements, across a large set of songs throughout the decades. This analysis can be used to demonstrate how peoples music tastes have been translated throughout the past two decades!

I will be creating an exploratory analysis by creating data visualizations and conducting statistical analyses to investigate the relationship between the use of non-traditional musical elements and the popularity of Spotify hits from 2000 to 2022.

## **Audio Features**

- **Track Metadata**
  
| column | description |
| --- | --- |
| song_title | Title of the song |
| artist | Song artist name|

- **Audio Numerical Quantitive Data**
  
| column | description |
| --- | --- |
| loudness | Loudness - How loud a song is (db) |
| duration_ms | Duration - How long the song is (seconds) |
| tempo | Tempo - How fast a song is (bpm) |

- **Audio Qualitative Data**
  
| column | description |
| --- | --- |
| energy | Energy level - How energetic the song is |
| danceability | How easy it is to dance to |
| instrumentalness | Predicts how likely a track is to contains no vocals |
| valence | How positive the mood of the song is |
| key | Estimates how the overall key of the trackis determined |
| liveness | Detects how much  presence of an audience in the recording |
| acousticness | How accoustic sounding the song is |
| speechiness | How much of a song is spoken word |
| mode | Indicates how the mode determines the modality of a track |
| time signature | The time signature indicates how many beats are in each bar |
| track_popularity |  How popular a song is (as of time of data collection) |

- More Information on Audio Features https://developer.spotify.com/documentation/web-api/reference/get-audio-features

## Data Sources

The dataset used for this analysis is the "Spotify_data.xlsx" file. 

- For Dataset **Click** Here(

## Prerequisites

Before running the code, make sure you have the following dependencies installed:

- Python (3.x)
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn


## Exploratory Data Analysis

EDA involved exploring the spotify data to answer key questions such as :

- Top 5 most popular artists
- Top 5 loudest tracks
- Top 5 Artists with the most danceability song
- Top 10 instrumentalness tracks
- Histogram plots for tempo, loudness, acoustiness, danceability, instrumentalness, etc.

## Methadology

I will be employing several techniques using Pandas, Numpy, Matplotlib, Seaborn in Jupyter Notebbok to clean, filter, group data and plot to provide the opportunity for meaningful measurements and insights.

## Summary of Analysis

- Top 5 artists based on popularity
- Top 5 songs based on loudness
- Top 5 artists with songs based on danceability
- Top 10 songs based on instrumentalness
- Analysis based on Popularity
- Analysis based on Loudness
- Analysis based on acousticness
- Analysis based on liveness

To view the analysis **Click** [Here](https://github.com/Narisetty-Geethika/Spotify_Data_Analysis/blob/main/Spotify%20Analysis.ipynb)

## Conclusion
- Conducted an extensive analysis of a Spotify dataset to identify trends in song attributes and artist popularity using Python (Pandas, NumPy) and data 
  visualization tools (Seaborn, Matplotlib).
- Visualized key insights such as the most popular artists, loudest tracks, and songs with high danceability and instrumentals, enhancing data storytelling and 
  presentation skills. 
- Improved scalability in data cleaning, exploratory data analysis (EDA), and creating insightful visualizations to communicate findings effectively.
