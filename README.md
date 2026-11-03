# Spotify Data Analysis – Milestone 1

## Project Overview

This project focuses on performing data analysis and transformation on a Spotify tracks dataset using Python. The objective is to understand the dataset, clean and transform the data, handle missing values, generate meaningful insights, and visualize the results.

## Objectives

- Read and explore the Spotify dataset using Pandas.
- Understand the structure and characteristics of the dataset.
- Perform data cleaning and transformation.
- Identify and handle missing values using mean imputation wherever applicable.
- Generate meaningful insights from the dataset.
- Visualize the findings using Matplotlib.

## Dataset Information

**Dataset:** `spotify_tracks.csv`

The dataset contains information about songs, artists, audio features, streaming statistics, and video engagement.

**Dataset dimensions:**
- Rows: 20,594
- Columns: 24

Some important columns include:

- `Artist` – Name of the artist.
- `Track` – Name of the song.
- `Album` – Album name.
- `Danceability` – Danceability score of the track.
- `Energy` – Energy level of the track.
- `Tempo` – Tempo of the track.
- `Duration_min` – Duration of the track in minutes.
- `Views` – Number of video views.
- `Likes` – Number of likes.
- `Comments` – Number of comments.
- `Stream` – Number of streams.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Tasks

### 1. Data Loading
Imported the required Python libraries and loaded the CSV dataset using Pandas.

### 2. Data Exploration
Explored the dataset using:
- `head()`
- `tail()`
- `shape`
- `columns`
- `info()`
- `describe()`

### 3. Data Transformation
- Removed the unnecessary `Title` column.
- Converted `Artist` and `Track` columns to string data types.
- Created a new column named `Duration_sec` by converting track duration from minutes to seconds.

### 4. Handling Missing Values
- Identified missing values using `isnull().sum()`.
- Applied mean imputation to numerical columns.
- Verified the dataset after imputation.

### 5. Data Analysis and Insights
Performed analysis to identify:
- Top 10 most-viewed songs.
- Top 10 most-streamed songs.
- Average danceability and energy.
- Top 10 artists based on total views.
- Average likes received by songs.

### 6. Data Visualization
Created visualizations using Matplotlib:
- Bar chart of the top 10 most-viewed songs.
- Histogram showing the distribution of energy.
- Scatter plot comparing danceability and energy.
- Bar chart of the top 10 artists by total views.
- Box plot showing the distribution of song views.

## Project Structure

```text
MILESTONE 1- CIE/
│
├── milestone.ipynb
├── spotify_tracks.csv
└── README.md
```


## Conclusion

This project helped in understanding the complete data analysis process, starting from loading and exploring a dataset to cleaning, transforming, analyzing, and visualizing data.

By analyzing the Spotify tracks dataset, meaningful insights were generated about song popularity, streaming performance, artist engagement, and audio features.

The project provided practical experience in using Python libraries such as Pandas, NumPy, and Matplotlib for data analysis.
