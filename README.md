# Music Recommender System

A content-based music recommendation system built using Python and Machine Learning.

## Features

- Search for a song
- Filter recommendations by language
- Recommend songs using cosine similarity
- Remove duplicate songs
- Choose the number of recommendations
- Handle invalid user input

## How It Works

The recommendation system uses a content-based filtering approach.

1. The dataset is cleaned and prepared for use.
2. Relevant song features are selected.
3. Categorical data is converted into numerical data.
4. The features are scaled so they can be compared fairly.
5. Cosine similarity is used to measure how similar songs are.
6. The system finds the song selected by the user.
7. Recommendations are filtered based on the user's preferred language.
8. Songs are sorted from highest to lowest similarity.
9. Duplicate songs are removed.
10. The requested number of recommendations is displayed.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git
- GitHub

## How to Run

1. Clone this repository.
2. Make sure the required Python libraries are installed.
3. Place the `spotify_tracks.csv` dataset in the project folder.
4. Open `Music_Reco_Project.ipynb` in Jupyter Notebook or VS Code.
5. Run the notebook cells from top to bottom.
6. Follow the prompts to enter a song, preferred language, and number of recommendations.

## Dataset

This project uses a Spotify tracks dataset containing information about songs and their features.

The dataset is stored locally as `spotify_tracks.csv` and is not included in this repository.

**Dataset Source:** 
https://www.kaggle.com/datasets/gauthamvijayaraj/spotify-tracks-dataset-updated-every-week

The dataset is required to run the recommendation system.

## Example

The system first checks whether multiple songs have the same title and allows the user to select the correct song.

## User Input
```text
Enter a song: Wake Me Up
Enter your preferred language for recommendation: english
Enter the number of recommendations you want: 5
```
```text
Multiple Songs Found
1 - Wake Me Up Avicii
2 - Wake Me Up TWICE
```
```text
Selected song:
Song name :  Wake Me Up
Artist name :  Avicii
Language :  english
```
```text
Recommended Songs:

1 - What Goes Around… - House of Shakira - English - 98.2
2 - Forever & Always (Taylor's Version) - Taylor Swift - English - 96.59
3 - Fade Into Darkness - Vocal Radio Mix - Avicii - English - 96.44
4 - Beauty And A Beat - Justin Bieber, Nicki Minaj - English - 96.11
5 - The Nights - Avicii - English - 95.42
```