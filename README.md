# PROJECT_DSA210_30659

# Spotify Listening Pattern Analysis

## **Project Overview**
This project analyzes my Spotify listening patterns to uncover the frequency of musing listenning and how my music preferences change during exams compared to regular times. I will focus on identifying trends that reveal potential links between music and focus.

## **Additional Features**
The features I will analyze include:
- **Listening Frequency**: The number of songs played during specific time periods.
- **Genres**: Dominant music genres during exams versus regular times.
- **Mood Attributes**: Other Spotify audio features, such as valence (happiness) and tempo, to understand emotional states.

## **Dataset**
- **Source**: My personal Spotify listening history data. I will retrieve this data using Spotify's data request feature or the Spotify API and the exam schedule data.
- **Data Content**: The dataset will include timestamps, track information (song names, artists, genres), and playback details.
- **Time Frame**: Focused on the periods during exams and non-exam times for meaningful comparisons.

## **Project Idea**
The goal is to investigate:
1. Changes in **listening frequency** during exams versus regular times.
2. **Genre preferences** or specific artists that dominate during exams.
3. Average **song duration** or **energy levels** in the music.
4. Any identifiable patterns that suggest mood changes reflected in the music.

## **Project Plan**
1. **Data Collection**
   - Obtain Spotify listening data from the Spotify API or data export feature.
   - Clean and preprocess the data, ensuring relevant fields are extracted (e.g., timestamps, genres, artists).

2. **Data Exploration**
   - Perform exploratory data analysis (EDA) to understand overall listening habits and key trends.
   - Identify the exam periods and label the data accordingly.

3. **Data Analysis**
   - Compare metrics such as listening frequency, genres, and song energy levels between exam and regular times.
   - Visualize findings using time-series plots, bar charts, and word clouds.

4. **Findings and Interpretation**
   - Summarize insights on how listening habits vary during exams and what this might reveal about mood and stress management.

5. **Future Work**
   - Extend the analysis to include other life events or explore how playlist creation habits change over time.

## **Repository Structure**
- `data/`: Contains raw and processed Spotify data (excluding private details).
- `notebooks/`: Jupyter notebooks for data cleaning, analysis, and visualization.
- `src/`: Python scripts for data processing and analysis.
- `README.md`: This document.
- `.gitignore`: To exclude sensitive or unnecessary files (e.g., raw data exports).
- `results/`: Visualizations and summary reports.

## **Usage**
1. Clone this repository.
2. Install dependencies (listed in `requirements.txt`).
3. Run analysis notebooks or scripts to reproduce results.

## **Acknowledgments**
- Spotify for providing data access through the Spotify API.
- Open-source tools and libraries used for data analysis and visualization.
