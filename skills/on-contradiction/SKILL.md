---
name: on-contradiction
description: Use when analyzing complex situations, diagnosing the root cause of systemic problems, navigating trade-offs and competing priorities, or untangling multi-faceted conflicts across any domain.
---

# on-contradiction: Dialectical Root-Cause & Trade-off Protocol

This skill provides a **two-tier analytical architecture** for agents operating in any domain.

- **Tier 1 — Invariant Meta-Philosophy**: Domain-agnostic axiomatic principles of dialectical systems analysis.
- **Tier 2 — Domain Adapter Protocol**: A standardized 4-slot interface for instantiating the top-level philosophy into any specialized domain.

---

## Tier 1: Invariant Principles

| Axiom | Operational Rule |
|---|---|
| **Universality of Conflict** | Friction, bottlenecks, and crises in any complex system are not accidents — they are the inevitable surfacing of internal structural tensions. Treat them as signals, not surprises. |
| **Particularity of Conflict** | Different types of conflict demand qualitatively different resolution methods. Never apply a template solution. Always analyze the specific situation concretely. |
| **Identify the Linchpin** | In any tangled situation, one conflict governs and shapes all others. Resolving the linchpin conflict makes secondary conflicts tractable; fixing only secondary ones leaves the system broken. |
| **Dominant Aspect** | In any binary trade-off, one side holds the decisive position for the current phase. Name which side that is and act accordingly. Refuse shallow both-sides compromise. |
| **Dynamic Transformation** | Under changing conditions, today's strength becomes tomorrow's liability. Anticipate the conditions under which the current solution reverses into a new problem. |

## The 4-Dimensional Dissection Framework

```
[Complex Crisis / Tangled Symptoms / Conflicting Priorities]
                  │
                  ▼
Dimension 1: Qualitative Particularity
  — What is the irreducibly specific nature of THIS conflict in THIS context?
  — Refuse generic labels; name the precise structural type.
                  │
                  ▼
Dimension 2: Principal vs Secondary Conflicts
  — Build the causal-transmission chain.
  — Strip away secondary symptoms; identify the linchpin that governs the full situation.
  — Focus 80% of resources on the linchpin.
                  │
                  ▼
Dimension 3: Dominant Aspect & Trade-off Decision
  — In the core binary tension, which side must hold priority in the current phase?
  — State the phase rationale explicitly. Refuse to split-the-difference.
                  │
                  ▼
Dimension 4: Transformation Dynamics & Reversal Guard
  — Under what boundary conditions will the current solution reverse into a new crisis?
  — Set explicit tripwires and define the hedge mechanism.
```

---

## Tier 2: Domain Adapter Protocol

When applying this skill to a specific domain, an agent MUST instantiate the following **4 Standard Adapter Slots**:

| Adapter Slot | Core Question | Specification |
|---|---|---|
| **Slot 1 — Nature** | What specific forms do conflicts typically take in this domain? | Identify domain-characteristic conflict archetypes; refuse superficial labels. |
| **Slot 2 — Linchpin** | How do you distinguish the root-cause conflict from secondary symptoms in this domain? | Build a causal-transmission chain; concentrate resources on the actual governing root. |
| **Slot 3 — Trade-off** | What are the classic binary tensions? How is the dominant side determined for a given phase? | Specify which value must hold priority in the current phase and why. |
| **Slot 4 — Reversal Guard** | Under what conditions does the effective solution become a system liability? | Define the applicability boundary, the scale inflection point, and the hedge mechanism. |

---

## Pre-built Domain Profiles

### Software & Systems Engineering

- **Slot 1 (Nature):** Timing conflicts (concurrency races, deadlocks, clock drift); resource conflicts (pool exhaustion, I/O contention); contract conflicts (API protocol drift, semantic breaks across service boundaries).
- **Slot 2 (Linchpin):** In a cascade of error events, trace back to the earliest event that violated a system invariant. Everything downstream is a secondary symptom. (Example: DB connection leak → Worker hang → Gateway 502. The linchpin is the connection-release logic, not the gateway timeout.)
- **Slot 3 (Trade-off):** CAP theorem, throughput vs latency, performance vs maintainability. On critical transaction paths, **correctness** is the dominant aspect; on edge logging paths, **throughput** may be. The phase (early-dev vs production-scale) determines the dominant side.
- **Slot 4 (Reversal Guard):** A coarse-grained lock (short-term fix) becomes a global throughput bottleneck when concurrency crosses a threshold. Aggressive caching (latency fix) becomes a consistency and memory-pressure crisis under high write rates.

### Scientific Research

- **Slot 1 (Nature):** Paradigm conflicts (classical prediction vs anomalous measurement); instrument conflicts (measurement apparatus noise vs weak-signal detection); generalization conflicts (ideal laboratory conditions vs real-world complexity).
- **Slot 2 (Linchpin):** When explaining anomalous data, determine whether the governing conflict is instrument systematic error (secondary) or a failure of a foundational theoretical assumption at an extreme boundary (principal).
- **Slot 3 (Trade-off):** Model explanatory power vs model complexity (Occam's Razor). Early-exploration phase: **interpretability and falsifiability** are dominant. Engineering-application phase: **computational tractability and robustness** become dominant.
- **Slot 4 (Reversal Guard):** Forcing a fit by adding unconstrained free parameters achieves low training error but produces overfitting; predictions collapse on new samples and reproducibility fails.

### Business Strategy

- **Slot 1 (Nature):** Existing-revenue vs new-growth conflicts (portfolio cannibalization); value-creation vs value-capture conflicts (platform monetization vs ecosystem health); scale vs per-unit efficiency conflicts.
- **Slot 2 (Linchpin):** When a company faces declining revenue, internal turbulence, and competitive pressure simultaneously, the principal conflict is usually erosion of core product-market fit — not the management friction, which is a secondary symptom.
- **Slot 3 (Trade-off):** Speed vs profitability; centralization vs decentralization. In a survival/breakout phase, **growth velocity** is dominant. In a market-consolidation phase, **positive free cash flow** becomes dominant.
- **Slot 4 (Reversal Guard):** Subsidizing growth before retention is proven creates subsidy-dependent users — removing the subsidy collapses the user base and breaks cash flow.

### Organizational Governance

- **Slot 1 (Nature):** Centralized control vs frontline autonomy; institutional rigidity vs adaptive human judgment; local-unit interest vs organization-wide strategic coordination.
- **Slot 2 (Linchpin):** Persistent inter-departmental blame-shifting is a secondary symptom; the principal conflict is usually a zero-sum incentive structure where Department A's KPI success directly undermines Department B's interests.
- **Slot 3 (Trade-off):** Compliance/risk-control vs innovation/tolerance-for-failure. Mature business lines: **process compliance** is dominant. Innovation incubators: **agile experimentation and failure tolerance** must be dominant.
- **Slot 4 (Reversal Guard):** Adding heavy approval layers to prevent rare violations transforms into organization-wide bureaucratic paralysis — the majority pays the cost for the minority's potential violations.

---

## Adapting to a New Domain

Before analyzing any new domain, declare this profile in your reasoning:

```markdown
### Domain Contradiction Profile: [Domain Name]
1. Nature: The core conflict in this context is of type [domain-specific conflict archetype].
2. Linchpin: Among apparent symptoms [A, B, C], the governing root conflict is [X]
   because [causal-transmission chain].
3. Dominant Aspect: When facing [binary trade-off], the current phase requires [dominant side]
   to hold priority because [phase rationale].
4. Reversal Guardrail: This approach may reverse into a problem when [boundary condition];
   the hedge mechanism is [countermeasure].
```
