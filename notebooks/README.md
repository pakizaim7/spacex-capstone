# SpaceX Capstone Project – Notebooks

This folder contains all Jupyter notebooks used in the SpaceX Falcon 9 capstone project.

Each notebook corresponds to a specific stage of the data science workflow required for the final peer-graded assignment.

## Notebook Overview

1. **spacex_api_data_collection.ipynb**
   - Collects SpaceX launch data using the SpaceX REST API.
   - Retrieves launch, rocket, payload, and landing outcome data.

2. **spacex_web_scraping.ipynb**
   - Scrapes Falcon 9 launch data from Wikipedia.
   - Extracts HTML tables and converts them into Pandas DataFrames.

3. **spacex_data_wrangling.ipynb**
   - Cleans and preprocesses the collected datasets.
   - Handles missing values and converts outcomes into binary labels.

4. **spacex_eda_visualization.ipynb**
   - Performs exploratory data analysis using data visualizations.
   - Includes scatter plots, bar charts, and line charts.

5. **spacex_eda_sql.ipynb**
   - Performs exploratory data analysis using SQL queries.
   - Analyzes launch sites, payload mass, and mission outcomes.

6. **spacex_folium_map.ipynb**
   - Builds interactive maps using Folium.
   - Visualizes launch site locations and landing outcomes.

7. **spacex_machine_learning.ipynb**
   - Builds and evaluates classification models.
   - Predicts Falcon 9 first-stage landing success.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL (SQLite)
- Folium
- Scikit-learn

These notebooks support the analysis and results presented in the final project presentation.

