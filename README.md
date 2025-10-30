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

## 📑 Dashboard Pages Overview

### **1️⃣ Overview Page**
- Displays key KPIs such as **Total Songs**, **Distinct Artists**, **Average Popularity**, and **Average Duration**.  
- Compares **Explicit vs Non-Explicit Songs** to understand content distribution.  
- Analyzes **Songs by Album Type** (single, album, compilation).  
- Visualizes **Distinct Songs** and **Average Popularity** by year.  
- Includes **trend analysis** for Average Popularity and Distinct Songs by month.  
- Highlights **Top Songs** and **Top Artists** based on popularity metrics.

### **2️⃣ Artist Page**
- Presents **Top Artists by Popularity** with comparison visuals.  
- Examines **Tracks per Album** and **Songs per Artist** for deeper insights.  
- Allows **drill-down** to artist-level data, showing details such as song names, release dates, average popularity, position, and duration.  
- Helps identify artists with **consistent hits** and multiple **#1 positions**.

### **3️⃣ Songs Page**
- Ranks **Top Songs by Popularity** for quick performance comparison.  
- Displays **Track distribution** across albums and singles.  
- Compares songs based on **song count** and associated metrics.  
- Provides a **detailed data table** including song name, release date, distinct artists, average popularity, position, and duration per year.

---

## 🧩 Tools & Technologies
- **Power BI** – Data Visualization  
- **DAX** – Custom Measures & KPIs  
- **Excel / CSV** – Data Source  
- **Data Modeling** – Relationships, Filters & Hierarchies  

---

## 📸 Dashboard Preview
![Spotify Dashboard](Images/Spotify%20Dashboard.png)

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

## 💡 Power BI File
You can explore and interact with the dashboard using the Power BI file below.

📊 Power BI file: [`PowerBI/Spotify Dashboard.pbix`](PowerBI/Spotify%20Dashboard.pbix)

---

## 📬 Contact
**Santhosh Babu S**  
📧 [santhoshbabus.analyst@gmail.com](mailto:santhoshbabus.analyst@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/santhoshbabus) | [GitHub](https://github.com/santhoshbabu-analyst)
