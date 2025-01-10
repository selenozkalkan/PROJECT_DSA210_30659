# PROJECT_DSA210_30659  

# Spotify Listening Pattern Analysis  

## **Project Overview**  
This project explores my Spotify listening patterns to analyze changes in listening frequency and behavior during exam periods compared to regular times. By leveraging personal playback data and a detailed exam schedule, the study aims to identify trends that reveal how external events like exams impact music-listening habits.  

## **Key Features Analyzed**  
- **Listening Frequency**: Analyzing the playback trends to determine whether listening habits increase or decrease during exams.  
- **Playback Trends**: Understanding daily playback durations during exam periods and identifying significant shifts.  

## **Dataset**  
- **Source**: Personal Spotify listening history data obtained via Spotify's data export feature, combined with manually created exam schedule data.  
- **Data Content**: The dataset includes playback timestamps, playback durations (in milliseconds), and metadata (e.g., song names, artists, albums).  
- **Time Frame**: The analysis focuses on playback data from **2024**, ensuring meaningful comparisons between exam and non-exam periods.  

## **Project Goals**  
The main objectives of the project are to:  
1. Investigate **daily playback trends** during exam periods compared to non-exam periods.  
2. Statistically test whether playback time increases or decreases during exams.  

## **Project Plan**  

1. **Data Collection**  
   - **Spotify Data**: Retrieved using Spotify's data export feature.  
   - **Exam Schedule Data**: Manually created to include the start and end dates of all 2024 exam periods.  
   - Combined both datasets for integrated analysis, with timestamps used to align playback trends with exam schedules.  

2. **Data Preprocessing**  
   - Filtered Spotify playback data to focus solely on 2024.  
   - Aggregated playback durations into **daily playback trends** (in minutes).  
   - Filled missing dates with zero playback to maintain temporal continuity.  
   - Labeled each day as an **exam period** or **non-exam period** based on the exam schedule.  

3. **Data Analysis**  
   - Created a time-series chart highlighting daily playback trends with exam periods marked.  
   - Segmented playback data into two groups: exam periods and non-exam periods.  
   - Performed statistical tests to compare playback trends between these groups.  

4. **Findings**  
   - Daily playback was significantly higher during exam periods, with an average playback time of **158.12 minutes** during exams compared to **47.42 minutes** during non-exam periods.  
   - Statistical testing (Welch's t-test and Mann-Whitney U test) confirmed this difference was highly significant (p-value < 0.0001).  

## **Techniques and Tools Used**  
The techniques and tools used in this project include:  
- **Data Cleaning and Preprocessing**:  
  - Processed JSON files to extract playback timestamps and playback durations.  
  - Integrated and synchronized playback data with exam period information.  
- **Exploratory Data Analysis (EDA)**:  
  - Aggregated playback data into daily trends and visualized these trends with time-series plots.  
- **Statistical Analysis**:  
  - Performed hypothesis testing (Welch's t-test and Mann-Whitney U test) to compare playback activity during exam and non-exam periods.  
- **Visualization**:  
  - Used `plotly` to create an interactive time-series chart with exam periods highlighted.  
- **Programming Tools**:  
  - Python was the primary language, with libraries such as `pandas`, `numpy`, `matplotlib`, `plotly`, and `scipy`.  

## **Findings and Interpretation**  
The results of the project revealed a clear increase in playback activity during exam periods, suggesting that external stress-inducing events like exams significantly impact music-listening habits.  
