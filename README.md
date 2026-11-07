# Trans Mountain Pipeline — Financial Modelling & Sensitivity Analysis

## Project Overview

This project evaluates the financial viability of a hypothetical investment in the Trans Mountain Pipeline using a discounted cash flow (DCF) model developed in Microsoft Excel.

The analysis incorporates project acquisition and construction costs, toll revenues, operating expenses, bond financing, and a terminal sale value. Sensitivity analysis is used to evaluate how changes in key assumptions affect project profitability.

**Tools:** Microsoft Excel

**Methods:** Discounted Cash Flow, Net Present Value (NPV), Internal Rate of Return (IRR), Financial Forecasting, Sensitivity Analysis

## Financial Model

The model incorporates the following assumptions:

| Parameter | Base-Case Value |
|---|---:|
| Purchase Cost | $1.4 billion |
| Construction Cost | $7.4 billion |
| Pipeline Capacity | 890,000 barrels/day |
| Initial Toll Rate | $12/barrel |
| Annual Toll Rate Increase | 5% |
| Annual Inflation Rate | 4% |
| Bond Financing | $1 billion |
| Bond Coupon Rate | 10% |
| Discount Rate | 20% |
| Terminal Sale Value | $1.5 billion |

The analysis models project cash flows over a 10-year financing and operating horizon, incorporating the initial investment, subsequent operating revenues and expenses, financing payments, and terminal proceeds.

## Base-Case Results

| Financial Metric | Result |
|---|---:|
| NPV (20% Discount Rate) | $308.83 million |
| IRR | 21.27% |
| NPV (15% Discount Rate) | $1.84 billion |
| NPV (25% Discount Rate) | -$758.40 million |

Under the base-case assumptions, the project generates a positive NPV and an IRR above the assumed 20% discount rate.

However, profitability is sensitive to changes in the discount rate and operating assumptions.

## Sensitivity Analysis

### Inflation Rate

The model evaluates inflation rates between 2% and 6%.

| Inflation Rate | NPV |
|---|---:|
| 2% | $759.24M |
| 3% | $538.44M |
| 4% | $308.83M |
| 5% | $70.05M |
| 6% | -$178.26M |

Higher inflation reduces project profitability under the model's assumptions. At 6% inflation, the estimated NPV becomes negative.

### Annual Toll Rate Increase

The model evaluates annual toll-rate increases between 3% and 7%.

| Annual Toll Increase | NPV |
|---|---:|
| 3% | -$559.89M |
| 4% | -$134.03M |
| 5% | $308.83M |
| 6% | $769.38M |
| 7% | $1.25B |

The project is highly sensitive to assumed toll-rate increases. Under the model's assumptions, lower toll growth can produce a negative NPV, while higher growth substantially improves projected profitability.

## Additional Sensitivity Metrics

The workbook estimates local NPV elasticities for the two assumptions:

- **Inflation elasticity:** -3.04
- **Toll-rate increase elasticity:** 7.32

These measures indicate the approximate percentage change in NPV associated with a 1% relative change in each input near the base case, holding other assumptions constant.

## Key Findings

- The base-case scenario produces a positive NPV of approximately $308.83 million.
- The investment's estimated IRR is 21.27%, slightly above the assumed discount rate.
- Higher inflation reduces projected profitability.
- Lower annual toll-rate growth can result in a negative NPV.
- Investment conclusions depend substantially on the model's financing, operating, and valuation assumptions.

## Repository Files

| File | Description |
|---|---|
| `Trans_Mountain_Financial_Model.xlsx` | Excel workbook containing financial assumptions, financing schedules, cash-flow projections, NPV/IRR calculations, sensitivity analysis, and charts. |

## Skills Demonstrated

- Excel financial modelling
- Discounted cash flow valuation
- Investment appraisal using NPV and IRR
- Cash-flow forecasting
- Bond financing calculations
- Sensitivity analysis and elasticity estimation
- Financial risk assessment

## Academic Context

**Course:** ECON 311 — Computer Applications in Economics

**Institution:** University of Calgary

This project was completed as an academic financial modelling exercise. Its assumptions and findings should not be interpreted as an independent valuation of the actual Trans Mountain Pipeline or as investment advice.
