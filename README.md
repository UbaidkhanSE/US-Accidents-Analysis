# US-Accidents-Analysis
# Overview
This project involves analyzing a dataset of traffic accidents in the United States to identify trends and visualize accident hotspots. The dataset includes various attributes such as weather conditions, road conditions, time of the accident, and geographical location.

# Dataset
The dataset used for this analysis is US_Accidents_March23.csv, which contains data on traffic accidents across the United States up to March 2023.

data/: Contains the dataset used for analysis.
notebooks/: Contains the Jupyter notebook used for the analysis.
output/: Contains the output files such as visualizations and HTML maps.
README.md: Detailed overview of the project.
requirements.txt: List of Python packages required to run the analysis.

# Requirements
To run the analysis, you need to have the following Python packages installed:

pandas
numpy
matplotlib
seaborn
folium
You can install the required packages using the following command:

# Analysis Steps
Loading the Dataset: The dataset is loaded into a Pandas DataFrame for analysis.
Data Preprocessing: The 'Start_Time' and 'End_Time' columns are converted to datetime objects, and rows with missing datetime values are dropped.
Feature Extraction: Hour, month, and day of the week are extracted from the 'Start_Time' column.
Grouping Data: Data is grouped by weather conditions, road conditions, hour of the day, day of the week, and month to identify trends.
# Visualizations:
Hourly Trend: Number of accidents by hour of the day.
Daily Trend: Number of accidents by day of the week.
Monthly Trend: Number of accidents by month.
Weather Conditions: Top 10 weather conditions during accidents.
Road Conditions: Top 10 road conditions during accidents.
Accident Hotspots Visualization: A heatmap is created to visualize accident hotspots using Folium.

Hourly Trend

Daily Trend

Monthly Trend

Top 10 Weather Conditions During Accidents

Top 10 Road Conditions During Accidents

Accident Hotspots

# Usage
To run the analysis, open the Jupyter notebook US_Accidents_Analysis.ipynb and execute the cells in order. Ensure the dataset is placed in the data/ directory.

# Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes. Ensure your code follows the project structure and coding standards
