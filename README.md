# Baseline‑Driven Imaging Performance Analysis (Sanitized Demo)

Demonstration of a baseline‑driven performance analysis workflow using synthetic identifiers.  
This project focuses on establishing normal imaging behavior, explaining performance variance, 
and reducing false escalations through contextual baselining.

All identifiers in this workbook have been sanitized. Metrics and durations are preserved 
solely for analytical demonstration.

---

## What this demonstrates
- Establishing performance baselines for imaging operations
- Explaining variance using hardware context (RAM / CPU buckets)
- Separating normal behavior from non‑impactful outliers
- Supporting operational and security decision‑making with explainable metrics

---

## Methodology & Scope
This analysis establishes a baseline of normal imaging performance using a deliberately scoped dataset consisting only of records I personally executed and timestamped. Data was normalized into structured categories and evaluated against defined criteria to distinguish expected operational variance from true anomalies. Results are intended to support planning, workload allocation, and pre-escalation decision-making rather than real-time alerting. Findings should not be extrapolated beyond the defined dataset or time period without re-validation. Records from other operators were intentionally excluded due to incomplete timestamp attribution to preserve data integrity and analytical defensibility.

---

## Repo contents
- `demo/` — Sanitized Excel workbook containing baseline analysis, pivots, and dashboard
- `docs/` — Optional screenshots for quick review

---

## Notes
- This project emphasizes **reasoning and analysis**, not automation
- The goal is to reduce noise and false escalations by grounding discussions in baselines

## Example dashboard output
![Baseline imaging dashboard screenshot](/docs/dashboard_screenshot.png)
