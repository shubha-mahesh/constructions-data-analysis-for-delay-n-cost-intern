# Construction Project Analytics Dashboard

## Overview
This project analyzes construction project performance using SQL and Power BI. The goal is to identify delays, cost overruns, and operational inefficiencies across projects.

---

## Dataset
- Synthetic construction dataset (1000 projects)
- Includes cost, schedule, labor, and risk-related features
- Stored and queried using SQLite

---

## Tech Stack
- SQL (SQLite)
- Python (data generation & preprocessing)
- Power BI (visualization)

---

## Key KPIs

| Metric | Value |
|------|------|
| Total Projects | 1000 |
| Delayed Projects | 830 |
| Average Delay (days) | 134.04 |
| Cost Overrun % | 19.41% |
| On-Time Completion % | 17.0% |

---

## Key Insights

- **High Delay Rate:** 83% of projects are delayed, indicating poor schedule planning or execution.
- **Severe Delays:** Average delay exceeds 130 days, suggesting systemic inefficiencies.
- **Cost Overruns:** Projects exceed budget by ~19% on average.
- **Low Reliability:** Only 17% of projects are completed on time.
- **Risk Identification:** High-risk projects show lower completion percentages.

---

## SQL Logic

KPIs were calculated using conditional aggregation:

```sql
