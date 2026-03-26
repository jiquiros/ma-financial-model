# M&A Financial Model — CloudCore / DataStream Analytics

**Project Atlas** · Fictional case study built for portfolio purposes

---

## What this is

A full M&A financial model analyzing the acquisition of **DataStream Analytics** (fictional SaaS analytics company) by **CloudCore Inc.** (fictional ERP SaaS, NYSE-listed) for **$570M (6.0x ARR)**. Built to demonstrate banker-level analytical skills across three formats: Excel model, investment memo, and sensitivity analysis.

> All companies, financials, and deal terms are **entirely fictional**. Comparable multiples and market benchmarks are based on publicly available SaaS M&A data (2022–2024).

---

## Files in this repository

| File | Description |
|------|-------------|
| `CloudCore_DataStream_MA_Model.xlsx` | Full Excel model — 4 tabs |
| `CloudCore_DataStream_InvestmentMemo.docx` | 2-page banker-style investment memo (bilingual EN/ES) |
| `README.md` | This file |

---

## Excel model structure

The workbook has four tabs, each feeding the next:

**1. Assumptions** — Every input lives here. Revenue growth, margins, deal structure, synergy ramp, tax rate, share price. Change one cell and the entire model updates. All inputs are in blue (industry standard).

**2. EPS Model** — Six sequential blocks that build the accretion/dilution bridge:
- Standalone CloudCore earnings (pre-deal baseline)
- Sources & uses (how the deal is financed)
- Share dilution from stock consideration
- Deal costs: interest on new debt + PPA amortization + transaction fees
- DataStream earnings contribution (with synergy ramp)
- Pro forma EPS bridge: Year 1, Year 2, Year 3

**3. Sensitivity** — Two 6×5 tables (Year 1 and Year 3) with conditional color formatting. Axes: acquisition price ($490M → $630M) vs. synergy realization (0% → 100%). Red = dilutive, white = breakeven, green = accretive.

**4. Output Summary** — One-page executive summary linking key outputs from the model. Designed to be shared standalone.

---

## Deal snapshot

| Parameter | Value |
|-----------|-------|
| Acquisition price | $570M |
| Purchase price / ARR | 6.0x |
| Deal structure | 60% cash / 40% stock |
| New debt (Term Loan B) | $200M @ 7.5% |
| Revenue synergies (fully ramped) | $42M ARR |
| Cost synergies (fully ramped) | $14M opex |
| Integration costs (one-time) | ($22M) |

---

## Key findings

**Year 1: (25.8%) dilutive** — driven by $11.4M in transaction fees expensed immediately, $19M annual PPA amortization, and synergies only 50% realized. This is structurally expected in SaaS acquisitions of this profile.

**Year 3: +54% accretive** (base case, 100% synergy realization) — once fees roll off and synergies are fully ramped. Even at 25% synergy realization, the deal is positive in Year 3 per the sensitivity table.

**Main insight:** Year 1 EPS is the worst moment to evaluate a SaaS deal. The right lens is Year 3 with a synergy sensitivity — which is what the model is built to show.

---

## Modeling assumptions & limitations

- DataStream financials are fictional but calibrated to real SaaS benchmarks (38% ARR growth, 74% gross margin, 118% NRR are consistent with top-quartile SaaS 2023–2024)
- CloudCore standalone model uses simplified 3-statement structure; no full balance sheet or cash flow statement
- PPA allocation (20% of purchase price to intangibles, 6-year straight-line) is a reasonable estimate — a real deal would require a formal purchase price allocation by an independent valuator
- Synergy ramp (50% / 80% / 100% over 3 years) is conservative relative to management guidance conventions; bankers typically haircut revenue synergies by 30–50%
- Tax shield on deal costs treated as fully deductible for simplicity; actual deductibility of M&A advisory fees varies by jurisdiction and deal structure

---

## Skills demonstrated

- M&A accretion / dilution modeling (EPS bridge)
- Sources & uses structuring
- Purchase price allocation (PPA) and intangibles amortization
- Synergy modeling with ramp assumptions
- Sensitivity / scenario analysis with conditional formatting
- Investment memo writing (banker-style, bilingual)
- Financial model architecture: assumption-driven, zero hardcoded formulas in calculation tabs

---

## Background

Built as part of a finance portfolio targeting roles in **Investment Banking**, **Private Equity**, and **Corporate M&A**. Other projects in this portfolio include a full DCF/trading comps/precedent transaction valuation, an LBO model, and an IPO readiness analysis.

---

*For questions or feedback, connect on [LinkedIn](www.linkedin.com/in/jose-isaac-quiros-b348a7217) or reach out directly.*

*This model is for educational and portfolio purposes only. It does not constitute financial or investment advice.*
