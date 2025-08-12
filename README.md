# findliad.github.io

# Top UK YouTubers 2024 Dashboard

This project replicates the dashboard tutorial from [SDW Online](https://sdw-online.github.io/top_uk_youtubers_2024/), including data prep, SQL setup, and visualization in Tableau.

The primary difference is SDW used Microsoft Platforms like SQL Server and PowerBI - whereas I used Azure Data Studio on Mac and Tableu

## 🧠 Project Flow
1. Kaggle CSV → cleaned via Python script (`prep_youtube_uk.py`)
2. Data loaded into Dockerized SQL Server
3. Tableau Dashboard created with 6 custom measures:
   - Total Views (B)
   - Total Subscribers (M)
   - Views per Subscriber
   - Avg Views per Video (M)
   - Engagement Rate
   - Total Videos

## 🗂️ Contents
- `Product_Requirements_Documentation`: Problem Statement, Stakeholders, User Stories and Acceptance Criteria
- `prep_youtube_uk.py`: Cleans and enriches the Kaggle data with YouTube API
- `final_youtube_data.csv`: Final dataset used for visualization
- `Youtube_Visualization.twb`: Tableau packaged workbook
- `Images/`: Preview images of the dashboard
- `README.md`: This file

## 📊 Preview
![dashboard](Images/dashboard_complete.png)
