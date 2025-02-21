# Personalized Spotify Songs Recommendation System

## Overview
The **Personalized Spotify Songs Recommendation System** is a machine learning-based project designed to recommend personalized songs based on the user's current emotional state and preferences. The system integrates Spotify data, analyzes the emotional content of songs using Thayer's 2D emotion model, and suggests songs that align with the user's mood.

### Key Features:
- **Mood-based Song Recommendations:** Recommends songs based on user emotions such as happy, sad, relaxed, angry, or depressed.
- **Spotify Playlist Integration:** Analyzes users' Spotify playlists to identify their favorite genres, artists, and other preferences.
- **Emotion Detection:** Utilizes Thayer's 2D emotion model to analyze the emotional content of songs based on features like energy and valence.
- **Personalization:** The system learns from the user's listening habits and mood inputs to provide accurate and tailored song suggestions.

## Project Structure

- `data/`: Folder containing the dataset used for emotion analysis (e.g., `spotifyDataset.csv`).
- `notebooks/`: Jupyter notebooks for preprocessing the data, emotion analysis, and training models.
- `src/`: Source code for the recommendation engine, data preprocessing, and integration with the Spotify API.
- `README.md`: Project documentation.
