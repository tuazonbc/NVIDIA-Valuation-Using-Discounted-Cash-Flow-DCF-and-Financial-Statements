# NVIDIA Discounted Cash Flow (DCF) Valuation

## Project Overview

For this project, I built a Discounted Cash Flow (DCF) model in Excel to estimate the value of NVIDIA Corporation (NASDAQ: NVDA). I used NVIDIA's financial statements and forecasts of future cash flow to estimate how much one share could be worth.

My valuation is based on **November 12, 2025**. It is a historical valuation, not an estimate based on today's stock price.

## Valuation Results

| Measure | My Model |
| --- | ---: |
| Estimated value per share | **$69.18** |
| NVIDIA share price used for comparison | $193.80 |
| Weighted Average Cost of Capital (WACC) | 13.78% |
| Long-term growth rate | 3.50% |
| Estimated FY2030 revenue | About $377 billion |
| Estimated FY2030 free cash flow | About $179.55 billion |

My estimated share value is lower than NVIDIA's market price on the valuation date. This does not mean NVIDIA was definitely overvalued. It means my model produces a lower value based on the assumptions I used.

## How I Built the Valuation

I started by reviewing NVIDIA's historical financial statements. I then estimated future revenue, expenses, and free cash flow. Free cash flow is the cash left after the company pays for its operations and investments.

I used WACC to bring those future cash flows back to their estimated value as of November 12, 2025. I also calculated a terminal value to account for cash flows beyond the forecast period. After adjusting for cash and debt, I estimated a value per share.

## Why My Estimated Value Is Lower

My model assumes NVIDIA's revenue growth slows over the forecast period. It also uses a WACC of 13.78%, which reduces the value of cash flows expected further in the future.

These assumptions help explain why my estimate is much lower than the market price. I treat **$69.18 as a conservative case**, not as the only possible value of NVIDIA.

## Growth Comparison and Sensitivity Analysis

I included a growth comparison to see how a higher cash flow forecast could change the result. My model estimates about $179.55 billion in free cash flow for FY2030. For comparison, an October 2025 Simply Wall St analysis used an estimate of about $249.21 billion.

The workbook also looks at how different WACC and long-term growth rates affect the valuation. These comparisons help show why two people can value the same company differently.

The published comparison uses a different valuation method, so its estimated share value is not directly equal to the result of my model.

## What's in the Excel Workbook

The Excel file includes NVIDIA's historical financial statements, revenue and cash flow forecasts, WACC calculations, the DCF model, sensitivity analysis, and a growth comparison. It also includes notes explaining the main assumptions.

## Sources

* [NVIDIA Investor Relations](https://investor.nvidia.com/)
* [NVIDIA SEC filings](https://www.sec.gov/edgar/browse/?CIK=1045810&owner=exclude)
* [U.S. Treasury interest rates](https://home.treasury.gov/resource-center/data-chart-center/interest-rates)
* [Damodaran valuation data](https://pages.stern.nyu.edu/~adamodar/)
* Simply Wall St, October 2025 NVIDIA DCF analysis, used for a forecast comparison

## Limitations

A DCF model depends on estimates. Changes in growth, profit margins, WACC, and terminal growth can lead to different share values. Not every historical input or market assumption has been independently verified against its original source.

This project is for learning and demonstrating my Excel and financial modeling skills. It is not investment advice.
