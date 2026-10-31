# Fixed Arsha + Flask + Tableau project

## Run on Windows (VS Code PowerShell)

1. Open this extracted folder in VS Code.
2. Open Terminal > New Terminal.
3. Create a virtual environment (only if you do not already have one):
   `python -m venv venv`
4. Activate it:
   `Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass`
   `.\\venv\\Scripts\\Activate.ps1`
5. Install Flask:
   `python -m pip install -r requirements.txt`
6. Start:
   `python app.py`
7. Open https://olympic-sports-performance-analysis.onrender.com

## What was fixed

- Flask `/` now renders `index_flask_ready.html`, which is the customized Olympic Analytics page.
- Static assets are in the standard `static/assets/` structure expected by the page's `url_for('static', filename='assets/...')` references.
- The Dashboard and Story routes now have template pages.

## Tableau URLs

The dashboard/story pages currently contain placeholders. Replace each `src` in `templates/dashboard.html` and `templates/story.html` with the corresponding published Tableau view/story URL when you have them. Ensure Tableau sharing permissions allow the intended viewers.

The `venv` folder is intentionally not included; it is machine-specific and should be recreated on your computer.
