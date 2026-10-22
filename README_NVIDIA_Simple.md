# NVIDIA Discounted Cash Flow (DCF) Valuation

## Project Overview

This project looks at the value of NVIDIA Corporation (NASDAQ: NVDA) using a discounted cash flow (DCF) model in Excel. I used financial statements and estimates of future cash flow to calculate what one NVIDIA share could be worth.

The valuation date is **November 12, 2025**. The model uses information and assumptions for that date, not NVIDIA's current share price.

## Valuation Results

| Measure | Value |
| --- | ---: |
| Estimated value per share | **$69.18** |
| Share price used for comparison | $193.80 |
| Weighted average cost of capital (WACC) | 13.78% |
| Long-term growth rate | 3.50% |
| Estimated FY2030 revenue | $377 billion |
| Estimated FY2030 free cash flow | $179.55 billion |

My model gives a value below the share price used for comparison. This does not prove that NVIDIA was overvalued. It shows the result of the assumptions used in my model.

## How I Built the Model

I reviewed NVIDIA's financial results and used them to estimate future revenue, costs, and free cash flow. Free cash flow is the cash a business has left after paying for its operations and investments.

I then used a DCF model to estimate the value of those future cash flows in November 2025. The model also includes a value for cash flows after the forecast period, called the terminal value. I adjusted for cash and debt to estimate the value per share.

## Why My Estimate Is Lower Than the Market Price

My forecast assumes NVIDIA's growth slows over time. It also uses a WACC of 13.78%, which lowers the value of cash flows expected further into the future.

These assumptions make my result more conservative than some other published NVIDIA valuations. The estimate should be read as a **conservative case**, not as a certain future share price.

## Growth Comparison

The workbook includes a separate growth comparison. My model estimates about **$179.55 billion** in FY2030 free cash flow. A published October 2025 Simply Wall St analysis used a higher FY2030 estimate of about **$249.21 billion**.

This comparison shows how different cash flow estimates can change a valuation. The two models also use different methods, so their share values should not be compared as if every assumption were the same.

## What Is in the Excel File

The workbook includes historical financial statements, forecasts, a DCF valuation, WACC calculations, sensitivity analysis, and a growth comparison. Some sheets also include notes about the model's assumptions and checks.

## Sources

- [NVIDIA Investor Relations](https://investor.nvidia.com/)
- [NVIDIA SEC filings](https://www.sec.gov/edgar/browse/?CIK=1045810&owner=exclude)
- [U.S. Treasury interest rate data](https://home.treasury.gov/resource-center/data-chart-center/interest-rates)
- [Damodaran valuation data](https://pages.stern.nyu.edu/~adamodar/)
- Simply Wall St, NVIDIA DCF analysis published in October 2025, used as a growth comparison

## Limitations

A DCF is based on estimates, so the result can change when revenue growth, profit margins, WACC, or long-term growth assumptions change. The model's historical inputs and market assumptions have not all been independently checked against original sources. This project is for learning and showing my financial modeling skills. It is not investment advice.
