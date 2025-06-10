# Sales Trend Analysis - Task 6

## Overview
This repository contains the solution for Task 6 of the Data Analyst Internship, focusing on sales trend analysis using SQL. The task analyzes monthly revenue and order volume from the `Online Sales Data.csv` dataset.

## Files
- `Online Sales Data.csv`: Input dataset.
- `results.txt`: Query results table.
- `screenshot.png` (optional): Screenshot of results from the online SQL editor.

## Methodology
- Created a table `online_sales` in SQLite.
- Used `strftime` to extract year and month from the `Date` column.
- Calculated total revenue with `SUM(Total_Revenue)` and order volume with `COUNT(DISTINCT Transaction_ID)`.
- Grouped by year and month, sorted chronologically.
- Added a query for the top 3 months by revenue using `ORDER BY Total_Revenue DESC LIMIT 3`.

## Results
The results show monthly revenue and order volume from January to August 2024. The top 3 months by revenue are March, January, and April 2024.
