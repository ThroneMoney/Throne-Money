# Throne Score System

The Throne Score is the core decision engine of Throne Money.  
Every yield opportunity is scored from **0 to 100**.

## Scoring Factors & Weights

| Factor                        | Weight | Description |
|------------------------------|--------|-----------|
| Net Real Yield               | 25%    | APY after estimated gas, slippage, and claim costs |
| Protocol Risk                | 25%    | Audits, TVL trend, incident history, team reputation, admin keys |
| Liquidity & Exit Risk        | 15%    | Depth, withdrawal queues, lockups |
| Smart Money / Concentration  | 10%    | Whale concentration and recent smart money flows |
| Correlation Risk             | 10%    | How correlated the opportunity is with existing positions |
| Opportunity Cost             | 10%    | How much better/worse vs current best alternatives |
| Points / Incentive Value     | 5%     | Estimated value of points or airdrops |

## Score Thresholds

- **≥ 85** → Elite (strong candidate for Core or Growth)
- **72 – 84** → Acceptable for Core / Growth
- **58 – 71** → Only allowed in Spec Throne (with user acknowledgment)
- **< 58** → Rejected

## How the Agent Should Use It

1. Always calculate and show the Throne Score when evaluating opportunities.
2. Never move capital into something below the relevant threshold without explicit user override.
3. Re-score existing positions periodically. If a position falls below threshold, propose an exit or reduction.
