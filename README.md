# Music Recommender System
## [Click Here for the Website Link!](https://cantartan.wixsite.com/cs210-music-recommen)
## Overview
This project involves the development of a music recommender system utilizing data from Spotify. The system analyzes my preferred playlist named "Chillax". The song features has been extracted from spotify as (df) and recommends songs from another dataset (dfliked) that match my "Chillax playlist's taste. The dfliked dataset is derived from my 1450 liked songs to get the best fitting results for myself.

## Table of Contents
### Installation

spotipy library is required. Install it using:

pip install spotipy

for visualizations, seaborn is required. Install it using:

pip install seaborn

### Data Extraction

 Extracts data using Spotify API, including audio features, artist popularity, and genre for each track in a playlist. The extraction part in this code does two extractions, one for the first playlist ("Chillax") that we want to find similar songs for, and the second playlist ("liked songs") that we want to find the best fitting songs from.

### Data Processing

 Processes the data by applying selective criteria, and filtering the playlist based on artist genres. dfliked playlist is then separated from its non-available genre inputs and it is then renamed as dfgenre.
 
### Data Visualization

 Visualizes the data using heatmaps for correlation analysis and distribution plots for numerical and categorical variables.
 
![2024-01-18_23h29_19](https://github.com/cannotartan/CS210/assets/156928273/c449d793-038e-406b-9aa9-a7cf027d8dfc)

![2024-01-18_23h28_51](https://github.com/cannotartan/CS210/assets/156928273/c5926607-1d62-4723-9058-0ebf9d433879)

![2024-01-18_23h28_24](https://github.com/cannotartan/CS210/assets/156928273/1adcebe1-184b-4a5e-8650-4f3f526bc122)

![2024-01-18_23h27_39](https://github.com/cannotartan/CS210/assets/156928273/129634cb-b3a3-429d-971d-f596d46b993c)

![2024-01-18_23h27_23](https://github.com/cannotartan/CS210/assets/156928273/b32b081b-bf94-4f44-abaf-e434816be1b4)

 
### Hypothesis Testing

 Conducts a hypothesis test to determine if there are significant differences between the "Chillax" playlist and the recommended songs playlist of "liked songs" in terms of various audio features.
 
### k-Nearest Neighbor

 Implements a k-Nearest Neighbor model to recommend songs from the dataset based on selected audio features. To get the best result, the kNN method is done three times with 1 nearest neighbor, 5 nearest neighbor and 10 nearest neighbor.
 
### Data Evaluation

 Evaluates the recommended songs by counting occurrences and selecting the top recommended songs for different k values (1, 5, 10). A final data frame named "dffinal" shows the most repeated 5 songs from these data frames to choose the best applicants for recommending to the user.
 


### Contributors
Can Tartan

### Acknowledgments
This project was developed as part of CS210 course I have took in Sabancı University.

### License
This project is licensed under the MIT License.
