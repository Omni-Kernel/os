# Dossier 04 — The Diplomat
> Mixed signals, partial authority · System reads intent through ambiguity

## Signal Profile
| Field | Value |
|---|---|
| Signal ID | SIG-19DC8D0C40B |
| Company | Stratos Financial Group |
| Deal Size | $1,500,000 |
| Action | ✅ ESCALATE |
| Kill Score | 15.0 / 100 |
| Entropy | 4.9 — STABLE |

## Input Signal
```
Company: Stratos Financial Group
Notes: Private equity fund considering enterprise license. Budget around
$1.5M pending partner approval. Managing Director confirmed interested.
Contract possible but competing vendor also evaluated. Expansion budget
allocated. Cash reserves confirmed. Timeline uncertain but urgent.
Budget: $1,500,000 | Urgency: MEDIUM | Authority: PARTIAL
```

## Kernel Output
```
CAPITAL_ACTION     : ESCALATE ($103,110)
REVENUE_PREDICTION : $423,880 (Range: $0 - $720,234)
KILL_SCORE         : 15 / 100
WASTE_AVOIDED      : $51,555
```

## X-AI Reasoning
| Factor | Weight | Value | Impact |
|---|---|---|---|
| Vector NLP Density | 0.25 | 12.9% — solid signal | POSITIVE |
| Kelly Edge | 0.20 | 10.3% — entropy tax 4.9 | POSITIVE |
| Thermodynamic Decay | 0.15 | 4.9 — STABLE | POSITIVE |
| Bayesian Posterior | 0.15 | α/β updated via priors | NEUTRAL |
| Thompson Sampling | 0.15 | p = 0.850 — ran hot | POSITIVE |
| Confidence Interval | 0.10 | 52.4% — above threshold | POSITIVE |

## Audit Trail
```
[2026-04-26T08:03:38Z] OMNI_KERNEL_V7
Monte Carlo: 5000 iterations
Expected: $423,880 | Volatility tax: 0.95
Thompson sampling ran hot — financial intent correctly identified
```

## Why This Matters
Mixed authority, uncertain timeline — yet cash, expansion and fund signals
drove a strong posterior. Thompson sampling ran hot at 85.0%, entropy near-floor.
System correctly identified underlying financial intent despite surface ambiguity.
This is the hardest class of deal for human reps — the system nailed it.
