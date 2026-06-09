# Netflix-Prime-Disney-Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Data%20Prep-Power%20Query-217346?style=for-the-badge)
![DAX](https://img.shields.io/badge/Analytics-DAX-0F6CBD?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Project-BI%20Dashboard-1F1F1F?style=for-the-badge)

Overview

This Power BI dashboard analyzes content across three major streaming platforms: Netflix, Amazon Prime Video, and Disney+ Hotstar.

The dashboard provides a platform-wise view of movies, TV shows, ratings, genres, directors, duration, release trends, IMDb scores, and awards-related insights. The goal of this project is to turn raw OTT datasets into a clean, interactive, and business-ready analytics report.

Dashboard Preview

<img src='dashboard_snaps\netflix_dashboard.jpg' class="center">
<img src='dashboard_snaps\amazon_prime_dashboard.png' class="center">
<img src='dashboard_snaps\disney_dashboard.png' class="center">

Key Highlights
Created a multi-page Power BI dashboard for Netflix, Amazon Prime Video, and Disney+ Hotstar.
Built platform-specific views to compare movies, TV shows, ratings, genres, and release trends.
Used Power Query to clean and prepare multiple CSV datasets.
Fixed data source path issues and handled CSV parsing errors during refresh.
Added interactive slicers, KPI cards, donut charts, bar charts, and trend visuals.
Designed a clean visual layout for portfolio and business presentation use.
Tools & Technologies
Category Tools / Skills
BI Tool Power BI Desktop
Data Cleaning Power Query
Analytics DAX
Data Source CSV Files
Visualization KPI Cards, Slicers, Donut Charts, Bar Charts, Line Charts
Version Control GitHub
Analysis Covered

The dashboard focuses on answering key content analytics questions:

How much content is available on each streaming platform?
What is the split between movies and TV shows?
Which ratings and genres are most common?
How has content availability changed over release years?
Which directors and content categories appear frequently?
How do Netflix, Amazon Prime Video, and Disney+ Hotstar differ in content strategy?
Data Preparation

Data preparation was completed in Power Query before building the report visuals.

Key steps included:

Imported Netflix, Amazon Prime, and Disney+ Hotstar CSV datasets.
Reconnected local file paths for Power BI refresh.
Fixed CSV column mismatch and parsing issues.
Standardized data types for release year, title, rating, duration, and category fields.
Removed unnecessary errors and prepared clean platform-level tables.
Validated fields used across slicers, KPIs, and visual charts.
Repository Structure
Netflix-Prime-Disney-Dashboard-Power-BI/
│
├── README.md
├── Streaming Apps Analysis.pbix
├── Streaming_Apps_Analysis.pdf
│
├── dataset/
│ ├── amazon_prime_titles.csv
│ ├── disney_plus_titles.csv
│ ├── netflix_titles.csv
│ ├── netflix-rotten-tomatoes-metacritic-imdb.csv
│ └── NetflixOriginals.csv
│
└── dashboard snaps/
├── netflix-dashboard.png
├── amazon-prime-dashboard.png
└── disney-hotstar-dashboard.png
How to Use
Download or clone this repository.
Open Streaming Apps Analysis.pbix in Power BI Desktop.
If Power BI asks for data source paths, reconnect the CSV files from the dataset folder.
Click Refresh.
Explore the Netflix, Amazon Prime, and Disney+ Hotstar dashboard pages.
Project Outcome

This project demonstrates practical Power BI dashboard development skills, including data cleaning, data transformation, DAX-based analysis, interactive reporting, and visual storytelling. The final dashboard presents streaming platform insights in a clean and professional format suitable for portfolio presentation.

Author

Janhavi Tatkare
Data Analyst
Power BI | SQL | DAX | Data Analytics |
