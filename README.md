# 🏆 FIFA World Cup 2026 — Power BI Data Analytics Dashboard

## 📊 Project Overview

This project is an interactive Power BI dashboard designed to analyze and visualize FIFA World Cup 2026 data.

The dashboard provides insights into tournament statistics, team performance, player achievements, match results, goal distribution, stadium utilization, and participating countries.

The goal of this project is to transform complex football data into an interactive and visually engaging analytical report using Power BI.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze FIFA World Cup 2026 tournament statistics
- Evaluate team performance
- Analyze player goals and saves
- Identify top-performing teams and players
- Analyze goal distribution across teams
- Analyze stadium-wise match hosting
- Explore match-level details
- Create an interactive Power BI dashboard
- Demonstrate data modeling and DAX skills

---

## 📌 Key Performance Indicators

The dashboard provides the following key metrics:

| KPI | Value |
|---|---:|
| Total Matches | 104 |
| Total Goals | 308 |
| Total Teams | 48 |
| Average Goals per Match | 2.96 |
| Total Players | 1,248 |
| Total Venues | 16 |

---

## 📊 Dashboard Features

### 🏆 Tournament Overview

The overview page provides a high-level summary of the FIFA World Cup 2026 tournament.

It includes:

- Total Matches
- Total Goals
- Total Teams
- Average Goals per Match
- Total Players
- Total Venues

---

### ⚽ Team Analysis

The dashboard analyzes team-level performance through:

- Top 5 Teams by Goals
- Top 5 Teams by Saves
- Team-wise Goal Distribution
- Participating Countries

---

### 👟 Player Analysis

Player performance is analyzed using:

- Top 10 Players by Goals
- Highest Goal Scoring Player
- Highest Saves by Player
- Player-level performance analysis

---

### 🏟️ Stadium Analysis

The dashboard provides insights into stadium utilization, including:

- Total Matches by Stadium
- Number of matches hosted by each stadium
- Stadium-level tournament analysis

---

### 🎮 Match Analysis

Detailed match-level information includes:

- Home Team
- Home Score
- Away Team
- Away Score
- Player of the Match
- Referee

---

### 🎛️ Interactive Filters

Users can dynamically filter the dashboard using:

- Teams
- Players
- Tournament Stage
- Stadium

These filters allow users to explore the data from different perspectives.

---

## 🛠️ Tools & Technologies

- **Power BI** — Dashboard development and visualization
- **DAX** — Calculated measures and KPIs
- **Power Query** — Data transformation and cleaning
- **Data Modeling** — Relationships between multiple data tables
- **Data Visualization** — Interactive analytical storytelling

---

## 🗂️ Data Model

The Power BI data model contains multiple tables related to tournament, team, player, match, venue, and referee information.

### Main Tables

- `matches`
- `matches_detailed`
- `match_team_stats`
- `match_prediction_features`
- `match_events`
- `match_lineups`
- `player_stats`
- `squads_and_players`
- `teams`
- `tournament_stages`
- `venues`
- `referees`
- `Measure Table`

The model connects match-level data with team, player, venue, tournament stage, and other supporting information.

---

## 🧮 Example DAX Measures

### Total Matches

```DAX
Total Matches =
DISTINCTCOUNT(matches[match_id])
