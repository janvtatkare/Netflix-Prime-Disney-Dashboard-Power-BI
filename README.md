# Netflix, Amazon Prime & Disney+ Hotstar Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Data%20Prep-Power%20Query-217346?style=for-the-badge)
![DAX](https://img.shields.io/badge/Analytics-DAX-0F6CBD?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Project-BI%20Dashboard-1F1F1F?style=for-the-badge)

## Overview

This Power BI dashboard analyzes content across **Netflix**, **Amazon Prime Video**, and **Disney+ Hotstar**. It provides a platform-wise view of movies, TV shows, ratings, genres, directors, duration, release trends, IMDb scores, and awards-related insights.

The goal of this project was to convert raw OTT datasets into a clean, interactive, and business-ready dashboard for content comparison and visual storytelling.

---

## Dashboard Preview

### Netflix Dashboard

<img src='dashboard_snaps\netflix_dashboard.jpg' class="center">

### Amazon Prime Dashboard

<img src='dashboard_snaps\amazon_prime_dashboard.png' class="center">

### Disney+ Hotstar Dashboard

<img src='dashboard_snaps\disney_dashboard.png' class="center">

---

## Key Features

- Multi-page Power BI report for Netflix, Amazon Prime Video, and Disney+ Hotstar.
- Platform-wise comparison of movies, TV shows, ratings, genres, duration, and release trends.
- Interactive slicers, KPI cards, donut charts, bar charts, and trend visuals.
- Power Query transformations for cleaning and preparing CSV datasets.
- DAX measures used for summary metrics and dashboard calculations.
- Clean dashboard layout designed for portfolio and business presentation use.

---

## Tools & Skills Used

| Category        | Tools / Skills                                            |
| --------------- | --------------------------------------------------------- |
| BI Tool         | Power BI Desktop                                          |
| Data Cleaning   | Power Query                                               |
| Analytics       | DAX                                                       |
| Data Source     | CSV Files                                                 |
| Visualization   | KPI Cards, Slicers, Donut Charts, Bar Charts, Line Charts |
| Version Control | GitHub                                                    |

---

## Data Preparation

The datasets were cleaned and prepared in Power Query before building the dashboard.

Key steps included:

- Imported Netflix, Amazon Prime, and Disney+ Hotstar CSV datasets.
- Reconnected local data source paths for refresh.
- Fixed CSV parsing and column mismatch issues.
- Standardized data types for title, release year, rating, duration, and category fields.
- Removed unnecessary errors and prepared clean platform-level tables.

---

## Repository Structure

```text
Netflix-Prime-Disney-Dashboard-Power-BI/
│
├── README.md
├── Streaming_Apps_Analysis.pbix
├── Streaming_Apps_Analysis.pdf
│
├── dataset/
│   ├── amazon_prime_titles.csv
│   ├── disney_plus_titles.csv
│   ├── netflix_titles.csv
│   ├── netflix-rotten-tomatoes-metacritic-imdb.csv
│   └── NetflixOriginals.csv
│
└── dashboard-snaps/
    ├── netflix-dashboard.png
    ├── amazon-prime-dashboard.png
    └── disney-hotstar-dashboard.png
```

---

## Author

**Janhavi Tatkare**
Data Analyst
Power BI | SQL | DAX | Data Analytics |
