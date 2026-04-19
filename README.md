Readme · MD
Copy

# Data Analyst Reactivation Program
 
A structured analytics curriculum built to reactivate and deepen hands-on data skills across SQL, Python/Pandas, Tableau, and Power BI — with every lesson grounded in real business questions.
 
---
 
## Curriculum Overview
 
| Phase | Weeks | Topics |
|---|---|---|
| **SQL** | 1–2 | SELECT/WHERE/ORDER BY, JOINs, GROUP BY + revenue KPIs, subqueries, window functions, CTEs, date functions |
| **Python / Pandas** | 3–4 | DataFrames, filter/groupby/merge, data cleaning, apply, pivot tables, time series, matplotlib |
| **BI Tools** | 5 | Tableau I & II, Power BI I & II, dashboard capstone |
| **Portfolio** | 6–8 | Three industry-flexible projects, story framing, AI audit documentation, resume integration, mock interview prep |
 
Every Friday is a ★ **Capstone** — A full business scenario requiring everything from the week combined into one end-to-end analysis.
 
---
 
## Databases Used
 
### Retail Ecommerce (SQLite)
Tables: `orders`, `customers`, `order_items`
Focus: revenue KPIs, order-level vs item-level grain, customer segmentation
 
### Canadian Logistics (SQLite)
Tables: `shipments`, `drivers`, `clients`, `routes`, `warehouses`, `vehicles`, `shipment_items`
Focus: freight analytics, driver performance, on-time delivery, date-based trend analysis
 
### Weeks 3–4 — Python / Pandas (same datasets + extensions)
Focus: replicating and extending SQL analysis in Python, cleaning raw data, time series, visualizations
 
---
 
## SQL Concepts Covered (Weeks 1–2)
 
**Week 1-2 — Foundations**
- `SELECT`, `WHERE`, `ORDER BY`, `LIMIT`
- `INNER JOIN`, `LEFT JOIN` with `IS NULL` anti-join pattern
- `GROUP BY` logic and grain discipline
- `HAVING` vs `WHERE`
- Revenue calculations — item-level vs order-level distinction
- `CASE WHEN` for classification and custom sorting
- Subqueries — placement in `WHERE`, `FROM`, `SELECT`
- Correlated subqueries
**Week 2 — Advanced**
- Window functions: `RANK()`, `DENSE_RANK()`, `ROW_NUMBER()`, `SUM() OVER`, `LAG()`, `LEAD()`
- `PARTITION BY` and `ORDER BY` inside `OVER()`
- CTEs: single, multi-step, scalar (with `CROSS JOIN`), and chained
- Column carry-through rules in multi-CTE queries
- Date functions: `strftime()`, `julianday()`, date arithmetic
- Month-over-month and quarter-over-quarter trend analysis
- Formatting with `printf()` — and why formatted columns can't be used for further math
- SQLite permissiveness vs production database behaviour (Snowflake/PostgreSQL)
---
 
## Notebook Standards
 
Every notebook in this repo follows the same structure:
 
- **Connection cell** — database setup
- **Table preview cell** — `SELECT * FROM table LIMIT 5` for every table used
- **Concept cells** — what the clause does, where it sits in clause order, common mistakes, and a worked example with real column names before any drill
- **Drill cells** — minimum 12 drills
- **Capstone cell** — one final query combining all concepts from the session
---
 
## On AI-Assisted Learning
 
All notebooks in this program were built with AI assistance and then critically audited. That audit process is intentional and documented:
 
- Structural errors in notebooks were identified and corrected (drills appearing before their concepts, tautological proof examples)
- Query solutions were diagnosed rather than blindly accepted — the single blocking issue was identified before any rewrite
This mirrors real analyst work: knowing when to trust a tool's output and when to push back.
 
---
 
## Status
 
| Week | Status |
|---|---|
| Week 1 — SQL Foundations | ✅ Complete |
| Week 2 — SQL Advanced | 🔄 In Progress |
| Week 3 — Python / Pandas | ⬜ Upcoming |
| Week 4 — Python / Pandas Advanced | ⬜ Upcoming |
| Week 5 — BI Tools | ⬜ Upcoming |
| Weeks 6–8 — Portfolio | ⬜ Upcoming |
 
---
 
