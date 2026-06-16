# Movie Industry Dataset - Tableau Visualisation

A Tableau Public workbook exploring budget and revenue distributions across the
movie industry - rebuilding (and extending) the descriptive-statistics analysis
I first did in Excel (histograms, cumulative-frequency polygons, right-skew).

> **Data note:** `data/movies.csv` is a **sample dataset** (200 films) generated
> with a deliberately right-skewed budget distribution to mirror the real-world
> pattern. Replace with any public movie dataset (e.g. a Kaggle TMDB export) to
> extend it.

## Data (`data/movies.csv`)
movie_id, title, year, genre, budget_musd, revenue_musd, rating.

## Build it (free - Tableau Public, ~30 min)
1. Install **Tableau Public** (free) and **Connect -> Text file** -> `data/movies.csv`.
2. Sheets to create:
   - **Histogram** of `budget_musd` (create a bin on the measure) -> shows the right skew.
   - **Scatter:** `budget_musd` (x) vs `revenue_musd` (y), colour by `genre`, size by `rating`.
   - **Bar:** average `revenue_musd` by `genre`, sorted descending.
   - **Cumulative line** of count of films by budget bin (the cumulative-frequency polygon).
3. Combine the sheets into a **Dashboard**, add a `genre` and `year` filter.
4. **Publish to Tableau Public**, then put the public link at the top of this README
   and drop a screenshot in `/screenshots`.

## Skills demonstrated
Tableau Public, distribution analysis, binning, scatter/correlation,
dashboard design, descriptive statistics, data storytelling.
