# CS122-Final-Project
## Project Title: CS122 Final Project
## Authors: Evelyn Widor & Sunny Doan
## Description: 
### For our final project, we intend to use Steam's API. With this API we intend to pull information on Steam's extensive catalog of published games. We plan to then use this information to generate graphs that group based on genre or tags. Data that we are looking to analyze are the average costs and ratings of games. With the GUI we are planning to make, users would be able to select data they'd like to visualize and graphs would be locally generated.
## Project Outline/Plan:
### Interface: GUI toggling what value you are generating a graph based on.
### Data Collection and Storage Plan: 
- Data Collection will be done through the Steam Web free API key and Steam Store API
- Save raw JSON responses in `data/raw/`, then write the cleaned table to `data/processed/games.csv` (or a SQLite database).
### Data Analysis and Visualization Plan: Bar graph of the average cost/ratings of games grouped by genre.
## .gitignore: `python` `.env` `data/`
## License: BSD-3
