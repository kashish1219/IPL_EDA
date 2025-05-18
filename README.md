# 📊 IPL Data Analysis (2008–2024)

This project explores trends and patterns in the Indian Premier League (IPL) using historical match data from the league's inception in 2008 through 2024.

## 🏏 Project Objectives

- Identify the **most successful IPL team** based on win percentage.
- Investigate the **impact of toss outcomes** on match results.
- Explore whether **specific venues** influence the toss advantage.
- Debunk common myths around **toss bias** and **match fixing speculation** using data.
- (Optional future work) Analyze **team-wise dependency** on toss outcomes.

## 📁 Dataset

- `matches.csv`: Contains IPL match-level data including team names, toss results, match winners, and venues.

## 📌 Key Insights

- **Chennai Super Kings** emerged as the most successful team with the highest win percentage (excluding teams with fewer than 50 matches).
- Teams that won the toss won the match **~50.6%** of the time — suggesting **no strong toss bias**.
- Toss impact remained mostly consistent across **years and venues**, averaging around **50%**.
- Analysis supports that match outcomes are likely determined by **team performance**, not toss results.

## 📈 Visualizations

- Bar chart of **win percentages** across teams.
- Season-wise **toss win impact**.
- Venue-wise **toss advantage rates**.
- Win percentage labels added to charts for easy interpretation.

## 🧠 Skills Used

- Data Cleaning & Preprocessing
- Grouping and Aggregation
- Mapping for name standardization
- Boolean logic in feature creation
- Matplotlib & Seaborn for Visualization
- Insight Communication with Data

## 🚀 How to Run

1. Clone the repository.
2. Install necessary packages:
   ```bash
   pip install pandas matplotlib seaborn
