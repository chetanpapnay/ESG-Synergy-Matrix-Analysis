Version History & Changelog

v2.0 (Oct 2026) — Enterprise Risk & Architecture Refinement
* DAX Risk Engine: Implemented dynamic `$12M Contractual Risk Exposure` threshold logic and normalized `Safety Incident Rate` (per 1,000 units) to eliminate plant volume bias.
* Data Engineering (M): Enforced strict column data types in `FACT_ESG`, standardized multi-currency energy costs to USD, and eliminated sensor null-data drift.
* Audit Alignment: Conformed multi-site reporting to 2026 EU-CSDDD compliance and GHG Protocol Scope 1 & 2 corporate standards.

v1.0 (Feb 2026) — Baseline Schema & PoC
* Designed core Kimball Star Schema (`FACT_ESG` + conformed dimensions) modeling 5 regional manufacturing hubs.
* Deployed baseline Power BI dashboard tracking aggregate carbon tonnage, energy expenditure, and raw incident logs.
