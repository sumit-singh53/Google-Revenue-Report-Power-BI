# Contributing Guide

Thanks for your interest in contributing to **Google Revenue Analysis (Power BI)** 🚀

## Ways to Contribute

- Improve documentation and data-source references
- Add additional visuals/pages in the Power BI report
- Improve DAX measures and modeling clarity
- Add validation checks for source data quality
- Suggest improvements via Issues

## Project Setup

1. Clone the repository.
2. Keep these files in the project root:
   - `GOOGLE REVENUE ANALYSIS-2014 to 2024.pbix`
   - `Google Revenue From 2014 to 2024.xlsx`
   - `revenue.png`
3. Open the `.pbix` in Power BI Desktop.
4. Refresh data and validate visuals.

## Data Rules

- Preserve the `Year` field as whole number.
- Treat `DNS` as "Data Not Specified" (recommended: convert to null for numeric modeling).
- Keep all revenue units in **billions USD**.

## Pull Request Process

1. Create a branch from `main`.
2. Make focused changes.
3. Update `README.md` if behavior/data assumptions change.
4. Submit a PR with:
   - What changed
   - Why it changed
   - Screenshots (if dashboard visuals changed)

## Commit Style

Prefer concise commit messages such as:

- `docs: improve dataset section`
- `feat: add new KPI measure`
- `fix: handle DNS values in query`

## Code of Conduct

Please be respectful and constructive in all discussions.
