# Streaming Apps Content Analysis Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Data%20Prep-Power%20Query-217346?style=for-the-badge)
![DAX](https://img.shields.io/badge/Analytics-DAX-0F6CBD?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Project-BI%20Dashboard-1F1F1F?style=for-the-badge)

## Overview

This Power BI project analyzes the content libraries of major streaming platforms, including **Netflix**, **Amazon Prime Video**, and **Disney+/Hotstar**.

The dashboard is designed to help users compare platform-level content strategies through interactive visuals, KPIs, filters, and trend analysis. It focuses on understanding how each platform differs in terms of content volume, movies vs TV shows, release trends, ratings, genres, directors, and audience classification.

The final report provides a clean, executive-style view of OTT content distribution and turns raw entertainment datasets into an interactive business intelligence solution.

---

## Dashboard Preview

### Netflix Dashboard

![Netflix Dashboard](dashboard-snaps/netflix-dashboard.png)

### Amazon Prime Dashboard

![Amazon Prime Dashboard](dashboard-snaps/amazon-prime-dashboard.png)

### Disney+/Hotstar Dashboard

![Disney Hotstar Dashboard](dashboard-snaps/disney-hotstar-dashboard.png)

---

## Business Objective

Streaming platforms invest heavily in content acquisition and production. However, raw title-level datasets do not clearly show how each platform positions its content library.

This dashboard was built to answer questions such as:

- How much content does each platform offer?
- What is the split between movies and TV shows?
- Which ratings and genres dominate each platform?
- How has content availability changed across release years?
- Which directors, content categories, and durations appear most frequently?
- How do Netflix, Amazon Prime, and Disney+/Hotstar differ from a content strategy perspective?

---

## Key Highlights

- Built a multi-page Power BI report for three streaming platforms
- Designed separate analytical views for Netflix, Amazon Prime, and Disney+/Hotstar
- Used Power Query to clean and prepare CSV datasets
- Fixed data source path issues and CSV parsing errors
- Created KPI cards, slicers, trend visuals, donut charts, and category breakdowns
- Added platform-specific visual themes for better storytelling
- Exported the report as a PDF for easy sharing
- Organized the project for GitHub portfolio presentation

---

## Tools & Skills Used

| Category      | Tools / Skills                                            |
| ------------- | --------------------------------------------------------- |
| BI Tool       | Power BI Desktop                                          |
| Data Cleaning | Power Query                                               |
| Analytics     | DAX Measures                                              |
| Data Source   | CSV Files                                                 |
| Visualization | KPI Cards, Donut Charts, Bar Charts, Line Charts, Slicers |
| Reporting     | Interactive Dashboard Design                              |
| Versioning    | GitHub                                                    |

---

## Dashboard Pages

### 1. Netflix Analysis

The Netflix dashboard focuses on title-level analysis with additional IMDb and awards-related information where available.

Key metrics include:

- Total titles
- Movies and TV shows
- Movie percentage
- IMDb score analysis
- Awards-related insights
- Release year trend
- Genre and rating distribution
- Director and title-level filtering

---

### 2. Amazon Prime Analysis

The Amazon Prime dashboard provides a detailed view of the platform’s content catalog.

Key metrics include:

- Total Amazon Prime titles
- Movie vs TV show distribution
- Rating breakdown
- Release year trend
- Genre/category analysis
- Duration analysis
- Director and title filters

---

### 3. Disney+/Hotstar Analysis

The Disney+/Hotstar dashboard highlights content distribution and audience classification.

Key metrics include:

- Total platform titles
- Movies and TV shows
- Rating distribution
- Year-wise content trend
- Genre-level breakdown
- Duration-based filtering
- Interactive slicers for detailed exploration

---

## Data Preparation Process

The datasets were cleaned and prepared in Power Query before dashboard development.

Key preparation steps included:

1. Imported multiple CSV datasets into Power BI
2. Reconnected local data source paths after opening the PBIX file
3. Fixed CSV parsing issues caused by quotation and column mismatch errors
4. Removed unnecessary error rows
5. Standardized data types for release year, title, rating, and duration fields
6. Handled missing and inconsistent values
7. Prepared separate platform-level tables for reporting
8. Validated fields used across visuals and slicers

---

## Analytical Approach

The report was structured to move from high-level KPIs to deeper content exploration.

The analysis includes:

- Platform-level content count
- Movies vs TV shows comparison
- Rating classification
- Release year trends
- Genre and category distribution
- Director-level exploration
- Duration-based segmentation
- IMDb and awards-related analysis for Netflix data

This approach makes the dashboard useful for both quick executive review and detailed platform-level analysis.

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
