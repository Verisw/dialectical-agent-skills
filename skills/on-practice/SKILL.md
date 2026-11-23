---
name: on-practice
description: Use when investigating unfamiliar situations, acquiring new domain knowledge, forming and testing hypotheses against reality, or when needing empirical grounding and actionable verification rather than speculative reasoning or blind action.
---

# on-practice: Empirical Inquiry & Verification Protocol

This skill provides a **two-tier epistemological architecture** for agents operating in any domain.

- **Tier 1 — Invariant Meta-Philosophy**: Domain-agnostic axiomatic principles of empirical reasoning.
- **Tier 2 — Domain Adapter Protocol**: A standardized 4-slot interface for instantiating the top-level philosophy into any specialized domain.

---

## Tier 1: Invariant Principles

| Axiom | Operational Rule |
|---|---|
| **Anti-Dogmatism** | No assertion without first-hand contact with objective reality. Refuse to reason from cached assumptions, training priors, or second-hand summaries alone. |
| **Anti-Blind-Action** | Unfocused iteration without abstraction is low-quality effort. Raw experience must be distilled into transferable causal models. |
| **Verification Primacy** | Internal confidence and elegant reasoning are not truth criteria. Only objective real-world feedback validates a claim. |

## The 4-Stage Empirical Loop

```
[Objective Reality / Unknown Domain]
         │
         ▼  Collect first-hand, unmediated evidence
[Stage 1: Sensory Grounding]
         │
         ▼  Filter noise → expose essentials → cross-link patterns → surface mechanism
[Stage 2: Cognitive Distillation  ← 1st Cognitive Leap: Percept → Concept]
         │
         ▼  Deploy the hypothesis; intervene actively in reality
[Stage 3: Active Reality Testing  ← 2nd Cognitive Leap (the critical step)]
         │
         ├─ [Confirmed] ──→ Relative truth established; scale the action
         │
         └─ [Diverged]  ──→ Objective feedback reveals a subjective blind spot
                                   │
                                   ▼
                      [Stage 4: Spiral Recalibration]
                                   │
                                   └─→ Revise mental model; begin next cycle at higher fidelity
```

> **Invariant rule:** A claim cannot be declared resolved without objective evidence from Stage 3. Logical soundness inside Stage 2 is a necessary but not sufficient condition for truth.

---

## Tier 2: Domain Adapter Protocol

When applying this skill to a specific domain, an agent MUST instantiate the following **4 Standard Adapter Slots**:

| Adapter Slot | Core Question | Specification |
|---|---|---|
| **Slot 1 — Sensory Source** | What counts as first-hand, unmediated fact in this domain? | Identify the raw-data channel; bypass secondary interpretations and aggregated reports. |
| **Slot 2 — Domain Distillation** | How do you filter noise, expose mechanisms, and cross-link evidence in this domain? | Name the domain-specific noise patterns, common false positives, lateral analogues, and causal depth indicators. |
| **Slot 3 — Practice Medium** | What is the reality-check arena, and what is the hard truth criterion? | Specify the deployment target and the objective, quantified success metric. |
| **Slot 4 — Calibration Signals** | What observable signals indicate that the agent's model has drifted from reality? | List the concrete failure signatures that must trigger a model update and re-entry into Stage 1. |

---

## Pre-built Domain Profiles

### Software & Systems Engineering

- **Slot 1 (Sensory Source):** Live runtime configuration, untruncated system logs, minimal reproduction scripts, production observability metrics — never assume version or dependency state.
- **Slot 2 (Distillation):** Strip irrelevant stack frames; eliminate transient cache artifacts and flapping signals; trace upstream config drift and recent change events; surface race conditions, resource leaks, and broken invariants.
- **Slot 3 (Practice Medium):** Compile + run; unit / integration / end-to-end test suite. **Truth criterion:** Exit code 0, all assertions green, target metrics stable.
- **Slot 4 (Calibration):** Test failures, memory spikes, deadlocks, flapping CI → signals that an environmental assumption or boundary condition is incorrect.

### Scientific Research

- **Slot 1 (Sensory Source):** Raw, unprocessed instrument readings; uncleaned datasets; primary-literature methods sections — not review summaries.
- **Slot 2 (Distillation):** Remove instrument baseline drift; identify spurious correlations and survivorship bias; build mechanistic models from first principles.
- **Slot 3 (Practice Medium):** Blinded controlled experiments; reproducibility stress tests; adversarial peer replication. **Truth criterion:** Strict reproducibility; predictions match new, independent measurements.
- **Slot 4 (Calibration):** Anomalous observations, vanishing statistical significance → signals that a foundational theoretical assumption is violated.

### Business Strategy

- **Slot 1 (Sensory Source):** Verbatim, unfiltered customer interview recordings; raw cash-flow statements and retention funnels; supplier/channel ground-level fieldwork.
- **Slot 2 (Distillation):** Filter PR-layer vanity metrics (e.g., gross registration counts); distinguish stated preference from revealed willingness-to-pay; map industry lifecycle stage and cross-category analogues.
- **Slot 3 (Practice Medium):** MVP pilots, controlled pricing experiments, closed commercial transactions. **Truth criterion:** Organic retention rate and positive net cash flow from real transactions.
- **Slot 4 (Calibration):** High CAC, low LTV, internal execution resistance → signals that the user-need or business-model hypothesis is subjectively biased.

### Organizational Governance

- **Slot 1 (Sensory Source):** Anonymous frontline employee feedback; actual end-to-end delivery cycle-time measurements; decision audit logs — not filtered middle-management reports.
- **Slot 2 (Distillation):** Separate emotional complaints from systemic process bottlenecks; identify gaps between the documented process and the shadow process that people actually follow.
- **Slot 3 (Practice Medium):** Pilot mechanism adjustments in an isolated team or unit. **Truth criterion:** Measurable improvement in end-to-end delivery velocity and frontline initiative rate.
- **Slot 4 (Calibration):** Blame-shifting, policy circumvention, key-talent attrition → signals of misaligned incentives or perverse institutional design.

---

## Adapting to a New Domain

Before engaging an unfamiliar domain, declare this adaptation profile in your reasoning:

```markdown
### Domain Adaptation Profile: [Domain Name]
1. Sensory Source: I will collect objective facts from [specific first-hand channel];
   I will not reason from second-hand summaries alone.
2. Domain Distillation: Key noise patterns to filter are [X];
   the bottom-layer causal mechanism I will seek is [Y].
3. Practice Medium: I will test my hypothesis against [specific deployment target];
   the hard truth criterion is [quantified objective metric].
4. Calibration Signals: If I observe [specific negative feedback pattern],
   I will immediately revise my model and re-enter Stage 1.
```
