# Code used for BlogPost

## Overview
This project was done to make a Blog post about Steam Data

## Features
- Extracts tag information from the top 50 Steam games
- Line graph of player count
- Creates a treemap visualization of the most popular tags
- Provides sorted data on tag popularity

## Requirements
- Python 3.13.1
- pandas
- matplotlib
- squarify
- numpy
- seaborn

## Installation
```bash
pip install pandas matplotlib squarify numpy seaborn
```

## Usage
1. Download and extract Zip File
2. Make sure the Jupiter Notebook file is in the same directory as Charts and SteamDB folder
3. Make sure the pd.read_csv('SteamDB_csv/SteamPlayers.csv) follows this to access the SteamDB_csv folder
4. Run all 

## Data Source
4 data sets are used included in SteamDB_csv Folder:
- `100 highest reviewed.csv`
- `Games released by Month.csv`
- `SteamPlayers.csv`
- `Top100 Steam games.csv`

## Analysis Insights
- Multiplayer, FPS, and Action tags dominate the Steam ecosystem
- Free to Play games have significant player numbers
- Competitive tags like eSports and PvP are highly represented

## Project Structure
For example:
- `BlogCode`: Main script that processes data and generates visualization
- `Top100 Steam games.csv`: Input data file with game information
- `Top 30 steam tags.png`: Output visualization

## Sources
SteamDB https://steamdb.info/charts/