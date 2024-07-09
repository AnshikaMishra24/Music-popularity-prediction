# Music Popularity Prediction Project

## Overview
This project aims to predict the popularity of music tracks using machine learning techniques. The popularity prediction is based on various features extracted from music metadata and audio analysis.

## Dataset
The dataset used for this project consists of music tracks from various genres and artists, spotify_data.csv It includes features such as:
- **Acousticness**: A measure of how acoustic the track is
- **Danceability**: A measure of how suitable the track is for dancing
- **Energy**: Perceptual measure of intensity and activity
- **Instrumentalness**: Predicts whether a track contains no vocals
- **Liveness**: Detects the presence of an audience in the recording
- **Speechiness**: Presence of spoken words in the track
- **Tempo**: Beats per minute (BPM) of the track
- **Valence**: Musical positiveness conveyed by a track
- **Duration_ms**: Duration of the track in milliseconds
- **Popularity**: Target variable indicating the popularity of the track (0 to 100)

## Methodology
1. **Data Preprocessing**: Cleaned and prepared the dataset by handling missing values, scaling numerical features, and encoding categorical variables.
   
2. **Feature Selection**: Identified relevant features using correlation analysis and feature importance techniques.
   
3. **Model Selection**: Explored various regression models including Random Forest, Gradient Boosting, and Neural Networks.
   
4. **Training**: Trained the model  and evaluated its performance.

## Usage
To use the trained model for predicting music popularity:
1. Install required libraries.
2. Run script and input the music track features to get the predicted popularity score.

## Files
- `spotify_data.csv`: Raw data file containing music track features and popularity scores.
- `music popularity prediction.ipynb`: Python script for data selection and preprocessing.

## Future Improvements
- Incorporate additional features like artist popularity, release date, and genre trends.
- Explore advanced machine learning techniques such as deep learning for better prediction accuracy.
- Deploy the model as a web service or application for real-time predictions.

## Contributor
- Anshika Mishra

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
