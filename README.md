# spacex-data-science-project

This project collects and analyzes SpaceX launch data using the SpaceX API and web scraping techniques.

## Project Overview

### The goal of this project is to:

Collect launch data from SpaceX API
Perform web scraping of additional launch information
Clean and structure the dataset for analysis
Prepare data for further visualization and modeling

### Files

1_api_data_collection.ipynb → Data extraction using SpaceX API
2_web_scraping.ipynb → Web scraping from Wikipedia
dataset_part_1.csv → Cleaned dataset from API
spacex_web_scraped.csv → Dataset from web scraping

### Technologies Used
Python
Pandas
Requests
BeautifulSoup

### Objective

Collect SpaceX launch data (API + web scraping)
Clean and structure datasets for analysis
Explore launch success factors
Build interactive dashboards for data visualization
Enable dynamic exploration of launch performance by site and payload

Features
Interactive dropdown menu to select launch sites
Pie chart showing success vs failure rates
Payload range slider for filtering data
Scatter plot showing correlation between payload mass and launch success
Booster version analysis using color encoding
Tools Used
Dash (web application framework)
Plotly (interactive visualizations)
Pandas (data manipulation)
How to Run the Dashboard

Run the following command in terminal:

python spacex-dash-app.py

Then open:

http://127.0.0.1:8050/
Dashboard Preview

Screenshots of the working dashboard:

Pie chart showing overall launch success
Interactive dropdown filtering by launch site
Scatter plot showing payload vs success outcome

(Images are available in the /screenshots folder)




