# Spotify_Music_Analysis

## Overview
This project presents an interactive Power BI dashboard analyzing Spotify music data across 952 tracks. The goal is to uncover patterns in **streaming behavior**, **audio features**, and **release strategies** to inform **growth and content decisions**—ideal for roles focused on data-driven music strategy.

---

## Problem Statement
With thousands of songs released daily, it's challenging to identify what makes certain tracks outperform others in terms of streams and listener engagement. Platforms like Spotify need to understand how factors like release timing, audio characteristics, and chart or playlist presence influence a song's success. Without these insights, optimizing release strategies and curating content for growth becomes guesswork.The insights are intended to support playlist optimization, release planning, and user engagement strategies for music platforms like Spotify.

---

## Tools & Technologies
- **Power BI**: Data cleaning, dashboard development and data modeling  
- **DAX**: Custom measures and calculated columns  

---

## Data Preparation Steps
1. **Cleaned Dataset**:
   - Removed nulls, formatted columns 
   - Converted audio feature metrics into readable % values

2. **Created Calendar Table**:
   - Built a custom Date table for time intelligence (Year, Month, Weekday)
   - Linked 'date` to the calendar for smooth filtering


---

## Key Insights
- **Friday dominates**: Highest streaming volume (~167B), 3x higher than other weekdays  
- **August–September**: Fewer releases, but **~20% higher avg. streams** per track  
- **Top Tracks Profile**:
  - High Energy (80%)
  - Low Speechiness (7%)
  - Mid Danceability (50%)
- **Blinding Lights** by The Weeknd is the highest streamed track (3.7B+ streams)

---

## Recommendations
- **Optimize Release Days**: Prioritize **Friday drops** to maximize exposure  
- **Target Aug–Sep** for big launches based on seasonal listener behavior  
- **Leverage Audio Traits**: Promote or curate tracks with **high energy** and **low speechiness** for better engagement  
- **Playlist Strategy**: Deep dive into playlist inclusion to identify stream-driving lists

---

## Dashboard Preview

> ![Overview](Images/Overview.png)



