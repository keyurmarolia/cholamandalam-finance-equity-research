# Model review

Publication review: 21 September 2026. Scope: repository presentation, saved workbook outputs, financial reconciliations and valuation arithmetic. The workbook was preserved unchanged.

## Checks completed

| Check | Result |
| --- | --- |
| README valuation figures | Agree with the saved workbook |
| Balance sheet | Assets equal liabilities and equity across all ten historical and forecast years, within numerical precision |
| Cash flow | Closing cash agrees with balance-sheet cash across all ten years |
| Forecast equity roll-forward | Opening equity, profit, dividends, new funding and CCD conversion reconcile to closing equity |
| FCFE valuation | Independently recomputed explicit and terminal present values, including the first-year fraction; INR 776.15 per share |
| Reverse DCF | Independently recomputed implied terminal ROE of 33.8%; saved repricing matches INR 1,779 |
| Saved formula results | No cached spreadsheet errors or formulas without saved values |
| Workbook dependencies | No external workbook links |

## Reading the valuation

Borrowings are operating funding for this lender. FCFE deducts required equity reinvestment from profit, and debt is not deducted a second time. Required equity is modelled at 14% of net loans; this is an analytical capital-intensity assumption, not regulatory CAR.

The 17% base terminal ROE is distinct from the model's FY2031 ROE. The reverse DCF changes terminal ROE while keeping the five-year forecast unchanged. Approximately 92.5% of base equity value comes from the terminal value, so long-term profitability, growth and cost of equity drive the result.

## Limits of this review

These checks inspect saved results and independently verify selected arithmetic; they do not constitute native Excel recalculation or a fresh cell-by-cell audit against every source filing. Prior sensitivity checks described in the main README were not repeated in this publication review.

The model uses standalone aggregate financials, estimated CCD dilution and a simplified cash-flow bridge. The 18 September 2026 reference price is a dated input, not a live quote. Operating assumptions, discount rate and terminal profitability remain estimates. This research is not an investment recommendation.
