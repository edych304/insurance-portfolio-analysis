# Insurance Portfolio Analysis

An insurance portfolio analysis using **R, SQL and DuckDB**.

The project investigates how **claim frequency, claim severity and burning cost** differ across portfolio segments, focusing on:

- Driver age
- Geography
- Vehicle value

The analysis uses the `dataCar` dataset and performs the portfolio calculations directly in SQL.

## Key findings

- **Driver age:** Burning cost generally decreases with age, driven by both lower frequency and lower severity.
- **Geography:** Area F has particularly high burning cost, driven primarily by claim severity.
- **Vehicle value:** Higher vehicle values are associated with higher burning cost, driven primarily by claim frequency.

## Files

- `SQL-Project.pdf` — the finished analysis
- `SQL Project.Rmd` — R Markdown source containing the analysis and SQL queries
