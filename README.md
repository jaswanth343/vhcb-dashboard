# 🏠 VHCB FY2025 Housing & Conservation Intelligence Dashboard

**Interactive data dashboard analyzing the Vermont Housing & Conservation Board's $106.7M FY2025 investments across Vermont's 14 counties.**

### 🔗 [View Live Dashboard →](https://jaswanth343.github.io/vhcb-dashboard/)

---

![Dashboard Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![Data Source](https://img.shields.io/badge/Data-VHCB%202025%20Annual%20Report-blue) ![Charts](https://img.shields.io/badge/Charts-Chart.js%204.4-orange)

## About This Project

I built this project as part of my application for the **Housing Data Specialist** position at the [Vermont Housing & Conservation Board (VHCB)](https://vhcb.org). Rather than just submitting a resume, I wanted to demonstrate the kind of data analysis I'd deliver on day one — compiling data from multiple sources, building interactive visualizations, and connecting the numbers to VHCB's dual-goal mission of expanding affordable housing while conserving Vermont's working lands.

Every data point in this dashboard comes from VHCB's official **2025 Annual Report to the Vermont General Assembly** and publicly available federal/state data sources. Nothing was fabricated.

## What's in the Dashboard

| Section | Description |
|---------|-------------|
| **KPI Cards** | Total VHCB investment, development costs leveraged, housing units funded, homeless-dedicated units, and leverage ratio — all update dynamically with filters |
| **Investment by County** | Horizontal bar chart showing VHCB dollar allocation across Vermont counties |
| **Investment by Project Type** | Donut chart breaking down funding by new construction, preservation, shelter, I/DD housing, motel conversion, etc. |
| **Units by Status** | Pie chart showing project pipeline — Operating, Under Construction, Funded |
| **Project Detail Table** | All 22 FY2025 housing awards with award amounts, total costs, unit counts, and status badges |
| **Top Grantee Organizations** | Ranked table of housing nonprofits by VHCB investment |
| **Strategic Priority Index** | Grouped bar chart comparing Housing Pressure vs Conservation Risk across top 10 counties |
| **Farmland Loss** | County-level farmland loss (2017–2022) from USDA Census of Agriculture |
| **Act 59 Progress** | Visual tracker showing Vermont's progress toward the 30×30 conservation goal |

**Interactive filters** at the top let you slice all charts and tables by county and project type simultaneously.

## Data Sources

| Source | What I Used It For |
|--------|-------------------|
| [VHCB 2025 Annual Report](https://vhcb.org) | FY2025 housing/conservation awards, program impact data, financial statements, balance sheet |
| [U.S. Census Bureau Vintage 2024](https://www.census.gov/data/tables/time-series/demo/popest/2020s-counties-total.html) | County population estimates (2020 base, 2024 estimates) |
| [American Community Survey 2023](https://data.census.gov) | Median household income, home values, gross rent, housing units, occupancy |
| [UVM 2025 Forest Cover Assessment (FIA 2022)](https://www.uvm.edu) | County-level forest acreage, forest share, annual change |
| [USDA NASS 2022 Census of Agriculture](https://www.nass.usda.gov) | Farmland acres 2017 vs 2022, farmland loss by county |
| [VHCB Act 59 Phase I Inventory](https://vhcb.org) | Statewide conserved land totals (1,576,783 acres = 26.8%) |
| [VHFA Housing Needs Assessment 2025–2029](https://vhfa.org) | 36,000-unit housing shortfall, 3.2% rental vacancy rate |

## Key Findings

- **$106.7M awarded** in FY2025, leveraging **$181M** from partners — a **1.7× multiplier** on public investment
- **595 permanently affordable rental homes** funded, plus **58 new shared-equity homeowners**
- **89% of VHCB expenditures** go directly to grants and loans — only 5% administrative overhead
- **Orange, Lamoille, Chittenden, and Franklin** counties rank highest on the combined Strategic Need Index
- Vermont has conserved **26.8%** of its land — approximately **190,000 acres** short of the 30×30 goal
- **19,547 acres** of farmland lost statewide between 2017 and 2022

## Full Analytical Package

This dashboard is one piece of a three-part deliverable:

| File | Description |
|------|-------------|
| **[Live Dashboard](https://jaswanth343.github.io/vhcb-dashboard/)** | This interactive web dashboard (HTML + Chart.js) |
| **Vermont_VHCB_Dashboard_v3.xlsx** | 10-sheet Excel workbook with 485 live formulas, county-level composite indices, FY2025 awards analysis, conservation data, balance sheet, and full source documentation |
| **Vermont_VHCB_Strategic_Deck_v3.pptx** | 12-slide executive presentation with native charts and strategic recommendations |
| **Vermont_VHCB_Project_Report_v3.docx** | Written analytical report with methodology, findings, and VHCB-specific operational analysis |

## Methodology

I built three composite indices to quantify the dual-mission tension VHCB navigates:

- **Housing Pressure Index (0–100):** Population Growth (30%) + Vacancy Rate (20%) + Home Value/Income Ratio (25%) + Rent-to-Income Stress (15%) + Renter Share (10%)
- **Conservation Risk Index (0–100):** Forest Share (35%) + Farmland Share (25%) + Water Share (10%) + Farmland Loss Rate (20%) + Forest Loss Rate (10%)
- **VHCB Strategic Need Index (0–100):** 55% Housing Pressure + 45% Conservation Risk

All metrics normalized via PERCENTRANK across Vermont's 14 counties. Higher score = greater need for VHCB intervention.

## Tech Stack

- **Dashboard:** HTML, CSS, JavaScript, [Chart.js 4.4](https://www.chartjs.org/)
- **Excel Analysis:** 485 live formulas (PERCENTRANK, SUMIF, weighted composites), conditional formatting
- **Fonts:** [Inter](https://rsms.me/inter/) + [DM Sans](https://fonts.google.com/specimen/DM+Sans)
- **Hosting:** GitHub Pages

## About Me

**Jaswanth Reddy Lanka**
MS Business Analytics | UMass Amherst (GPA 3.8) | Expected May 2026

I'm a data analyst with 3+ years of experience in consulting and business analytics. At Flo Group (part of Accenture), I built SQL data pipelines, automated reporting workflows, and developed Oracle BI dashboards used by multiple operational teams. I'm drawn to VHCB's mission because the intersection of data analysis, housing policy, and community impact is exactly the kind of meaningful work I want to do.

📧 [jaswanth.reddy060@gmail.com](mailto:jaswanth.reddy060@gmail.com) · 📱 (413) 510-7534 · 💼 [LinkedIn](https://linkedin.com/in/jaswanthreddy06)

---

*Data sourced from VHCB's 2025 Annual Report to the Vermont General Assembly and publicly available U.S. government datasets. This project was built independently as a demonstration of analytical capabilities.*
