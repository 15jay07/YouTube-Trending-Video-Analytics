# YouTube Trending Video Analytics | Power BI Dashboard

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)

A data-driven analysis of YouTube trending videos to understand category performance, viewer engagement behavior, sentiment patterns, and content popularity trends.

Built using **Power BI**, **Python**, **SQL**, and **DAX**, this project analyzes **40,000+ trending videos** and visualizes key insights to support content strategy decisions.

---

# Project Objectives

- Identify top-performing YouTube content categories
- Analyze sentiment distribution across video categories
- Study trending duration and viewer engagement metrics
- Understand changes in performance over time via time-series analysis
- Present data storytelling insights for business decision-making

---

# Tech Stack

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard & visualization |
| **Python** | Data cleaning & EDA |
| **SQL** | Structured storage & queries |
| **DAX** | Calculations & measures |
| **Excel / CSV** | Input data |

---

# Dataset

| Attribute | Details |
|-----------|---------|
| **Source** | Kaggle YouTube Trending Dataset | https://www.kaggle.com/datasets/thedevastator/youtube-trending-videos-dataset?select=youtube.csv  |
| **Rows** | ~40,000 records |
| **Columns** | 30+ attributes including views, likes, comment count, category, publish date, tags |

> **Note:** Region-wise data was not included, so category segments were used as region-equivalent analysis for storytelling purposes.

---

# Dashboard Features

### Dashboard 1: KPI Overview
- Total Views
- Distinct Videos
- Average Sentiment
- Average Views
- Top Channels
- Time-Series Trend Analysis

### Dashboard 2: Deep Category Insights
- Total Views by Category
- Average Views by Category
- Sentiment Heatmap by Category
- Trending Duration Across Categories

---

# Key Insights

| Category | Finding |
|----------|---------|
| **Music** | Dominates in views & high audience interaction |
| **Film & Animation** | Strong average views but lower retention |
| **Neutral Sentiment** | Most common emotional tone across trending videos |
| **Trending Duration** | Stable across categories (average ~12–15 days) |

---

# Data Storytelling Summary

Trending videos succeed when:

- They belong to highly engaging genres such as **Music** or **Film & Animation**
- Titles and presentation encourage **neutral emotional response**
- Content sustains relevance over **extended trending days**
- Viewer engagement patterns suggest **consistency matters more than spikes**

---

# Repository Structure
youtube-trending-analytics/
│
├── data/
│ └── youtube_trending_data.csv
│
├── PowerBI_Report/
│ └── YouTube_Analytics_Dashboard.pbix
│
├── images/
│ └── dashboard_screenshots
│
└── README.md


---

# Future Improvements

- Add country-wise comparison once region-based dataset is available
- Build prediction model for video trending probability

---

# Author

**Jay Shankar Giri**

Data Analyst | Power BI | Python | SQL

---

# Show Your Support

If you found this project helpful, please consider giving it a **star** ⭐
