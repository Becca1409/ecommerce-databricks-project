# E-commerce Customer Retention Analysis

This project analyzes customer retention and cohort behavior for an e-commerce business using a Databricks Lakehouse approach.  
The goal is to understand how customer value evolves over time and how insights change as new data is added.

---

## Project Context
- E-commerce business focused on customer retention
- Analysis compares **2024 data only** vs **2024–2025 data**
- Emphasis on cohort maturity rather than short-term performance drops
- Results are translated into clear, business-oriented insights

---

## Tech Stack
- Databricks
- SQL
- Delta Lake (Bronze / Silver / Gold)
- Cohort Analysis
- Dashboard visualizations

---

## Repository Structure

- `presentation/`  
  Final stakeholder presentation (PDF)

- `dashboards/`  
  Dashboard screenshots (2024 vs 2024–2025) and the SQL queries used to build them

- `sql/`  
  Databricks SQL notebook containing data transformations and cohort logic

- `docs/`  
  Final customer retention analysis report

---

## Key Focus Areas
- Customer retention by cohort
- Impact of cohort maturity on performance metrics
- Handling incremental data without changing pipeline logic
- Clear storytelling for non-technical stakeholders

---

## Outcome
The analysis shows that apparent performance declines in recent cohorts are largely explained by **time and cohort maturity**, not by worse customer behavior.  
Improving **early re-engagement** emerges as a stronger lever for long-term value than increasing acquisition volume alone.

---

## Notes
This project was built as part of a data analytics portfolio to demonstrate:
- structured data modeling
- analytical thinking
- and clear communication of insights
