# IPLT20Analysis
# 🏏 IPL Analysis Dashboard (2008–2025) | Power BI

## 📌 Project Overview
This repository contains an **interactive Power BI dashboard** that analyzes **18 seasons of the Indian Premier League (IPL)** from **2008 to 2025**.  
The project transforms raw cricket data into meaningful insights focused on **team performance, player achievements, and season-level KPIs** using DAX-driven metrics.

Users can dynamically select any IPL season and instantly explore standings, champions, player stats, and tournament highlights.

---

## 🎯 Business Objectives
- Analyze **team performance** across IPL seasons  
- Enable **season-wise analysis** using slicers and filters  
- Dynamically identify **Champion and Runner-Up teams**  
- Highlight **top-performing players** (Orange Cap & Purple Cap)  
- Present key tournament KPIs for quick insights  

---

## 📊 Dashboard Features

### 🔹 Primary KPIs
- Champion Team (with dynamic team logo)
- Runner-Up Team (with dynamic team logo)
- Season selector using slicers

### 🔹 Points Table (Season-wise)
- Team Logo  
- Team Name  
- Matches Played  
- Wins  
- Losses  
- No Result  
- Ties  
- **Total Points (DAX calculated)**  

**Points Calculation Logic:**
Total Points = (Wins × 2) + (Ties × 1) + (No Results × 1)


---

### 🔹 Player Statistics
- 🟠 **Orange Cap Stats**
  - Player Name
  - Total Runs in the Season
  - Team Name
  - Player Image (dynamic)

- 🟣 **Purple Cap Stats**
  - Player Name
  - Total Wickets in the Season
  - Team Name
  - Player Image (dynamic)

---

### 🔹 Season Highlights
- Total Matches Played  
- Total Sixes  
- Total Fours  
- Total Teams Participated  
- Total Centuries  
- Total Half-Centuries  
- Total Venues Used  

---

## 🛠 Tech Stack
- **Power BI Desktop**
- **DAX**
- **Power Query**
- **Data Modeling**
- **Interactive Visual Design**

---

## 📂 Data Sources
The dashboard is built using the following CSV files:
- `ball_by_ball_data.csv`
- `ipl_matches_data.csv`
- `players_data_updated.csv`
- `teams_data.csv`

All data cleaning, transformation, and modeling were performed inside **Power BI**.

---

## 🧠 Key Learnings
- Translating **business requirements into BI solutions**
- Writing effective **DAX measures**
- Designing clean **data models**
- Building dashboards focused on **data storytelling**
- Improving usability through slicers and visuals

---

## 🙏 Acknowledgements
This project was developed using the foundational Power BI concepts learned from **Codebasics**.  
The training helped strengthen my understanding of DAX, data modeling, and dashboard design best practices.

---

## 📸 Dashboard Preview
_Add screenshots of your final dashboard here_

---

## 🚀 Future Enhancements
- Net Run Rate (NRR) calculations  
- Advanced DAX performance optimization  
- Drill-through pages for team & player analysis  

---

## 📬 Feedback
Feedback and suggestions are welcome.  

This project is part of my ongoing learning journey in **Data Analytics & Business Intelligence**.
