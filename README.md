# Power-BI_Dashboard
Project Overview:
This project provides a deep-dive analysis of the Spotify Top 50 Global Songs dataset, encompassing over 27,800 rows of streaming data. The goal is to identify the underlying patterns that drive song popularity, analyze seasonal release trends, and visualize the impact of content characteristics (like "Explicitness" and "Album Type") on global rankings.

Key Metrics Tracked:
Average Popularity Score: ~86/100

Average Song Duration: 2.85 Minutes

Total Track Count: Comprehensive analysis of global chart leaders.
Tech Stack & Methodology
Business Intelligence: Microsoft Power BI Desktop

Data Transformation: Power Query (ETL process to clean and normalize duration and date formats)

Analytical Engine: DAX (Data Analysis Expressions) for dynamic measures:

Avg Popularity = AVERAGE(Spotify[Popularity])

Track Count = DISTINCTCOUNT(Spotify[Track_Name])

Data Source: Spotify Global Daily Charts (via Kaggle/Spotify API).
Dashboard Insights
1. Monthly Popularity Trends
The analysis reveals a peak in average popularity during the mid-year (June-July), suggesting that "Summer Hits" dominate the global top 50 more consistently than winter releases.

2. Album Type Distribution
Singles: 52.33% (Dominant format for chart entry)

Albums: 47.67%
