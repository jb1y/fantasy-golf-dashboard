Masters Fantasy Golf Dashboard

An interactive fantasy golf dashboard built in Tableau with a supporting Python data pipeline.

The project was created to track a private fantasy league during the Masters Tournament, combining live leaderboard data, custom fantasy scoring, player scorecards, trend analysis, and available-player tracking in one dashboard.

Project summary

The dashboard allows users to:
	•	follow the current fantasy league standings
	•	track how each user’s score develops over time
	•	inspect drafted golfers hole by hole
	•	compare score breakdowns and bonus categories
	•	monitor undrafted players during the tournament

How it was built

The project consists of two parts:
	•	Python for collecting, cleaning, and structuring tournament data
	•	Tableau for the dashboard, calculations, interactivity, and visual design

The Python script pulls data from ESPN golf leaderboard and player summary pages, processes hole-by-hole results, applies custom fantasy logic, and exports CSV files that are used as data sources in Tableau.

Main features
	•	fantasy leaderboard with score breakdown
	•	user-specific golfer scorecards
	•	trend graph for fantasy score development
	•	KPI cards for best golfer, tie-break, and holes remaining
	•	list of currently available players
	•	interactive user selection and filtering

Tools used
	•	Python
	•	pandas
	•	requests
	•	NumPy
	•	Tableau

Purpose

This project was built as a practical sports analytics / BI project combining:
	•	real-world data collection
	•	dashboard design
	•	custom scoring logic
	•	interactive visual analysis

It is also intended as a portfolio project to demonstrate applied skills in data processing, analytics, and dashboard development.

Repository contents

This repository contains:
	•	project description
	•	dashboard screenshots
	•	supporting Python code
	•	Tableau Public link after publication
