# Spotify-Listening-Trends-Analysis
Power BI Project
## Project Overview
This project analyzes my personal Spotify listening history to uncover listening patterns, top artists, genres, seasonal trends, and user behavior insights. Built using Power BI, it transforms raw streaming data into interactive dashboards for actionable intelligence.

## Key Features

-Interactive Dashboards: Trends by artist, track, album, genre, and time periods
-Listening Behavior Analysis: Platform usage, shuffle vs non-shuffle, skip rates, session patterns
-Temporal Insights: Monthly/seasonal listening habits, peak hours, and Covid-era impact (where applicable)
-Engagement Metrics: Most played tracks, artists, completion rates, and reasons for starting/ending tracks
-Advanced DAX & Modeling: Optimized relationships, calculated measures, and dynamic filtering
-Clean Data Pipeline: Power Query transformations for handling timestamps, missing values, and aggregations

## Data Dictionary (Key Columns):

spotify_track_uri: Unique track identifier
ts: Timestamp (UTC) when track stopped playing
platform: Device (desktop, mobile, web, smart_speaker)
ms_played: Milliseconds played (for duration & completion analysis)
track_name, artist_name, album_name
reason_start / reason_end: User actions (trackdone, clickrow, fwdbtn, skip, etc.)
shuffle & skipped: Behavioral flags


(https://github.com/aravinddev13/Spotify-Listening-Trends-Analysis/blob/main/Spotify%20Trends%20Dashboard.png)]

## Tools & Technologies
Power BI Desktop (DAX, Power Query, Data Modeling)

## Key Insights Delivered:

-Identified top artists, playlists, and genre distribution
-Analyzed seasonal changes and demographic listening habits
-Optimized DAX for faster performance on large listening logs
-Derived actionable patterns on user engagement and retention
