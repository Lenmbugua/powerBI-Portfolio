Spotify Listening Behavior Analysis – Power BI
📌 Project Overview

This project analyzes Spotify listening behavior by segmenting users based on listening time and track frequency. Using DAX measures and interactive Power BI dashboards, listeners are classified into quadrants (Low/High Time vs. Low/High Frequency), enabling deeper insights into engagement patterns.

📊 Business Requirements

1. Albums

🎵 Total Albums Played Over Time – Track how album listening trends change across months and years.

 Number of Albums Listened by Year – Identify annual listening habits and volume.

 Top 5 Albums – Identify the most played albums.

 Latest Year vs Previous Year Analysis – Compare consumption between LY (Latest Year) and PY (Previous Year), including YoY growth.

2. Tracks

🎵 Total Tracks Played Over Time – Monitor listening trends across months and years.

 Number of Tracks Listened by Year – Analyze yearly track diversity.

 Top 5 Tracks – Identify the most frequently played tracks.

Latest Year vs Previous Year Analysis – Compare track engagement (LY vs PY) and YoY growth.

3. Listening Patterns

Listening Hours Analysis – Use a Heat Map to identify peak listening times (by hour & day).

Average Listening Time (min) vs Track Frequency – Use a Scatter Plot with Quadrant Analysis to categorize tracks:

High Frequency & High Listening Time – Most engaging tracks

Low Frequency & High Listening Time – Niche but impactful tracks

High Frequency & Low Listening Time – Short & frequently played tracks

Low Frequency & Low Listening Time – Less popular tracks

4. Details Grid

Grid View with Essential Fields – Album Name, Artist Name, Track Name, and other key attributes.

Drill Through Functionality – Allow users to drill through reports for detailed insights, with export to CSV option.

Drill Down, Drill Up, Hierarchy – Support hierarchical exploration of data.

📂 Domain Documentation
🎶 spotify_track_uri

Description: Unique identifier for each track in Spotify’s database.

Format: "spotify:track:<base-62 string>" (e.g., spotify:track:3n3Ppam7vgaVa1iaRUc9Lp).

Purpose: Links tracks to metadata and allows cross-referencing with Spotify’s catalog.

⏱️ ts (Timestamp)

Description: Time (UTC) when the track stopped playing.

Format: ISO 8601 (e.g., 2024-02-07T14:30:45Z).

Purpose: Analyze listening patterns, session durations, and track end times.

💻 platform

Description: Device or platform used to stream the track.

Values: desktop, mobile, web, smart_speaker.

Purpose: Helps understand where users are consuming music.

🎧 ms_played

Description: Total milliseconds the track was played.

Format: Integer (e.g., 215000 = 3m35s).

Purpose: Engagement analysis, completion rates, revenue calculations.

🎵 track_name

Description: Title of the track.

Example: Shape of You.

Purpose: Identifies most played tracks.

🎤 artist_name

Description: Performing artist.

Example: Ed Sheeran.

Purpose: Rank popular artists, identify user preferences.

💿 album_name

Description: Album the track belongs to.

Example: ÷ (Divide).

Purpose: Album popularity & trend analysis.

▶️ reason_start

Description: Reason playback started.

Values: trackdone, clickrow, backbtn, fwdbtn, playbtn, autoplay.

Purpose: Helps understand user behavior and engagement triggers.

⏹️ reason_end

Description: Reason playback ended.

Values: trackdone, endplay, fwdbtn, backbtn, logout.

Purpose: Identify drop-offs, skipping behavior, and retention issues.

🔀 shuffle

Description: Whether shuffle was ON.

Values: TRUE / FALSE.

Purpose: Understand shuffle usage patterns.

⏭️ skipped

Description: Whether the song was skipped.

Values: TRUE / FALSE.

Purpose: Analyze drop-off rates and track engagement.

📊 Dashboard Features

✔️ Quadrant segmentation using DAX logic
✔️ Interactive filters for platform & artist
✔️ Insights on track skips and reasons for ending playback
✔️ KPI cards for listening time and frequency

🖼️ Dashboard Preview

(Add your screenshot here once you upload it to GitHub)

📈 Key Insights

Frequent listeners who spend less time per session prefer short tracks.

Skipping behavior is highest on mobile platforms.

Autoplay contributes significantly to session continuation.

🛠️ Tools Used

Power BI

DAX

Power Query

Dataset: Spotify listening history

👤 Author: Hellen Mbugua