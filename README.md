# Olympic Sports Performance Analysis

## Project Documentation
- [Document 1 — Project Overview and Description](docs/01_PROJECT_OVERVIEW.pdf)
- [Document 2 — Data Analysis and Methodology](docs/02_DATA_ANALYSIS.pdf)
- [Document 3 — Visualization and Dashboard](docs/03_VISUALIZATION_AND_DASHBOARD.pdf)
- [Document 4 — Results and Conclusion](docs/04_RESULTS_AND_CONCLUSION.pdf)

## Project Links
- **Live Website:** [https://olympic-sports-performance-analysis.onrender.com](https://olympic-sports-performance-analysis.onrender.com)
- **GitHub Repository:** [https://github.com/KoshikiChouksey/olympic-sports-performance-analysis](https://github.com/KoshikiChouksey/olympic-sports-performance-analysis)
- **Tableau Public Profile:** [https://public.tableau.com/app/profile/koshiki.chouksey/vizzes](https://public.tableau.com/app/profile/koshiki.chouksey/vizzes)

> If you have a direct public URL for the specific Tableau dashboard or story, replace the profile link with that direct workbook link.

## Project Overview
Olympic Sports Performance Analysis is a data-visualization project built with Tableau and a Flask web application. It explores sports-performance measures across countries, athletes, sports, regions, and years. The website provides access to the project's dashboard and story pages.

## Dashboard Highlights
- Medal distribution by country
- Medal trends over time
- Average medals per athlete and country metrics
- Regional efficiency and sport-category distribution
- Investment-versus-medal comparisons
- Host-country comparisons

## Technology Stack
- **Tableau** — visual analysis and dashboards
- **Python / Flask** — website routes and page rendering
- **HTML / CSS** — website templates
- **Gunicorn** — production WSGI server
- **Render** — hosting
- **GitHub** — source-code repository

## Data and Interpretation Note
The project context describes demonstration data covering 1992–2026, 60 countries, and 50 sports, with approximately 4,652 athlete records, 3,164 medal-result records, and 1,010 country-year summaries. Verify these figures against the final workbook before submission. If the dataset is synthetic or illustrative, do not present its patterns as verified historical Olympic facts. An investment-versus-medal association does not prove causation.

## Run Locally
1. Install Python.
2. Open the project folder in a terminal.
3. Install dependencies: `pip install -r requirements.txt`
4. Run `python app.py`.
5. Open `http://127.0.0.1:5000`.

The production start command is `gunicorn app:app`.

## Author
Academic project on Olympic sports performance analysis.


