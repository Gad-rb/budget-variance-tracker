# Budget Variance & Reporting Tracker — FY2025 (Nonprofit Program Simulation)

## Overview
This project simulates a monthly budget-variance tracking and reporting workflow for a multi-program nonprofit operation, covering 12 months and 8 program categories (Health Outreach, WASH, Education & Training, Livelihoods & Financial Inclusion, Monitoring & Evaluation, Emergency Response, Community Mobilization, and Admin & Operations). Raw budget and actual expenditure data is cross-referenced across tabs using VLOOKUP and INDEX/MATCH, rolled up into a category-level summary with SUMIFS, and visualized through conditional-formatting flags (green/yellow/red) that let a program manager identify over- and under-spending at a glance without reading raw numbers. The workbook is structured the way I'd hand it to a supervisor: a clean Raw Data tab, a Variance Analysis tab, and a Summary Dashboard — mirroring the monthly reporting cycle used in cost and budget tracking roles.

## What's inside
- **Raw Data** — 96 rows of source budget/actual figures (12 months × 8 categories), plus a category-budget reference table.
- **Analysis** — Cross-referenced Budget (VLOOKUP) and Actual (INDEX/MATCH) values, variance $ and %, a status classification (Over Budget / Under Budget / On Track at a ±5% threshold), and color-coded flags.
- **Summary Dashboard** — SUMIFS-based rollup by category with a grand total, a 12-month trend table, and a Budget vs. Actual chart.

## Skills demonstrated
- VLOOKUP vs. INDEX/MATCH (and when each is the right tool — left-to-right lookup vs. any-direction lookup)
- SUMIFS for pivot-style aggregation
- Conditional formatting for non-technical stakeholder communication
- Structured, auditable spreadsheet design (labeled inputs vs. formulas, documented assumptions)

## Notes
All data is fictional, built to reflect realistic patterns (e.g., a program trending over budget as activity scales up, a program under budget due to procurement delays, seasonal spikes in emergency response spending).
