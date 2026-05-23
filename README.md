# HR Analytics Dashboard (Power BI)

This repository contains the assets for an HR Analytics Power BI dashboard: visuals, documentation, and DAX measures.

What I did in this project
- Built a Power BI dashboard that shows key HR KPIs and attrition analysis.
- Created KPI cards: `Total Employees`, `Total Attrition`, `Attrition Rate`, `Active Employee`.
- Added visuals: age-distribution by gender, attrition by age, department-wise attrition (donut), attrition by job role, job satisfaction table, and attrition by education field.
- Added slicers for gender, marital status, travel frequency, and education field to enable interactive filtering.

DAX measures used
- See `docs/dax_measures.md` for the exact formulas used in the dashboard.

Embed your screenshot
Place your Power BI screenshot at `Images/screenshots/Screenshot 2026-05-23 075801.png` then add it to the repo.

Embed a preview image
If you haven't added your own screenshot yet, the README shows an available preview image from the repo. To use your own screenshot, place it at `Images/screenshots/Screenshot 2026-05-23 075801.png` and commit it.

![Dashboard](Images/screenshots/Screenshot%202026-05-23%20075801.png)

How to push the project to GitHub
See `docs/push.md` for step-by-step commands.

Notes and tips
- Keep raw data in `data/raw/` and processed exports in `data/processed/`.
- Move reusable Python helpers into `src/` when needed.
- Add `Images/screenshots/Screenshot 2026-05-23 075801.png` to show the dashboard preview on GitHub.
