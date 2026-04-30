# P2P Transaction Spam and Failure Analysis

## Role Targets
Payments Analyst, Data Analyst, Risk Analyst

## Business Question
Which payment amounts, agents and user patterns generated the highest number of failed or suspicious P2P transactions?

## Stack
Python, pandas, NumPy, Matplotlib, Seaborn, SciPy, BigQuery, Parquet, Excel reporting.

## Metrics
Failed transaction count, failure rate, pending rate, unique users by amount, hourly failure rate, volume-to-failure correlation.

## What I Did
- Combined transaction data from multiple BigQuery sources.
- Cleaned payment agent and sub-agent names.
- Segmented transactions by amount, agent, user, hour and status.
- Detected suspicious users with abnormally high failed-attempt rates.
- Tested whether failures were connected to peak traffic or time-of-day behavior.

## Business Impact
Showed that the issue was not caused by peak load and highlighted specific amounts, agents and user patterns for payments and compliance teams.

## Selected Achievement Bullets
- Analyzed 284K+ P2P transactions to detect failure patterns, suspicious users and problematic agents.
- Built amount-level, agent-level and hourly failure-rate analysis for payment operations.
- Found that failure rates were not explained by peak transaction volume, shifting the investigation toward agent and user-pattern issues.

## Relevance Notes
Relevant for payments, risk, compliance, fraud detection and operations analytics work.

## Anonymization Notes
Payment agents, GEO and suspicious user IDs are removed or generalized.
