# Which Real Estate Investment Vehicle Is Best at Present?  
## A Data-Driven Rule-Based Decision Framework for FIN446 Property Valuation, Funding and Finance

This project was developed for the **FIN446 Property Valuation, Funding and Finance** course at **Hong Kong Shue Yan University**.

The assignment question is:

> **After studying the whole course, suggest which real estate investment vehicles are the best at present.**

To answer this question, this project uses a **data-driven rule-based decision framework** to compare different real estate investment vehicle types under the current interest-rate and property-financing environment.

Instead of giving a purely subjective investment opinion, the project applies real estate finance concepts, market data, funding indicators, REIT evidence, and automated Python-based analysis to support the final recommendation.

---

## Project Summary

This project compares three real estate investment vehicle types:

1. **Listed REIT ETF**, represented by **XLRE**
2. **Direct Residential Property**
3. **Private / Leveraged Real Estate**

The model uses observable ETF data for the listed REIT vehicle and macro-financial indicators for the non-listed vehicles. The final recommendation is generated through a weighted scoring framework.

The result shows that the best real estate investment vehicle at present is:

> **Listed REIT ETF (XLRE)**

This result is mainly driven by XLRE’s liquidity, diversification, observable income yield, positive medium-term performance, and lower implementation difficulty compared with direct property ownership and highly leveraged private real estate strategies.

---

## Connection with FIN446 Course Content

This project is directly related to **FIN446 Property Valuation, Funding and Finance** because it applies several major themes from the course:

- **Real estate market fundamentals**
- **Property funding conditions**
- **Mortgage rate and financing cost analysis**
- **Real estate investment trusts**
- **Real estate investment performance**
- **Portfolio considerations**
- **Automated real estate and Python-based decision analysis**

The project does not replace formal property-level valuation methods such as direct comparison, investment approach, profit approach, replacement cost approach, residual valuation, or DCF valuation. Instead, it focuses on comparing real estate investment vehicle types from an investment and funding perspective.

This is suitable for the assignment because the question asks which real estate investment vehicles are currently the best, rather than asking for the valuation of one specific property.

---

## Link to FIN446 Course Intended Learning Outcomes

### CILO1: Explain and apply valuation methods in valuing different types of properties

This project does not conduct a full property-level valuation report. However, it applies valuation-related indicators such as yield, forward P/E ratio, performance history, and asset scale to evaluate the attractiveness of the listed REIT vehicle.

### CILO2: Examine the fundamentals driving the real estate market

The model uses interest-rate and mortgage-rate indicators to examine the current real estate market environment. These factors are important because property values and real estate investment returns are strongly affected by financing costs, long-term rates, and macro-financial conditions.

### CILO3: Identify the key factors that affect property funding

This is one of the strongest parts of the project. The model explicitly considers:

- 10-year Treasury yield
- 30-year mortgage rate
- Mortgage rate trend
- Refinancing pressure
- Leverage stress
- Financing resilience

These factors are used to compare how different real estate investment vehicles are affected by the current funding environment.

### CILO4: Explain the structure and development of real estate related products

The project compares different real estate-related investment structures, including a listed REIT ETF, direct residential property, and private / leveraged real estate. XLRE is used as the public-market REIT proxy because it represents a liquid and diversified real estate product.

---

## Research Question

The main research question is:

> **Which real estate investment vehicle is best at present?**

The project evaluates this question by comparing the attractiveness of different real estate investment vehicles based on income, performance, liquidity, financing resilience, and implementation difficulty.

---

## Investment Vehicles Compared

### 1. Listed REIT ETF (XLRE)

XLRE is used as the proxy for the listed REIT vehicle. It represents a liquid and diversified way to invest in real estate through the public market.

The model evaluates XLRE using:

- 1-year return
- 3-year return
- 5-year return
- Fund distribution yield
- 30-day SEC yield
- Forward P/E ratio
- Number of holdings
- Gross expense ratio
- Total net assets
- Interest-rate sensitivity

This part is related to the FIN446 topic on **real estate investment trusts** and **real estate investment performance**.

---

### 2. Direct Residential Property

Direct residential property represents buying physical property directly.

The model evaluates this vehicle type using:

- Mortgage rate level
- Mortgage rate trend
- Long-term interest-rate environment
- Liquidity limitation
- Capital requirement
- Implementation difficulty

This part is related to the FIN446 topics on **residential property markets**, **mortgage financing**, and **property funding**.

---

### 3. Private / Leveraged Real Estate

Private / leveraged real estate represents real estate strategies that rely more heavily on debt financing, refinancing, and private-market execution.

The model evaluates this vehicle type using:

- Refinancing pressure
- Leverage stress
- Mortgage rate level
- 10-year Treasury yield
- Federal debt-to-GDP ratio
- Liquidity and transparency limitations

This part is related to the FIN446 topics on **financing corporate real estate**, **real estate development funding**, and **investment risk**.

---

## Why This Project Uses a Rule-Based Framework

This project uses a rule-based decision framework because the assignment asks students to suggest the best real estate investment vehicle at present. A rule-based model is suitable because it makes the investment decision process transparent and explainable.

The framework is useful because:

- It makes the decision process clear.
- It converts real estate finance indicators into comparable scores.
- It allows different vehicle types to be evaluated under the same structure.
- It considers property funding conditions.
- It includes scenario analysis and sensitivity analysis.
- It connects real estate investment decisions with current market conditions.

This approach is also related to the later part of FIN446, which introduces **automated real estate**, **Python programming**, **PropTech**, and **AI-related real estate applications**.

---

## Data Used

The project uses Excel files stored locally in the `FINT400` and `FIN446` folders.

The ETF data files are used to evaluate the listed REIT vehicle, while the macro-financial files are used to evaluate the broader interest-rate and property-financing environment.

### ETF and REIT-Related Data

- `three_etf_performance(FINT400).xlsx`
- `etf_fund_data_mar10_2026(FINT400).xlsx`
- `spdr-product-data-us-en(FINT400).xlsx`

### Macro-Financial and Property-Funding Data

- `DGS10(FIN446).xlsx`
- `MORTGAGE30US(FIN446).xlsx`
- `GFDEGDQ188S(FIN446).xlsx`

---

## Key Market Inputs

The model uses the following observed market inputs:

| Indicator | Value |
|---|---:|
| Latest 10Y Treasury yield | 4.15% |
| Average 10Y Treasury yield over the last ~1 year | 4.23% |
| Latest 30Y mortgage rate | 6.00% |
| Average 30Y mortgage rate over the last ~1 year | 6.45% |
| 30Y mortgage rate change over ~12 weeks | -0.22 percentage points |
| Latest federal debt-to-GDP ratio | 122.31% |

These indicators are important because real estate investment is highly sensitive to interest rates, mortgage costs, and refinancing conditions.

---

## XLRE Evidence

The listed REIT vehicle is represented by XLRE.

| Metric | Value |
|---|---:|
| XLRE 1-year return | 2.58% |
| XLRE 3-year return | 6.63% |
| XLRE 5-year return | 5.49% |
| XLRE fund distribution yield | 3.24% |
| XLRE 30-day SEC yield | 3.29% |
| XLRE forward P/E ratio | 37.03 |
| XLRE number of holdings | 31 |
| XLRE gross expense ratio | 0.08% |
| XLRE total net assets | US$7,606.70M |

These data are used to evaluate the income, performance, diversification, transparency, and implementation characteristics of the listed REIT vehicle.

---

## Scoring Framework

The final score is a weighted sum of five dimensions. Each dimension is scored on a 0–100 basis.

| Dimension | Weight |
|---|---:|
| Income | 20% |
| Performance | 20% |
| Liquidity & Diversification | 20% |
| Financing Resilience | 25% |
| Implementation & Transparency | 15% |

The total score is calculated as:

```text
Total Score =
Income × 20%
+ Performance × 20%
+ Liquidity & Diversification × 20%
+ Financing Resilience × 25%
+ Implementation & Transparency × 15%
