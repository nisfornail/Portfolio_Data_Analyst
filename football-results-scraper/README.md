# Primeira Liga Match Stats (2017/18–2024/25)

This notebook collects **results and detailed match statistics** for the Portuguese top-1 tier championship (Liga Portugal / Primeira Liga / https://www.football-data.co.uk/portugalm.php), 
and produces clean CSVs and summary tables (Top-5 per season, team summaries, win%, goals, shots on target, etc.).  
It can also be adapted to **download historical stats for many other national leagues** that follow the same public CSV schema (https://www.football-data.co.uk/).

## What it does
- Downloads league match CSVs (season-by-season).
- Builds full league tables and **Top-5** for each season.
- Computes team summaries (e.g., **Sporting** and **Benfica**):  
  Points, Place, Goals For/Against, Goal Difference, Win% (overall & home), **shots on target (team/opponent totals)**, and average totals per match.
- Saves results to CSV.

## Files
- `football matches web scraping.ipynb` — main notebook.
- Output CSVs include raw files (they are downloaded during execution of the code):
  - `P1_1718_2017-18.csv`
  - `P1_1819_2018-19.csv`
  - `P1_1920_2019-20.csv`
  - `P1_2021_2020-21.csv`
  - `P1_2122_2021-22.csv`
  - `P1_2223_2022-23.csv`
  - `P1_2324_2023-24.csv`
  - `P1_2425_2024-25.csv`
- Output CSVs include processed files (they are prepared during execution of the code):  
  - `primeira_liga_top5_1718_2425.csv`  
  - `sporting_benfica_totals_per_season_1718_2425.csv`  
  - `sporting_benfica_totals_in_1718_2425.csv.csv`
