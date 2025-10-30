# 🎧 Spotify Dashboard

An interactive Power BI dashboard analyzing Spotify tracks to uncover insights on artist performance, song popularity, duration trends, and explicit content distribution.

---

## 📊 Project Overview
This dashboard was created to analyze Spotify music data using Power BI.  
It visualizes relationships between popularity, artists, album types, and explicit content to uncover patterns in global music trends.

**Key Highlights:**
- Average, maximum, and minimum popularity of songs 🎶  
- Distribution of explicit vs non-explicit songs ⚠️  
- Average song duration (minutes) ⏱️  
- Most popular artists and top-ranked songs 🏆  
- Analysis of singles vs albums 📀  

---

## 🧩 Tools & Technologies
- **Power BI** – Data Visualization  
- **DAX** – Custom Measures & KPIs  
- **Excel / CSV** – Data Source  
- **Data Modeling** – Relationships, Filters & Hierarchies  

---

## 📸 Dashboard Preview
![Spotify Dashboard](Spotify Dashboard.png)

---

## 🗂️ Dataset
The dataset used for this project contains Spotify music data with the following key columns:

| Column | Description |
|---------|-------------|
| `song` | Name of the track |
| `artist` | Performing artist |
| `album_type` | Whether it’s a single or album |
| `duration_ms` | Song duration in milliseconds |
| `popularity` | Popularity score (0–100) |
| `is_explicit` | Explicit content indicator |
| `position` | Song’s position on the chart |

📂 Dataset file: [`Data/spotify-top-50-world.csv`](Data/spotify-top-50-world.csv)

---

## ⚙️ DAX Measures
All key calculations (like averages, explicit song count, and popularity KPIs) are written in DAX.

📄 DAX file: [`Dax/spotify_measures.dax`](Dax/spotify_measures.dax)

---

## 📬 Contact
**Santhosh Babu S**  
📧 [santhoshbabus.analyst@gmail.com](mailto:santhoshbabus.analyst@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/santhoshbabus) | [GitHub](https://github.com/santhoshbabu-analyst)
