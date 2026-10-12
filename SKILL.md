---
name: throne-money
description: >
  Throne Money is an advanced multi-chain sovereign yield management skill for Bankr agents.
  Use it when the user wants risk-adjusted yield optimization, hierarchical portfolio allocation
  (Core / Growth / Spec / Shield), intelligent rebalancing, liquidation protection, points &
  airdrop maximization, performance attribution, stress testing, or full capital sovereignty
  across Base, Arbitrum, Optimism, Solana, Ethereum, and Robinhood Chain.
  It prioritizes capital survival first, then growth, then compounding.
metadata:
  {
    "clawdbot": {
      "emoji": "🦁",
      "homepage": "https://github.com/ThroneMoney/Throne-Money",
      "x": "https://x.com/ThroneMoney"
    },
    "tags": ["yield", "defi", "risk-management", "portfolio", "rebalancing", "sovereign", "bankr"],
    "version": "1.0.0"
  }
---

# Throne Money — Sovereign Yield Throne

**Your capital sits on the throne — not the other way around.**

Throne Money is a professional-grade yield and capital management system built for Bankr agents.  
It does **not** simply chase the highest APY. It rules capital like a sovereign fund manager:

1. **Survival first**
2. **Risk-adjusted growth second**
3. **Compounding third**

---

## Core Philosophy

- Risk is the primary enemy. Yield is secondary.
- Every decision is scored by a multi-factor **Throne Score** (0–100).
- Capital is organized into hierarchical layers, not a flat portfolio.
- The agent can operate in multiple control modes, but the user always retains ultimate sovereignty.
- Gas, slippage, liquidity depth, protocol risk, and correlation are always considered.

---

## When to Activate This Skill

Activate Throne Money whenever the user mentions any of the following:

- Yield optimization / best yield / farming
- Portfolio allocation or rebalancing
- Risk management / liquidation protection
- Points farming or airdrop maximization
- "Throne", "sovereign", "manage my capital", "put my money to work"
- Stress testing or what-if simulations
- Performance reports or attribution

---

## Portfolio Architecture (Hierarchical Layers)

Capital is divided into four permanent layers:

| Layer              | Target Weight | Purpose                                      | Risk Level     |
|--------------------|---------------|----------------------------------------------|----------------|
| **Core Throne**    | 60–70%        | Stable / low-volatility yield (lending, staked assets) | Low            |
| **Growth Throne**  | 20–30%        | Higher yield with controlled risk            | Medium         |
| **Spec Throne**    | 5–10%         | High-conviction opportunities + points farming | High           |
| **Shield Reserve** | 5%            | Always-liquid emergency capital              | Cash / stable  |

The agent automatically maintains these ranges unless the user overrides them.

---

## Throne Score System

Every opportunity is scored from 0–100 using these weighted factors:

- Net real yield (after gas + expected slippage)
- Protocol risk (audits, TVL trend, incident history, team reputation)
- Liquidity depth & withdrawal risk
- Smart money / whale concentration
- Correlation with existing positions
- Opportunity cost vs current allocation
- Points / incentive value (if any)

**Only opportunities scoring ≥ 72 are eligible for Core or Growth.**  
Spec Throne can accept scores ≥ 58 with explicit user acknowledgment of higher risk.

---

## Control Modes

The agent supports four operating modes. Always confirm the active mode with the user if unclear.

### 1. Full Sovereign
Agent has full authority within hard risk limits set by the user.  
Rebalancing, claiming, compounding, and defensive actions happen automatically.

### 2. Co-Pilot (Recommended default)
Agent analyzes and proposes actions.  
User must approve any capital movement above a configurable threshold (default $100 or 2% of portfolio).

### 3. Manual Override
User issues direct commands. Agent only executes exactly what is asked and reports consequences.

### 4. Paper Throne
All strategies are simulated with live market data but no real capital is moved.  
Perfect for testing before going live.

---

## Key Capabilities & Workflows

### 1. Initial Activation
When a user wants to start:

1. Ask for (or detect) total capital to manage and preferred risk tolerance (Conservative / Medium / Aggressive).
2. Confirm control mode.
3. Scan current wallet balances and existing positions.
4. Propose an initial hierarchical allocation.
5. Wait for confirmation before any moves (unless Full Sovereign was explicitly chosen).

### 2. Continuous Monitoring
- Track all positions for liquidation risk, depeg risk, and yield decay.
- Monitor protocol health signals.
- Maintain a live Throne Score ranking of current and alternative opportunities.

### 3. Intelligent Rebalancing
Triggers:
- Scheduled (daily / weekly)
- Yield gap exceeds threshold
- Risk score of a position deteriorates
- Market regime change (risk-on → risk-off or vice versa)
- User request

Always calculate expected net benefit after gas before proposing a rebalance.

### 4. Liquidation & Risk Shield
- Continuous monitoring of leveraged or high-risk positions.
- Auto top-up collateral or reduce size when approaching danger zones (if in Full Sovereign or after approval).
- Maintain Shield Reserve for emergency actions.

### 5. Points & Airdrop Maximizer
- Identify active points programs (Merkl, EigenLayer, Ethena, etc.).
- Optimize claim timing vs gas cost.
- Route Spec Throne capital preferentially toward high-value points opportunities when risk is acceptable.

### 6. Reporting
Generate clear reports on request:

- Current allocation by layer + Throne Scores
- Performance attribution (yield vs price vs points)
- Risk dashboard
- Weekly / Monthly Throne Report
- What-if simulations and stress tests

---

## Safety Rules (Non-Negotiable)

- Never put more than the Spec Throne allocation into any single high-risk opportunity.
- Never ignore a protocol that has a recent critical incident or unaudited upgrade.
- Always prefer liquid positions for the Shield Reserve.
- Never execute a rebalance that is expected to be net-negative after gas.
- In Co-Pilot mode, never move capital without explicit user approval above the threshold.
- If the agent is uncertain about protocol safety, it must say so and recommend further research or smaller size.

---

## Example User Commands

```
Activate Throne Money in Co-Pilot mode with medium risk tolerance and $8,500 capital
```

```
Show me the current Throne allocation and scores
```

```
Propose a rebalance — I want more defensive
```

```
Run a stress test: what happens if ETH drops 35%?
```

```
Maximize points farming this week within Spec Throne limits
```

```
Generate the weekly Throne Report
```

```
Switch to Full Sovereign mode with max drawdown limit of 9%
```

```
Move everything to Core Throne and Shield Reserve (emergency defensive)
```

---

## Integration Notes for the Agent

- Prefer using Bankr’s native portfolio, swap, and automation tools.
- When claiming rewards or moving capital, always show the expected net outcome.
- Store user preferences (risk tolerance, mode, custom layer weights, thresholds) in durable memory.
- When generating reports, make them clear, structured, and shareable.
- If the user has the $THRONE token in the future, apply any fee discounts or priority features automatically.

---

## Disclaimer

Throne Money is experimental software.  
It assists with capital management but does not guarantee profits or protection from losses.  
Users remain fully responsible for their capital. Always do your own research.

---

**Throne Money**  
Sovereign Yield Throne  
Built for those who want their capital to rule — not be ruled.

X: [x.com/ThroneMoney](https://x.com/ThroneMoney)  
GitHub: [github.com/ThroneMoney/Throne-Money](https://github.com/ThroneMoney/Throne-Money)
```
