# Delivery Performance Analytics Dashboard
**Live Dashboard → [View Here](https://saivarnika-ba.github.io/delivery-analytics)**

> Built with Power BI · SQL · Statistical Analysis · DAX · Geographic Mapping

---

## Business Problem
A delivery operations team was making decisions about delay reduction based on assumption — they believed distance was the primary delay driver and were planning infrastructure changes accordingly. No data had been used to validate this assumption.

## What I Built
A full **delivery performance analytics dashboard** that broke the assumption and redirected strategy:

- **Multi-variable analysis** across traffic, distance, weather, and time-of-day against delay outcomes
- **Scatter plots** to visualise correlation between each variable and delay frequency
- **Decomposition tree visuals** to drill into delay causes by route, zone, and hour
- **Geographic map visuals** with zone-level benchmarking to identify the 3 worst-performing delivery zones
- **Executive summary report** — structured with findings, trend charts, and a recommended action plan

## The Counter-Intuitive Finding
> **Traffic — not distance — was the primary delay driver.**

This was the opposite of what the operations team assumed. Distance showed weak correlation with delays. Traffic density during peak hours showed strong, consistent correlation. This finding was validated through scatter plot analysis and decomposition tree drill-down — not guesswork.

| Finding | Data Evidence |
|---|---|
| Primary delay driver | Traffic (not distance) — validated via scatter + decomposition tree |
| Peak hour delay surge | **+40% increase** in delays during peak hours |
| Underperforming zones | **3 zones** flagged via geographic benchmarking |
| Projected improvement | **15–20% delay reduction** if peak-hour routing optimised |

## Why This Project Is Different
The value wasn't in building a dashboard — it was in **overturning a business assumption with data**. The recommended action plan was built on validated evidence, not opinion. That's what analytics is for.

## Technical Stack
| Layer | Tool |
|---|---|
| Data Preparation | SQL — joins, aggregations, time-of-day segmentation |
| Statistical Analysis | Correlation analysis, variable decomposition |
| Visualisation | Power BI — Scatter Plot, Decomposition Tree, Map Visual, Waterfall |
| KPI Measures | DAX — delay rate %, zone benchmarks, rolling averages |
| Deliverable | Executive summary report with trend charts + action plan |

## Files in This Repo
```
index.html          → Live interactive dashboard (open in browser)
README.md           → This file
```

## Skills Demonstrated
`Power BI` `DAX` `SQL` `Statistical Analysis` `Geographic Mapping` `Decomposition Tree` `Root Cause Analysis` `Stakeholder Reporting` `Executive Communication` `Data-Driven Decision Making`

---
*Part of my analytics portfolio → [saivarnika-portfolio.netlify.app](https://saivarnika-portfolio.netlify.app)*# delivery-dashboard
