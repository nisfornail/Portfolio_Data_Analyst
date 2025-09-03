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
- Output CSVs include (examples):  
  - `primeira_liga_top5_1718_2425.csv`  
  - `sporting_benfica_totals_per_season_1718_2425.csv`  
  - `sporting_benfica_totals_in_1718_2425.csv.csv`

## Quick start
```bash
# (Optional) create a venv
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate

# Install dependencies
pip install pandas requests beautifulsoup4 lxml jupyter

# Launch
jupyter lab  # or: jupyter notebook
