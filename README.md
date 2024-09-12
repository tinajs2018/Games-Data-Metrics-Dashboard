# Games-Data-Metrics-Dashboard
## Overview
This project focuses on building a Google Looker Studio Dashboard that visualizes data for game players based on metrics such as college, position, weight, height, age, and salary. The goal is to allow for easy analysis and insights into player attributes and their salaries across different teams and positions.

## Dataset
The dataset used in this project contains information about various game players, including the following key metrics:

College: The college the player attended.
Position: The position of the player (e.g., forward, guard, center).
Weight: The player’s weight.
Height: The player’s height.
Age: The player’s age.
Salary: The player's salary in the most recent season.

### You can find the data here if you'd like to explore it.https://drive.google.com/file/d/1owTqTO-TbfD4g29yifsqH9Gvg9ht4jHD/view?usp=drive_link


# Project Goals
The primary objective of this project was to:

Analyze player attributes across various metrics.
Visualize the distribution of player salaries, positions, and physical attributes.
Enable dynamic filtering by different player characteristics like college and position.
# Tools Used
Google Sheets: For initial data storage and cleanup.
Google Looker Studio: For dashboard creation and visualization.
GitHub: For project documentation and version control.

# Steps to Build the Dashboard
## Step 1: Data Preparation
Collected data on players with attributes like college, position, weight, height, age, and salary.
Cleaned and formatted the data in a CSV file using Google Sheets.
Removed missing values.
Standardized the units for weight (in lbs) and height (in inches).
Saved the dataset for use in the dashboard.

## Step 2: Load Data into Google Looker Studio
Uploaded the CSV file to Google Sheets to act as the data source.
Connected Google Sheets to Google Looker Studio:
Opened Google Looker Studio.
Created a new report and added the Google Sheets data source.

## Step 3: Design the Dashboard
Bar Chart for player count by college:
Dimension: College
Metric: Count of Players
Pie Chart for player position distribution:
Dimension: Position
Metric: Count of Players
Scatter Plot for weight vs height:
Dimension 1: Weight
Dimension 2: Height
Age Distribution:
Histogram or bar chart to visualize the age distribution of players.
Table for Salary Data:
Displayed a table with columns for Player Name, Position, College, and Salary.

## Step 4: Add Filters for Interactivity
Added filters for College and Position to allow users to narrow down the dataset and explore specific groups of players.
Step 5: Customize the Dashboard
Customized the look and feel by choosing a consistent color scheme, font style, and layout.
Added text descriptions to provide context for each visualization.
Step 6: Publish and Share
Shared the dashboard with stakeholders by generating a public link and ensuring permissions were set correctly.
Step 7: Maintain and Update
Enabled automatic data refresh in Looker Studio to keep the dashboard up to date as new player data becomes available.

# Dashboard Screenshots
![Dashboard Screenshot](https://github.com/tinajs2018/Games-Data-Metrics-Dashboard/raw/main/Screenshot%20from%202024-09-12%2021-06-42.png)

# Future Improvements
Add new metrics such as player performance stats or injury reports.
Improve the interactivity by adding more filters (e.g., age range, salary range).
Integrate external data sources such as APIs for live updates

# Live Dashboard
You can access the live dashboard here.
https://lookerstudio.google.com/reporting/3222f1db-d5d7-413e-a940-d1934b1c5237
