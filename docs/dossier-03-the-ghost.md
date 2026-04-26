# Dossier 03 — The Ghost
> Zero signal, maximum noise · Authority sovereignty kill

## Signal Profile
| Field | Value |
|---|---|
| Signal ID | SIG-19DC8D06B30 |
| Company | Unknown LLC |
| Deal Size | $0 |
| Action | ❌ KILL |
| Kill Score | 75.0 / 100 (hard floor) |
| Entropy | 24.7 — STABLE |

## Input Signal
```
Company: Unknown LLC
Notes: Maybe interested sometime. Testing free options first. Discount
preferred. No budget confirmed. Unsure about timeline. Exploring maybe
later. No decision maker available. Could be cheap alternative perhaps.
Budget: $0 | Urgency: NONE | Authority: NO
```

## Kernel Output
```
CAPITAL_ACTION     : KILL ($18,753)
REVENUE_PREDICTION : $373,891 (Range: $0 - $711,117)
KILL_SCORE         : 75 / 100
WASTE_AVOIDED      : $211,143
```

## X-AI Reasoning
| Factor | Weight | Value | Impact |
|---|---|---|---|
| Vector NLP Density | 0.25 | 3.4% — signal void | NEGATIVE |
| Kelly Edge | 0.20 | 1.9% — below threshold | NEGATIVE |
| Thermodynamic Decay | 0.15 | 24.7 — STABLE | POSITIVE |
| Bayesian Posterior | 0.15 | prior-dominated, no evidence | NEUTRAL |
| Thompson Sampling | 0.15 | p = 0.747 — prior only | NEUTRAL |
| Confidence Interval | 0.10 | 47.7% | NEGATIVE |

## Authority Kill Logic
```
hasAuthority = FALSE
→ kellyFraction *= 0.03 (sovereignty multiplier)
→ killScore = Math.max(killScore, 75) (hard floor)
→ Action: KILL — no appeal
```

## Audit Trail
```
[2026-04-26T08:03:15Z] OMNI_KERNEL_V7
Monte Carlo: 5000 iterations
authority_override: TRUE — kill score hard-clamped to 75
```

## Why This Matters
Win probability was 74.7% — but driven entirely by priors, not evidence.
The system correctly identified that a high prior-based probability
with zero actual signal is worthless. No authority = dead deal.
This dossier proves the system cannot be fooled by prior momentum alone.
