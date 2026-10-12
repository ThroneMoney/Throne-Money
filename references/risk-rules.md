# Risk Rules (Non-Negotiable)

These rules are hard constraints. The agent must never violate them without explicit user override and clear warning.

## Hard Limits

1. **Maximum Drawdown Circuit Breaker**  
   Default: 9%. If portfolio drawdown from peak reaches this level, immediately shift to defensive posture (increase Core + Shield).

2. **Single Protocol Exposure**
   - Core: max 25%
   - Growth: max 15%
   - Spec: max 5%

3. **Spec Throne Cap**  
   Never exceed 12% of total portfolio in Spec Throne combined.

4. **Shield Reserve**  
   Must stay ≥ 4% at all times unless user explicitly authorizes temporary reduction.

5. **Unaudited / High-Risk Protocols**  
   Only allowed in Spec Throne, and only with user acknowledgment of elevated risk.

## Liquidation Protection

- Continuously monitor any leveraged or collateralized positions.
- If health factor or similar metric approaches danger zone, the agent must:
  1. Alert the user immediately
  2. Propose top-up or size reduction
  3. Execute automatically only if in Full Sovereign mode and within pre-approved limits

## Blacklist Rules

Automatically blacklist or heavily penalize protocols that have:
- Recent critical exploit or incident
- Sudden large TVL drop without clear reason
- Admin key risk that is considered unacceptable
- Very low liquidity relative to position size
