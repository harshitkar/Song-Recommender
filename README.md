# Spotify Song Recommender

A Python-based music song recommender application with a graphical user interface (GUI) built using Tkinter. The app processes a dataset of songs and allows users to filter and recommend songs based on their preferences using clustering techniques.

## Features

- **Display Top Songs**: View the top 10 songs based on the number of streams.
- **Interactive Sliders**: Adjust parameters like danceability, energy, acousticness, and instrumentalness using sliders.
- **Clustered Recommendations**: Dynamically recommend songs based on user preferences using K-Means clustering.
- **Customizable Filters**: Enable or disable filters for each feature (danceability, energy, acousticness, instrumentalness).
- **Dark Theme**: User-friendly dark-themed interface for a modern look.
- **Data-driven**: Processes a CSV file containing song data to provide insights and recommendations.

## Requirements

- Python 3.7 or higher
- Required Python packages:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `tkinter` (comes pre-installed with Python)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/music-song-recommender.git
   cd music-song-recommender
