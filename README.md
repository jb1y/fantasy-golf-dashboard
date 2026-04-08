# Masters Fantasy Golf Dashboard

An interactive fantasy golf dashboard built in Tableau with a supporting Python data pipeline.

The project was created to track a private fantasy league during the Masters Tournament, combining live leaderboard data, custom fantasy scoring, player scorecards, trend analysis, and available-player tracking in one dashboard.

## Project Summary

The dashboard allows users to:

- Follow the current fantasy standings
- Track how each user's score develops over time
- Inspect drafted golfers hole by hole
- Compare score breakdowns and bonus categories
- Monitor undrafted players during the tournament

## How It Was Built

The project combines:

- **Python** for collecting, cleaning, and structuring tournament data
- **Tableau** for calculations, interactivity, and dashboard design

The Python script pulls data from ESPN golf leaderboard and player summary pages, processes hole-by-hole results, applies custom fantasy scoring logic, and exports CSV files used as data sources in Tableau.

## Main Features

- Fantasy leaderboard with score breakdown
- User-specific golfer scorecards
- Trend graph for fantasy score development
- KPI cards for best golfer, tie-break, and holes remaining
- Available-player view
- Interactive user selection and filtering

## Tools Used

- Python
- pandas
- requests
- NumPy
- Tableau

## Note on Screenshots

The screenshots in this repository use data from the PGA Tour event the weekend before the Masters, which was used as a test event while building and validating the dashboard. The dashboard itself was designed for use during the Masters Tournament.

## Purpose

This project was built as a sports analytics / BI portfolio project combining real-world data collection, custom scoring logic, and interactive dashboard development.

## Repository Contents

- Project description
- Dashboard screenshots
- Supporting Python code
- Tableau Public link (after publication)
