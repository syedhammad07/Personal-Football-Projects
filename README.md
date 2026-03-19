# ⚽ Erling Haaland 2024/25 Season Analysis Dashboard

![Haaland Dashboard](dashboard.png)

## 📖 Overview
An automated, interactive data visualization tool designed to evaluate Erling Haaland's shot efficiency, spatial tendencies, and overall attacking impact for the 2024/25 Premier League season. 

This project bridges macro-level season statistics with micro-level event data, providing a dynamic platform for rapid scouting and performance reviews. It automatically updates after each matchweek, ensuring the analysis is always current without the need for manual data entry.

## ✨ Key Features
* **Live Data Pipeline:** Automatically fetches and updates match event data using the Understat API.
* **Interactive Shot Map & Heatmap:** Custom pitch mapping that visually represents shot locations and high-density "Golden Zones."
* **Granular Drill-Downs:** Interactive hover states reveal detailed metadata for every single shot event, including:
  * Expected Goals (xG) value
  * Match minute and date
  * Opponent
  * Assist provider
  * Shot outcome (Goal, Miss, Saved, etc.)
* **Macro Analytics Tracking:** Real-time tracking of Season Totals (Goals, Shots, Total xG, xG/Shot) and current Golden Boot race rankings.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Sourcing:** Understat API
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** Custom plotting 

## 🚀 Getting Started

### Prerequisites
Make sure you have Python 3.8+ installed. You will also need to install the required packages.

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/syedhammad07/Personal-Football-Projects.git](https://github.com/syedhammad07/Personal-Football-Projects.git)
