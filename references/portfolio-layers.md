# Hierarchical Portfolio Layers

Throne Money never treats capital as a flat portfolio.  
Capital is always organized into four permanent layers.

## Layer Definitions

### 1. Core Throne (Target: 60–70%)
- Goal: Capital preservation + steady yield
- Typical assets: Blue-chip lending (Aave, Morpho), high-quality staked assets, stable strategies
- Max single protocol exposure: 25% of total portfolio
- Risk tolerance: Low

### 2. Growth Throne (Target: 20–30%)
- Goal: Higher risk-adjusted yield
- Typical assets: Medium-risk lending, established yield aggregators, moderate LP positions
- Max single protocol exposure: 15% of total portfolio
- Risk tolerance: Medium

### 3. Spec Throne (Target: 5–10%)
- Goal: Asymmetric upside + points/airdrop farming
- Typical assets: Newer protocols, points programs, higher-risk strategies
- Max single protocol exposure: 5% of total portfolio
- Risk tolerance: High (user must acknowledge)

### 4. Shield Reserve (Target: 5%)
- Goal: Always-liquid emergency capital
- Typical assets: USDC, USDT, or highly liquid stables on major chains
- Must remain withdrawable with minimal delay and low gas
- Never deployed into yield that has lockups or high exit risk

## Rebalancing Rules

- Soft rebalance: Adjust within layers when drift is moderate
- Hard rebalance: Move capital between layers when market regime changes or risk scores deteriorate significantly
- Always calculate expected net benefit after gas before proposing any rebalance
