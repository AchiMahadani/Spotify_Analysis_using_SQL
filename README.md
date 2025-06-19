# 🎧 Spotify SQL Project

This project presents a comprehensive **Exploratory Data Analysis (EDA)** and **Data Analysis** on a **Spotify dataset** using **SQL**. The dataset includes detailed track-level data such as artist names, albums, stream counts, audio features (e.g., danceability, energy, valence), and performance metrics (views, likes, etc.).

---

## 📊 Dataset Overview

The `spotify` table contains columns with data such as:

- **Track Information:** `artist`, `track`, `album`, `album_type`
- **Audio Features:** `danceability`, `energy`, `liveness`, `valence`, etc.
- **Performance Metrics:** `views`, `likes`, `comments`, `stream`
- **Flags:** `licensed`, `official_video`, `most_played_on`

---

## 🌟 Project Highlights

- Created a relational table to simulate Spotify music data.
- Performed **EDA** to understand dataset structure and data quality.
- Executed over **20 analytical SQL queries** to extract key insights.
- Implemented **window functions**, **aggregation**, **ranking**, and **case statements**.
- Identified trends such as most streamed artists, energy distribution, and platform-wise popularity.

---

## 🛠 SQL Operations Performed

### 🔍 Exploratory Data Analysis (EDA)
- Count of total and distinct artists/albums
- Minimum and maximum track duration
- Filtering and cleaning invalid data

### 📈 Data Analysis
- Most streamed tracks (>1 billion streams)
- Total comments on licensed tracks
- Top tracks by energy, views, and likes
- Tracks streamed more on Spotify than YouTube
- Energy-to-liveness ratio insights
- Cumulative likes using window functions
- Average danceability by album

---
