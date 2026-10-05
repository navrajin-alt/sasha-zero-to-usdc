# SASHA // $0 → First USDC

A public experiment in agentic commerce: an AI operator starts with a registered identity and a zero balance, then tries to earn its first real USDC by finding, evaluating, completing and documenting legitimate paid work.

## Live state

- **Operator:** SASHA / ShadowOrders
- **TaskMarket agent ID:** `96694`
- **Public payout wallet:** `0x0a22db6FE11a0B0580D97B29DCAf00C5783E4BEe`
- **Starting USDC balance:** `0.00`
- **Completed paid tasks:** `0`
- **Verified earnings:** `0.00 USDC`

No simulated earnings, fake customers, purchased engagement or invented transactions are counted.

## What the agent actually does

1. Discover funded work and grants.
2. Reject tasks with bad payout economics, fake currency, required deposits or weak eligibility.
3. Produce a real deliverable when the expected value is reasonable.
4. Publish evidence of the work.
5. Count revenue only after an actual settlement or confirmed payment.

## Current evidence

### El Encuentro 2026 content bounty

SASHA found a live Superteam bounty for La Familia and produced an original Spanish article under human direction.

- Live article: https://navrajin-alt.github.io/el-encuentro-2026/
- Source: https://github.com/navrajin-alt/el-encuentro-2026
- Status: **submitted to sponsor by email / not won / not counted as revenue**

### TaskMarket

The agent is registered and can query on-chain funded work directly from the server. The first scan found funded tasks, but SASHA deliberately did not claim low-value/crowded or ineligible work. This is part of the experiment: autonomous earning includes saying no.

## Economic loop

`discover → verify funding → evaluate ROI/eligibility → claim or pitch → deliver → prove → settle → update public ledger`

## Next integration target: GOAT Network

The next technical step is to connect the existing earning loop to GOAT x402 / ERC-8004 infrastructure so SASHA can use agent-native payments and identity as part of the workflow rather than as a demo layer.

## Why this exists

The experiment asks a measurable question: **can an AI operator with tools, a public identity, and no starting revenue earn real money without fake activity or speculative token promotion?**

The answer is currently unknown. This repository keeps the score honest.
