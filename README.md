# Amazon_Prime_Video_Dashboard

## Project Overview

An interactive Power BI dashboard designed to analyze the Prime Video catalog, track core content distribution metrics (9,655 Total Titles, 7.81K Movies, 1.85K TV Shows), and identify release trends and regional availability across global markets.

---

## Short Description

This report provides a comprehensive view of the Prime Video streaming library, evaluating content types (Movies vs. TV Shows), maturity ratings, release year growth trends, and geographical distribution across countries.

---

## Tech Stack

- **Power BI Desktop:** Used as the core business intelligence platform to design interactive layouts and visual reports.
- **Power Query:** Utilized for data cleaning, transforming raw catalog data, and handling null values or text formats.
- **Calculated Measures:** Applied basic DAX formulas to create key metrics (Total Titles, Content Counts, Rating aggregations).
- **Data Architecture:** Single-table catalog data model focused on clean presentation and smooth usability.

---

## Data Source

- **Dataset Name:** Prime Video Movies and TV Shows Dataset (Kaggle)
- **Key Attributes:** Show ID, Type, Title, Director, Cast, Country, Date Added, Release Year, Rating, Duration, and Listed In (Genres).

---

## Features & Highlights

### Business Questions Addressed
- What is the overall proportion of Movies compared to TV Shows on the platform?
- Which maturity ratings (e.g., 13+, 16+, ALL, 18+) dominate the catalog?
- How has content production and addition grown over the years based on release trends?
- Which regions/countries contribute the highest number of titles to the platform?

---

### Walkthrough of Key Visuals
- **Top KPI Cards:** Direct view of Total Titles (9,655), Total Rating (25), Total Categories (519), Total Directors (5,771), Start Date (1920), and End Date (2021).
- **Bar Charts:** Showcasing Genres by Total Shows (Drama leading with 986) and Ratings by Total Shows (13+ leading with 2.1K).
- **Geographic Map:** Count of shows distributed across global countries (Total Shows by Country).
- **Donut Chart:** Visual breakdown of Movies (7.81K) vs. TV Shows (1.85K).
- **Line/Area Chart:** Total shows tracking growth by release year (Total Shows by Release Year).

---

## How to Use

1. Download the `.pbit` (Power BI Template) file and the dataset `.csv` file from this repository.
2. Open the `.pbit` file in Microsoft Power BI Desktop.
3. Connect the dataset source when prompted to load the interactive dashboard locally.
4. Check out the `Snapshot of the Dashboard.png` for a quick preview of the final design!

---

## Key Insights

- **Content Dominance:** Movies (7.81K) significantly dominate compared to TV Shows (1.85K) in the dataset.
- **Release Growth:** Growth in content releases and additions increased exponentially over time, especially post-2000.
- **Genre Popularity:** Drama (986) and Comedy (536) are the most dominant content genres on the platform.

---

## Dashboard Preview

![Snapshot of the Dashboard](Snapshot%20of%20the%20Dashboard.png)

---

## Author

**Divyani Tiwari** | B.Sc. Computer Science & Mathematics Student | Aspiring Data Analyst

