# A7 — Path V Compute Request Brief

**Toolkit:** Path E Execution Toolkit  
**Artifact:** A7  
**Status:** INITIAL / HIGH-LEVEL  
**Date:** 2026-08-21  
**Scope:** High-level description of the computational workload expected during Path V

---

## 1. Purpose

A7 explains **why Neuro-TMR will require scalable computational infrastructure during Path V**.

It does **not** prescribe exact GPUs, cloud instances, storage volumes, or compute hours.

> **The purpose of A7 is to describe the computational character of the work clearly enough that an infrastructure provider can understand why lightweight local development alone will not be sufficient.**

---

## 2. Path V Computational Character

Path V will not be a single-dataset / single-model experiment.

The workflow is expected to involve:

```text
Multiple EEG / PSG datasets
        ↓
different formats / labels / channels
        ↓
preprocessing + harmonization
        ↓
cross-dataset comparisons
        ↓
multiple model baselines and candidates
        ↓
repeated training / validation
        ↓
reduced-channel experiments
        ↓
external validation
        ↓
later real-time inference testing
```

The workload will be iterative: findings from one stage may require reprocessing data, retraining models, changing configurations, and repeating validation.

---

## 3. Main Computational Demands

The main workload classes are expected to include:

- preprocessing large EEG / PSG recordings;
- maintaining multiple standardized and derived dataset versions;
- handling cross-dataset differences in channels, annotations, populations, and recording conditions;
- training and comparing several model families;
- repeating experiments for reproducibility;
- running reduced-channel / wearable-oriented analyses;
- performing external validation across independent datasets;
- storing experiment outputs, checkpoints, logs, and intermediate representations;
- later testing real-time inference and latency behavior.

---

## 4. Current Local Development Constraint

The currently available local development environment is suitable for:

- coding;
- repository work;
- lightweight preprocessing;
- debugging;
- small-scale experiments.

However, sustained multi-dataset EEG/PSG model development, repeated training, and cross-dataset validation are expected to exceed the practical capacity of the current local machine.

Temporary notebook/cloud environments may support individual experiments, but they are not a full substitute for dependable research-compute access across an extended validation process.

---

## 5. Why Scalable Infrastructure Matters

Scalable compute should allow Neuro-TMR to:

- avoid reducing scientific scope only because of hardware limitations;
- compare models fairly;
- repeat experiments reliably;
- work with multiple datasets without constant infrastructure bottlenecks;
- preserve reproducibility across training and validation runs;
- test more realistic sensor-reduction and external-validation scenarios;
- later evaluate real-time performance under controlled conditions.

> **Compute infrastructure should prevent hardware limitations from becoming scientific limitations.**

---

## 6. Expected Outputs

The computational work should progressively support:

- reproducible EEG / PSG preprocessing;
- baseline sleep-stage models;
- cross-dataset benchmark results;
- reduced-channel / wearable-oriented validation;
- external validation results;
- documented model comparisons;
- later real-time inference / latency measurements;
- a technically grounded Path V validation report.

---

## 7. Boundary — Exact Resources Deferred

A7 intentionally does **not** define:

- GPU model or count;
- CPU count;
- RAM requirement;
- storage capacity;
- cloud instance type;
- compute hours;
- exact cost.

These should be estimated only after Path V defines the actual datasets, model families, experiment counts, and measured workload.

---

## 8. Update Rule

A7 should be updated when Path V produces enough real workload evidence to estimate infrastructure needs responsibly.

At that stage, this high-level brief can be converted into a provider-specific compute request.

---

# A7 Completion Gate

A7 is complete at the initial toolkit level when Neuro-TMR has:

- a clear explanation of the expected computational workload;
- a clear reason why local lightweight development is insufficient;
- a clear connection between compute access and scientific execution;
- no unsupported or premature infrastructure numbers;
- a boundary between current high-level justification and later exact resource sizing.

**A7 — PATH V COMPUTE REQUEST BRIEF: INITIAL HIGH-LEVEL VERSION COMPLETE**
