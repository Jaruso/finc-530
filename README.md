# FINC-530 · Financial Modeling & Forecasting

A week-by-week static portfolio of coursework for FINC-530 (Fall 2026), using the fictional biotechnology company TitanHelix Therapeutics.

## Site

GitHub Pages is served from the `docs/` folder on the `main` branch after Pages is enabled in repository settings. No build step, Python, or JavaScript framework is required.

## Organization

- `docs/index.html` — course homepage
- `docs/week-01/` through `docs/week-07/` — weekly pages
- `docs/assets/styles.css` — shared styling

The Week 1 page embeds the TitanHelix profile and downloads its workbook directly from `docs/week-01/TitanHelix.xlsx`. Export the workbook from Google Sheets, then commit that `.xlsx` file at exactly this path. GitHub Pages will serve the committed Excel file directly; no Google Sheets download URL or external access permission is required. The download button returns 404 until the file is committed. For future weeks, keep each workbook in its respective `docs/week-NN/` directory and use a relative `./<filename>.xlsx` link.

Course data and company information are synthetic; this site is a presentation portfolio and not a substitute for submitted Excel assignments.
