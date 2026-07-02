# Fandango Movie Ratings Analysis

Analyzed whether Fandango inflates its displayed movie ratings compared to true user ratings, using Python and Pandas. Compared results against Rotten Tomatoes, Metacritic, and IMDB scores.

## Key Findings
- Fandango's displayed STARS were consistently higher than the true RATING
- **Taken 3** was the biggest offender — 4.5 stars on Fandango vs. average of 1.86 on other platforms
- Strong correlation (~0.99) between displayed and true ratings, but consistently shifted upward

## Tech Stack
Python, Pandas, Seaborn, Matplotlib, Jupyter Notebook

## Files
- `00-Capstone-Project.ipynb` – analysis notebook
- `fandango_scrape.csv`, `all_sites_scores.csv` – datasets
