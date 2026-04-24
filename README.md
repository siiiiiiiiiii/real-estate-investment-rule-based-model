# Which Real Estate Investment Vehicle Is Best at Present?  
## A Data-Driven Rule-Based Decision Framework

This project was developed for the **FINT400 Artificial Intelligence** course at **Hong Kong Shue Yan University**.

The project answers the following question:

> **Which real estate investment vehicle is best at present?**

Instead of giving a subjective investment opinion, this project uses a **data-driven rule-based decision framework** to compare different real estate investment vehicle types under the current interest-rate environment.

---

## Project Summary

This project compares three real estate investment vehicle types:

1. **Listed REIT ETF**, represented by **XLRE**
2. **Direct Residential Property**
3. **Private / Leveraged Real Estate**

The model uses observable ETF data for the listed REIT vehicle and macro-financial indicators for the non-listed vehicles. The final recommendation is generated through a weighted scoring framework.

The result shows that the best real estate investment vehicle at present is:

> **Listed REIT ETF (XLRE)**

---

## Why This Project Uses a Rule-Based Framework

This project is not designed as a pure machine learning prediction model. Instead, it applies a **rule-based decision framework**, which is suitable for this coursework because the objective is to support investment decision-making using structured data and algorithmic logic.

The framework is useful because:

- It makes the investment decision process transparent.
- It converts financial indicators into comparable scores.
- It allows different vehicle types to be evaluated under the same structure.
- It includes scenario analysis and sensitivity analysis.
- It is easier to interpret than a black-box model.

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

### 2. Direct Residential Property

Direct residential property represents buying physical property directly.

The model evaluates this vehicle type using:

- Mortgage rate level
- Mortgage rate trend
- Long-term interest-rate environment
- Liquidity limitation
- Capital requirement
- Implementation difficulty

### 3. Private / Leveraged Real Estate

Private / leveraged real estate represents real estate strategies that rely more heavily on debt financing, refinancing, and private-market execution.

The model evaluates this vehicle type using:

- Refinancing pressure
- Leverage stress
- Mortgage rate level
- 10-year Treasury yield
- Federal debt-to-GDP ratio
- Liquidity and transparency limitations

---

## Data Used

The project uses Excel files stored locally in the `FINT400` and `FIN446` folders.

### FINT400 Data

- `three_etf_performance(FINT400).xlsx`
- `etf_fund_data_mar10_2026(FINT400).xlsx`
- `spdr-product-data-us-en(FINT400).xlsx`

### FIN446 Data

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
