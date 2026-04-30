# Call Campaign ROI Analysis

## Role Targets
CRM Analyst, Data Analyst, Product Analyst

## Business Question
Did outbound calls lead to deposits, and how did campaign performance differ across 3-day, 7-day and 14-day windows, countries and traffic sources?

## Stack
Python, pandas, NumPy, Matplotlib, regex, BigQuery, openpyxl.

## Metrics
Call-to-deposit conversion, deposits before and after call, net deposit, average deposit per call, average deposit per user, traffic-source effectiveness, data completeness.

## What I Did
- Filtered answered calls and excluded no-answer records from conversion logic.
- Normalized phone numbers and matched them with user activity.
- Calculated before/after deposit behavior in 3, 7 and 14 day windows.
- Deduplicated activity so one transaction was not counted across multiple calls.
- Added breakdowns by country, traffic source and user-level performance.

## Business Impact
Showed whether users reacted after calls and where campaign effectiveness was limited by low reachability or weak post-call conversion.

## Selected Achievement Bullets
- Built a call campaign ROI analysis with 3/7/14-day before-after windows.
- Matched normalized phone data with user activity and traffic-source data.
- Calculated true call-to-deposit conversion from all answered numbers, not only active users.

## Relevance Notes
Relevant for CRM, lifecycle, campaign ROI, contact strategy and conversion analytics.

## Anonymization Notes
Phone numbers, countries, campaign source names and internal counts are removed or generalized.
