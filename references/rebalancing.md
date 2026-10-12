# Rebalancing Engine

## Trigger Types

1. **Scheduled** — Daily or weekly (user configurable)
2. **Threshold** — When yield gap or risk score difference exceeds set limits
3. **Regime Change** — Detected shift from risk-on to risk-off (or vice versa)
4. **User Request** — Manual command
5. **Emergency** — Drawdown circuit breaker or protocol incident

## Decision Process

Before proposing any rebalance the agent must:

1. Calculate current Throne Scores of existing positions
2. Scan and score alternative opportunities
3. Estimate gas + slippage cost of the proposed moves
4. Compute expected net improvement
5. Check that the new allocation still respects layer targets and risk rules
6. Present a clear before/after comparison to the user (in Co-Pilot mode)

## Gas Awareness

- Prefer fewer, higher-impact moves over many small ones
- Avoid rebalancing when gas costs would consume a large portion of expected yield gain
- On high-gas chains, be more conservative
