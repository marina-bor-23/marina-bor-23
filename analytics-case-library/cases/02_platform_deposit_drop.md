# Platform Deposit Drop Investigation

## Role Targets
Product Analyst, Data Analyst, Product Health Analyst

## Business Question
Did a suspected mobile app issue cause a statistically significant decline in deposit activity, and which platforms or GEOs were most affected?

## Stack
Python, pandas, NumPy, Matplotlib, Seaborn, SciPy, BigQuery, Parquet, openpyxl.

## Metrics
Depositors, deposit count, deposit sum, average deposit per user, average deposit per transaction, p-value.

## What I Did
- Processed 451K+ transaction rows from BigQuery.
- Cached data in Parquet to speed up repeat analysis.
- Split the month into baseline, transition and incident periods.
- Compared deposit behavior across iOS, Android, mobile web and web platforms.
- Applied statistical tests to validate whether changes were significant.
- Generated a multi-sheet Excel report and visual summary.

## Business Impact
Confirmed a statistically significant post-incident decline and localized the strongest impact to one platform and several affected GEOs, helping the product team prioritize investigation.

## Selected Achievement Bullets
- Investigated a mobile product incident using 451K+ deposit transactions from BigQuery.
- Confirmed statistically significant decline in depositors and deposit volume after the incident date.
- Built platform and GEO breakdowns to localize the affected user segment.

## Relevance Notes
Relevant for product health, incident analytics, mobile app analytics and statistically rigorous diagnostics.

## Anonymization Notes
Exact platform labels, GEO names and internal dates may be generalized when used publicly.
