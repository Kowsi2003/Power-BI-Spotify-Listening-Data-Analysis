# 🎧 Spotify Listening Data Analysis using Power BI

This project showcases a comprehensive analysis of personal Spotify listening history using **Power BI**. By transforming raw listening data into interactive dashboards, it highlights music preferences, listening patterns, and user engagement behavior.

Explore the interactive Power BI report:  
👉 [View Live Power BI Report](https://app.powerbi.com/links/iqbx9B8dKc?ctid=deb1b7b3-b2e4-49f8-b031-9a339ea9839c&pbi_source=linkShare)

---

## ✅ Business Requirements

This project replicates a real-world use case for music streaming analytics, aimed at delivering:

1. **Listening Behavior Analysis**  
   - Track when users listen (by hour, day, and month).
   - Identify peak hours and high-engagement days.

2. **Top Content Identification**  
   - Find most played artists, albums, and tracks.
   - Compare content performance over time.

3. **User Platform Insights**  
   - Understand which devices or platforms users prefer.

4. **Engagement Pattern Recognition**  
   - Detect skips, repeats, and shuffle usage.
   - Measure how long users engage with content.

5. **Personalization & Recommendations**  
   - Use insights to tailor recommendations or improve curated playlists.

---

## 📌 Key KPIs (Key Performance Indicators)

| KPI | Description |
|-----|-------------|
| 🎧 **Total Tracks Played** | Number of track playback events |
| 👤 **Unique Artists** | Total distinct artists listened |
| 💽 **Unique Albums** | Total distinct albums listened |
| ⏱️ **Total Listening Time** | Sum of all `ms_played` values |
| 🕐 **Average Listening Time per Track** | Measures per-track engagement |
| 📅 **Listening Time by Hour/Day** | Behavioral trends by time |
| 📈 **Year-on-Year Trends** | Track growth/decline in listening over time |
| 🔁 **Skip Rate** | Track engagement drop-off |
| 🔀 **Shuffle Usage** | Frequency of shuffled listening |
| 🏆 **Top Artists/Albums/Tracks** | Identifies top content per user |

---

## 🔍 Key Insights

- 🎶 **The Beatles** emerged as the most listened artist, with top albums and tracks.
- 🕓 **Evening hours (5 PM – 10 PM)** and **late night (12 AM – 1 AM)** were peak listening periods.
- 📆 **Weekends** had significantly higher listening time than weekdays.
- 📉 A listening dip was observed post-2022, possibly due to lifestyle changes.
- 🔂 Some tracks were played frequently but had low average playtime—potential indicators of skips or background listening.

---

## 📊 Dashboards

The Power BI report consists of 3 key dashboards:

### 1. **Main Dashboard**
- Overview of artists, albums, and track count
- Year-wise listening trends
- Listening by weekday/weekend
- Top 5 artists, albums, tracks

![Main Dashboard](Spotify%20-%20Dashboard.png)

---

### 2. **Drill-Through Dashboard**
- Deep dive into album-level and artist-level performance
- Track engagement: total playtime and average play length

![Drill-Through Dashboard](Spotify%20-%20Details%20drill%20through.png)

---

### 3. **Listening Pattern Dashboard**
- Heatmap of listening frequency by hour and day
- Scatterplot comparing track frequency vs average playtime

![Listening Pattern](Spotify%20Listening%20Pattern.png)

---

## 🛠️ Tools Used

- **Power BI Desktop** — for building dashboards
- **Microsoft Excel** — for data preprocessing
- **Spotify Data Export** — from Spotify's user data archive

---

## 📂 Project Files

| File Name | Description |
| --------- | ----------- |
| `spotify_dashboard.pbix` | Full Power BI report file |
| `spotify_history.csv` | Raw Spotify listening data |
| `*.png` files | Dashboard images for presentation or GitHub |

---

---

