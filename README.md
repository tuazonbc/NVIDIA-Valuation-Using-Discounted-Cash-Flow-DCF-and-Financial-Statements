# NVIDIA (NVDA) | Discounted Cash Flow Valuation

**Valuation date:** November 12, 2025  
**Currency:** USD  
**Method:** Discounted Cash Flow (DCF), using projected free cash flow to the firm (FCFF)

## Project Overview

This project evaluates NVIDIA Corporation's estimated intrinsic equity value using historical financial statements, projected operating performance, a weighted average cost of capital (WACC), and a terminal value calculation. It also examines how changes in long-term growth and discount rates affect the implied share price.

The analysis is a **historical, assumptions-based valuation as of November 12, 2025**, not a forecast made using information available today.

## Valuation Summary

| Metric | Estimate |
| --- | ---: |
| Reference market price (model input) | $193.80 |
| Conservative-case implied share price | Approximately $69.18 |
| Implied downside versus reference price | Approximately 64.3% |
| WACC | 13.78% |
| Perpetual growth rate | 3.50% |
| Projected FY2030 revenue | Approximately $377 billion |
| Projected FY2030 free cash flow | Approximately $179.55 billion |

**Interpretation:** Under the model's conservative growth and discount-rate assumptions, estimated intrinsic value is substantially below the reference market price. This is a **scenario outcome**, not proof that NVIDIA was mispriced by 64.3%.

## Valuation Methodology

The model forecasts free cash flow to the firm:

```text
FCFF = EBIT × (1 − Tax Rate) + Depreciation & Amortization
       − Capital Expenditures − Change in Net Working Capital
```

Forecast FCFF is discounted at WACC. Terminal value is estimated using perpetual growth:

```text
Terminal Value = Final Forecast FCFF × (1 + g) / (WACC − g)
```

Enterprise value is the sum of the present value of forecast-period cash flows and terminal value. Equity value is calculated by adding cash and subtracting debt, then divided by the assumed diluted share count to estimate intrinsic value per share.

## Key Assumptions and Interpretation

- **WACC (13.78%):** A relatively high discount rate that materially reduces the present value of future cash flows. The underlying beta and equity risk premium are model assumptions and should not be described as independently verified estimates.
- **Long-term growth (3.50%):** A perpetual growth assumption, not NVIDIA management guidance.
- **Revenue trajectory:** The model assumes growth slows considerably by FY2030. This is an important reason the valuation is below some published analyst estimates.
- **Profitability and cash conversion:** Forecast operating margins, reinvestment, and working capital determine how projected revenue becomes free cash flow.

## Growth Comparison

An additional **Growth Comparison** worksheet illustrates a higher-free-cash-flow scenario using an external FY2030 benchmark of approximately **$249.21 billion**, versus approximately **$179.55 billion** in the original forecast. This comparison is a sensitivity exercise: it is **not** a complete independently constructed operating forecast and should not be interpreted as a directly comparable replication of another analyst's DCF.

Different published valuations may use different forecast horizons, cash-flow definitions (FCFF versus FCFE), discount rates, terminal assumptions, and share counts. Their implied prices should not be compared without considering those differences.

## Workbook Contents

The Excel workbook includes financial statement analysis, forecast assumptions, DCF calculations, and sensitivity or comparison analyses. Review the worksheets for the full model and formula detail.

## Sources and Research

Primary sources to consult for the historical valuation include:

- [NVIDIA Investor Relations — Financial Information](https://investor.nvidia.com/financial-info/financial-reports-and-sec-filings/default.aspx)
- [NVIDIA SEC filings](https://www.sec.gov/edgar/browse/?CIK=1045810&owner=exclude)
- [U.S. Treasury — Interest Rate Statistics](https://home.treasury.gov/resource-center/data-chart-center/interest-rates)
- [Damodaran Online — Data](https://pages.stern.nyu.edu/~adamodar/)

Sources listed here are research references. Not every historical input, beta estimate, equity risk premium, or forecast has been independently reconciled to its source. The valuation date should be respected when evaluating what information was available at the time.

## Limitations

This is an educational financial modeling project, **not an independently audited equity research report**. Its results depend on uncertain forecasts, including AI infrastructure demand, revenue growth, operating margins, reinvestment, and long-run cash flow. The base-case model is best understood as a **conservative scenario**. The model's approximate $69.18 value is not an objectively established fair value or a current price target.

Before relying on any output, open the workbook in Excel, recalculate formulas, and confirm that the displayed implied share price and sensitivity tables reflect the same assumptions.

## Disclaimer

For educational and portfolio purposes only. This project is not investment advice or a recommendation to buy or sell NVIDIA shares.
