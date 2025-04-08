# Spotify-Music-Trends-Analysis

## Table of Contents
1. [Introduction](#introduction)
2. [Research Question](#research-question)
3. [Data Sources](#data-sources)
4. [Methodology](#methodology)
5. [Deliverables](#deliverables)
6. [Project Plan](#project-plan)
7. [Tools & Technologies](#tools--technologies)
8. [License](#license)

---

## Introduction
Spotify has transformed how people consume music, making it a rich source for analyzing global and regional music trends. This project aims to study patterns in music preferences by examining audio features (e.g., tempo, energy), song metadata (e.g., genre, artist), and popularity metrics over time and across regions. The insights will be visualized through an interactive dashboard.

---

## Research Question
**What are the trends in music preferences across different regions and time periods, and how do audio features (e.g., tempo, energy) correlate with song popularity?**

This question is significant because:
- It helps artists and record labels understand audience preferences.
- It highlights cultural differences in music consumption.
- It provides insights for improving music recommendation systems.

---

## Data Sources
The project uses the following datasets:

1. **Kaggle: Spotify Tracks Dataset**  
   - **Description**: Contains metadata (artist, genre), audio features (tempo, energy), and popularity scores for over 10,000 tracks.
   - **Provenance**: Publicly available on Kaggle.
   - **Link**: [Spotify Tracks Dataset on Kaggle](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)

2. **Spotify API**  
   - **Description**: Provides real-time data on track popularity, regional top charts, and artist information.
   - **Provenance**: Official Spotify Developer API.
   - **Link**: [Spotify API Documentation](https://developer.spotify.com/documentation/web-api)

---

## Methodology
The project will follow these steps:

### Step 1: Data Collection
- Download the Kaggle dataset for historical data on songs.
- Use the Spotify API to fetch real-time data on regional top tracks.

### Step 2: Data Cleaning
- Handle missing values in the dataset.
- Normalize numerical features (e.g., tempo, loudness) for consistency.

### Step 3: Exploratory Data Analysis (EDA)
- Analyze trends in genres, artists, and audio features over time.
- Visualize correlations between audio features (e.g., energy) and popularity.

### Step 4: Regional Analysis
- Compare top genres and artists across different regions using heatmaps or bar charts.

### Step 5: Dashboard Development
- Create an interactive dashboard using Google BigQuery and Looker Studio to present findings.

---

## Deliverables
At the end of this project, we will provide:
1. **Interactive Dashboard**:
   - Visualizations of genre/artist trends over time.
   - Regional differences in music preferences.
   - Correlations between audio features and popularity.

2. **Final Report**:
   - A detailed document summarizing methodology, results, and insights.

3. **Presentation Video**:
   - A 20-minute video explaining our findings.

4. **Cleaned Dataset**:
   - A processed version of the dataset used for analysis.

---

## Project Plan
Below is a timeline for completing the project:

| Task                      | Start Date | End Date   | Dependencies       |
|---------------------------|------------|------------|--------------------|
| Data Collection           | April 1    | April 3    | None               |
| Data Cleaning             | April 3    | April 6    | Data Collection    |
| Exploratory Data Analysis | April 6    | April 10   | Data Cleaning      |
| Regional Analysis         |
