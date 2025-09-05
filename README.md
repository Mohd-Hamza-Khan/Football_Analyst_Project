# Football Analyst Project

This project analyzes and visualizes football (soccer) match data using Python. It leverages the [StatsBomb Open Data](https://github.com/statsbomb/open-data) to provide insights into Spain Women's team performance, focusing on passes and shots during a specific match.

## Features

- **Data Loading:**  
  Downloads and loads match event data from StatsBomb's open data repository.

- **Data Processing:**  
  - Transforms raw JSON event data into a pandas DataFrame.
  - Filters data for Spain Women's team passes and shots.

- **Visualization:**  
  - Draws a football pitch using `mplsoccer`.
  - Creates pass maps showing successful and unsuccessful passes.
  - Highlights passes by specific players (e.g., Olga Carmona García).
  - Creates a shot map, visualizing shot locations, outcomes, and expected goals (xG).

- **Analysis:**  
  - Counts and displays the number and proportion of passes by individual players.

## Requirements

- Python 3.x
- matplotlib
- mplsoccer
- pandas
- numpy
- requests

You can install the required packages using:
```bash
pip install matplotlib mplsoccer pandas numpy requests
```

## Author