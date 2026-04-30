# CRM Timing Optimization

## Role Targets
Product Analyst, CRM Analyst, Data Analyst

## Business Question
Which weekday is the weakest for VIP deposits in each country and VIP segment, and how can CRM use this to improve reactivation and retention timing?

## Stack
SQL, BigQuery, CTEs, window functions, date functions, aggregation.

## Metrics
Average deposit by weekday, segment average deposit, decline percentage, VIP user count, transaction count.

## What I Did
- Filtered VIP users by target period, weekday and country.
- Calculated weekday-level deposit metrics for each country and VIP segment.
- Compared each weekday with the segment benchmark.
- Used ranking logic to identify the weakest weekday for each segment-country pair.

## Business Impact
Delivered a ready-to-use table for CRM teams to schedule reactivation pushes and bonus campaigns on days with the strongest deposit decline.

## Selected Achievement Bullets
- Built a BigQuery analysis to identify the weakest deposit weekdays by VIP segment and country.
- Used CTEs, date functions and window functions to rank segment-level deposit decline.
- Delivered an actionable CRM table for targeted retention and reactivation campaigns.

## Relevance Notes
Relevant for CRM, retention, lifecycle, VIP segmentation and SQL-heavy analytics work.

## Anonymization Notes
Country names, product names and internal campaign details are intentionally generalized.
