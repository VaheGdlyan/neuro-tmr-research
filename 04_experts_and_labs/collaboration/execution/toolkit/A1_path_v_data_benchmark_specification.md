# A1 — Path V Data & Benchmark Specification

**Toolkit:** Path E Execution Toolkit  
**Artifact:** A1  
**Status:** INITIAL / HIGH-LEVEL  
**Date:** 2026-08-21  
**Primary source:** `final_active_opportunities.md`  
**Scope:** High-level data strategy and treatment principles for future Path V engineering

---

## 1. Purpose

A1 defines the **data philosophy, resource landscape, high-level resource roles, lifecycle, and treatment principles** that will guide Neuro-TMR when Path V engineering begins.

A1 is intentionally **not** the detailed Path V implementation plan.

Its purpose is to ensure that future engineering starts from a controlled and reproducible data strategy rather than from ad-hoc dataset selection, uncontrolled preprocessing, or model-specific assumptions.

> **A1 defines how Neuro-TMR will select, organize, preserve, document, and reason about data before Path V defines the exact experiments and models.**

---

## 2. Scope Boundary

### A1 decides now

A1 defines:

- which active data / infrastructure opportunities are relevant to Path V;
- the high-level role of each resource;
- the general data lifecycle;
- dataset-selection principles;
- access and licensing principles;
- data-preservation principles;
- reproducibility principles;
- general development / validation / external-evaluation separation principles;
- treatment of labels and metadata;
- treatment of different EEG sensor/channel domains;
- the role of external models/toolboxes versus Neuro-TMR-owned inference;
- what must be deferred to the later Path V technical design.

### A1 does not decide now

The following are **explicitly deferred to Path V technical design**:

- exact dataset subsets;
- exact subject counts;
- exact train / validation / test percentages;
- exact preprocessing filters;
- exact resampling rates;
- exact epoching implementation;
- exact artifact-removal pipeline;
- exact channel selection;
- exact label-mapping implementation;
- exact model architecture;
- exact feature representation;
- exact hyperparameters;
- exact training schedule;
- exact performance thresholds;
- exact statistical analysis;
- exact causal / real-time inference implementation;
- exact TMR cue-eligibility logic;
- exact closed-loop controller architecture.

---

## 3. Active Data / Infrastructure Landscape

The active Path E portfolio contains a strong set of resources relevant to Path V.

They should not be treated as interchangeable datasets.

| OPP ID | Resource | High-Level A1 Role |
|---|---|---|
| OPP-069 | Sleep-EDF Expanded | Baseline / pipeline-development resource |
| OPP-075 | Bitbrain Open Access Sleep (BOAS) | Core wearable / reduced-channel versus reference PSG resource |
| OPP-064 | National Sleep Research Resource (NSRR) | Large-scale controlled-access sleep-data gateway |
| OPP-078A | NEMAR Research Infrastructure | Open EEG data-discovery / reproducibility / computational infrastructure |
| OPP-078B | Dreamento Open Sleep-EEG / Closed-Loop Research Toolbox | Real-time engineering reference and offline-to-online bridge |
| OPP-067 | STAGES | Multi-site / cross-center generalization resource |
| OPP-065 | Sleep Heart Health Study (SHHS) | Large-scale PSG generalization resource |
| OPP-070 | HMC Sleep Staging Database | Clinical external-validation resource |
| OPP-072 | ISRUC-Sleep | Population, repeated-night, and scorer-variability resource |
| OPP-077 | Dreem Open Datasets (DOD-H / DOD-O) | Human-scoring / label-uncertainty resource |
| OPP-076 | Ear-EEG Sleep Monitoring 2017 (EESM17) | Ear-EEG / reduced-sensor feasibility resource |
| OPP-066 | MESA Sleep | Home PSG / multimodal contextual comparison resource |
| OPP-074 | PhysioNet / CinC 2018 Sleep Arousal Dataset | Arousal / sleep-disturbance safety resource |

---

## 4. High-Level Resource Roles

### 4.1 Baseline / Pipeline Development — Sleep-EDF

Role:

> Establish a simple, reproducible sleep-staging development path before more complex, larger, or product-specific datasets are introduced.

Use at A1 level:
- pipeline-development reference;
- reproducibility baseline;
- not the primary evidence for wearable V1 feasibility.

### 4.2 Core Product-Relevant Sensor Validation — BOAS

Role:

> Provide the most direct active data opportunity for comparing wearable / reduced-channel EEG against reference PSG within the same sleep context.

Use at A1 level:
- primary product-relevant sensor-validation resource;
- kept conceptually separate from generic PSG development data.

### 4.3 Large-Scale / Cross-Cohort Generalization — NSRR / SHHS / STAGES

Role:

> Test whether future Neuro-TMR staging logic generalizes beyond one benchmark dataset, one center, or one subject population.

Use at A1 level:
- NSRR = access gateway;
- SHHS = scale/generalization;
- STAGES = multi-site/generalization;
- not all large resources should automatically become training data.

### 4.4 Clinical External Validation — HMC

Role:

> Provide a distinct clinical distribution for later external validation.

Use at A1 level:
- strong candidate for a future genuinely external test;
- should not silently become a tuning dataset after results are seen.

### 4.5 Label Uncertainty / Human Variability — DOD / ISRUC

Role:

> Prevent Neuro-TMR from treating sleep-stage annotations as perfectly objective ground truth.

Use at A1 level:
- preserve scorer/consensus information where available;
- preserve repeated-night information;
- interpret future model performance in the context of annotation variability.

### 4.6 Sensor Reduction / Alternative EEG Domain — EESM17

Role:

> Support future ear-EEG / sparse-channel feasibility analysis.

Use at A1 level:
- treat ear-EEG as a distinct sensing domain;
- exact electrode experiments are deferred to Path V.

### 4.7 Multimodal / Contextual Comparison — MESA Sleep

Role:

> Provide a secondary route for broader home / multimodal comparison.

Use at A1 level:
- useful context;
- secondary to the EEG-first V1 questions.

### 4.8 Arousal / Safety-Oriented Data — PhysioNet 2018

Role:

> Support future detection of arousal and sleep disturbance relevant to safe cue suppression.

Use at A1 level:
- separate safety-side task;
- should not distract from the first staging work.

### 4.9 Data / Compute Infrastructure — NEMAR / NSRR

Role:

> Provide access, discovery, organization, and computational pathways for Path V resources.

Use at A1 level:
- open resources first where possible;
- controlled-access resources requested in parallel;
- exact source, version, access terms, and intended role must be recorded.

### 4.10 Real-Time Engineering Reference — Dreamento

Role:

> Provide an open reference for real-time sleep EEG monitoring, event handling, stimulation, and the transition from offline analysis toward a closed-loop system.

Use at A1 level:
- Dreamento is **not** the predetermined Neuro-TMR sleep-stage architecture;
- it may serve as a reference implementation, baseline, tooling source, and engineering comparison point;
- Neuro-TMR retains control over future model selection and validation.

---

## 5. General Data Lifecycle

All Path V data should follow the same high-level lifecycle.

```text
Opportunity / Data Source
        ↓
Access + License / Use-Condition Check
        ↓
Raw Data Acquisition
        ↓
Raw Data Preservation
        ↓
Dataset Documentation + Provenance
        ↓
Standardized Internal Representation
        ↓
Experiment-Specific Derived Data
        ↓
Path V Experiment
        ↓
Evaluation Results
        ↓
Reproducibility Record
```

### Core rule

> **Raw data and original annotations remain immutable. All processing creates derived data.**

---

## 6. Data Treatment Principles

### A1-P01 — No Data Soup
Every dataset must have a defined purpose before significant effort is invested in downloading, preprocessing, or modeling it.

### A1-P02 — Preserve Raw Data
Raw EEG/PSG files, original annotations, and original metadata must never be overwritten by preprocessing.

### A1-P03 — Preserve Original Labels
Original sleep-stage labels must be retained even if Path V later creates a standardized internal label representation.

### A1-P04 — Subject-Level Separation
Future development/evaluation splits must prevent subject leakage. Different epochs or nights from the same subject must not silently appear across train and evaluation partitions.

### A1-P05 — External Validation Must Stay External
Datasets assigned an external-validation role must not later become tuning datasets simply because their results are disappointing.

### A1-P06 — Different EEG Domains Are Not Equivalent
Conventional PSG EEG, frontal wearable EEG, ear-EEG, and other reduced-channel configurations represent different sensing domains and must not be assumed equivalent.

### A1-P07 — Open First, Controlled Access in Parallel
Open resources should enable immediate engineering progress while controlled-access resources are requested early where valuable.

### A1-P08 — Every Dataset Requires Provenance
For every resource used, record at minimum:
- dataset/resource name;
- source;
- version/release;
- access date;
- license or use conditions;
- intended experimental role;
- known limitations;
- preprocessing version;
- code/configuration version.

### A1-P09 — Reproducibility Over Convenience
Every transformation from raw data to model input should eventually be reproducible from code/configuration.

### A1-P10 — Human Labels Are Not Perfect Ground Truth
Where multiple scorers, consensus labels, or repeated-night data are available, preserve that information for later interpretation of model limits.

### A1-P11 — Data Volume Does Not Equal Evidence Quality
Large datasets provide scale; smaller but product-specific datasets may provide stronger evidence for a particular V1 question.

### A1-P12 — Safety Data Remains a Distinct Task
Arousal / sleep-disturbance data should be introduced deliberately after the core staging pipeline is stable.

### A1-P13 — Model Independence
Neuro-TMR should ultimately select and validate its own sleep-stage inference architecture for V1. Existing systems may be references, baselines, reusable components, or comparison systems—not unquestioned dependencies.

### A1-P14 — Benchmark Before Model Preference
The future Path V benchmark should be defined independently of the final model architecture.

### A1-P15 — Data Decisions Must Remain Auditable
If a dataset role, access condition, preprocessing rule, or evaluation role changes later, document the change rather than silently overwriting the earlier decision.

---

## 7. Conceptual Internal Data Organization

```text
data/
├── raw/
│   ├── sleep_edf/
│   ├── boas/
│   ├── hmc/
│   └── ...
│
├── metadata/
│   ├── dataset_registry.md
│   ├── licenses/
│   └── access_notes/
│
├── derived/
│   ├── standardized/
│   └── experiment_specific/
│
└── splits/
    └── [future Path V split definitions]
```

This is conceptual only. The exact Path V repository layout is deferred.

---

## 8. Dataset Registry Requirement

Before a dataset becomes part of a formal Path V experiment, it should have a registry entry containing:

| Field | Purpose |
|---|---|
| Dataset | Canonical resource name |
| OPP ID | Path E lineage |
| Source / Host | Where it was obtained |
| Access Type | Open / account / approval / other |
| License / Use Terms | Reuse constraints |
| Intended Role | Why Neuro-TMR needs it |
| Sensor Domain | PSG / wearable / ear-EEG / multimodal / etc. |
| Label Type | Original scoring / annotation source |
| External-Test Status | Whether the dataset must remain untouched during development |
| Known Limitations | Issues already identified |
| Version | Exact dataset release |
| Access Date | When Neuro-TMR obtained it |
| Path V Status | Not accessed / available / prepared / active / completed |

---

## 9. High-Level Evaluation Separation

A1 does not define exact benchmarks yet, but fixes one structural principle:

> **Development evidence and external-validation evidence must remain distinguishable.**

Future Path V planning should preserve separate roles for:

1. development / pipeline testing;
2. product-relevant sensor validation;
3. large-scale / cross-site generalization;
4. clinical external validation;
5. label / scorer uncertainty;
6. sensor-reduction experiments;
7. safety / arousal analysis.

---

## 10. Neuro-TMR Data Philosophy

> **Use the smallest sufficient set of datasets to answer each scientific or engineering question rigorously, preserve truly external tests, and expand the data universe only when a new question requires it.**

The objective is not to maximize the number of datasets.

The objective is to produce trustworthy evidence about the feasibility and limits of the EEG-based Neuro-TMR V1.

---

## 11. Relationship to Path V

A1 is a **Path E execution-toolkit artifact**.

It provides principles that future Path V technical documentation should inherit.

When Path V formally begins, deeper technical documents may be created, for example:

```text
validation_lite/
├── DATASET_PLAN.md
├── PREPROCESSING_SPEC.md
├── LABEL_HARMONIZATION.md
├── SPLIT_PROTOCOL.md
├── MODELING_PLAN.md
├── BENCHMARK_PROTOCOL.md
├── REALTIME_INFERENCE_SPEC.md
└── PATH_V_RESULTS.md
```

These documents may deepen A1 but should not contradict its core principles without a documented reason.

---

## 12. Update Rule

A1 should be updated only when:

- a new active data/infrastructure opportunity materially expands Path V capability;
- an existing resource becomes inaccessible or materially changes;
- Path V discovers that a high-level data principle is technically invalid;
- a collaboration provides a new resource that changes the benchmark architecture;
- a documented methodological correction is necessary.

Routine model experimentation should not continuously rewrite A1.

---

# A1 Completion Gate

A1 is complete at the execution-toolkit level when Neuro-TMR has:

- a clear map of the active data / infrastructure landscape;
- a high-level role for each relevant resource;
- a common data lifecycle;
- explicit data-preservation and reproducibility principles;
- clear rules against leakage and uncontrolled dataset mixing;
- a separation between development and external validation;
- a model-independence principle;
- a clear boundary between A1 and future Path V technical design.

**A1 — PATH V DATA & BENCHMARK SPECIFICATION: INITIAL HIGH-LEVEL VERSION COMPLETE**
