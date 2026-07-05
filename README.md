# Project 01 — Netflix EDA & Insights Report

**Pluto Academy AI & ML Internship — Project 01**

## Dataset
[Netflix Movies and TV Shows Dataset — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
File used: `netflix_titles.csv` (8,807 titles, official Kaggle file)

## Files in this repo
- `Netflix_EDA_Project.ipynb` — the complete, already-executed analysis notebook
- `netflix_titles.csv` — the dataset (same file used in the notebook)
- `README.md` — this file

## Data Flow / Workflow
1. **Load** `netflix_titles.csv` with Pandas → inspect shape, dtypes, missing values, duplicates.
2. **Clean** — fill `director`/`cast`/`country` missing values with `"Unknown"`; drop rows missing `date_added`/`rating`; parse `date_added` to datetime; split `duration` into value + unit; extract `year_added`, `month_added`, `primary_genre`, `primary_country`.
3. **Analyze** — answer 5 EDA questions (Movie vs TV split, top countries, titles added per year, top ratings, top genres + avg duration).
4. **Visualize** — 7 charts: bar (type split), bar (top countries), line (titles/year), histogram (duration), pie (ratings), scatter (duration vs release year), heatmap (month × year).
5. **Report** — 5 numbered insights + 5 business recommendations + a 3–5 line "most surprising finding" note, all written directly inside the notebook.

## Checklist Mapping
| Requirement | Where it is |
|---|---|
| GitHub repo (public, .ipynb + README) | This repo |
| Colab link (Anyone with link can view) | You generate this after uploading `Netflix_EDA_Project.ipynb` to Colab — see posting steps below |
| 6+ visualizations visible in output | 7 charts already rendered in the notebook (Step 4) |
| 5 numbered insights in plain English | "Step 5 — Insights Report" markdown cell |
| 3–5 line note on most surprising finding | Final markdown cell of the notebook |

## How to Post
1. Upload `Netflix_EDA_Project.ipynb` to Google Colab (**File → Upload notebook**).
2. In Colab's left sidebar, open the **Files** panel → upload `netflix_titles.csv` there (not through the notebook-open dialog).
3. Run **Runtime → Run all**, confirm all 7 charts render and no cell errors.
4. Click **Share → Anyone with the link → Viewer** → copy the link.
5. Create a public GitHub repo → upload `Netflix_EDA_Project.ipynb`, `netflix_titles.csv`, and this `README.md`.
6. Submit both links via the Google Form.
