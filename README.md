# spotify-classification
The objective of the challenge is to build a machine learning model that is able to predict the genre of a song. Using data provided by Spotify, Genre of a song is a categorical value and this problem statement is a classification problem. There are various possible genres that makes this a multinomial classification problem.

## Dataset

There are two files `CS98XClassificationTrain.csv` that contains the training dataset and `CS98XClassificationTest.csv` that contains the dataset for final testing. These files have been provided in the repository. The dataset is a collection of spotify songs with their **audio features** (tempo, energy, danceability etc.) The training dataset contains 15 columns that are described below:

- `Id` - an arbitrary unique track identifier
- `title` - track title
- `artist` - singer or band
- `year` - year of release (or re-release)
- `bpm` - beats per minute (tempo)
- `nrgy` - energy: the higher the value the more energetic
- `dnce` - danceability: the higher the value, the easier it is to dance to this song
- `dB` - loudness (dB): the higher the value, the louder the song
- `live` - liveness: the higher the value, the more likely the song is a live recording
- `val` - valence: the higher the value, the more positive mood for the song
- `dur` - duration: the length of the song
- `acous` - acousticness: the higher the value the more acoustic the song is
- `spch` - speechiness: the higher the value the more spoken word the song contains
- `pop` - popularity: the higher the value the more popular the song is
- `top genre` - genre of the track (and the target variable for this problem)

## Approach

As for any machine learning project, we will be following a series of steps to come up with the solution to our classification problem. 

- Data Analysis
- Data Preparation & Feature Engineering
    - Identifying Data distribution
    - Outlier detection
    - Feature selection
    - Preprocessing
        - Scaling
        - Train/Test split
- Model Selection
    - Basic models
- Model training & evaluation
- Ensemble learning

## Required python libraries

- [Numpy](https://numpy.org/) - for numerical operations
- [Pandas](https://pandas.pydata.org/) - for loading, querying and manipulating datasets
- [Matplotlib (pyplot)](https://matplotlib.org/3.5.3/api/_as_gen/matplotlib.pyplot.html) - for visual analysis
- [Seaborn](https://seaborn.pydata.org/) - for visual analysis
- [Scikit-Learn](https://scikit-learn.org/stable/) - for machine learning
