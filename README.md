# PROJECT_DSA210_30659

# Spotify Listening Pattern Analysis

## **Project Overview**
This project analyzes my Spotify listening patterns to uncover the frequency of musing listenning and how my music preferences change during exams compared to regular times. I will focus on identifying trends that reveal potential links between music and focus.

## **Additional Features**
The features I will analyze include:
- **Listening Frequency**: The number of songs played during specific time periods.
- **Genres**: Dominant music genres during exams versus regular times.

## **Dataset**
- **Source**: My personal Spotify listening history data. I will retrieve this data using Spotify's data request feature and the exam schedule data.
- **Data Content**: The dataset will include timestamps, track information (song names, artists, genres), and playback details.
- **Time Frame**: Focused on the periods during exams and non-exam times for meaningful comparisons.

## **Project Idea**
The goal is to investigate:
1. Changes in **listening frequency** during exams versus regular times.
2. **Genre preferences** or specific artists that dominate during exams.

## **Project Plan**
1. **Data Collection**
   - Obtain Spotify listening data from the Spotify data export feature.
   - Obtain exam schedule data
   - Clean and preprocess the data, ensuring relevant fields are extracted (e.g., timestamps, genres, artists).

2. **Data Exploration**
   - Perform exploratory data analysis (EDA) to understand overall listening habits and key trends.
   - Identify the exam periods and label the data accordingly.

3. **Data Analysis**
   - Compare metrics: listening frequency, genres between exam and regular times.
   - Visualize findings using time-series plots, bar charts, and word clouds.

4. **Findings and Interpretation**
   - Summarize insights on how listening habits vary during exams and what this might reveal about mood and stress management.
## **Techniques**
The techniques I will use for this project include:
- **Data Cleaning**: Preprocessing raw Spotify data to extract relevant features and handle missing or inconsistent values.
- **Exploratory Data Analysis (EDA)**: Identifying trends and patterns in the dataset using statistical summaries and visualizations.
- **Data Visualization**: Creating insightful visual representations of the data, such as:
  - Time-series plots to analyze listening frequency over time.
  - Bar charts and pie charts to compare genre distributions.
  - Word clouds to showcase dominant artists or songs.
- **Statistical Analysis**: Comparing features (e.g., energy levels, song durations) between exam and regular periods to identify significant differences.
- **Programming Tools**: Using Python and libraries like `pandas`, `matplotlib`, `seaborn`, and `plotly` for data processing and visualization.


