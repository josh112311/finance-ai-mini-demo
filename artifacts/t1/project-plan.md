# Project Plan

## Project Goal

Develop a clear and reproducible research workflow for comparing three familiar asset classes:

- `SPY` — US equities
- `TLT` — long-term US Treasury bonds
- `GLD` — gold

The goal is to set up a bounded analysis task that can be repeated and verified, using versioned files and AI-assisted collaboration.

## Available Data

`data/etf_snapshot.csv` is a small, fixed dataset with one row per ETF. Columns are `ticker`, `asset_class`, `expected_return_pct`, `volatility_pct`, `max_drawdown_pct`, and `expense_ratio_pct`. It contains:

| ticker | asset_class | expected_return_pct | volatility_pct | max_drawdown_pct | expense_ratio_pct |
|---|---|---|---|---|---|
| SPY | US Equity | 8.2 | 18 | -24 | 0.09 |
| TLT | Long-Term US Treasury | 4 | 14 | -18 | 0.15 |
| GLD | Gold | 5.5 | 15.5 | -16 | 0.4 |

The dataset is synthetic teaching data: all numeric values are illustrative assumptions, not live or historical market observations, and must not be used as investment advice.

## Expected Final Deliverable

A reproducible analysis comparing SPY, TLT, and GLD on the available metrics (expected return, volatility, max drawdown, and expense ratio), together with the artifacts produced during the tutorials — such as the written plan, any analysis scripts or notebooks, and verification results.

## Three Project Milestones

1. **Project setup (T1)**: Create the initial project plan at `artifacts/t1/project-plan.md` and save it with Git for review.
2. **Bounded analysis design**: Define the analysis task, expected outputs, and an agent workflow for performing and verifying the comparison.
3. **Execution and verification**: Run the planned analysis, verify the results against the data dictionary and acceptance checks, and document the outcome.

## One Data Limitation

The dataset is synthetic and intentionally omits correlations, taxes, transaction costs, liquidity, currency exposure, and investor-specific constraints; it contains only three illustrative rows, so no conclusion from it can be generalized to real markets.

## Next Action

Have a learner review this plan and save it with Git as the T1 deliverable; the analysis itself is planned work for later tutorials and has not been completed yet.
