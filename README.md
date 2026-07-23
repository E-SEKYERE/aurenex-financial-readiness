# 📊 Workforce & Financial Readiness Analysis — Aurenex Systems Ltd.

![Dashboard Preview](screenshots/dashboard_overview.png)

## 📌 Project Summary
An integrated HR Analytics and FP&A project built for Aurenex Systems Ltd., a fictional
B2B SaaS company assessing readiness for a North American expansion. The model combines
workforce planning, payroll forecasting, CAPEX and financing analysis, and scenario
simulation into a single executive dashboard — answering whether the company can afford
to hire, fund, and sustain its growth plan without running into a cash shortfall.

## 🛠️ Tools Used
- **Microsoft Excel** — 3-statement model, financing & funding analysis, CAPEX schedule, OPEX ratio analysis, HR analyst report
- **Power BI** 
- **Scenario modelling** — Worst / Base / Best case toggles across revenue, payroll, and CAPEX assumptions

## ✨ Key Features
- Fully linked **3-statement model** in Excel — formula-driven, not hardcoded, with a single Assumptions tab controlling every scenario
- Executive KPI strip: FY Revenue, FY EBITDA, FY CAPEX, funding raised, break-even month, liquidity risk months
- EBITDA bridge: Revenue → Payroll → Other OPEX → EBITDA
- CAPEX coverage: monthly free cash flow after CAPEX, flagging any month where spend outpaces cash generation
- Funding mix and FY cost composition as stacked bars
- Cumulative CAPEX vs. cumulative EBITDA payback trend
- Live Worst / Base / Best scenario toggle recalculating every KPI and chart
- 12-month liquidity readiness timeline highlighting the one flagged risk month

## 📂 Data Source
 Dataset built to simulate a mid-sized B2B SaaS company's HR and finance systems
(Employee/HR data, payroll, recruitment cost, CAPEX, financing, and a 12-month financial
forecast for FY2026). 

## 📈 Key Insights
- **Break-even holds at February 2026 across every scenario** — even under the Worst case
  (-20% revenue, +10% payroll, +10% CAPEX), adjusted free cash flow still turns positive
  in month two, showing the cost structure is resilient to a revenue miss.
- **Only one liquidity risk month in the base case (January 2026)** — driven by the £200k
  initial infrastructure CAPEX landing in the same month as the first loan repayment,
  before hiring and revenue have ramped.
- **Under the Best case, the January risk disappears entirely** — a 20% revenue upside is
  enough to make adjusted free cash flow positive from month one.
- **CAPEX payback is achieved by February 2026** — cumulative EBITDA (£787.6k) overtakes
  cumulative CAPEX (£220k) just one month after the initial outlay.
- **EBITDA margin expands from 9.1% in January to 51.5% by December**, as payroll — the
  largest fixed cost — is diluted by a fast-growing revenue base; Payroll/Revenue falls
  from 80.6% to 42.6% over the same period.
- **FY2026 base case: £28.2m revenue, £12.7m EBITDA (45.0% margin), £420k CAPEX**, funded
  by £700k of expansion capital (£500k loan at 8% over 24 months, £200k founder equity).
- **Sales headcount ramps from 0 to 6 reps by May 2026** and holds flat, with hiring cost
  fully absorbed by April — workforce readiness is achieved well ahead of the funding
  runway tightening.
- Scenario spread is wide but directionally consistent: FY EBITDA ranges from **£5.7m
  (Worst)** to **£18.3m (Best)** against a **£12.7m Base case**, with CAPEX moving only
  modestly (£420k–£462k) across scenarios.

## 📸 Screenshots

### 🧮 Financial Model (Excel)

**3 Statement Model**
![3 Statement Model](https://github.com/user-attachments/assets/e22af818-4118-42bc-9eca-889f13278b58)


**Formula View** — Income Statement / EBITDA build shown with formulas visible (`Ctrl` + `` ` ``)
![Formula View](screenshots/formula_view.png)

**Assumptions Tab** — the single input tab driving Revenue, Payroll and CAPEX across all three scenarios
![Assumptions](screenshots/assumptions.png)

### Executive Dashboard
![Dashboard](screenshots/dashboard_overview.png)

### EBITDA Bridge & CAPEX Coverage
!(screenshots/waterfall_charts.png)

### Scenario Comparison
![Scenario Comparison](screenshots/scenario_comparison.png)

---
*Built by Emmanuel Sekyere | [Add your LinkedIn URL]*
