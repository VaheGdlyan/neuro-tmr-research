# Path E — L8 Scoring Ledger

**Evaluation date:** 2026-08-21  
**Input population:** 120 L7-ready qualification units  
**Methodological authority:** `qualification/layer_logs/L8_comparative_evaluation.md`  
**Status:** L8 comparative scoring and final decisions completed

## Purpose

This ledger is the complete audit record for L8. It preserves the evaluation of **all 120 candidates**, including opportunities that are ultimately deferred or dropped.

> **The numerical scores are structured comparative judgments, not empirical probabilities of collaboration, funding, technical success, or response.**

The raw discovery universe and the frozen L7-qualified universe remain unchanged. This file records only the L8 comparison, ranking, dependency adjustment, and final decision.

## Evidence Basis

L8 was grounded in the frozen Path E discovery and qualification evidence:

- `Original 167-opportunity discovery universe.md`
- `qualification/opportunity_qualification_ledger.md`
- `qualification/funnel_results.md`
- `qualification/enrichment/F1–F8`
- `opportunities_database/l7_qualified_opportunities.md`
- the frozen `L8_comparative_evaluation.md` methodology

Targeted current-state web verification was used only where recency or unresolved technical/access conditions could materially change the comparison, especially for open datasets/tooling, EEG hardware/API access, funding eligibility/cycles, and 2025–2026 future-horizon research. Unknown willingness to collaborate, negotiate, host, or approve access was **not invented**.

## Scoring Rules Applied

- Every candidate receives one within-family 0–100 raw score and one global 0–100 raw score.
- Criterion ratings are integers from 0–5; weighted points follow `weight × rating / 5`.
- Family and global scores are never added.
- One discrete dependency penalty (`0, -2, -4, -6, -8, -10, -12`) is applied consistently to both score systems only for a distinct external blocker.
- Earlier L4/L5/L6 statuses are evidence/context, not automatic L8 bonuses.
- All 120 candidates were scored before `KEEP / RESERVE / DEFER / DROP` decisions were assigned.
- Ties follow: adjusted score → raw score → highest-weight criterion → evaluation confidence; genuine remaining ties share a rank.

## L8 Outcome Summary

- **KEEP:** 53
- **RESERVE:** 32
- **DEFER:** 21
- **DROP:** 14
- **Active post-L8 ranked universe (`KEEP + RESERVE`): 85**
- **Removed from current active ranked universe (`DEFER + DROP`): 35**

### Decisions by Family

| Family | KEEP | RESERVE | DEFER | DROP | Total |
|---|---:|---:|---:|---:|---:|
| F1 | 24 | 16 | 0 | 9 | 49 |
| F2 | 13 | 3 | 0 | 0 | 16 |
| F3 | 1 | 1 | 9 | 2 | 13 |
| F4 | 0 | 1 | 2 | 0 | 3 |
| F5 | 10 | 1 | 0 | 1 | 12 |
| F6 | 3 | 5 | 3 | 2 | 13 |
| F7 | 0 | 1 | 7 | 0 | 8 |
| F8 | 2 | 4 | 0 | 0 | 6 |

### Highest Global Priorities

| Global Rank | ID | Opportunity | Family | Adjusted Global | Decision |
|---:|---|---|---|---:|---|
| 1 | `OPP-078B` | Dreamento Open Sleep-EEG / Closed-Loop Research Toolbox | F2 | 99 | `KEEP` |
| 2 | `OPP-064` | National Sleep Research Resource (NSRR) | F2 | 98 | `KEEP` |
| 2 | `OPP-075` | Bitbrain Open Access Sleep (BOAS) | F2 | 98 | `KEEP` |
| 2 | `OPP-078A` | NEMAR Research Infrastructure | F2 | 98 | `KEEP` |
| 5 | `OPP-011` | Sleep and Memory Laboratory (Cecilia Forcato) | F1 | 96 | `KEEP` |
| 5 | `OPP-014` | Hong-Viet V. Ngo-Dehning — Sleep, Memory and Real-Time Stimulation | F1 | 96 | `KEEP` |
| 5 | `OPP-015` | Centre for Sleep and Cognition / Sleep and Cognition Laboratory (Michael Chee) | F1 | 96 | `KEEP` |
| 5 | `OPP-020` | SleepLoopFM / Sensory-Motor Systems Lab | F1 | 96 | `KEEP` |
| 5 | `OPP-046` | Neurology, Electrophysiology & Sleep Laboratory | F1 | 96 | `KEEP` |
| 5 | `OPP-067` | STAGES | F2 | 96 | `KEEP` |
| 5 | `OPP-123` | OpenBCI Cyton / Ganglion Open Hardware Ecosystem | F5 | 96 | `KEEP` |
| 5 | `OPP-124` | Bitbrain Ikon Sleep + SDK Ecosystem | F5 | 96 | `KEEP` |
| 5 | `OPP-129` | CGX Patch EEG + Sleep Technology / Partner Program | F5 | 96 | `KEEP` |
| 14 | `OPP-076` | Ear-EEG Sleep Monitoring 2017 (EESM17) | F2 | 95 | `KEEP` |
| 14 | `OPP-121` | Earable Neuroscience / FRENZ Research & B2B Partnership | F5 | 95 | `KEEP` |
| 16 | `OPP-026` | Surrey Sleep Research Centre | F1 | 94 | `KEEP` |
| 17 | `OPP-039` | Neurotechnology Laboratory, Engineering City | F1 | 93 | `KEEP` |
| 18 | `OPP-016` | Swartz Center for Computational Neuroscience (SCCN) | F1 | 93 | `KEEP` |
| 19 | `OPP-004` | Neuroscience and Psychology of Sleep Lab (NaPS) / CUBRIC Sleep Research | F1 | 92 | `KEEP` |
| 19 | `OPP-019` | Center for Ear-EEG / Neurotechnology Group | F1 | 92 | `KEEP` |
| 19 | `OPP-065` | Sleep Heart Health Study (SHHS) | F2 | 92 | `KEEP` |
| 19 | `OPP-126` | Brain Products + sync2brain Real-Time Closed-Loop EEG Stack | F5 | 92 | `KEEP` |
| 19 | `OPP-128` | ANT Neuro eego rt / eego Research Ecosystem | F5 | 92 | `KEEP` |
| 24 | `OPP-074` | PhysioNet / CinC 2018 Sleep Arousal Dataset | F2 | 91 | `KEEP` |
| 25 | `OPP-001` | Cognitive Neuroscience Laboratory (Ken Paller) | F1 | 90 | `KEEP` |

## Portfolio Interpretation

The scoring distribution concentrates current Neuro-TMR value in **direct sleep/TMR science, Path V datasets/tooling, deployable or reference-grade EEG systems, and a small set of high-leverage local/institutional mechanisms**. Networks are treated mainly as multipliers; governance mechanisms are mostly study-triggered; and future-horizon technologies are preserved without allowing them to displace the EEG-based V1 pathway.

`DEFER` is not equivalent to rejection. It preserves opportunities whose intrinsic value remains credible but whose current use is structurally gated by academic stage, institutional host, programme cycle, human-study trigger, or another major dependency.

### Portfolio-Preservation Exceptions

L8 did not impose a hard score cutoff. A small number of lower-scoring candidates were retained in `RESERVE` because they preserve a useful capability not fully captured by score alone (for example home-vs-lab domain shift, local clinical/institutional access, focused Armenian pilot funding, or low-cost reproducibility infrastructure). This follows the frozen rule that strategically useful portfolio coverage may justify retention below nearby numerical alternatives.

---

# F1 — Scientific Collaboration & Expertise

## OPP-011 — Sleep and Memory Laboratory (Cecilia Forcato)

**Organization:** Instituto Tecnológico de Buenos Aires (ITBA)  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** TMR plus automatic sleep-event detection and cue scheduling

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 5 | 20 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 94 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 94 / 100  
**Family Rank:** #1 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 96 / 100  
**Global Rank:** #5 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** This opportunity combines direct TMR science with automatic sleep-event detection and engineering collaboration, making it unusually well matched to both scientific validation and closed-loop implementation questions.

---

## OPP-014 — Hong-Viet V. Ngo-Dehning — Sleep, Memory and Real-Time Stimulation

**Organization:** University of Essex  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Real-time sleep-stimulation architecture, timing, and latency

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 5 | 20 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 94 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 94 / 100  
**Family Rank:** #1 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 96 / 100  
**Global Rank:** #5 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Real-time sleep stimulation, timing, and latency are central to the closed-loop control problem. The capability is highly distinctive; the main unresolved factor is collaboration willingness rather than scientific fit.

---

## OPP-015 — Centre for Sleep and Cognition / Sleep and Cognition Laboratory (Michael Chee)

**Organization:** National University of Singapore  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Real-time sleep staging, acoustic stimulation, and wearable translation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 5 | 20 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 94 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 94 / 100  
**Family Rank:** #1 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 96 / 100  
**Global Rank:** #5 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** The combination of real-time sleep-stage classification, acoustic stimulation, and wearable translation maps directly onto the proposed V1 control loop and its later deployment path.

---

## OPP-020 — SleepLoopFM / Sensory-Motor Systems Lab

**Organization:** ETH Zurich  
**Original Section:** 02  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Real-time sparse-EEG sleep decoding and closed-loop gating

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 5 | 20 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 94 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 94 / 100  
**Family Rank:** #1 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 96 / 100  
**Global Rank:** #5 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** SleepLoopFM is a close technical analogue to Neuro-TMR: sparse wearable EEG is decoded in real time to gate immediate interventions. It can materially inform sensor reduction, latency, and causal online validation.

---

## OPP-004 — Neuroscience and Psychology of Sleep Lab (NaPS) / CUBRIC Sleep Research

**Organization:** Cardiff University  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Sleep engineering, EEG replay detection, and closed-loop auditory stimulation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 5 | 20 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 94 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 94 / 100  
**Family Rank:** #1 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 92 / 100  
**Global Rank:** #19 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Sleep engineering, EEG replay detection, and closed-loop auditory stimulation. The adjusted global score (92) and F1 family position (#1) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-001 — Cognitive Neuroscience Laboratory (Ken Paller)

**Organization:** Northwestern University  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** TMR protocol, cue design, and behavioral-validation guidance

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 5 | 20 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 94 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 94 / 100  
**Family Rank:** #1 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 90 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 90 / 100  
**Global Rank:** #25 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** TMR protocol, cue design, and behavioral-validation guidance. The adjusted global score (90) and F1 family position (#1) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-002 — Memory and Sleep Group (Bernhard Staresina)

**Organization:** University of Oxford  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Sleep oscillation physiology and phase-aware closed-loop timing

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 5 | 20 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 92 / 100  
**Family Rank:** #7 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 90 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 90 / 100  
**Global Rank:** #25 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Sleep oscillation physiology and phase-aware closed-loop timing. The adjusted global score (90) and F1 family position (#7) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-007 — Institute of Medical Psychology and Behavioural Neurobiology / Sleep & Memory in Humans

**Organization:** University Hospital Tübingen  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Sleep-memory physiology and slow-oscillation closed-loop validation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 5 | 20 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 92 / 100  
**Family Rank:** #7 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 90 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 90 / 100  
**Global Rank:** #25 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Sleep-memory physiology and slow-oscillation closed-loop validation. The adjusted global score (90) and F1 family position (#7) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-039 — Neurotechnology Laboratory, Engineering City

**Organization:** Enterprise Incubator Foundation (EIF), Engineering City  
**Original Section:** 03  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Local EEG/neurotechnology support for Path V

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 4 | 20 |
| Ability to resolve a current scientific bottleneck | 20 | 5 | 20 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 92 / 100  
**Family Rank:** #9 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 93 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 93 / 100  
**Global Rank:** #17 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `KEEP`

**Rationale:** Local EEG/neurotechnology support for Path V. The adjusted global score (93) and F1 family position (#9) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-003 — Cognitive Neuroscience of Sleep Lab (CogNoS)

**Organization:** University of California, Irvine  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** TMR neural decoding and future reactivation-feedback design

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 90 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 90 / 100  
**Family Rank:** #10 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 88 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 88 / 100  
**Global Rank:** #29 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** High  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** TMR neural decoding and future reactivation-feedback design. The adjusted global score (88) and F1 family position (#10) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-046 — Neurology, Electrophysiology & Sleep Laboratory

**Organization:** Erebuni Medical Center  
**Original Section:** 03  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Local PSG/EEG validation infrastructure

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 4 | 20 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 89 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 89 / 100  
**Family Rank:** #11 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 96 / 100  
**Global Rank:** #5 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** This is the strongest identified local Armenian PSG/EEG/sleep infrastructure route. Its combination of local accessibility and clinical sleep capability gives it unusually high cross-project leverage for later validation.

---

## OPP-019 — Center for Ear-EEG / Neurotechnology Group

**Organization:** Aarhus University  
**Original Section:** 02  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Ear-EEG and sparse-channel sleep staging

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 4 | 20 |
| Ability to resolve a current scientific bottleneck | 20 | 5 | 20 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 89 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 89 / 100  
**Family Rank:** #11 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 92 / 100  
**Global Rank:** #19 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Ear-EEG and sparse-channel sleep staging. The adjusted global score (92) and F1 family position (#11) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-006 — DreamTeam — Sleep, Dreams, and Cognition

**Organization:** Paris Brain Institute / Sorbonne Université / INSERM  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Cue eligibility, sleep responsiveness, and stimulation safeguards

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 88 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 88 / 100  
**Family Rank:** #13 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 84 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 84 / 100  
**Global Rank:** #41 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** High  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Cue eligibility, sleep responsiveness, and stimulation safeguards. The adjusted global score (84) and F1 family position (#13) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-009 — Emmy Noether Memory Consolidation Group (Thomas Schreiner)

**Organization:** Ludwig Maximilian University of Munich  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Oscillatory event detection and sleep-memory physiology

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 5 | 20 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 86 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 86 / 100  
**Family Rank:** #14 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 86 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 86 / 100  
**Global Rank:** #34 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Oscillatory event detection and sleep-memory physiology. The adjusted global score (86) and F1 family position (#14) support active continuation.

---

## OPP-051 — Hrayr Attarian

**Organization:** Northwestern University Feinberg School of Medicine / Northwestern Medicine  
**Original Section:** 04  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Sleep medicine and PSG/EEG validation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 4 | 20 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 86 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 86 / 100  
**Family Rank:** #15 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 85 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 85 / 100  
**Global Rank:** #36 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Sleep medicine and PSG/EEG validation. The adjusted global score (85) and F1 family position (#15) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-016 — Swartz Center for Computational Neuroscience (SCCN)

**Organization:** University of California, San Diego  
**Original Section:** 02  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** EEG preprocessing, synchronization, artifact handling, and tooling

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 86 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 86 / 100  
**Family Rank:** #16 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 93 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 93 / 100  
**Global Rank:** #18 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** EEG preprocessing, synchronization, artifact handling, and tooling. The adjusted global score (93) and F1 family position (#16) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-005 — Cognitive Biopsychology and Methods / Sleep Laboratory (Björn Rasch)

**Organization:** University of Fribourg  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** TMR cueing and sleep-memory experimental design

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 85 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 85 / 100  
**Family Rank:** #17 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 82 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 82 / 100  
**Global Rank:** #47 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** TMR cueing and sleep-memory experimental design. The adjusted global score (82) and F1 family position (#17) support active continuation.

---

## OPP-026 — Surrey Sleep Research Centre

**Organization:** University of Surrey  
**Original Section:** 02  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Wearable-versus-PSG sleep validation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 4 | 20 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 85 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 85 / 100  
**Family Rank:** #18 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 94 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 94 / 100  
**Global Rank:** #16 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Wearable-versus-PSG sleep validation. The adjusted global score (94) and F1 family position (#18) support active continuation.

---

## OPP-008 — York Sleep / Memory Reactivation Research (Scott Cairney and collaborators)

**Organization:** University of York  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** TMR protocol design, EEG reactivation markers, and emotional-memory validation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 82 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 82 / 100  
**Family Rank:** #19 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 81 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 81 / 100  
**Global Rank:** #49 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `KEEP`

**Rationale:** TMR protocol design, EEG reactivation markers, and emotional-memory validation. The adjusted global score (81) and F1 family position (#19) support active continuation.

---

## OPP-025 — In-Ear Physiological Sensing / Danilo Mandic Research

**Organization:** Imperial College London  
**Original Section:** 02  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** In-ear EEG plus multimodal physiological sensing

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 4 | 20 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 82 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 82 / 100  
**Family Rank:** #20 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 81 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 81 / 100  
**Global Rank:** #50 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** In-ear EEG plus multimodal physiological sensing. The adjusted global score (81) and F1 family position (#20) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-029 — Mobile EEG / Neuropsychology Ecosystem (Stefan Debener)

**Organization:** University of Oldenburg  
**Original Section:** 02  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Mobile/around-ear EEG and real-world acquisition

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 4 | 20 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 82 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 82 / 100  
**Family Rank:** #20 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 81 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 81 / 100  
**Global Rank:** #50 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Mobile/around-ear EEG and real-world acquisition. The adjusted global score (81) and F1 family position (#20) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-010 — Social & Cognitive Neuroscience Laboratory (Xiaoqing Hu)

**Organization:** The University of Hong Kong  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Translational scope for enhancement, updating, and memory outcomes

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 5 | 25 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 80 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 80 / 100  
**Family Rank:** #22 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 70 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 70 / 100  
**Global Rank:** #84 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Translational scope for enhancement, updating, and memory outcomes. The opportunity remains useful, but its adjusted global score (70) and comparative family position (#22) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-013 — Sleep Neuroscience & Cognition Laboratory (Michael Scullin)

**Organization:** Baylor University  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Real-world learning outcomes and translational TMR task design

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 4 | 20 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 78 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 78 / 100  
**Family Rank:** #23 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 76 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 76 / 100  
**Global Rank:** #60 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Real-world learning outcomes and translational TMR task design. The opportunity remains useful, but its adjusted global score (76) and comparative family position (#23) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-021 — Stanford Sleep Medicine Computational & Sensing Ecosystem

**Organization:** Stanford University School of Medicine  
**Original Section:** 02  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Clinical/computational sleep validation and PSG benchmarking

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 4 | 20 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 2 | 6 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 77 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 77 / 100  
**Family Rank:** #24 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 78 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 78 / 100  
**Global Rank:** #56 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Clinical/computational sleep validation and PSG benchmarking. The opportunity remains useful, but its adjusted global score (78) and comparative family position (#24) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-018 — Translational Neural Engineering Laboratory

**Organization:** École Polytechnique Fédérale de Lausanne (EPFL)  
**Original Section:** 02  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Closed-loop neural-interface architecture and feedback design

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 77 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 77 / 100  
**Family Rank:** #25 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 72 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 72 / 100  
**Global Rank:** #72 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Closed-loop neural-interface architecture and feedback design. The opportunity remains useful, but its adjusted global score (72) and comparative family position (#25) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-050 — Paul Nuyujukian / Brain Interfacing Laboratory

**Organization:** Stanford University  
**Original Section:** 04  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Neuroengineering, neural decoding, and closed-loop systems

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 5 | 15 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 2 | 6 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 77 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 77 / 100  
**Family Rank:** #25 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 72 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 72 / 100  
**Global Rank:** #72 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Neuroengineering, neural decoding, and closed-loop systems. The opportunity remains useful, but its adjusted global score (72) and comparative family position (#25) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-012 — Schapiro Lab — Sleep, Learning and Memory

**Organization:** University of Pennsylvania  
**Original Section:** 01  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Computational memory modelling linked to empirical TMR

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 4 | 20 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 76 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 76 / 100  
**Family Rank:** #27 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 76 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 76 / 100  
**Global Rank:** #60 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Computational memory modelling linked to empirical TMR. The opportunity remains useful, but its adjusted global score (76) and comparative family position (#27) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-028 — Wisconsin Institute for Sleep and Consciousness

**Organization:** University of Wisconsin–Madison  
**Original Section:** 02  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Sleep neurophysiology and causal sleep modulation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 4 | 20 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 2 | 6 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 75 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 75 / 100  
**Family Rank:** #28 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 66 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 66 / 100  
**Global Rank:** #94 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DROP`

**Rationale:** The institute offers excellent sleep neurophysiology, but the identified contribution is broader than TMR and current access is less direct than several stronger sleep-memory and closed-loop groups. It is comparatively dominated within F1.

---

## OPP-047 — Neurology & Epileptology / EEG ecosystem

**Organization:** Arabkir Medical Center  
**Original Section:** 03  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Clinical EEG and neurophysiology expertise

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 75 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 75 / 100  
**Family Rank:** #29 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 85 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 85 / 100  
**Global Rank:** #36 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Clinical EEG and neurophysiology expertise. The adjusted global score (85) and F1 family position (#29) support active continuation.

---

## OPP-017 — Chair of Neurotechnology / Berlin BCI

**Organization:** Technische Universität Berlin  
**Original Section:** 02  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Online EEG decoding, calibration, and uncertainty handling

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 3 | 9 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 74 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 74 / 100  
**Family Rank:** #30 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 72 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 72 / 100  
**Global Rank:** #72 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Online EEG decoding, calibration, and uncertainty handling. The opportunity remains useful, but its adjusted global score (72) and comparative family position (#30) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-030 — BrainLinks-BrainTools

**Organization:** University of Freiburg  
**Original Section:** 02  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** General closed-loop neurotechnology architecture and neural-signal control

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 4 | 16 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 5 | 15 |
| Realistic collaboration / access pathway | 15 | 2 | 6 |
| Translational / engineering alignment | 10 | 5 | 10 |

**Family Raw Score:** 74 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 74 / 100  
**Family Rank:** #30 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 66 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 66 / 100  
**Global Rank:** #94 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DROP`

**Rationale:** The closed-loop neurotechnology capability is credible, but its broad system-level value overlaps with more directly usable EEG/software/hardware routes in the surviving portfolio.

---

## OPP-038 — Neuro-Psycholinguistics Laboratory

**Organization:** H. Acharyan Institute of Language, NAS RA  
**Original Section:** 03  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Language-memory task design with EEG-linked experimentation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 74 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 74 / 100  
**Family Rank:** #32 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 86 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 86 / 100  
**Global Rank:** #35 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `KEEP`

**Rationale:** Language-memory task design with EEG-linked experimentation. The adjusted global score (86) and F1 family position (#32) support active continuation.

---

## OPP-034 — L. A. Orbeli Institute of Physiology

**Organization:** National Academy of Sciences of the Republic of Armenia (NAS RA)  
**Original Section:** 03  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Neurophysiology and learning/memory scientific input

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 72 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 72 / 100  
**Family Rank:** #33 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 76 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 76 / 100  
**Global Rank:** #62 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Neurophysiology and learning/memory scientific input. The opportunity remains useful, but its adjusted global score (76) and comparative family position (#33) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-031 — COBRAIN Scientific-Educational Center for Fundamental Brain Research

**Organization:** Yerevan State Medical University (YSMU)  
**Original Section:** 03  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Local Armenian neuroscience institutional bridge

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 3 | 9 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 71 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 71 / 100  
**Family Rank:** #34 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 85 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 85 / 100  
**Global Rank:** #40 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `KEEP`

**Rationale:** Local Armenian neuroscience institutional bridge. The adjusted global score (85) and F1 family position (#34) support active continuation.

---

## OPP-058 — Rami Apelian

**Organization:** California clinical neurology / Armenian-American medical ecosystem  
**Original Section:** 04  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Clinical EEG/neurophysiology and neuromodulation perspective

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 69 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 69 / 100  
**Family Rank:** #35 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 71 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 71 / 100  
**Global Rank:** #77 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Clinical EEG/neurophysiology and neuromodulation perspective. The opportunity remains useful, but its adjusted global score (71) and comparative family position (#35) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-059 — Armen J. Cherik

**Organization:** California neurology / sleep-medicine ecosystem  
**Original Section:** 04  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Sleep medicine and neurodiagnostic consultation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 69 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 69 / 100  
**Family Rank:** #35 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 71 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 71 / 100  
**Global Rank:** #77 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Sleep medicine and neurodiagnostic consultation. The opportunity remains useful, but its adjusted global score (71) and comparative family position (#35) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-037 — Psychology Research Center

**Organization:** Yerevan State University (YSU)  
**Original Section:** 03  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Behavioral and cognitive validation design

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 3 | 9 |
| Experimental or validation capability | 15 | 3 | 9 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 66 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 66 / 100  
**Family Rank:** #37 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 71 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 71 / 100  
**Global Rank:** #77 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Behavioral and cognitive validation design. The opportunity remains useful, but its adjusted global score (71) and comparative family position (#37) place it behind stronger current mechanisms. Functional substitution by stronger surviving candidates is a material reason to keep it in reserve.

---

## OPP-052 — Lorig Panossian

**Organization:** Northern California sleep-medicine / Armenian healthcare ecosystem  
**Original Section:** 04  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Sleep-medicine consultation plus diaspora bridge

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 3 | 9 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 66 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 66 / 100  
**Family Rank:** #37 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 71 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 71 / 100  
**Global Rank:** #77 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Sleep-medicine consultation plus diaspora bridge. The opportunity remains useful, but its adjusted global score (71) and comparative family position (#37) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-053 — Talin Babikian

**Organization:** UCLA Semel Institute / UCLA Health  
**Original Section:** 04  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Cognitive and neuropsychological endpoint design

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 3 | 9 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 66 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 66 / 100  
**Family Rank:** #37 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 71 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 71 / 100  
**Global Rank:** #77 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Cognitive and neuropsychological endpoint design. The opportunity remains useful, but its adjusted global score (71) and comparative family position (#37) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-033 — Department of Neurology & Clinical Research Network

**Organization:** Yerevan State Medical University (YSMU)  
**Original Section:** 03  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Clinical neurology and neurophysiology linkage

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 3 | 9 |
| Experimental or validation capability | 15 | 4 | 12 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 66 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 66 / 100  
**Family Rank:** #37 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 69 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 69 / 100  
**Global Rank:** #89 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Clinical neurology and neurophysiology linkage. The opportunity remains useful, but its adjusted global score (69) and comparative family position (#37) place it behind stronger current mechanisms. Functional substitution by stronger surviving candidates is a material reason to keep it in reserve.

---

## OPP-040 — Coding and Signal Processing Department

**Organization:** Institute for Informatics and Automation Problems (IIAP), NAS RA  
**Original Section:** 03  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Signal-processing and algorithmic support

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 2 | 10 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 3 | 9 |
| Experimental or validation capability | 15 | 3 | 9 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 63 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 63 / 100  
**Family Rank:** #41 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 71 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 71 / 100  
**Global Rank:** #77 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Signal-processing and algorithmic support. The opportunity remains useful, but its adjusted global score (71) and comparative family position (#41) place it behind stronger current mechanisms. Functional substitution by stronger surviving candidates is a material reason to keep it in reserve.

---

## OPP-032 — Scientific Research Center, Neuroscience Laboratory

**Organization:** Scientific Research Center, Yerevan State Medical University (YSMU)  
**Original Section:** 03  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Local neuroscience laboratory collaboration

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 3 | 15 |
| Ability to resolve a current scientific bottleneck | 20 | 2 | 8 |
| Distinctive expertise / non-substitutability | 15 | 3 | 9 |
| Experimental or validation capability | 15 | 3 | 9 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 62 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 62 / 100  
**Family Rank:** #42 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 70 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 70 / 100  
**Global Rank:** #86 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Local neuroscience laboratory collaboration. The opportunity remains useful, but its adjusted global score (70) and comparative family position (#42) place it behind stronger current mechanisms. Functional substitution by stronger surviving candidates is a material reason to keep it in reserve.

---

## OPP-041 — Telecommunications / Signal Processing Laboratories

**Organization:** Russian-Armenian University (RAU)  
**Original Section:** 03  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** EEG-related signal analysis and engineering support

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 2 | 10 |
| Ability to resolve a current scientific bottleneck | 20 | 3 | 12 |
| Distinctive expertise / non-substitutability | 15 | 2 | 6 |
| Experimental or validation capability | 15 | 3 | 9 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 60 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 60 / 100  
**Family Rank:** #43 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 2 | 4 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 62 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 62 / 100  
**Global Rank:** #98 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DROP`

**Rationale:** Local signal-processing capability is useful but substantially overlaps with stronger computational and neurotechnology candidates, with no equally distinctive sleep/EEG mechanism.

---

## OPP-042 — Bioengineering / Biomedical Engineering Ecosystem

**Organization:** Russian-Armenian University (RAU)  
**Original Section:** 03  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future biomedical-engineering co-creation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 2 | 10 |
| Ability to resolve a current scientific bottleneck | 20 | 2 | 8 |
| Distinctive expertise / non-substitutability | 15 | 2 | 6 |
| Experimental or validation capability | 15 | 3 | 9 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 56 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 56 / 100  
**Family Rank:** #44 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 2 | 4 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 57 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 57 / 100  
**Global Rank:** #106 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DROP`

**Rationale:** The local bioengineering ecosystem is accessible but too broad to resolve a current Neuro-TMR bottleneck relative to more specific EEG, neurotechnology, and instrumentation candidates.

---

## OPP-045 — Biomedical Engineering / Electronics & Measurement Systems ecosystem

**Organization:** National Polytechnic University of Armenia (NPUA)  
**Original Section:** 03  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future instrumentation and biomedical-device engineering

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 2 | 10 |
| Ability to resolve a current scientific bottleneck | 20 | 2 | 8 |
| Distinctive expertise / non-substitutability | 15 | 2 | 6 |
| Experimental or validation capability | 15 | 3 | 9 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 56 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 56 / 100  
**Family Rank:** #44 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 2 | 4 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 57 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 57 / 100  
**Global Rank:** #106 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DROP`

**Rationale:** The engineering ecosystem could help future instrumentation, but its current contribution is broad and highly substitutable compared with stronger local neurotechnology and EEG routes.

---

## OPP-044 — Levon Hovhannisyan / wearable physiological systems capability

**Organization:** American University of Armenia (AUA)  
**Original Section:** 03  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future wearable/peripheral physiological sensing

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 2 | 10 |
| Ability to resolve a current scientific bottleneck | 20 | 2 | 8 |
| Distinctive expertise / non-substitutability | 15 | 3 | 9 |
| Experimental or validation capability | 15 | 3 | 9 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 4 | 8 |

**Family Raw Score:** 56 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 56 / 100  
**Family Rank:** #44 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 56 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 56 / 100  
**Global Rank:** #108 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DROP`

**Rationale:** Wearable physiological-sensing expertise is useful for later hybrid sensing, but it is peripheral to the EEG-based V1 and is covered by stronger hardware/industry options.

---

## OPP-060 — Maral Aghvinian Vartanian / Meedk Scientific Bridge

**Organization:** Meedk / Armenian brain-health research ecosystem  
**Original Section:** 04  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Armenian brain-health mentorship and network bridge

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 2 | 10 |
| Ability to resolve a current scientific bottleneck | 20 | 2 | 8 |
| Distinctive expertise / non-substitutability | 15 | 3 | 9 |
| Experimental or validation capability | 15 | 2 | 6 |
| Realistic collaboration / access pathway | 15 | 5 | 15 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 54 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 54 / 100  
**Family Rank:** #47 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 62 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 62 / 100  
**Global Rank:** #98 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DROP`

**Rationale:** The Armenian brain-health bridge is useful, but the same network function is represented more directly by OPP-144 Meedk as a multiplier opportunity. Keeping both would add little marginal value.

---

## OPP-043 — Mariam Avagyan / sleep-EEG signal-analysis capability

**Organization:** American University of Armenia (AUA)  
**Original Section:** 03  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Signal processing and machine learning with historical sleep-EEG experience

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 2 | 10 |
| Ability to resolve a current scientific bottleneck | 20 | 2 | 8 |
| Distinctive expertise / non-substitutability | 15 | 3 | 9 |
| Experimental or validation capability | 15 | 2 | 6 |
| Realistic collaboration / access pathway | 15 | 4 | 12 |
| Translational / engineering alignment | 10 | 3 | 6 |

**Family Raw Score:** 51 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 51 / 100  
**Family Rank:** #48 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 56 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 56 / 100  
**Global Rank:** #108 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DROP`

**Rationale:** Historical sleep-EEG experience is real, but current activity is centered on signal processing/deep learning rather than an active sleep-EEG programme. More direct local and global EEG partners dominate the present use case.

---

## OPP-049 — Ardem Patapoutian

**Organization:** Scripps Research  
**Original Section:** 04  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** High-level neuroscience introductions and mentorship

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Neuro-TMR / sleep-memory scientific fit | 25 | 1 | 5 |
| Ability to resolve a current scientific bottleneck | 20 | 1 | 4 |
| Distinctive expertise / non-substitutability | 15 | 4 | 12 |
| Experimental or validation capability | 15 | 2 | 6 |
| Realistic collaboration / access pathway | 15 | 2 | 6 |
| Translational / engineering alignment | 10 | 2 | 4 |

**Family Raw Score:** 37 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 37 / 100  
**Family Rank:** #49 / 49

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 1 | 5 |
| Critical bottleneck resolution | 20 | 1 | 4 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 44 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 44 / 100  
**Global Rank:** #118 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DROP`

**Rationale:** Scientific stature and network reach are exceptional, but the identified Neuro-TMR contribution remains generic mentorship/introduction value. L8 therefore does not allow prestige to substitute for a concrete bottleneck contribution.

---


# F2 — Data / Research Infrastructure & Path V Resources

## OPP-075 — Bitbrain Open Access Sleep (BOAS)

**Organization:** Bitbrain / NEMAR ecosystem  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Wearable EEG versus PSG validation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 5 | 25 |
| Data / ground-truth quality | 20 | 5 | 20 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 5 | 15 |
| Reproducibility / documentation / tooling | 10 | 5 | 10 |
| Scale and generalizability | 10 | 4 | 8 |
| Distinctiveness versus alternatives | 5 | 5 | 5 |

**Family Raw Score:** 98 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 98 / 100  
**Family Rank:** #1 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 98 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 98 / 100  
**Global Rank:** #2 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Simultaneous PSG and wearable EEG with expert-consensus labels directly tests the central reduced-sensor assumption behind an EEG-based deployable V1. The 2026 BOAS release is open (CC0), current, and unusually well aligned with Path V.

**Targeted current-state verification:**
- https://nemar.org/dataset/on005555

---

## OPP-064 — National Sleep Research Resource (NSRR)

**Organization:** NHLBI-supported sleep-data infrastructure  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Large-scale PSG repository and dataset gateway

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 5 | 25 |
| Data / ground-truth quality | 20 | 5 | 20 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 4 | 12 |
| Reproducibility / documentation / tooling | 10 | 5 | 10 |
| Scale and generalizability | 10 | 5 | 10 |
| Distinctiveness versus alternatives | 5 | 5 | 5 |

**Family Raw Score:** 97 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 97 / 100  
**Family Rank:** #2 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 98 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 98 / 100  
**Global Rank:** #2 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Critical  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** NSRR provides a broad gateway to large PSG cohorts rather than a single benchmark, giving Path V scale and cross-cohort generalization capacity. It is highly valuable, though individual datasets still need study-specific selection and access compliance.

---

## OPP-078A — NEMAR Research Infrastructure

**Organization:** NEMAR  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** EEG data-discovery and computational research infrastructure

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 5 | 25 |
| Data / ground-truth quality | 20 | 4 | 16 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 5 | 15 |
| Reproducibility / documentation / tooling | 10 | 5 | 10 |
| Scale and generalizability | 10 | 5 | 10 |
| Distinctiveness versus alternatives | 5 | 5 | 5 |

**Family Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 96 / 100  
**Family Rank:** #3 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 98 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 98 / 100  
**Global Rank:** #2 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** NEMAR provides open neural-data discovery plus computational pathways and now hosts directly relevant wearable-sleep datasets. It is immediately usable and compounds the value of several other F2 resources.

**Targeted current-state verification:**
- https://nemar.org/

---

## OPP-065 — Sleep Heart Health Study (SHHS)

**Organization:** National Sleep Research Resource  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Large-scale PSG sleep-staging generalization

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 5 | 25 |
| Data / ground-truth quality | 20 | 5 | 20 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 4 | 12 |
| Reproducibility / documentation / tooling | 10 | 5 | 10 |
| Scale and generalizability | 10 | 5 | 10 |
| Distinctiveness versus alternatives | 5 | 4 | 4 |

**Family Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 96 / 100  
**Family Rank:** #3 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 92 / 100  
**Global Rank:** #19 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Critical  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Large-scale PSG sleep-staging generalization. The adjusted global score (92) and F2 family position (#3) support active continuation.

---

## OPP-078B — Dreamento Open Sleep-EEG / Closed-Loop Research Toolbox

**Organization:** Dreamento  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Open real-time sleep-EEG, event-detection, and stimulation tooling

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 5 | 25 |
| Data / ground-truth quality | 20 | 4 | 16 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 5 | 15 |
| Reproducibility / documentation / tooling | 10 | 5 | 10 |
| Scale and generalizability | 10 | 3 | 6 |
| Distinctiveness versus alternatives | 5 | 5 | 5 |

**Family Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 92 / 100  
**Family Rank:** #5 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 99 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 99 / 100  
**Global Rank:** #1 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Open-source real-time sleep EEG monitoring, staging, event detection, and sensory stimulation directly reduce Path V implementation burden. Its public tooling and immediate usability make it the strongest current infrastructure bridge from offline validation toward a closed-loop prototype.

**Targeted current-state verification:**
- https://github.com/dreamento/dreamento

---

## OPP-067 — STAGES

**Organization:** Multi-center sleep research consortium / NSRR  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Multi-site sleep-model generalization

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 4 | 20 |
| Data / ground-truth quality | 20 | 5 | 20 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 4 | 12 |
| Reproducibility / documentation / tooling | 10 | 5 | 10 |
| Scale and generalizability | 10 | 5 | 10 |
| Distinctiveness versus alternatives | 5 | 5 | 5 |

**Family Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 92 / 100  
**Family Rank:** #6 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 96 / 100  
**Global Rank:** #5 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Multi-site sleep-model generalization. The adjusted global score (96) and F2 family position (#6) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-070 — HMC Sleep Staging Database

**Organization:** Haaglanden Medisch Centrum / PhysioNet  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Clinical external sleep-stage validation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 4 | 20 |
| Data / ground-truth quality | 20 | 5 | 20 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 5 | 15 |
| Reproducibility / documentation / tooling | 10 | 5 | 10 |
| Scale and generalizability | 10 | 3 | 6 |
| Distinctiveness versus alternatives | 5 | 4 | 4 |

**Family Raw Score:** 90 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 90 / 100  
**Family Rank:** #7 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 85 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 85 / 100  
**Global Rank:** #36 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Clinical external sleep-stage validation. The adjusted global score (85) and F2 family position (#7) support active continuation.

---

## OPP-066 — MESA Sleep

**Organization:** National Sleep Research Resource  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Home PSG and actigraphy multimodal comparison

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 4 | 20 |
| Data / ground-truth quality | 20 | 5 | 20 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 4 | 12 |
| Reproducibility / documentation / tooling | 10 | 5 | 10 |
| Scale and generalizability | 10 | 4 | 8 |
| Distinctiveness versus alternatives | 5 | 4 | 4 |

**Family Raw Score:** 89 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 89 / 100  
**Family Rank:** #8 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 83 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 83 / 100  
**Global Rank:** #44 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Home PSG and actigraphy multimodal comparison. The adjusted global score (83) and F2 family position (#8) support active continuation.

---

## OPP-069 — Sleep-EDF Expanded

**Organization:** PhysioNet  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Baseline reproducible sleep-stage classification

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 5 | 25 |
| Data / ground-truth quality | 20 | 4 | 16 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 5 | 15 |
| Reproducibility / documentation / tooling | 10 | 5 | 10 |
| Scale and generalizability | 10 | 2 | 4 |
| Distinctiveness versus alternatives | 5 | 3 | 3 |

**Family Raw Score:** 88 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 88 / 100  
**Family Rank:** #9 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 88 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 88 / 100  
**Global Rank:** #29 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Baseline reproducible sleep-stage classification. The adjusted global score (88) and F2 family position (#9) support active continuation. Although alternatives exist, the present access/impact profile still justifies retention.

---

## OPP-074 — PhysioNet / CinC 2018 Sleep Arousal Dataset

**Organization:** PhysioNet  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Arousal and sleep-disturbance detection

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 4 | 20 |
| Data / ground-truth quality | 20 | 5 | 20 |
| Technical compatibility with Neuro-TMR | 15 | 4 | 12 |
| Access and licensing usability | 15 | 5 | 15 |
| Reproducibility / documentation / tooling | 10 | 4 | 8 |
| Scale and generalizability | 10 | 4 | 8 |
| Distinctiveness versus alternatives | 5 | 5 | 5 |

**Family Raw Score:** 88 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 88 / 100  
**Family Rank:** #10 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 91 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 91 / 100  
**Global Rank:** #24 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Arousal and sleep-disturbance detection. The adjusted global score (91) and F2 family position (#10) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-077 — Dreem Open Datasets (DOD-H / DOD-O)

**Organization:** Dreem research ecosystem  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Scorer disagreement and sleep-stage label uncertainty

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 4 | 20 |
| Data / ground-truth quality | 20 | 5 | 20 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 4 | 12 |
| Reproducibility / documentation / tooling | 10 | 5 | 10 |
| Scale and generalizability | 10 | 3 | 6 |
| Distinctiveness versus alternatives | 5 | 5 | 5 |

**Family Raw Score:** 88 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 88 / 100  
**Family Rank:** #10 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 83 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 83 / 100  
**Global Rank:** #44 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Scorer disagreement and sleep-stage label uncertainty. The adjusted global score (83) and F2 family position (#10) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-076 — Ear-EEG Sleep Monitoring 2017 (EESM17)

**Organization:** OpenNeuro / ear-EEG research ecosystem  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Ear-EEG sensor-reduction experiments

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 5 | 25 |
| Data / ground-truth quality | 20 | 4 | 16 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 5 | 15 |
| Reproducibility / documentation / tooling | 10 | 4 | 8 |
| Scale and generalizability | 10 | 1 | 2 |
| Distinctiveness versus alternatives | 5 | 5 | 5 |

**Family Raw Score:** 86 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 86 / 100  
**Family Rank:** #12 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 95 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 95 / 100  
**Global Rank:** #14 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `KEEP`

**Rationale:** Ear-EEG sensor-reduction experiments. The adjusted global score (95) and F2 family position (#12) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-072 — ISRUC-Sleep

**Organization:** University of Coimbra research ecosystem  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Population and night-to-night variability validation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 4 | 20 |
| Data / ground-truth quality | 20 | 4 | 16 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 5 | 15 |
| Reproducibility / documentation / tooling | 10 | 4 | 8 |
| Scale and generalizability | 10 | 3 | 6 |
| Distinctiveness versus alternatives | 5 | 4 | 4 |

**Family Raw Score:** 84 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 84 / 100  
**Family Rank:** #13 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 84 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 84 / 100  
**Global Rank:** #42 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `KEEP`

**Rationale:** Population and night-to-night variability validation. The adjusted global score (84) and F2 family position (#13) support active continuation.

---

## OPP-073 — Montreal Archive of Sleep Studies (MASS)

**Organization:** Montreal research sleep ecosystem  
**Original Section:** 05  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Cross-dataset generalization and reproducibility

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 4 | 20 |
| Data / ground-truth quality | 20 | 4 | 16 |
| Technical compatibility with Neuro-TMR | 15 | 5 | 15 |
| Access and licensing usability | 15 | 4 | 12 |
| Reproducibility / documentation / tooling | 10 | 4 | 8 |
| Scale and generalizability | 10 | 3 | 6 |
| Distinctiveness versus alternatives | 5 | 3 | 3 |

**Family Raw Score:** 80 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 80 / 100  
**Family Rank:** #14 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 70 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 70 / 100  
**Global Rank:** #84 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Cross-dataset generalization and reproducibility. The opportunity remains useful, but its adjusted global score (70) and comparative family position (#14) place it behind stronger current mechanisms. Functional substitution by stronger surviving candidates is a material reason to keep it in reserve.

---

## OPP-071 — CAP Sleep Database

**Organization:** PhysioNet  
**Original Section:** 05  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** NREM microstructure and sleep-stability analysis

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 3 | 15 |
| Data / ground-truth quality | 20 | 4 | 16 |
| Technical compatibility with Neuro-TMR | 15 | 4 | 12 |
| Access and licensing usability | 15 | 5 | 15 |
| Reproducibility / documentation / tooling | 10 | 4 | 8 |
| Scale and generalizability | 10 | 2 | 4 |
| Distinctiveness versus alternatives | 5 | 5 | 5 |

**Family Raw Score:** 75 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 75 / 100  
**Family Rank:** #15 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 73 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 73 / 100  
**Global Rank:** #71 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** NREM microstructure and sleep-stability analysis. The opportunity remains useful, but its adjusted global score (73) and comparative family position (#15) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-068 — HomePAP

**Organization:** National Sleep Research Resource  
**Original Section:** 05  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Home-versus-laboratory domain-shift validation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Direct Path V utility | 25 | 3 | 15 |
| Data / ground-truth quality | 20 | 4 | 16 |
| Technical compatibility with Neuro-TMR | 15 | 4 | 12 |
| Access and licensing usability | 15 | 4 | 12 |
| Reproducibility / documentation / tooling | 10 | 4 | 8 |
| Scale and generalizability | 10 | 3 | 6 |
| Distinctiveness versus alternatives | 5 | 4 | 4 |

**Family Raw Score:** 73 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 73 / 100  
**Family Rank:** #16 / 16

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 67 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 67 / 100  
**Global Rank:** #93 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Home-versus-laboratory domain-shift validation. The opportunity remains useful, but its adjusted global score (67) and comparative family position (#16) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---


# F3 — Funding & Institutional Support

## OPP-104 — Artificial Intelligence Virtual Institute / HPC State Support

**Organization:** Ministry of High-Tech Industry of the Republic of Armenia  
**Original Section:** 07  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Compute infrastructure for Path V and ML experiments

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 4 | 20 |
| Strategic fit with current or next project phase | 20 | 4 | 16 |
| Usable funding magnitude / scope | 15 | 3 | 9 |
| Structural attainability | 15 | 4 | 12 |
| Time-to-funding | 10 | 4 | 8 |
| Institutional / credibility leverage | 10 | 4 | 8 |
| Administrative-effort efficiency | 5 | 4 | 4 |

**Family Raw Score:** 77 / 100  
**Dependency Penalty:** -4  
**Family Adjusted Score:** 73 / 100  
**Family Rank:** #1 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 91 / 100  
**Dependency Penalty:** -4  
**Global Adjusted Score:** 87 / 100  
**Global Rank:** #31 / 120

### Dependency Adjustment

**Penalty:** -4  
**Reason:** Compute access remains subject to project eligibility and programme allocation rules, although the technical resource itself is directly relevant.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Compute support can immediately reduce Path V infrastructure burden and is locally relevant. It scores below core data/hardware opportunities because access allocation is still programme-dependent, but the cost-to-value profile justifies active retention.

---

## OPP-079 — Horizon Europe — Cluster 1: Health

**Organization:** European Commission  
**Original Section:** 06  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** International collaborative health-research funding

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 4 | 20 |
| Strategic fit with current or next project phase | 20 | 4 | 16 |
| Usable funding magnitude / scope | 15 | 5 | 15 |
| Structural attainability | 15 | 2 | 6 |
| Time-to-funding | 10 | 3 | 6 |
| Institutional / credibility leverage | 10 | 5 | 10 |
| Administrative-effort efficiency | 5 | 2 | 2 |

**Family Raw Score:** 75 / 100  
**Dependency Penalty:** -6  
**Family Adjusted Score:** 69 / 100  
**Family Rank:** #2 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 73 / 100  
**Dependency Penalty:** -6  
**Global Adjusted Score:** 67 / 100  
**Global Rank:** #92 / 120

### Dependency Adjustment

**Penalty:** -6  
**Reason:** Requires an eligible institutional/legal-entity structure and normally a collaborative Horizon consortium; value is therefore externally gated beyond ordinary application effort.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DEFER`

**Rationale:** International collaborative health-research funding. The underlying raw global value (73) is not treated as lost, but current activation is gated: Requires an eligible institutional/legal-entity structure and normally a collaborative Horizon consortium; value is therefore externally gated beyond ordinary application effort. The opportunity should be reassessed when that trigger changes.

**Targeted current-state verification:**
- https://research-and-innovation.ec.europa.eu/strategy/strategy-research-and-innovation/europe-world/international-cooperation/association-horizon-europe/armenia_en

---

## OPP-095 — Remote Laboratories 2026

**Organization:** Higher Education and Science Committee / Republic of Armenia  
**Original Section:** 07  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Armenia laboratory building with international scientific leadership

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 3 | 15 |
| Strategic fit with current or next project phase | 20 | 5 | 20 |
| Usable funding magnitude / scope | 15 | 4 | 12 |
| Structural attainability | 15 | 3 | 9 |
| Time-to-funding | 10 | 3 | 6 |
| Institutional / credibility leverage | 10 | 5 | 10 |
| Administrative-effort efficiency | 5 | 3 | 3 |

**Family Raw Score:** 75 / 100  
**Dependency Penalty:** -8  
**Family Adjusted Score:** 67 / 100  
**Family Rank:** #3 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 82 / 100  
**Dependency Penalty:** -8  
**Global Adjusted Score:** 74 / 100  
**Global Rank:** #67 / 120

### Dependency Adjustment

**Penalty:** -8  
**Reason:** Requires an Armenian institutional host, an appropriate international scientific leader/team configuration, and an open programme cycle.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DEFER`

**Rationale:** Armenia laboratory building with international scientific leadership. The underlying raw global value (82) is not treated as lost, but current activation is gated: Requires an Armenian institutional host, an appropriate international scientific leader/team configuration, and an open programme cycle. The opportunity should be reassessed when that trigger changes.

---

## OPP-096 — Integration of Foreign Scientists into the Scientific Community of Armenia

**Organization:** Higher Education and Science Committee / Republic of Armenia  
**Original Section:** 07  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Integration of international scientists into Armenia-based research

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 3 | 15 |
| Strategic fit with current or next project phase | 20 | 5 | 20 |
| Usable funding magnitude / scope | 15 | 4 | 12 |
| Structural attainability | 15 | 3 | 9 |
| Time-to-funding | 10 | 3 | 6 |
| Institutional / credibility leverage | 10 | 5 | 10 |
| Administrative-effort efficiency | 5 | 3 | 3 |

**Family Raw Score:** 75 / 100  
**Dependency Penalty:** -8  
**Family Adjusted Score:** 67 / 100  
**Family Rank:** #3 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 82 / 100  
**Dependency Penalty:** -8  
**Global Adjusted Score:** 74 / 100  
**Global Rank:** #67 / 120

### Dependency Adjustment

**Penalty:** -8  
**Reason:** Requires an Armenian host structure, a qualified foreign scientist, and a suitable programme cycle.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DEFER`

**Rationale:** Integration of international scientists into Armenia-based research. The underlying raw global value (82) is not treated as lost, but current activation is gated: Requires an Armenian host structure, a qualified foreign scientist, and a suitable programme cycle. The opportunity should be reassessed when that trigger changes.

---

## OPP-101 — ADVANCE Research Grants

**Organization:** FAST Foundation / Higher Education and Science Committee ecosystem  
**Original Section:** 07  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** International PI-led Armenia research-team formation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 3 | 15 |
| Strategic fit with current or next project phase | 20 | 5 | 20 |
| Usable funding magnitude / scope | 15 | 4 | 12 |
| Structural attainability | 15 | 3 | 9 |
| Time-to-funding | 10 | 3 | 6 |
| Institutional / credibility leverage | 10 | 5 | 10 |
| Administrative-effort efficiency | 5 | 3 | 3 |

**Family Raw Score:** 75 / 100  
**Dependency Penalty:** -8  
**Family Adjusted Score:** 67 / 100  
**Family Rank:** #3 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 82 / 100  
**Dependency Penalty:** -8  
**Global Adjusted Score:** 74 / 100  
**Global Rank:** #67 / 120

### Dependency Adjustment

**Penalty:** -8  
**Reason:** Requires an Armenia-based research-group/institution structure, international PI alignment, and a suitable funding cycle.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DEFER`

**Rationale:** International PI-led Armenia research-team formation. The underlying raw global value (82) is not treated as lost, but current activation is gated: Requires an Armenia-based research-group/institution structure, international PI alignment, and a suitable funding cycle. The opportunity should be reassessed when that trigger changes.

---

## OPP-080 — European Partnership for Brain Health (EP BrainHealth)

**Organization:** European brain-health research partnership  
**Original Section:** 06  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Brain-health and neuroscience research funding

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 3 | 15 |
| Strategic fit with current or next project phase | 20 | 5 | 20 |
| Usable funding magnitude / scope | 15 | 5 | 15 |
| Structural attainability | 15 | 2 | 6 |
| Time-to-funding | 10 | 2 | 4 |
| Institutional / credibility leverage | 10 | 5 | 10 |
| Administrative-effort efficiency | 5 | 2 | 2 |

**Family Raw Score:** 72 / 100  
**Dependency Penalty:** -8  
**Family Adjusted Score:** 64 / 100  
**Family Rank:** #6 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 1 | 1 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 77 / 100  
**Dependency Penalty:** -8  
**Global Adjusted Score:** 69 / 100  
**Global Rank:** #87 / 120

### Dependency Adjustment

**Penalty:** -8  
**Reason:** Requires eligible transnational institutional participation and a suitable future call; the current activation path is consortium/cycle dependent.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DEFER`

**Rationale:** Brain-health and neuroscience research funding. The underlying raw global value (77) is not treated as lost, but current activation is gated: Requires eligible transnational institutional participation and a suitable future call; the current activation path is consortium/cycle dependent. The opportunity should be reassessed when that trigger changes.

---

## OPP-102 — ANSEF Yervant Terzian Research Grants

**Organization:** Armenian National Science & Education Fund (ANSEF)  
**Original Section:** 07  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Focused pilot-research funding

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 3 | 15 |
| Strategic fit with current or next project phase | 20 | 4 | 16 |
| Usable funding magnitude / scope | 15 | 2 | 6 |
| Structural attainability | 15 | 4 | 12 |
| Time-to-funding | 10 | 4 | 8 |
| Institutional / credibility leverage | 10 | 3 | 6 |
| Administrative-effort efficiency | 5 | 4 | 4 |

**Family Raw Score:** 67 / 100  
**Dependency Penalty:** -4  
**Family Adjusted Score:** 63 / 100  
**Family Rank:** #7 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 65 / 100  
**Dependency Penalty:** -4  
**Global Adjusted Score:** 61 / 100  
**Global Rank:** #100 / 120

### Dependency Adjustment

**Penalty:** -4  
**Reason:** Applicant/institution requirements and programme timing create a meaningful but tractable external dependency.

### Interpretation

**Substitutability:** High  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Focused pilot-research funding. The opportunity remains useful, but its adjusted global score (61) and comparative family position (#7) place it behind stronger current mechanisms. Functional substitution by stronger surviving candidates is a material reason to keep it in reserve.

---

## OPP-107 — “100 Ideas for Armenia” 2026

**Organization:** Republic of Armenia educational/scientific innovation ecosystem  
**Original Section:** 07  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Modest youth-innovation funding, recognition, and visibility

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 4 | 20 |
| Strategic fit with current or next project phase | 20 | 3 | 12 |
| Usable funding magnitude / scope | 15 | 1 | 3 |
| Structural attainability | 15 | 4 | 12 |
| Time-to-funding | 10 | 3 | 6 |
| Institutional / credibility leverage | 10 | 3 | 6 |
| Administrative-effort efficiency | 5 | 4 | 4 |

**Family Raw Score:** 63 / 100  
**Dependency Penalty:** -2  
**Family Adjusted Score:** 61 / 100  
**Family Rank:** #8 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 2 | 4 |
| Non-substitutability / unique value | 10 | 2 | 4 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 51 / 100  
**Dependency Penalty:** -2  
**Global Adjusted Score:** 49 / 100  
**Global Rank:** #114 / 120

### Dependency Adjustment

**Penalty:** -2  
**Reason:** Value depends on the competition cycle and proposal eligibility; this is a minor timing gate rather than a deep structural barrier.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DROP`

**Rationale:** The competition can provide modest recognition/funding, but its expected scientific leverage is low compared with more substantive Armenian research-support mechanisms.

---

## OPP-093 — NIH BRAIN Initiative Funding Ecosystem

**Organization:** U.S. National Institutes of Health  
**Original Section:** 06  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** U.S. neurotechnology/human-neuroscience funding collaboration

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 2 | 10 |
| Strategic fit with current or next project phase | 20 | 5 | 20 |
| Usable funding magnitude / scope | 15 | 5 | 15 |
| Structural attainability | 15 | 2 | 6 |
| Time-to-funding | 10 | 2 | 4 |
| Institutional / credibility leverage | 10 | 5 | 10 |
| Administrative-effort efficiency | 5 | 2 | 2 |

**Family Raw Score:** 67 / 100  
**Dependency Penalty:** -8  
**Family Adjusted Score:** 59 / 100  
**Family Rank:** #9 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 79 / 100  
**Dependency Penalty:** -8  
**Global Adjusted Score:** 71 / 100  
**Global Rank:** #75 / 120

### Dependency Adjustment

**Penalty:** -8  
**Reason:** Practical access depends on a qualifying institutional applicant/collaborator and the rules of a specific NIH BRAIN funding announcement.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DEFER`

**Rationale:** U.S. neurotechnology/human-neuroscience funding collaboration. The underlying raw global value (79) is not treated as lost, but current activation is gated: Practical access depends on a qualifying institutional applicant/collaborator and the rules of a specific NIH BRAIN funding announcement. The opportunity should be reassessed when that trigger changes.

---

## OPP-100 — State Scientific Equipment Re-Equipment Programme

**Organization:** Republic of Armenia scientific funding system  
**Original Section:** 07  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** EEG/PSG and laboratory-equipment infrastructure

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 2 | 10 |
| Strategic fit with current or next project phase | 20 | 4 | 16 |
| Usable funding magnitude / scope | 15 | 5 | 15 |
| Structural attainability | 15 | 2 | 6 |
| Time-to-funding | 10 | 2 | 4 |
| Institutional / credibility leverage | 10 | 5 | 10 |
| Administrative-effort efficiency | 5 | 2 | 2 |

**Family Raw Score:** 63 / 100  
**Dependency Penalty:** -8  
**Family Adjusted Score:** 55 / 100  
**Family Rank:** #10 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 78 / 100  
**Dependency Penalty:** -8  
**Global Adjusted Score:** 70 / 100  
**Global Rank:** #83 / 120

### Dependency Adjustment

**Penalty:** -8  
**Reason:** Equipment support operates through an eligible Armenian university/scientific organization and depends on programme timing.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DEFER`

**Rationale:** EEG/PSG and laboratory-equipment infrastructure. The underlying raw global value (78) is not treated as lost, but current activation is gated: Equipment support operates through an eligible Armenian university/scientific organization and depends on programme timing. The opportunity should be reassessed when that trigger changes.

---

## OPP-094 — Young Scientific Groups Formation & Research Promotion 2026

**Organization:** Higher Education and Science Committee / Republic of Armenia  
**Original Section:** 07  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Future young-team pilot research funding

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 2 | 10 |
| Strategic fit with current or next project phase | 20 | 3 | 12 |
| Usable funding magnitude / scope | 15 | 2 | 6 |
| Structural attainability | 15 | 3 | 9 |
| Time-to-funding | 10 | 3 | 6 |
| Institutional / credibility leverage | 10 | 3 | 6 |
| Administrative-effort efficiency | 5 | 3 | 3 |

**Family Raw Score:** 52 / 100  
**Dependency Penalty:** -6  
**Family Adjusted Score:** 46 / 100  
**Family Rank:** #11 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 59 / 100  
**Dependency Penalty:** -6  
**Global Adjusted Score:** 53 / 100  
**Global Rank:** #112 / 120

### Dependency Adjustment

**Penalty:** -6  
**Reason:** Activation depends on programme-cycle timing plus eligible team/institution configuration rather than a direct independent application path.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DEFER`

**Rationale:** Future young-team pilot research funding. The underlying raw global value (59) is not treated as lost, but current activation is gated: Activation depends on programme-cycle timing plus eligible team/institution configuration rather than a direct independent application path. The opportunity should be reassessed when that trigger changes.

---

## OPP-088 — Human Frontier Science Program Research Grants

**Organization:** Human Frontier Science Program  
**Original Section:** 06  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** International interdisciplinary life-science collaboration funding

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 1 | 5 |
| Strategic fit with current or next project phase | 20 | 3 | 12 |
| Usable funding magnitude / scope | 15 | 4 | 12 |
| Structural attainability | 15 | 1 | 3 |
| Time-to-funding | 10 | 1 | 2 |
| Institutional / credibility leverage | 10 | 5 | 10 |
| Administrative-effort efficiency | 5 | 1 | 1 |

**Family Raw Score:** 45 / 100  
**Dependency Penalty:** -12  
**Family Adjusted Score:** 33 / 100  
**Family Rank:** #12 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 1 | 3 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 1 | 1 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 51 / 100  
**Dependency Penalty:** -12  
**Global Adjusted Score:** 39 / 100  
**Global Rank:** #119 / 120

### Dependency Adjustment

**Penalty:** -12  
**Reason:** HFSP Research Grants require independent group leaders and a Principal Applicant with a laboratory in an HFSP member country; the 2027 LOI initiation/submission deadlines have already passed.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DEFER`

**Rationale:** HFSP is scientifically prestigious and potentially powerful, but the current route is structurally misaligned: Research Grants require independent group leaders and the 2027 LOI window has passed. Future value is preserved through DEFER rather than inflated by prestige.

**Targeted current-state verification:**
- https://www.hfsp.org/funding/hfsp-funding/research-grants
- https://www.hfsp.org/funding/hfsp-funding/hfsp-member-countries

---

## OPP-099 — Research Support Program for PhD Students & Young Applicants

**Organization:** Armenian national science-support ecosystem  
**Original Section:** 07  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future doctoral/young-researcher support

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / accessibility | 25 | 1 | 5 |
| Strategic fit with current or next project phase | 20 | 2 | 8 |
| Usable funding magnitude / scope | 15 | 2 | 6 |
| Structural attainability | 15 | 2 | 6 |
| Time-to-funding | 10 | 1 | 2 |
| Institutional / credibility leverage | 10 | 2 | 4 |
| Administrative-effort efficiency | 5 | 3 | 3 |

**Family Raw Score:** 34 / 100  
**Dependency Penalty:** -12  
**Family Adjusted Score:** 22 / 100  
**Family Rank:** #13 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 1 | 5 |
| Critical bottleneck resolution | 20 | 1 | 4 |
| Realistic actionability / access | 15 | 1 | 3 |
| Expected impact if successful | 10 | 2 | 4 |
| Non-substitutability / unique value | 10 | 2 | 4 |
| Cross-project leverage | 10 | 2 | 4 |
| Time-to-value | 5 | 1 | 1 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 29 / 100  
**Dependency Penalty:** -12  
**Global Adjusted Score:** 17 / 100  
**Global Rank:** #120 / 120

### Dependency Adjustment

**Penalty:** -12  
**Reason:** Dominant constraint is future doctoral/young-researcher academic-stage eligibility and institutional positioning.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DROP`

**Rationale:** The mechanism is strongly future-stage dependent and offers less distinct project leverage than the stronger Armenian and international research-support pathways retained or deferred.

---


# F4 — Fellowships / Placements / Training

## OPP-116 — CAJAL Neurobiology of Sleep

**Organization:** CAJAL Advanced Neuroscience Training  
**Original Section:** 08  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Specialized sleep-EEG, auditory-stimulation, and memory-method training

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / current-stage fit | 25 | 3 | 15 |
| Neuro-TMR-relevant research or training value | 20 | 5 | 20 |
| Mentorship / laboratory quality | 20 | 5 | 20 |
| Hands-on research and output potential | 15 | 5 | 15 |
| Network / credibility leverage | 10 | 5 | 10 |
| Timing and practical feasibility | 10 | 5 | 10 |

**Family Raw Score:** 90 / 100  
**Dependency Penalty:** -4  
**Family Adjusted Score:** 86 / 100  
**Family Rank:** #1 / 3

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 80 / 100  
**Dependency Penalty:** -4  
**Global Adjusted Score:** 76 / 100  
**Global Rank:** #59 / 120

### Dependency Adjustment

**Penalty:** -4  
**Reason:** Participation depends on competitive admission plus financing/stipend availability; the current official 2026 course page is open through 27 August and no explicit degree-level exclusion was verified.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** CAJAL Neurobiology of Sleep is the strongest F4 opportunity by topic fit: its 2026 programme directly covers human high-density EEG, sleep monitoring, auditory stimulation, learning/memory tasks, data analysis, and computational modelling. The current course window is open, but admission and financing remain external gates. It is therefore retained as `RESERVE`: exceptionally strong within F4, yet less direct to the project's present bottlenecks than a dataset, collaborator, or EEG platform.

**Targeted current-state verification:**
- https://cajal-training.org/on-site/neurobiology_sleep/
- https://cajal-training.org/

---

## OPP-120 — Armenia Professional Training Programme

**Organization:** Armenian national science-support ecosystem  
**Original Section:** 08  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Funded international laboratory placement and method transfer

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / current-stage fit | 25 | 2 | 10 |
| Neuro-TMR-relevant research or training value | 20 | 4 | 16 |
| Mentorship / laboratory quality | 20 | 4 | 16 |
| Hands-on research and output potential | 15 | 5 | 15 |
| Network / credibility leverage | 10 | 4 | 8 |
| Timing and practical feasibility | 10 | 3 | 6 |

**Family Raw Score:** 71 / 100  
**Dependency Penalty:** -6  
**Family Adjusted Score:** 65 / 100  
**Family Rank:** #2 / 3

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 75 / 100  
**Dependency Penalty:** -6  
**Global Adjusted Score:** 69 / 100  
**Global Rank:** #88 / 120

### Dependency Adjustment

**Penalty:** -6  
**Reason:** Requires institutional affiliation/nomination and programme-specific placement conditions before the training route can activate.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DEFER`

**Rationale:** Funded international laboratory placement and method transfer. The underlying raw global value (75) is not treated as lost, but current activation is gated: Requires institutional affiliation/nomination and programme-specific placement conditions before the training route can activate. The opportunity should be reassessed when that trigger changes.

---

## OPP-115 — FENS / IBRO-PERC Exchange Fellowships Programme

**Organization:** Federation of European Neuroscience Societies / IBRO-PERC  
**Original Section:** 08  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Method-transfer placement in an external neuroscience laboratory

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Eligibility / current-stage fit | 25 | 1 | 5 |
| Neuro-TMR-relevant research or training value | 20 | 4 | 16 |
| Mentorship / laboratory quality | 20 | 4 | 16 |
| Hands-on research and output potential | 15 | 5 | 15 |
| Network / credibility leverage | 10 | 4 | 8 |
| Timing and practical feasibility | 10 | 1 | 2 |

**Family Raw Score:** 62 / 100  
**Dependency Penalty:** -10  
**Family Adjusted Score:** 52 / 100  
**Family Rank:** #3 / 3

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 1 | 3 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 1 | 1 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 59 / 100  
**Dependency Penalty:** -10  
**Global Adjusted Score:** 49 / 100  
**Global Rank:** #113 / 120

### Dependency Adjustment

**Penalty:** -10  
**Reason:** The exchange mechanism is tied to graduate/early-career neuroscience status, host-lab arrangements, and annual call timing.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DEFER`

**Rationale:** Method-transfer placement in an external neuroscience laboratory. The underlying raw global value (59) is not treated as lost, but current activation is gated: The exchange mechanism is tied to graduate/early-career neuroscience status, host-lab arrangements, and annual call timing. The opportunity should be reassessed when that trigger changes.

---


# F5 — Hardware / Industry / Technology Access

## OPP-124 — Bitbrain Ikon Sleep + SDK Ecosystem

**Organization:** Bitbrain  
**Original Section:** 09  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Sleep-specific wearable EEG and SDK integration

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 5 | 25 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 5 | 20 |
| Signal quality / research validity | 15 | 4 | 12 |
| Closed-loop latency and control compatibility | 15 | 4 | 12 |
| Access / procurement / partnership feasibility | 10 | 4 | 8 |
| Wearability / deployment suitability | 10 | 5 | 10 |
| Strategic partnership potential | 5 | 4 | 4 |

**Family Raw Score:** 91 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 91 / 100  
**Family Rank:** #1 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 96 / 100  
**Global Rank:** #5 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Bitbrain Ikon Sleep is purpose-built for sleep, supports real-time SDK/LSL integration and raw data, and has direct relevance to wearable EEG deployment. This makes it stronger than generic EEG hardware for V1-oriented experiments.

**Targeted current-state verification:**
- https://downloads.bitbrain.com/products/hardware/ikon-sleep
- https://cdn.bitbrain.com/docs/2024/Ikon-Sleep-Brochure-121124.pdf

---

## OPP-121 — Earable Neuroscience / FRENZ Research & B2B Partnership

**Organization:** Earable Neuroscience  
**Original Section:** 09  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Real-time wearable sleep EEG, API access, and closed-loop audio

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 5 | 25 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 4 | 16 |
| Signal quality / research validity | 15 | 4 | 12 |
| Closed-loop latency and control compatibility | 15 | 5 | 15 |
| Access / procurement / partnership feasibility | 10 | 4 | 8 |
| Wearability / deployment suitability | 10 | 5 | 10 |
| Strategic partnership potential | 5 | 5 | 5 |

**Family Raw Score:** 91 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 91 / 100  
**Family Rank:** #2 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 95 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 95 / 100  
**Global Rank:** #14 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `KEEP`

**Rationale:** FRENZ combines real-time EEG/EMG/EOG, API access, sleep staging, audio intervention, and an explicit research/B2B partnership route. Vendor dependence remains, but the end-to-end architecture is unusually close to Neuro-TMR.

**Targeted current-state verification:**
- https://frenzband.com/pages/earable-neuroscience-research-partnership-services
- https://frenzband.com/pages/business

---

## OPP-128 — ANT Neuro eego rt / eego Research Ecosystem

**Organization:** ANT Neuro  
**Original Section:** 09  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Reference-grade real-time EEG validation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 5 | 25 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 5 | 20 |
| Signal quality / research validity | 15 | 5 | 15 |
| Closed-loop latency and control compatibility | 15 | 5 | 15 |
| Access / procurement / partnership feasibility | 10 | 3 | 6 |
| Wearability / deployment suitability | 10 | 2 | 4 |
| Strategic partnership potential | 5 | 3 | 3 |

**Family Raw Score:** 88 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 88 / 100  
**Family Rank:** #3 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 92 / 100  
**Global Rank:** #19 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** ANT Neuro eego rt offers high-quality real-time EEG, SDK/BrainFlow integration, and flexible channel configurations. It is excellent for reference-grade validation but less aligned with lightweight home deployment.

**Targeted current-state verification:**
- https://www.ant-neuro.com/products/eego-rt
- https://academy.ant-neuro.com/blog/application-notes-2/streaming-eeg-data-into-the-brainflow-platform-using-the-eegotm-sdk-71

---

## OPP-126 — Brain Products + sync2brain Real-Time Closed-Loop EEG Stack

**Organization:** Brain Products / sync2brain  
**Original Section:** 09  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Research-grade low-latency closed-loop EEG

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 5 | 25 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 5 | 20 |
| Signal quality / research validity | 15 | 5 | 15 |
| Closed-loop latency and control compatibility | 15 | 5 | 15 |
| Access / procurement / partnership feasibility | 10 | 3 | 6 |
| Wearability / deployment suitability | 10 | 1 | 2 |
| Strategic partnership potential | 5 | 4 | 4 |

**Family Raw Score:** 87 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 87 / 100  
**Family Rank:** #4 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 92 / 100  
**Global Rank:** #19 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Brain Products plus sync2brain provides research-grade raw EEG and millisecond-accurate brain-state-dependent closed-loop processing. It is a strong technical reference stack, although less suitable as a wearable product path.

**Targeted current-state verification:**
- https://www.brainproducts.com/solutions/bossdevice-research/
- https://www.brainproducts.com/support-resources/closed-loop-brain-state-dependent-stimulation-a-complete-walkthrough-using-turbolink-bossdevice-and-bossapp-research/

---

## OPP-129 — CGX Patch EEG + Sleep Technology / Partner Program

**Organization:** CGX Systems  
**Original Section:** 09  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Low-channel frontal sleep-EEG validation

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 5 | 25 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 4 | 16 |
| Signal quality / research validity | 15 | 4 | 12 |
| Closed-loop latency and control compatibility | 15 | 3 | 9 |
| Access / procurement / partnership feasibility | 10 | 5 | 10 |
| Wearability / deployment suitability | 10 | 5 | 10 |
| Strategic partnership potential | 5 | 4 | 4 |

**Family Raw Score:** 86 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 86 / 100  
**Family Rank:** #5 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 96 / 100  
**Global Rank:** #5 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Critical  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** CGX Patch provides a self-applied two-channel forehead EEG platform with raw data, validated sleep scoring, 500 Hz/24-bit acquisition, and real-time Bluetooth streaming. It is one of the clearest low-burden hardware candidates for testing V1 sensor assumptions.

**Targeted current-state verification:**
- https://www.cgxsystems.com/patcheeg

---

## OPP-122 — InteraXon / Muse Research Partnership + Muse SDK

**Organization:** InteraXon / Muse  
**Original Section:** 09  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Wearable EEG/SDK prototyping

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 4 | 20 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 5 | 20 |
| Signal quality / research validity | 15 | 3 | 9 |
| Closed-loop latency and control compatibility | 15 | 4 | 12 |
| Access / procurement / partnership feasibility | 10 | 5 | 10 |
| Wearability / deployment suitability | 10 | 5 | 10 |
| Strategic partnership potential | 5 | 4 | 4 |

**Family Raw Score:** 85 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 85 / 100  
**Family Rank:** #6 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 87 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 87 / 100  
**Global Rank:** #32 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Wearable EEG/SDK prototyping. The adjusted global score (87) and F5 family position (#6) support active continuation.

**Targeted current-state verification:**
- https://choosemuse.com/pages/developers

---

## OPP-123 — OpenBCI Cyton / Ganglion Open Hardware Ecosystem

**Organization:** OpenBCI  
**Original Section:** 09  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Open raw-EEG closed-loop prototyping

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 4 | 20 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 5 | 20 |
| Signal quality / research validity | 15 | 4 | 12 |
| Closed-loop latency and control compatibility | 15 | 5 | 15 |
| Access / procurement / partnership feasibility | 10 | 5 | 10 |
| Wearability / deployment suitability | 10 | 2 | 4 |
| Strategic partnership potential | 5 | 3 | 3 |

**Family Raw Score:** 84 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 84 / 100  
**Family Rank:** #7 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 96 / 100  
**Global Rank:** #5 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Critical  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** OpenBCI offers unusually open raw EEG and software control with low procurement friction, making it excellent for prototyping even though wearability and sleep-specific validation are weaker than dedicated sleep platforms.

---

## OPP-127 — Wearable Sensing DSI EEG + DSI API

**Organization:** Wearable Sensing  
**Original Section:** 09  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Dry mobile EEG with developer API

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 4 | 20 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 5 | 20 |
| Signal quality / research validity | 15 | 4 | 12 |
| Closed-loop latency and control compatibility | 15 | 4 | 12 |
| Access / procurement / partnership feasibility | 10 | 4 | 8 |
| Wearability / deployment suitability | 10 | 4 | 8 |
| Strategic partnership potential | 5 | 3 | 3 |

**Family Raw Score:** 83 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 83 / 100  
**Family Rank:** #8 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 81 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 81 / 100  
**Global Rank:** #50 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Dry mobile EEG with developer API. The adjusted global score (81) and F5 family position (#8) support active continuation.

---

## OPP-130 — g.tec Unicorn Hybrid Black + g.Pype

**Organization:** g.tec medical engineering  
**Original Section:** 09  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Developer-oriented EEG/Python prototyping

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 4 | 20 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 5 | 20 |
| Signal quality / research validity | 15 | 4 | 12 |
| Closed-loop latency and control compatibility | 15 | 3 | 9 |
| Access / procurement / partnership feasibility | 10 | 5 | 10 |
| Wearability / deployment suitability | 10 | 4 | 8 |
| Strategic partnership potential | 5 | 3 | 3 |

**Family Raw Score:** 82 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 82 / 100  
**Family Rank:** #9 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 85 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 85 / 100  
**Global Rank:** #36 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Developer-oriented EEG/Python prototyping. The adjusted global score (85) and F5 family position (#9) support active continuation.

---

## OPP-132 — Elemind Closed-Loop EEG Acoustic Neurotechnology

**Organization:** Elemind  
**Original Section:** 09  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Closed-loop EEG-acoustic architecture and potential partnership

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 5 | 25 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 1 | 4 |
| Signal quality / research validity | 15 | 4 | 12 |
| Closed-loop latency and control compatibility | 15 | 5 | 15 |
| Access / procurement / partnership feasibility | 10 | 2 | 4 |
| Wearability / deployment suitability | 10 | 5 | 10 |
| Strategic partnership potential | 5 | 5 | 5 |

**Family Raw Score:** 75 / 100  
**Dependency Penalty:** -4  
**Family Adjusted Score:** 71 / 100  
**Family Rank:** #10 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 5 | 25 |
| Critical bottleneck resolution | 20 | 5 | 20 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 87 / 100  
**Dependency Penalty:** -4  
**Global Adjusted Score:** 83 / 100  
**Global Rank:** #43 / 120

### Dependency Adjustment

**Penalty:** -4  
**Reason:** The research/integration opportunity depends on a vendor partnership because general raw-data/SDK access is not openly confirmed.

### Interpretation

**Substitutability:** Low  
**Current Priority:** High  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `KEEP`

**Rationale:** Closed-loop EEG-acoustic architecture and potential partnership. The adjusted global score (83) and F5 family position (#10) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-125 — Beacon Biosignals Waveband (formerly Dreem 3S)

**Organization:** Beacon Biosignals  
**Original Section:** 09  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Home sleep-EEG validation reference platform

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 5 | 25 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 2 | 8 |
| Signal quality / research validity | 15 | 5 | 15 |
| Closed-loop latency and control compatibility | 15 | 2 | 6 |
| Access / procurement / partnership feasibility | 10 | 2 | 4 |
| Wearability / deployment suitability | 10 | 5 | 10 |
| Strategic partnership potential | 5 | 4 | 4 |

**Family Raw Score:** 72 / 100  
**Dependency Penalty:** -4  
**Family Adjusted Score:** 68 / 100  
**Family Rank:** #11 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 77 / 100  
**Dependency Penalty:** -4  
**Global Adjusted Score:** 73 / 100  
**Global Rank:** #70 / 120

### Dependency Adjustment

**Penalty:** -4  
**Reason:** Useful research access is institution/partnership controlled; unrestricted raw-data/SDK integration is not an open developer path.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Home sleep-EEG validation reference platform. The opportunity remains useful, but its adjusted global score (73) and comparative family position (#11) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-131 — Empatica EmbracePlus Research Platform

**Organization:** Empatica  
**Original Section:** 09  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Peripheral arousal and autonomic-state sensing

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Real-time EEG suitability for V1 | 25 | 0 | 0 |
| Integration openness — raw stream / API / SDK / LSL | 20 | 4 | 16 |
| Signal quality / research validity | 15 | 4 | 12 |
| Closed-loop latency and control compatibility | 15 | 2 | 6 |
| Access / procurement / partnership feasibility | 10 | 4 | 8 |
| Wearability / deployment suitability | 10 | 5 | 10 |
| Strategic partnership potential | 5 | 3 | 3 |

**Family Raw Score:** 55 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 55 / 100  
**Family Rank:** #12 / 12

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 59 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 59 / 100  
**Global Rank:** #104 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DROP`

**Rationale:** Empatica is useful for peripheral arousal/autonomic monitoring but does not provide EEG, so it cannot serve as the V1 neural sensing core. Stronger EEG candidates already cover the principal hardware bottleneck, making the marginal value insufficient for the active portfolio.

---


# F6 — Networks / Events / Multipliers

## OPP-134 — European Sleep Research Society / Sleep Europe

**Organization:** European Sleep Research Society  
**Original Section:** 10  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Sleep-specific scientific networking and collaboration

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 5 | 25 |
| Expected collaboration / introduction potential | 20 | 5 | 20 |
| Second-order multiplier power | 15 | 5 | 15 |
| Access / participation feasibility | 15 | 5 | 15 |
| Timing / current opportunity window | 10 | 5 | 10 |
| Scientific visibility / credibility | 10 | 5 | 10 |
| Effort / cost efficiency | 5 | 3 | 3 |

**Family Raw Score:** 98 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 98 / 100  
**Family Rank:** #1 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 83 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 83 / 100  
**Global Rank:** #44 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Sleep-specific scientific networking and collaboration. The adjusted global score (83) and F6 family position (#1) support active continuation.

---

## OPP-143 — CuttingGardens / CuttingEEG Community

**Organization:** CuttingEEG  
**Original Section:** 10  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** EEG methods and technical community

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 5 | 25 |
| Expected collaboration / introduction potential | 20 | 5 | 20 |
| Second-order multiplier power | 15 | 5 | 15 |
| Access / participation feasibility | 15 | 5 | 15 |
| Timing / current opportunity window | 10 | 5 | 10 |
| Scientific visibility / credibility | 10 | 4 | 8 |
| Effort / cost efficiency | 5 | 5 | 5 |

**Family Raw Score:** 98 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 98 / 100  
**Family Rank:** #2 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 82 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 82 / 100  
**Global Rank:** #48 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `KEEP`

**Rationale:** EEG methods and technical community. The adjusted global score (82) and F6 family position (#2) support active continuation.

---

## OPP-139 — NeuroTechX Global Community

**Organization:** NeuroTechX  
**Original Section:** 10  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Neurotechnology engineering and industry community

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 4 | 20 |
| Expected collaboration / introduction potential | 20 | 5 | 20 |
| Second-order multiplier power | 15 | 5 | 15 |
| Access / participation feasibility | 15 | 5 | 15 |
| Timing / current opportunity window | 10 | 5 | 10 |
| Scientific visibility / credibility | 10 | 4 | 8 |
| Effort / cost efficiency | 5 | 5 | 5 |

**Family Raw Score:** 93 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 93 / 100  
**Family Rank:** #3 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 76 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 76 / 100  
**Global Rank:** #62 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Neurotechnology engineering and industry community. The opportunity remains useful, but its adjusted global score (76) and comparative family position (#3) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-144 — Meedk — Global Armenian Brain-Health Network

**Organization:** Meedk  
**Original Section:** 10  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Armenian brain-health mentorship and scientific network

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 4 | 20 |
| Expected collaboration / introduction potential | 20 | 5 | 20 |
| Second-order multiplier power | 15 | 5 | 15 |
| Access / participation feasibility | 15 | 5 | 15 |
| Timing / current opportunity window | 10 | 5 | 10 |
| Scientific visibility / credibility | 10 | 4 | 8 |
| Effort / cost efficiency | 5 | 5 | 5 |

**Family Raw Score:** 93 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 93 / 100  
**Family Rank:** #4 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 77 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 77 / 100  
**Global Rank:** #58 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Armenian brain-health mentorship and scientific network. The opportunity remains useful, but its adjusted global score (77) and comparative family position (#4) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-135 — Sleep Research Society / SLEEP + ASCS

**Organization:** Sleep Research Society  
**Original Section:** 10  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Sleep-research networking and collaboration

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 5 | 25 |
| Expected collaboration / introduction potential | 20 | 5 | 20 |
| Second-order multiplier power | 15 | 5 | 15 |
| Access / participation feasibility | 15 | 4 | 12 |
| Timing / current opportunity window | 10 | 4 | 8 |
| Scientific visibility / credibility | 10 | 5 | 10 |
| Effort / cost efficiency | 5 | 2 | 2 |

**Family Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 92 / 100  
**Family Rank:** #5 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 78 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 78 / 100  
**Global Rank:** #56 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Sleep-research networking and collaboration. The opportunity remains useful, but its adjusted global score (78) and comparative family position (#5) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-138 — International Brain Research Organization

**Organization:** IBRO  
**Original Section:** 10  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Neuroscience training, mobility, and grant network

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 4 | 20 |
| Expected collaboration / introduction potential | 20 | 5 | 20 |
| Second-order multiplier power | 15 | 5 | 15 |
| Access / participation feasibility | 15 | 5 | 15 |
| Timing / current opportunity window | 10 | 4 | 8 |
| Scientific visibility / credibility | 10 | 5 | 10 |
| Effort / cost efficiency | 5 | 4 | 4 |

**Family Raw Score:** 92 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 92 / 100  
**Family Rank:** #6 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 81 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 81 / 100  
**Global Rank:** #50 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** High  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Neuroscience training, mobility, and grant network. The adjusted global score (81) and F6 family position (#6) support active continuation. Few realistic substitutes provide the same capability.

---

## OPP-136 — World Sleep Society / World Sleep Congress

**Organization:** World Sleep Society  
**Original Section:** 10  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Global sleep-science network access

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 5 | 25 |
| Expected collaboration / introduction potential | 20 | 4 | 16 |
| Second-order multiplier power | 15 | 5 | 15 |
| Access / participation feasibility | 15 | 4 | 12 |
| Timing / current opportunity window | 10 | 3 | 6 |
| Scientific visibility / credibility | 10 | 5 | 10 |
| Effort / cost efficiency | 5 | 2 | 2 |

**Family Raw Score:** 86 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 86 / 100  
**Family Rank:** #7 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 75 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 75 / 100  
**Global Rank:** #66 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Global sleep-science network access. The opportunity remains useful, but its adjusted global score (75) and comparative family position (#7) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-141 — Cognitive Neuroscience Society

**Organization:** Cognitive Neuroscience Society  
**Original Section:** 10  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Memory and cognitive-neuroscience network

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 4 | 20 |
| Expected collaboration / introduction potential | 20 | 4 | 16 |
| Second-order multiplier power | 15 | 4 | 12 |
| Access / participation feasibility | 15 | 4 | 12 |
| Timing / current opportunity window | 10 | 3 | 6 |
| Scientific visibility / credibility | 10 | 5 | 10 |
| Effort / cost efficiency | 5 | 3 | 3 |

**Family Raw Score:** 79 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 79 / 100  
**Family Rank:** #8 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 63 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 63 / 100  
**Global Rank:** #97 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DROP`

**Rationale:** CNS is scientifically credible, but its cognitive-neuroscience network is less targeted to the immediate sleep-EEG/TMR bottlenecks than the surviving sleep and EEG communities.

---

## OPP-133 — Society for Neuroscience (SfN) / Neuroscience Annual Meeting

**Organization:** Society for Neuroscience  
**Original Section:** 10  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Broad neuroscience collaborator discovery and visibility

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 4 | 20 |
| Expected collaboration / introduction potential | 20 | 4 | 16 |
| Second-order multiplier power | 15 | 5 | 15 |
| Access / participation feasibility | 15 | 4 | 12 |
| Timing / current opportunity window | 10 | 2 | 4 |
| Scientific visibility / credibility | 10 | 5 | 10 |
| Effort / cost efficiency | 5 | 2 | 2 |

**Family Raw Score:** 79 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 79 / 100  
**Family Rank:** #8 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 2 | 4 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 61 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 61 / 100  
**Global Rank:** #101 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DROP`

**Rationale:** SfN is an excellent broad neuroscience network, but L8 prioritizes more targeted sleep, EEG, neurotechnology, and Armenian multiplier channels for the present project.

---

## OPP-137 — Federation of European Neuroscience Societies / FENS Forum

**Organization:** FENS  
**Original Section:** 10  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** European neuroscience methods and collaboration network

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 4 | 20 |
| Expected collaboration / introduction potential | 20 | 4 | 16 |
| Second-order multiplier power | 15 | 4 | 12 |
| Access / participation feasibility | 15 | 5 | 15 |
| Timing / current opportunity window | 10 | 3 | 6 |
| Scientific visibility / credibility | 10 | 5 | 10 |
| Effort / cost efficiency | 5 | 3 | 3 |

**Family Raw Score:** 82 / 100  
**Dependency Penalty:** -4  
**Family Adjusted Score:** 78 / 100  
**Family Rank:** #10 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 63 / 100  
**Dependency Penalty:** -4  
**Global Adjusted Score:** 59 / 100  
**Global Rank:** #102 / 120

### Dependency Adjustment

**Penalty:** -4  
**Reason:** The relevant FENS event cycle is timing-dependent; immediate value is delayed until the next suitable participation window.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DEFER`

**Rationale:** European neuroscience methods and collaboration network. The underlying raw global value (63) is not treated as lost, but current activation is gated: The relevant FENS event cycle is timing-dependent; immediate value is delayed until the next suitable participation window. The opportunity should be reassessed when that trigger changes.

---

## OPP-145 — Armenian American Medical Society

**Organization:** Armenian American Medical Society  
**Original Section:** 10  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Armenian clinical, neurology, and sleep-medicine network

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 3 | 15 |
| Expected collaboration / introduction potential | 20 | 4 | 16 |
| Second-order multiplier power | 15 | 4 | 12 |
| Access / participation feasibility | 15 | 5 | 15 |
| Timing / current opportunity window | 10 | 4 | 8 |
| Scientific visibility / credibility | 10 | 4 | 8 |
| Effort / cost efficiency | 5 | 4 | 4 |

**Family Raw Score:** 78 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 78 / 100  
**Family Rank:** #11 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 76 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 76 / 100  
**Global Rank:** #65 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Armenian clinical, neurology, and sleep-medicine network. The opportunity remains useful, but its adjusted global score (76) and comparative family position (#11) place it behind stronger current mechanisms. It is preserved because it retains differentiated or portfolio-level value.

---

## OPP-140 — IEEE Engineering in Medicine and Biology Society / EMBC

**Organization:** IEEE Engineering in Medicine and Biology Society  
**Original Section:** 10  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Biomedical signal-processing and neural-engineering network

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 4 | 20 |
| Expected collaboration / introduction potential | 20 | 4 | 16 |
| Second-order multiplier power | 15 | 4 | 12 |
| Access / participation feasibility | 15 | 5 | 15 |
| Timing / current opportunity window | 10 | 1 | 2 |
| Scientific visibility / credibility | 10 | 5 | 10 |
| Effort / cost efficiency | 5 | 3 | 3 |

**Family Raw Score:** 78 / 100  
**Dependency Penalty:** -4  
**Family Adjusted Score:** 74 / 100  
**Family Rank:** #12 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 1 | 1 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 61 / 100  
**Dependency Penalty:** -4  
**Global Adjusted Score:** 57 / 100  
**Global Rank:** #105 / 120

### Dependency Adjustment

**Penalty:** -4  
**Reason:** EMBC 2026 has already passed; value depends on the next conference cycle rather than a current event window.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DEFER`

**Rationale:** Biomedical signal-processing and neural-engineering network. The underlying raw global value (61) is not treated as lost, but current activation is gated: EMBC 2026 has already passed; value depends on the next conference cycle rather than a current event window. The opportunity should be reassessed when that trigger changes.

---

## OPP-142 — Cognitive Computational Neuroscience

**Organization:** Cognitive Computational Neuroscience community  
**Original Section:** 10  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** ML-neuroscience and computational-research network

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Density and relevance of target researchers/opportunities | 25 | 4 | 20 |
| Expected collaboration / introduction potential | 20 | 4 | 16 |
| Second-order multiplier power | 15 | 4 | 12 |
| Access / participation feasibility | 15 | 4 | 12 |
| Timing / current opportunity window | 10 | 1 | 2 |
| Scientific visibility / credibility | 10 | 5 | 10 |
| Effort / cost efficiency | 5 | 3 | 3 |

**Family Raw Score:** 75 / 100  
**Dependency Penalty:** -4  
**Family Adjusted Score:** 71 / 100  
**Family Rank:** #13 / 13

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 1 | 1 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 63 / 100  
**Dependency Penalty:** -4  
**Global Adjusted Score:** 59 / 100  
**Global Rank:** #102 / 120

### Dependency Adjustment

**Penalty:** -4  
**Reason:** CCN 2026 has already passed; value depends on the next conference cycle.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DEFER`

**Rationale:** ML-neuroscience and computational-research network. The underlying raw global value (63) is not treated as lost, but current activation is gated: CCN 2026 has already passed; value depends on the next conference cycle. The opportunity should be reassessed when that trigger changes.

---


# F7 — Governance / Institutional Enablement

## OPP-153 — Open Science Framework Registrations / EEG-ERP Preregistration

**Organization:** Center for Open Science / OSF  
**Original Section:** 11  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** EEG/ERP preregistration, transparency, and reproducibility

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Ability to enable legitimate human validation | 30 | 3 | 18 |
| Applicability to likely Neuro-TMR study design | 20 | 5 | 20 |
| Host / institutional accessibility | 20 | 5 | 20 |
| Governance authority and completeness | 15 | 4 | 12 |
| Operational / timing feasibility | 10 | 5 | 10 |
| Future multi-site / scalability value | 5 | 5 | 5 |

**Family Raw Score:** 85 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 85 / 100  
**Family Rank:** #1 / 8

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 5 | 5 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 68 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 68 / 100  
**Global Rank:** #91 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Medium  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** EEG/ERP preregistration, transparency, and reproducibility. The opportunity remains useful, but its adjusted global score (68) and comparative family position (#1) place it behind stronger current mechanisms. Functional substitution by stronger surviving candidates is a material reason to keep it in reserve.

---

## OPP-151 — Republic of Armenia Personal Data Protection Agency

**Organization:** Republic of Armenia  
**Original Section:** 11  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future Armenian privacy and research-data governance

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Ability to enable legitimate human validation | 30 | 3 | 18 |
| Applicability to likely Neuro-TMR study design | 20 | 4 | 16 |
| Host / institutional accessibility | 20 | 5 | 20 |
| Governance authority and completeness | 15 | 5 | 15 |
| Operational / timing feasibility | 10 | 3 | 6 |
| Future multi-site / scalability value | 5 | 3 | 3 |

**Family Raw Score:** 78 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 78 / 100  
**Family Rank:** #2 / 8

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 66 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 66 / 100  
**Global Rank:** #96 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DEFER`

**Rationale:** Future Armenian privacy and research-data governance. The underlying raw global value (66) is not treated as lost, but current activation is gated: No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria. The opportunity should be reassessed when that trigger changes.

---

## OPP-146 — YSMU Ethics Committee

**Organization:** Yerevan State Medical University  
**Original Section:** 11  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future YSMU human-research ethics pathway

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Ability to enable legitimate human validation | 30 | 5 | 30 |
| Applicability to likely Neuro-TMR study design | 20 | 5 | 20 |
| Host / institutional accessibility | 20 | 3 | 12 |
| Governance authority and completeness | 15 | 5 | 15 |
| Operational / timing feasibility | 10 | 2 | 4 |
| Future multi-site / scalability value | 5 | 2 | 2 |

**Family Raw Score:** 83 / 100  
**Dependency Penalty:** -6  
**Family Adjusted Score:** 77 / 100  
**Family Rank:** #3 / 8

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 1 | 1 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 59 / 100  
**Dependency Penalty:** -6  
**Global Adjusted Score:** 53 / 100  
**Global Rank:** #110 / 120

### Dependency Adjustment

**Penalty:** -6  
**Reason:** Meaningful use requires a YSMU-hosted/affiliated human-subject study, responsible investigators, and a concrete protocol.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DEFER`

**Rationale:** Future YSMU human-research ethics pathway. The underlying raw global value (59) is not treated as lost, but current activation is gated: Meaningful use requires a YSMU-hosted/affiliated human-subject study, responsible investigators, and a concrete protocol. The opportunity should be reassessed when that trigger changes.

---

## OPP-147 — AUA Institutional Review Boards

**Organization:** American University of Armenia  
**Original Section:** 11  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future AUA human-research ethics pathway

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Ability to enable legitimate human validation | 30 | 5 | 30 |
| Applicability to likely Neuro-TMR study design | 20 | 5 | 20 |
| Host / institutional accessibility | 20 | 3 | 12 |
| Governance authority and completeness | 15 | 5 | 15 |
| Operational / timing feasibility | 10 | 2 | 4 |
| Future multi-site / scalability value | 5 | 2 | 2 |

**Family Raw Score:** 83 / 100  
**Dependency Penalty:** -6  
**Family Adjusted Score:** 77 / 100  
**Family Rank:** #3 / 8

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 1 | 1 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 59 / 100  
**Dependency Penalty:** -6  
**Global Adjusted Score:** 53 / 100  
**Global Rank:** #110 / 120

### Dependency Adjustment

**Penalty:** -6  
**Reason:** Meaningful use requires an AUA institutional relationship/sponsorship and a concrete human-subject study.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DEFER`

**Rationale:** Future AUA human-research ethics pathway. The underlying raw global value (59) is not treated as lost, but current activation is gated: Meaningful use requires an AUA institutional relationship/sponsorship and a concrete human-subject study. The opportunity should be reassessed when that trigger changes.

---

## OPP-152 — REDCap Consortium / Secure Research Data Infrastructure

**Organization:** REDCap Consortium  
**Original Section:** 11  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future secure human-study data-management infrastructure

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Ability to enable legitimate human validation | 30 | 4 | 24 |
| Applicability to likely Neuro-TMR study design | 20 | 5 | 20 |
| Host / institutional accessibility | 20 | 3 | 12 |
| Governance authority and completeness | 15 | 4 | 12 |
| Operational / timing feasibility | 10 | 4 | 8 |
| Future multi-site / scalability value | 5 | 5 | 5 |

**Family Raw Score:** 81 / 100  
**Dependency Penalty:** -4  
**Family Adjusted Score:** 77 / 100  
**Family Rank:** #5 / 8

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 3 | 9 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 72 / 100  
**Dependency Penalty:** -4  
**Global Adjusted Score:** 68 / 100  
**Global Rank:** #90 / 120

### Dependency Adjustment

**Penalty:** -4  
**Reason:** Long-term human-study use requires an eligible institutional REDCap deployment or hosted organizational route.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DEFER`

**Rationale:** Future secure human-study data-management infrastructure. The underlying raw global value (72) is not treated as lost, but current activation is gated: Long-term human-study use requires an eligible institutional REDCap deployment or hosted organizational route. The opportunity should be reassessed when that trigger changes.

---

## OPP-148 — AUA Office of Sponsored Programs & Technology Transfer

**Organization:** American University of Armenia  
**Original Section:** 11  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future AUA grants, contracts, IP, and research administration

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Ability to enable legitimate human validation | 30 | 3 | 18 |
| Applicability to likely Neuro-TMR study design | 20 | 4 | 16 |
| Host / institutional accessibility | 20 | 3 | 12 |
| Governance authority and completeness | 15 | 4 | 12 |
| Operational / timing feasibility | 10 | 3 | 6 |
| Future multi-site / scalability value | 5 | 3 | 3 |

**Family Raw Score:** 67 / 100  
**Dependency Penalty:** -4  
**Family Adjusted Score:** 63 / 100  
**Family Rank:** #6 / 8

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 50 / 100  
**Dependency Penalty:** -4  
**Global Adjusted Score:** 46 / 100  
**Global Rank:** #115 / 120

### Dependency Adjustment

**Penalty:** -4  
**Reason:** The office becomes useful through a substantive AUA research relationship and an actual sponsored-project/IP/contract need.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DEFER`

**Rationale:** Future AUA grants, contracts, IP, and research administration. The underlying raw global value (50) is not treated as lost, but current activation is gated: The office becomes useful through a substantive AUA research relationship and an actual sponsored-project/IP/contract need. The opportunity should be reassessed when that trigger changes.

---

## OPP-149 — YSMU Science Coordination Council

**Organization:** Yerevan State Medical University  
**Original Section:** 11  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future YSMU scientific-governance pathway

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Ability to enable legitimate human validation | 30 | 3 | 18 |
| Applicability to likely Neuro-TMR study design | 20 | 4 | 16 |
| Host / institutional accessibility | 20 | 3 | 12 |
| Governance authority and completeness | 15 | 4 | 12 |
| Operational / timing feasibility | 10 | 3 | 6 |
| Future multi-site / scalability value | 5 | 2 | 2 |

**Family Raw Score:** 66 / 100  
**Dependency Penalty:** -4  
**Family Adjusted Score:** 62 / 100  
**Family Rank:** #7 / 8

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 2 | 2 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 48 / 100  
**Dependency Penalty:** -4  
**Global Adjusted Score:** 44 / 100  
**Global Rank:** #117 / 120

### Dependency Adjustment

**Penalty:** -4  
**Reason:** This is an internal YSMU governance pathway and therefore requires a YSMU host/collaborator and a concrete institutional research action.

### Interpretation

**Substitutability:** High  
**Current Priority:** Low  
**Future Strategic Value:** Medium  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `DEFER`

**Rationale:** Future YSMU scientific-governance pathway. The underlying raw global value (48) is not treated as lost, but current activation is gated: This is an internal YSMU governance pathway and therefore requires a YSMU host/collaborator and a concrete institutional research action. The opportunity should be reassessed when that trigger changes.

---

## OPP-154 — ClinicalTrials.gov Protocol Registration and Results System

**Organization:** U.S. National Library of Medicine / NIH  
**Original Section:** 11  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future public human-study registration and results transparency

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Ability to enable legitimate human validation | 30 | 3 | 18 |
| Applicability to likely Neuro-TMR study design | 20 | 4 | 16 |
| Host / institutional accessibility | 20 | 2 | 8 |
| Governance authority and completeness | 15 | 5 | 15 |
| Operational / timing feasibility | 10 | 2 | 4 |
| Future multi-site / scalability value | 5 | 5 | 5 |

**Family Raw Score:** 66 / 100  
**Dependency Penalty:** -6  
**Family Adjusted Score:** 60 / 100  
**Family Rank:** #8 / 8

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 2 | 10 |
| Critical bottleneck resolution | 20 | 2 | 8 |
| Realistic actionability / access | 15 | 2 | 6 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 3 | 6 |
| Time-to-value | 5 | 1 | 1 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 50 / 100  
**Dependency Penalty:** -6  
**Global Adjusted Score:** 44 / 100  
**Global Rank:** #116 / 120

### Dependency Adjustment

**Penalty:** -6  
**Reason:** Protocol registration becomes meaningful only after a real study, responsible party, and organizational/investigator registration structure exist.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Low  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `DEFER`

**Rationale:** Future public human-study registration and results transparency. The underlying raw global value (50) is not treated as lost, but current activation is gated: Protocol registration becomes meaningful only after a real study, responsible party, and organizational/investigator registration structure exist. The opportunity should be reassessed when that trigger changes.

---


# F8 — Future-Horizon Strategic Technologies

## OPP-163 — Phase-Specific Closed-Loop TMR — Open Data + Code Research Stack

**Organization:** Multi-institution academic research collaboration  
**Original Section:** 12  
**L6 Context:** `L6_ACTIONABLE`  
**Key Neuro-TMR Contribution:** Phase-aware TMR timing and closed-loop methodology

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Long-term strategic upside | 25 | 5 | 25 |
| Scientific / technological maturity | 20 | 4 | 16 |
| Relevance to future Neuro-TMR bottlenecks | 20 | 5 | 20 |
| Integration plausibility with V1/V2 architecture | 15 | 5 | 15 |
| Unique option value / non-substitutability | 10 | 5 | 10 |
| Readiness horizon | 10 | 5 | 10 |

**Family Raw Score:** 96 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 96 / 100  
**Family Rank:** #1 / 6

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 5 | 10 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 90 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 90 / 100  
**Global Rank:** #28 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** High  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `KEEP`

**Rationale:** Phase-specific closed-loop TMR is directly relevant to the later stage-versus-phase control decision, with published evidence plus open data/code pathways. It should be carried forward without expanding V1 into phase-locking prematurely.

**Targeted current-state verification:**
- https://www.nature.com/articles/s41467-025-57602-2

---

## OPP-159 — Sleep Interpreter — Real-Time Semantic Memory-Reactivation Decoding

**Organization:** Academic sleep / memory / neural-decoding research ecosystem  
**Original Section:** 12  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future post-cue memory-reactivation decoding and feedback

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Long-term strategic upside | 25 | 5 | 25 |
| Scientific / technological maturity | 20 | 5 | 20 |
| Relevance to future Neuro-TMR bottlenecks | 20 | 5 | 20 |
| Integration plausibility with V1/V2 architecture | 15 | 4 | 12 |
| Unique option value / non-substitutability | 10 | 5 | 10 |
| Readiness horizon | 10 | 4 | 8 |

**Family Raw Score:** 95 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 95 / 100  
**Family Rank:** #2 / 6

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 4 | 12 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 80 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 80 / 100  
**Global Rank:** #55 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Medium  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Sleep Interpreter demonstrates real-time sleep staging and semantic reactivation decoding with a large released dataset/codebase. It is strategically important, but memory-content feedback is beyond the current stage-aware V1 requirement, so it remains reserve rather than core.

**Targeted current-state verification:**
- https://pubmed.ncbi.nlm.nih.gov/41999754/
- https://www.sciencedirect.com/science/article/pii/S0896627326002199

---

## OPP-162 — Personalized TMR Based on Memory Difficulty

**Organization:** Korea University Brain and Cognitive Engineering / AI research ecosystem  
**Original Section:** 12  
**L6 Context:** `L6_RESERVE_CANDIDATE`  
**Key Neuro-TMR Contribution:** Future memory-difficulty-aware adaptive cue scheduling

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Long-term strategic upside | 25 | 5 | 25 |
| Scientific / technological maturity | 20 | 4 | 16 |
| Relevance to future Neuro-TMR bottlenecks | 20 | 5 | 20 |
| Integration plausibility with V1/V2 architecture | 15 | 5 | 15 |
| Unique option value / non-substitutability | 10 | 5 | 10 |
| Readiness horizon | 10 | 4 | 8 |

**Family Raw Score:** 94 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 94 / 100  
**Family Rank:** #3 / 6

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 81 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 81 / 100  
**Global Rank:** #50 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** Medium  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** Personalized TMR based on memory difficulty has direct evidence for adaptive cue scheduling and is conceptually important for later personalization. It does not solve the immediate V1 sensing/control bottleneck, so reserve status preserves the option without scope expansion.

**Targeted current-state verification:**
- https://www.nature.com/articles/s41539-025-00340-3

---

## OPP-164 — Portiloop / Closed-Loop Sleep-Spindle Targeting

**Organization:** Academic closed-loop sleep-neurotechnology ecosystem  
**Original Section:** 12  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Future spindle/microstate-aware cue control

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Long-term strategic upside | 25 | 4 | 20 |
| Scientific / technological maturity | 20 | 4 | 16 |
| Relevance to future Neuro-TMR bottlenecks | 20 | 5 | 20 |
| Integration plausibility with V1/V2 architecture | 15 | 5 | 15 |
| Unique option value / non-substitutability | 10 | 5 | 10 |
| Readiness horizon | 10 | 5 | 10 |

**Family Raw Score:** 91 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 91 / 100  
**Family Rank:** #4 / 6

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 4 | 20 |
| Critical bottleneck resolution | 20 | 4 | 16 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 5 | 10 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 4 | 4 |

**Global Raw Score:** 87 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 87 / 100  
**Global Rank:** #33 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Low  
**Current Priority:** High  
**Future Strategic Value:** Critical  
**Evaluation Confidence:** Medium

### Final Decision

**Decision:** `KEEP`

**Rationale:** Portiloop provides an open, portable closed-loop spindle-targeting architecture and is strategically useful as an engineering reference for event-aware sleep intervention. It is later-generation rather than a V1 requirement.

---

## OPP-160 — Open EEG Foundation-Model Ecosystem — EEGPT / LaBraM

**Organization:** Open academic EEG-AI research ecosystem  
**Original Section:** 12  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** General EEG representation learning and transfer

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Long-term strategic upside | 25 | 4 | 20 |
| Scientific / technological maturity | 20 | 5 | 20 |
| Relevance to future Neuro-TMR bottlenecks | 20 | 4 | 16 |
| Integration plausibility with V1/V2 architecture | 15 | 4 | 12 |
| Unique option value / non-substitutability | 10 | 4 | 8 |
| Readiness horizon | 10 | 5 | 10 |

**Family Raw Score:** 86 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 86 / 100  
**Family Rank:** #5 / 6

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 3 | 6 |
| Non-substitutability / unique value | 10 | 3 | 6 |
| Cross-project leverage | 10 | 4 | 8 |
| Time-to-value | 5 | 4 | 4 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 71 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 71 / 100  
**Global Rank:** #76 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** High  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** General EEG representation learning and transfer. The opportunity remains useful, but its adjusted global score (71) and comparative family position (#5) place it behind stronger current mechanisms. Functional substitution by stronger surviving candidates is a material reason to keep it in reserve.

---

## OPP-158 — SleepFM — Multimodal Sleep Foundation Model

**Organization:** International academic sleep-AI research ecosystem  
**Original Section:** 12  
**L6 Context:** `L6_ACTIONABLE_WITH_PREPARATION`  
**Key Neuro-TMR Contribution:** Future pretrained sleep representations and transfer learning

### Within-Family Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Long-term strategic upside | 25 | 4 | 20 |
| Scientific / technological maturity | 20 | 5 | 20 |
| Relevance to future Neuro-TMR bottlenecks | 20 | 4 | 16 |
| Integration plausibility with V1/V2 architecture | 15 | 4 | 12 |
| Unique option value / non-substitutability | 10 | 4 | 8 |
| Readiness horizon | 10 | 4 | 8 |

**Family Raw Score:** 84 / 100  
**Dependency Penalty:** +0  
**Family Adjusted Score:** 84 / 100  
**Family Rank:** #6 / 6

### Global Evaluation

| Criterion | Weight | Rating (0–5) | Weighted Points |
|---|---:|---:|---:|
| Contribution to Neuro-TMR objectives | 25 | 3 | 15 |
| Critical bottleneck resolution | 20 | 3 | 12 |
| Realistic actionability / access | 15 | 5 | 15 |
| Expected impact if successful | 10 | 4 | 8 |
| Non-substitutability / unique value | 10 | 4 | 8 |
| Cross-project leverage | 10 | 5 | 10 |
| Time-to-value | 5 | 3 | 3 |
| Evidence confidence | 5 | 5 | 5 |

**Global Raw Score:** 76 / 100  
**Dependency Penalty:** +0  
**Global Adjusted Score:** 76 / 100  
**Global Rank:** #62 / 120

### Dependency Adjustment

**Penalty:** +0  
**Reason:** No distinct dependency penalty; ordinary access difficulty is handled inside the scoring criteria.

### Interpretation

**Substitutability:** Medium  
**Current Priority:** Medium  
**Future Strategic Value:** High  
**Evaluation Confidence:** High

### Final Decision

**Decision:** `RESERVE`

**Rationale:** SleepFM is a strong 2026 foundation-model reference trained on very large multimodal PSG data. Its near-term value is methodological transfer/benchmarking rather than direct TMR gating, so it is preserved as reserve.

**Targeted current-state verification:**
- https://www.nature.com/articles/s41591-025-04133-4

---

# Decision Registers

These registers make the L8 reduction auditable without removing any candidate from this ledger.

## KEEP

- `OPP-078B` — Dreamento Open Sleep-EEG / Closed-Loop Research Toolbox — Global 99 — F2 rank #5
- `OPP-064` — National Sleep Research Resource (NSRR) — Global 98 — F2 rank #2
- `OPP-075` — Bitbrain Open Access Sleep (BOAS) — Global 98 — F2 rank #1
- `OPP-078A` — NEMAR Research Infrastructure — Global 98 — F2 rank #3
- `OPP-011` — Sleep and Memory Laboratory (Cecilia Forcato) — Global 96 — F1 rank #1
- `OPP-014` — Hong-Viet V. Ngo-Dehning — Sleep, Memory and Real-Time Stimulation — Global 96 — F1 rank #1
- `OPP-015` — Centre for Sleep and Cognition / Sleep and Cognition Laboratory (Michael Chee) — Global 96 — F1 rank #1
- `OPP-020` — SleepLoopFM / Sensory-Motor Systems Lab — Global 96 — F1 rank #1
- `OPP-046` — Neurology, Electrophysiology & Sleep Laboratory — Global 96 — F1 rank #11
- `OPP-067` — STAGES — Global 96 — F2 rank #6
- `OPP-123` — OpenBCI Cyton / Ganglion Open Hardware Ecosystem — Global 96 — F5 rank #7
- `OPP-124` — Bitbrain Ikon Sleep + SDK Ecosystem — Global 96 — F5 rank #1
- `OPP-129` — CGX Patch EEG + Sleep Technology / Partner Program — Global 96 — F5 rank #5
- `OPP-076` — Ear-EEG Sleep Monitoring 2017 (EESM17) — Global 95 — F2 rank #12
- `OPP-121` — Earable Neuroscience / FRENZ Research & B2B Partnership — Global 95 — F5 rank #2
- `OPP-026` — Surrey Sleep Research Centre — Global 94 — F1 rank #18
- `OPP-039` — Neurotechnology Laboratory, Engineering City — Global 93 — F1 rank #9
- `OPP-016` — Swartz Center for Computational Neuroscience (SCCN) — Global 93 — F1 rank #16
- `OPP-004` — Neuroscience and Psychology of Sleep Lab (NaPS) / CUBRIC Sleep Research — Global 92 — F1 rank #1
- `OPP-019` — Center for Ear-EEG / Neurotechnology Group — Global 92 — F1 rank #11
- `OPP-065` — Sleep Heart Health Study (SHHS) — Global 92 — F2 rank #3
- `OPP-126` — Brain Products + sync2brain Real-Time Closed-Loop EEG Stack — Global 92 — F5 rank #4
- `OPP-128` — ANT Neuro eego rt / eego Research Ecosystem — Global 92 — F5 rank #3
- `OPP-074` — PhysioNet / CinC 2018 Sleep Arousal Dataset — Global 91 — F2 rank #10
- `OPP-001` — Cognitive Neuroscience Laboratory (Ken Paller) — Global 90 — F1 rank #1
- `OPP-002` — Memory and Sleep Group (Bernhard Staresina) — Global 90 — F1 rank #7
- `OPP-007` — Institute of Medical Psychology and Behavioural Neurobiology / Sleep & Memory in Humans — Global 90 — F1 rank #7
- `OPP-163` — Phase-Specific Closed-Loop TMR — Open Data + Code Research Stack — Global 90 — F8 rank #1
- `OPP-003` — Cognitive Neuroscience of Sleep Lab (CogNoS) — Global 88 — F1 rank #10
- `OPP-069` — Sleep-EDF Expanded — Global 88 — F2 rank #9
- `OPP-104` — Artificial Intelligence Virtual Institute / HPC State Support — Global 87 — F3 rank #1
- `OPP-122` — InteraXon / Muse Research Partnership + Muse SDK — Global 87 — F5 rank #6
- `OPP-164` — Portiloop / Closed-Loop Sleep-Spindle Targeting — Global 87 — F8 rank #4
- `OPP-009` — Emmy Noether Memory Consolidation Group (Thomas Schreiner) — Global 86 — F1 rank #14
- `OPP-038` — Neuro-Psycholinguistics Laboratory — Global 86 — F1 rank #32
- `OPP-047` — Neurology & Epileptology / EEG ecosystem — Global 85 — F1 rank #29
- `OPP-051` — Hrayr Attarian — Global 85 — F1 rank #15
- `OPP-070` — HMC Sleep Staging Database — Global 85 — F2 rank #7
- `OPP-130` — g.tec Unicorn Hybrid Black + g.Pype — Global 85 — F5 rank #9
- `OPP-031` — COBRAIN Scientific-Educational Center for Fundamental Brain Research — Global 85 — F1 rank #34
- `OPP-006` — DreamTeam — Sleep, Dreams, and Cognition — Global 84 — F1 rank #13
- `OPP-072` — ISRUC-Sleep — Global 84 — F2 rank #13
- `OPP-132` — Elemind Closed-Loop EEG Acoustic Neurotechnology — Global 83 — F5 rank #10
- `OPP-066` — MESA Sleep — Global 83 — F2 rank #8
- `OPP-077` — Dreem Open Datasets (DOD-H / DOD-O) — Global 83 — F2 rank #10
- `OPP-134` — European Sleep Research Society / Sleep Europe — Global 83 — F6 rank #1
- `OPP-005` — Cognitive Biopsychology and Methods / Sleep Laboratory (Björn Rasch) — Global 82 — F1 rank #17
- `OPP-143` — CuttingGardens / CuttingEEG Community — Global 82 — F6 rank #2
- `OPP-008` — York Sleep / Memory Reactivation Research (Scott Cairney and collaborators) — Global 81 — F1 rank #19
- `OPP-025` — In-Ear Physiological Sensing / Danilo Mandic Research — Global 81 — F1 rank #20
- `OPP-029` — Mobile EEG / Neuropsychology Ecosystem (Stefan Debener) — Global 81 — F1 rank #20
- `OPP-127` — Wearable Sensing DSI EEG + DSI API — Global 81 — F5 rank #8
- `OPP-138` — International Brain Research Organization — Global 81 — F6 rank #6

## RESERVE

- `OPP-162` — Personalized TMR Based on Memory Difficulty — Global 81 — F8 rank #3
- `OPP-159` — Sleep Interpreter — Real-Time Semantic Memory-Reactivation Decoding — Global 80 — F8 rank #2
- `OPP-021` — Stanford Sleep Medicine Computational & Sensing Ecosystem — Global 78 — F1 rank #24
- `OPP-135` — Sleep Research Society / SLEEP + ASCS — Global 78 — F6 rank #5
- `OPP-144` — Meedk — Global Armenian Brain-Health Network — Global 77 — F6 rank #4
- `OPP-116` — CAJAL Neurobiology of Sleep — Global 76 — F4 rank #1
- `OPP-012` — Schapiro Lab — Sleep, Learning and Memory — Global 76 — F1 rank #27
- `OPP-013` — Sleep Neuroscience & Cognition Laboratory (Michael Scullin) — Global 76 — F1 rank #23
- `OPP-034` — L. A. Orbeli Institute of Physiology — Global 76 — F1 rank #33
- `OPP-139` — NeuroTechX Global Community — Global 76 — F6 rank #3
- `OPP-158` — SleepFM — Multimodal Sleep Foundation Model — Global 76 — F8 rank #6
- `OPP-145` — Armenian American Medical Society — Global 76 — F6 rank #11
- `OPP-136` — World Sleep Society / World Sleep Congress — Global 75 — F6 rank #7
- `OPP-125` — Beacon Biosignals Waveband (formerly Dreem 3S) — Global 73 — F5 rank #11
- `OPP-071` — CAP Sleep Database — Global 73 — F2 rank #15
- `OPP-017` — Chair of Neurotechnology / Berlin BCI — Global 72 — F1 rank #30
- `OPP-018` — Translational Neural Engineering Laboratory — Global 72 — F1 rank #25
- `OPP-050` — Paul Nuyujukian / Brain Interfacing Laboratory — Global 72 — F1 rank #25
- `OPP-160` — Open EEG Foundation-Model Ecosystem — EEGPT / LaBraM — Global 71 — F8 rank #5
- `OPP-037` — Psychology Research Center — Global 71 — F1 rank #37
- `OPP-040` — Coding and Signal Processing Department — Global 71 — F1 rank #41
- `OPP-052` — Lorig Panossian — Global 71 — F1 rank #37
- `OPP-053` — Talin Babikian — Global 71 — F1 rank #37
- `OPP-058` — Rami Apelian — Global 71 — F1 rank #35
- `OPP-059` — Armen J. Cherik — Global 71 — F1 rank #35
- `OPP-010` — Social & Cognitive Neuroscience Laboratory (Xiaoqing Hu) — Global 70 — F1 rank #22
- `OPP-073` — Montreal Archive of Sleep Studies (MASS) — Global 70 — F2 rank #14
- `OPP-032` — Scientific Research Center, Neuroscience Laboratory — Global 70 — F1 rank #42
- `OPP-033` — Department of Neurology & Clinical Research Network — Global 69 — F1 rank #37
- `OPP-153` — Open Science Framework Registrations / EEG-ERP Preregistration — Global 68 — F7 rank #1
- `OPP-068` — HomePAP — Global 67 — F2 rank #16
- `OPP-102` — ANSEF Yervant Terzian Research Grants — Global 61 — F3 rank #7

## DEFER

- `OPP-095` — Remote Laboratories 2026 — Global 74 — F3 rank #3
- `OPP-096` — Integration of Foreign Scientists into the Scientific Community of Armenia — Global 74 — F3 rank #3
- `OPP-101` — ADVANCE Research Grants — Global 74 — F3 rank #3
- `OPP-093` — NIH BRAIN Initiative Funding Ecosystem — Global 71 — F3 rank #9
- `OPP-100` — State Scientific Equipment Re-Equipment Programme — Global 70 — F3 rank #10
- `OPP-080` — European Partnership for Brain Health (EP BrainHealth) — Global 69 — F3 rank #6
- `OPP-120` — Armenia Professional Training Programme — Global 69 — F4 rank #2
- `OPP-152` — REDCap Consortium / Secure Research Data Infrastructure — Global 68 — F7 rank #5
- `OPP-079` — Horizon Europe — Cluster 1: Health — Global 67 — F3 rank #2
- `OPP-151` — Republic of Armenia Personal Data Protection Agency — Global 66 — F7 rank #2
- `OPP-137` — Federation of European Neuroscience Societies / FENS Forum — Global 59 — F6 rank #10
- `OPP-142` — Cognitive Computational Neuroscience — Global 59 — F6 rank #13
- `OPP-140` — IEEE Engineering in Medicine and Biology Society / EMBC — Global 57 — F6 rank #12
- `OPP-146` — YSMU Ethics Committee — Global 53 — F7 rank #3
- `OPP-147` — AUA Institutional Review Boards — Global 53 — F7 rank #3
- `OPP-094` — Young Scientific Groups Formation & Research Promotion 2026 — Global 53 — F3 rank #11
- `OPP-115` — FENS / IBRO-PERC Exchange Fellowships Programme — Global 49 — F4 rank #3
- `OPP-148` — AUA Office of Sponsored Programs & Technology Transfer — Global 46 — F7 rank #6
- `OPP-154` — ClinicalTrials.gov Protocol Registration and Results System — Global 44 — F7 rank #8
- `OPP-149` — YSMU Science Coordination Council — Global 44 — F7 rank #7
- `OPP-088` — Human Frontier Science Program Research Grants — Global 39 — F3 rank #12

## DROP

- `OPP-028` — Wisconsin Institute for Sleep and Consciousness — Global 66 — F1 rank #28
- `OPP-030` — BrainLinks-BrainTools — Global 66 — F1 rank #30
- `OPP-141` — Cognitive Neuroscience Society — Global 63 — F6 rank #8
- `OPP-041` — Telecommunications / Signal Processing Laboratories — Global 62 — F1 rank #43
- `OPP-060` — Maral Aghvinian Vartanian / Meedk Scientific Bridge — Global 62 — F1 rank #47
- `OPP-133` — Society for Neuroscience (SfN) / Neuroscience Annual Meeting — Global 61 — F6 rank #8
- `OPP-131` — Empatica EmbracePlus Research Platform — Global 59 — F5 rank #12
- `OPP-042` — Bioengineering / Biomedical Engineering Ecosystem — Global 57 — F1 rank #44
- `OPP-045` — Biomedical Engineering / Electronics & Measurement Systems ecosystem — Global 57 — F1 rank #44
- `OPP-043` — Mariam Avagyan / sleep-EEG signal-analysis capability — Global 56 — F1 rank #48
- `OPP-044` — Levon Hovhannisyan / wearable physiological systems capability — Global 56 — F1 rank #44
- `OPP-107` — “100 Ideas for Armenia” 2026 — Global 49 — F3 rank #8
- `OPP-049` — Ardem Patapoutian — Global 44 — F1 rank #49
- `OPP-099` — Research Support Program for PhD Students & Young Applicants — Global 17 — F3 rank #13

# Targeted External Verification Sources

Repository evidence remained the primary basis. The following current sources were used to verify high-impact or time-sensitive facts that could materially affect L8:

- NEMAR BOAS dataset: https://nemar.org/dataset/on005555
- Dreamento open-source toolbox: https://github.com/dreamento/dreamento
- Muse SDK / research access: https://choosemuse.com/pages/developers
- Bitbrain Ikon Sleep documentation: https://downloads.bitbrain.com/products/hardware/ikon-sleep
- Brain Products / sync2brain bossdevice RESEARCH: https://www.brainproducts.com/solutions/bossdevice-research/
- ANT Neuro eego rt: https://www.ant-neuro.com/products/eego-rt
- CGX Patch EEG: https://www.cgxsystems.com/patcheeg
- FRENZ research/B2B partnership: https://frenzband.com/pages/earable-neuroscience-research-partnership-services
- Horizon Europe association — Armenia: https://research-and-innovation.ec.europa.eu/strategy/strategy-research-and-innovation/europe-world/international-cooperation/association-horizon-europe/armenia_en
- HFSP Research Grants: https://www.hfsp.org/funding/hfsp-funding/research-grants
- CAJAL Neurobiology of Sleep 2026: https://cajal-training.org/on-site/neurobiology_sleep/
- SleepFM: https://www.nature.com/articles/s41591-025-04133-4
- Sleep Interpreter: https://pubmed.ncbi.nlm.nih.gov/41999754/
- Personalized TMR: https://www.nature.com/articles/s41539-025-00340-3
- Phase-specific closed-loop TMR: https://www.nature.com/articles/s41467-025-57602-2

# L8 Gate Result

**120 candidates entered L8.**  
**120 candidates received complete family + global scoring.**  
**53 received `KEEP`.**  
**32 received `RESERVE`.**  
**21 received `DEFER`.**  
**14 received `DROP`.**  

**Active post-L8 universe for `l8_ranked_opportunities.md`: 85 candidates.**

Candidates marked `DEFER` or `DROP` remain permanently preserved in this ledger for traceability but do not enter the active ranked universe.

**L8 SCORING: COMPLETE**
