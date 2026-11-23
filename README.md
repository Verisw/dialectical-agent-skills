# dialectical-agent-skills

**Two universal cognitive-framework skills for AI agents, available in English and Chinese (中文).**

These skills encode two domain-agnostic reasoning protocols based on classical dialectical materialism, re-expressed in modern systems-thinking and cognitive-science terminology. They work for *any* domain: software engineering, scientific research, business strategy, organizational governance — or any analytical context where grounded reasoning and structured problem decomposition are needed.

---

## Skills

| Skill | Trigger Condition | Core Mechanism |
|---|---|---|
| [`on-practice`](skills/on-practice/) | Unfamiliar domain investigation, hypothesis formation, empirical grounding, actionable verification | 4-stage Empirical Inquiry Loop + Domain Adapter Protocol |
| [`on-contradiction`](skills/on-contradiction/) | Complex situation analysis, root-cause diagnosis, trade-off decisions, systemic conflict navigation | 4-Dimensional Dialectical Dissection Framework + Domain Adapter Protocol |

---

## Architecture: Two-Tier Design

Both skills share the same **two-tier structure**:

```
Tier 1: Invariant Meta-Philosophy  (domain-agnostic, never changes)
         ↓  Standard 4-slot Adapter Interface
Tier 2: Domain Adapter Layer       (plug-in profiles per specialized field)
```

**Tier 1** establishes the invariant philosophical axioms that apply universally.  
**Tier 2** provides a standardized 4-slot adapter interface so agents can instantiate the protocol for any new domain on-the-fly.

---

## Skill: `on-practice` — Empirical Inquiry & Verification Protocol

**Load when:** investigating unfamiliar situations, acquiring new domain knowledge, forming and testing hypotheses against reality, or when needing empirical grounding and actionable verification rather than speculative reasoning or blind action.

### Tier 1: Invariant Principles

| Axiom | Statement |
|---|---|
| Anti-Dogmatism | No assertion without first-hand contact with objective reality. Refuse to reason from cached assumptions alone. |
| Anti-Blind-Action | Unfocused iteration without abstraction is low-quality effort. Raw experience must be distilled into transferable models. |
| Verification Primacy | Internal confidence and elegant reasoning are not truth criteria. Only objective real-world feedback validates a claim. |

### The 4-Stage Empirical Loop

```
[Objective Reality / Unknown Domain]
         │
         ▼  Collect first-hand, unmediated evidence
[Stage 1: Sensory Grounding]
         │
         ▼  Distill: filter noise → expose essentials → cross-link → surface mechanism
[Stage 2: Cognitive Distillation  (1st Cognitive Leap)]
         │
         ▼  Deploy the hypothesis; intervene actively
[Stage 3: Active Reality Testing  (2nd Cognitive Leap — the critical step)]
         │
         ├─ [Confirmed] → Relative truth established; scale up
         │
         └─ [Divergence] → Objective feedback reveals a subjective blind spot
                                │
                                ▼
                   [Stage 4: Spiral Recalibration]
                                │
                                └─→ Update mental model; begin next cycle at higher fidelity
```

### Tier 2: Domain Adapter Protocol (4 Slots)

| Slot | Key Question | Specification |
|---|---|---|
| **Slot 1 — Sensory Source** | What counts as first-hand, unmediated fact in this domain? | Identify the raw data channel; bypass secondary interpretations. |
| **Slot 2 — Domain Distillation** | How do you filter noise, expose mechanisms, and cross-link in this domain? | Name the domain-specific noise patterns, common false positives, and causal depth indicators. |
| **Slot 3 — Practice Medium** | What is the reality-check arena and the hard truth criterion? | Specify the deployment target and the objective success metric. |
| **Slot 4 — Calibration Signals** | What observable signals indicate that your model has drifted from reality? | List the concrete failure signatures that must trigger a cognitive model update. |

### Pre-built Domain Profiles

<details>
<summary><strong>Software & Systems Engineering</strong></summary>

- **Slot 1:** Live runtime config, untruncated system logs, minimal reproduction scripts, production metrics
- **Slot 2:** Strip irrelevant stack frames; eliminate transient cache artifacts; trace upstream config drift; surface race conditions and resource leaks
- **Slot 3:** Compile + run; unit/integration/e2e test suite. **Truth criterion:** Exit code 0, all assertions green, metrics stable
- **Slot 4:** Test failures, memory spikes, deadlocks, flapping CI — signals that an environmental assumption is wrong

</details>

<details>
<summary><strong>Scientific Research</strong></summary>

- **Slot 1:** Raw, unprocessed instrument readings; uncleaned datasets; primary-literature methods sections
- **Slot 2:** Remove instrument baseline drift; identify spurious correlations and survivorship bias; model from first principles
- **Slot 3:** Blinded controlled experiments; reproducibility stress tests; adversarial peer replication. **Truth criterion:** Strict reproducibility, predictions match new measurements
- **Slot 4:** Anomalous observations, vanishing statistical significance — signals that a theoretical assumption has failed

</details>

<details>
<summary><strong>Business Strategy</strong></summary>

- **Slot 1:** Verbatim unfiltered customer interviews; actual cash-flow and retention funnels; supplier/channel ground truth
- **Slot 2:** Filter PR-layer vanity metrics; distinguish stated preference from revealed willingness-to-pay; compare industry lifecycle analogues
- **Slot 3:** MVP pilots, pricing experiments, closed commercial transactions. **Truth criterion:** Organic retention rate and positive net cash flow
- **Slot 4:** High CAC, low LTV, internal execution resistance — signals that the user-need hypothesis is subjectively biased

</details>

<details>
<summary><strong>Organizational Governance</strong></summary>

- **Slot 1:** Anonymous frontline feedback; actual end-to-end delivery cycle times; decision audit logs
- **Slot 2:** Separate emotional venting from systemic bottlenecks; identify gaps between documented process and actual shadow process
- **Slot 3:** Pilot mechanism adjustments in an isolated team. **Truth criterion:** End-to-end delivery velocity improvement, frontline initiative
- **Slot 4:** Blame-shifting, policy circumvention, key talent attrition — signals of mis-aligned incentives or perverse institutional design

</details>

### Adapting to a New Domain

When facing an unfamiliar domain, declare this profile before analysis:

```markdown
### Domain Adaptation Profile: [Domain Name]
1. Sensory Source: I will collect objective facts from [specific first-hand channel]; I will not reason from second-hand summaries.
2. Domain Distillation: Key noise patterns to filter are [X]; the bottom-layer causal mechanism I will seek is [Y].
3. Practice Medium: I will test my hypothesis against [specific deployment target]; the hard truth criterion is [quantified objective metric].
4. Calibration Signals: If I observe [specific negative feedback], I will immediately revise my mental model and restart the loop.
```

---

## Skill: `on-contradiction` — Dialectical Root-Cause & Trade-off Protocol

**Load when:** analyzing complex situations, diagnosing the root cause of systemic problems, navigating trade-offs and competing priorities, or untangling multi-faceted conflicts across any domain.

### Tier 1: Invariant Principles

| Axiom | Statement |
|---|---|
| Universality of Conflict | Friction, bottlenecks, and crises in any complex system are not accidents — they are the inevitable surfacing of internal structural tensions. |
| Particularity of Conflict | Different types of conflict demand different resolution methods. Never apply a template solution; always analyze the specific situation concretely. |
| Identify the Linchpin | In any tangled situation, one conflict governs and shapes all others. Resolving the linchpin conflict makes secondary conflicts tractable. |
| Dominant Aspect | In any binary trade-off, one side holds the decisive position for the current phase. Name which side that is and act accordingly. Refuse shallow compromise. |
| Dynamic Transformation | Under changing conditions, today's strength becomes tomorrow's liability. Anticipate the conditions under which the current solution reverses into a new problem. |

### The 4-Dimensional Dissection Framework

```
[Complex Crisis / Tangled Symptoms / Conflicting Priorities]
                  │
                  ▼
Dimension 1: Qualitative Particularity
  — What is the irreducibly specific nature of THIS conflict?
                  │
                  ▼
Dimension 2: Principal vs Secondary Conflicts
  — Strip away secondary symptoms; identify the linchpin that governs the full situation.
                  │
                  ▼
Dimension 3: Dominant Aspect & Trade-off Decision
  — In the core binary tension, which side must hold priority in the current phase?
                  │
                  ▼
Dimension 4: Transformation Dynamics & Reversal Guard
  — Under what boundary conditions will the current solution reverse into a new crisis?
```

### Tier 2: Domain Adapter Protocol (4 Slots)

| Slot | Key Question | Specification |
|---|---|---|
| **Slot 1 — Nature** | What specific forms do conflicts typically take in this domain? | Identify domain-characteristic conflict archetypes; refuse superficial labels. |
| **Slot 2 — Linchpin** | How do you distinguish the root-cause conflict from secondary symptoms in this domain? | Build a causal-transmission chain; concentrate resources on the actual root. |
| **Slot 3 — Trade-off** | What are the classic binary tensions in this domain? How is the dominant side determined? | Specify which value must hold priority in the current phase and why. |
| **Slot 4 — Reversal Guard** | Under what conditions does the effective solution become a system liability? | Define the applicability boundary, the scale inflection point, and the hedge mechanism. |

### Pre-built Domain Profiles

<details>
<summary><strong>Software & Systems Engineering</strong></summary>

- **Slot 1:** Timing conflicts (concurrency, deadlock, drift); resource conflicts (exhaustion, contention); contract conflicts (protocol drift, semantic breaks)
- **Slot 2:** In a cascade of failures, trace back to the earliest event that violated a system invariant. Everything downstream is a secondary symptom.
- **Slot 3:** CAP theorem, throughput vs latency, performance vs maintainability. On critical transaction paths, **correctness** is the dominant aspect; on edge logging paths, **throughput** may be.
- **Slot 4:** A coarse-grained lock (short-term fix) becomes a global throughput bottleneck once concurrency crosses a threshold. Aggressive caching becomes a consistency and memory-pressure crisis under high write rates.

</details>

<details>
<summary><strong>Scientific Research</strong></summary>

- **Slot 1:** Paradigm conflicts (classical prediction vs anomalous measurement); instrument conflicts (measurement noise vs signal detection); generalization conflicts (controlled lab vs real-world complexity)
- **Slot 2:** Determine whether anomalous data is explained by instrument systematic error (secondary) or by a failure of a foundational theoretical assumption (principal).
- **Slot 3:** Model explanatory power vs model complexity (Occam's Razor). Early exploration: **interpretability and falsifiability** are dominant. Engineering application phase: **computational tractability and robustness** are dominant.
- **Slot 4:** Forcing a fit by adding free parameters produces overfitting; predictions collapse on new samples.

</details>

<details>
<summary><strong>Business Strategy</strong></summary>

- **Slot 1:** Existing-revenue vs new-growth conflicts; value-creation vs value-capture conflicts; scale vs per-unit efficiency conflicts
- **Slot 2:** When a company faces declining revenue, internal turbulence, and competitive pressure simultaneously, the principal conflict is usually the erosion of core product-market fit — not the management friction, which is secondary.
- **Slot 3:** Speed vs profitability; centralization vs decentralization. In a survival/breakout phase, **growth velocity** is dominant. In a market-consolidation phase, **positive free cash flow** becomes dominant.
- **Slot 4:** Subsidizing growth before retention is proven leads to "subsidy-dependent users" — removing the subsidy collapses the user base and breaks cash flow.

</details>

<details>
<summary><strong>Organizational Governance</strong></summary>

- **Slot 1:** Centralized control vs frontline autonomy; institutional rigidity vs human adaptability; local unit interest vs organization-wide coordination
- **Slot 2:** Persistent inter-departmental blame-shifting is a secondary symptom; the principal conflict is usually a zero-sum incentive structure where Department A's KPI success directly undermines Department B's.
- **Slot 3:** Compliance/risk-control vs innovation/tolerance-for-failure. Mature business lines: **process compliance** is dominant. Innovation incubators: **agile experimentation** must be dominant.
- **Slot 4:** Adding heavy approval layers to prevent rare violations transforms into organization-wide bureaucratic paralysis, suppressing the majority for the mistakes of a minority.

</details>

### Adapting to a New Domain

Before analyzing any new domain, declare this profile:

```markdown
### Domain Contradiction Profile: [Domain Name]
1. Nature: The core conflict in this context is of type [domain-specific conflict archetype].
2. Linchpin: Among symptoms [A, B, C], the governing root conflict is [X] because [causal chain].
3. Dominant Aspect: When facing [binary trade-off], the current phase requires [dominant side] to hold priority because [phase rationale].
4. Reversal Guardrail: This approach may reverse into a problem when [boundary condition]; the hedge mechanism is [countermeasure].
```

---

## Compatibility

These skills follow the [Antigravity Agent Skill](https://antigravity.dev) `SKILL.md` format and are compatible with any agent platform that supports directory-based skill loading.

---

## License

MIT © 2026 Verisw
