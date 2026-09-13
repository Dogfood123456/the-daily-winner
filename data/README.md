# The Daily Winner — Daily Data

This folder is the permanent home for the source files used to build and review each Daily Winner edition.

## Folder structure

- `andy-h/` — Andy H daily speed-figure files.
- `proform/` — Proform / RaceMetrics daily card and data exports.
- `results/` — completed daily result files used for the autopsy and performance tracking.

## File naming

Use the race date in ISO format so files sort chronologically:

- `andy-h/2026-09-14.xlsx`
- `proform/2026-09-14.csv`
- `results/2026-09-14.csv`

If more than one source file is needed for a category, add a short description after the date, for example:

- `proform/2026-09-14-cards.xlsx`
- `proform/2026-09-14-racemetrics.csv`
- `results/2026-09-14-final.csv`

## Daily workflow

1. Andy H file goes in `data/andy-h/`.
2. Proform/RaceMetrics file goes in `data/proform/`.
3. Stage 1 is built price-blind from the day's source data, with greatest weight given to strong same-surface speed figures within 50 days.
4. Once racing is complete, the final results file goes in `data/results/` for the autopsy.

Do not overwrite an earlier day's source file. The dated files are intended to preserve the evidence used for each edition.
