# <h1 align="center">  An Exploratory Data Analysis of Spotify Data
  
This project is an Exploratory Data Analysis (EDA) on the Spotify dataset. The dataset contains information about various songs, including their features such as danceability, energy, loudness, and more. Through this analysis, we aim to gain insights into the characteristics of the songs and explore any patterns or trends.

### About the Project

Spotify is a Swedish audio streaming and media services provider founded in April 2006. It is the world's largest music streaming service provider and has over 381 million monthly active users, which also includes 172 million paid subscribers.

![Banner](https://github.com/user-attachments/assets/097a127a-19ce-42ec-a5f0-1ea8b8a32acf)

Spotify is a digital music streaming service that provides users access to over 82 million songs, podcasts and audio books. The app was developed by Daniel Ek and Martin Lorenzton in 2006. This app has become a family name over the years and boasts over 457 million subscribers as of 2022, rivaling SoundCloud and Apple Music. 

Spotify measures the popularity of its' artists based on their monthly listeners and number of streams they receive on songs produced. These streams are then multipled by (0.003) and paid to artists as "Royalties", it is a modernized system of monetizing digital sales from traditional album sales (100 streams = 1 album). Ed Sheeran was Spotify's most streamed artist in 2019, however, the rank placements change rapidly depending on album relases, EP's, mixtapes and so forth!

Spotify is a perfect dataset to measure the popularity of songs against various music elements, across a large set of songs throughout the decades. This analysis can be used to demonstrate how peoples music tastes have been translated throughout the past two decades!

I will be creating an exploratory analysis by creating data visualizations and conducting statistical analyses to investigate the relationship between the use of non-traditional musical elements and the popularity of Spotify hits from 2000 to 2019.

**Audio Features**


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


## Prerequisites

Before running the code, make sure you have the following dependencies installed:

- Python (3.x)
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn