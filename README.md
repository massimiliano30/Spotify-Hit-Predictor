# Spotify Hit Predictor

A machine learning project that predicts whether a Spotify track is likely to become a hit using audio, artist, and genre features.

## Project Overview

This project uses the Kaggle Spotify Tracks Dataset to build a binary classification model.  
A track is classified as a hit if its Spotify popularity score is greater than or equal to 50.

The goal is to help a record label decide which tracks deserve promotional investment before release.

## Models Used

- Logistic Regression
- Decision Tree
- Random Forest

The final selected model is a tuned Random Forest classifier.

## Key Results

- Best model: Random Forest
- Test AUC: 0.9596
- Business threshold: 0.40
- Hit Recall at threshold 0.40: 0.853

## Main Findings

Artist popularity and genre hit rate are the strongest predictors of whether a track becomes a hit.  
Raw audio features also help, but they are less predictive on their own.

## Dataset

The project uses the Kaggle Spotify Tracks Dataset.
