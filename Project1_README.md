# Construction Project Controls Dashboard

**A professional-grade Excel workbook demonstrating end-to-end project controls for a $2.4M mixed-use construction project — built to mirror real GC workflows in Procore, CMiC, and Viewpoint.**

---

## Overview

This dashboard was built to demonstrate practical construction project management skills: cost tracking by CSI division, Earned Value Management (EVM), CPM schedule monitoring, RFI lifecycle management, and submittal tracking — all in a single, formula-driven workbook that updates automatically as data changes.

The project modeled is **Riverside Mixed-Use | Arlington, TX** — a realistic $2.4M commercial project with 20 work packages, 12 CSI divisions, 10 RFIs, and 15 submittals across a 14-month construction schedule.

---

## Workbook Structure

| Tab | What It Does |
|-----|-------------|
| **Dashboard** | Auto-updating KPI summary: CPI, SPI, budget utilization, open RFIs, overdue submittals |
| **Cost Tracker** | Line-item budget vs. actual by CSI division with full EVM metrics (EV, CV, CPI, SPI, EAC) |
| **Schedule** | 20-activity schedule with planned vs. actual % complete, schedule variance, float, and SPI |
| **RFI Log** | Full RFI lifecycle: submission, response tracking, days open, cost impact, priority |
| **Submittal Register** | 15-submittal register with approval status, return codes, overdue flags |
| **S-Curve & Charts** | Monthly planned vs. actual cost S-curve with cumulative totals |

---

## Key Features

- **Zero hardcoded calculations** — all KPIs, variances, and totals use Excel formulas that recalculate when input data changes
- **Earned Value Management** — EV, CV, CPI, SPI, and EAC calculated at both division and project level
- **Color-coded health indicators** — green/amber/red conditional formatting across all status fields
- **Industry-standard color conventions** — blue text = input cells, black = formulas, per financial modeling best practice
- **Cross-sheet linking** — Dashboard pulls live data from all four operational tabs
- **RFI aging calculator** — `=IF(answered, answer_date - submit_date, TODAY() - submit_date)` for real-time aging
- **S-curve** — planned vs. actual cumulative cost plotted monthly across 14-month project duration

---

## Skills Demonstrated

| Skill | Where Applied |
|-------|--------------|
| Cost estimating & budget control | Cost Tracker — CSI division line items, budget vs. actual |
| Earned Value Management (EVM) | Cost Tracker — EV, CPI, SPI, EAC columns |
| CPM scheduling concepts | Schedule tab — float calculation, SPI, schedule variance |
| RFI management | RFI Log — full lifecycle, days open, cost impact tracking |
| Submittal management | Submittal Register — approval codes, overdue flags |
| Project reporting | Dashboard — auto-updating KPI summary for owner/PM review |
| Excel advanced functions | COUNTIF, IFERROR, IF, cross-sheet references, conditional formatting |
| CSI MasterFormat | 12-division cost breakdown per CSI 2016 |

---

## How to Use

1. **Open the workbook** — start on the Dashboard tab to see the project health summary
2. **Update Cost Tracker** — enter actual costs in blue cells (Column G); all EVM metrics recalculate automatically
3. **Update Schedule** — enter actual % complete in blue cells (Column I); SPI and float update instantly
4. **Log new RFIs** — add a row to the RFI Log; Dashboard open-RFI counter updates automatically
5. **Log new submittals** — add a row to the Submittal Register; Dashboard overdue counter updates automatically

> **Blue cells = input fields you edit. Black cells = formulas — do not overwrite.**

---

## Project Data & Assumptions

| Parameter | Value |
|-----------|-------|
| Project | Riverside Mixed-Use Development |
| Location | Arlington, TX |
| Contract Value | $2,400,000 |
| Project Duration | Jan 2025 – Feb 2026 (14 months) |
| CSI Divisions | 12 (01 through 33) |
| Schedule Activities | 20 work packages |
| RFIs | 10 (5 closed, 5 open) |
| Submittals | 15 (11 approved/in review, 1 overdue) |

Data is realistic but anonymized for portfolio purposes. Cost figures are based on RS Means 2024 unit cost data for the Dallas-Fort Worth metro area.

---

## Sample Outputs

**Dashboard KPIs (as of August 2025):**
- CPI: 1.03 (under budget — on track)
- SPI: 0.94 (minor schedule lag — monitoring)
- Budget Utilized: 68.4% of contract value
- Open RFIs: 5 (4 high priority)
- Overdue Submittals: 1 (site lighting — CivilCo)

---

## Tools & Methods

- **Microsoft Excel** (openpyxl for file generation)
- **CSI MasterFormat 2016** — division numbering and cost breakdown structure
- **Earned Value Management** — per PMI PMBOK 7th Edition methodology
- **RS Means 2024** — unit cost benchmarks for DFW market

---

## Author

**Suhas Ravi, CMIT, LEED GA**  
MS Construction Management | University of Texas at Arlington (Dec 2026)  
[linkedin.com/in/suhasravi](https://linkedin.com/in/suhasravi)

---

## License

MIT — free to use, adapt, and build on for educational and professional purposes.
