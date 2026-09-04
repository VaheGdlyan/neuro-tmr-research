# Path V — Immediate Opportunity Execution

**Date:** 2026-09-04  
**Project:** Neuro-TMR / Neuroscience Product Project  
**Phase:** Phase II — Path V / Validation-Lite  
**Status:** ACTIVE — PRE-PATH V COMPLETE, PATH V READY  
**Source universe:** 14 opportunities previously classified as `PATH_V`  
**Primary related documents:**

- `path_e_execution_phase_classification.md`
- `final_active_opportunities.md`
- `A6_execution_tracker.md`
- Neuro-TMR 11 continuation state, 2026-09-04

---

## 1. Purpose

This document converts the earlier **14-opportunity Path V classification** into the actual **2026-09-04 immediate execution order**.

It does **not**:

- re-run Path E discovery;
- re-score the 53 active opportunities;
- reopen Pre-Path V;
- require all 14 Path V opportunities to be used;
- turn every dataset into training data;
- force hardware procurement before a software/control need exists;
- replace the scientific/engineering Path V protocol.

Its purpose is narrower:

> **Distinguish which Path V opportunities are required now, which become useful only after the first evidence exists, which are external/triggered, which are optional scientific extensions, and which should deliberately remain inactive.**

The governing principle remains:

> **EVIDENCE BEFORE ENGINEERING.**

The immediate Path V objective is not to maximize opportunity usage. It is to use the **smallest sufficient opportunity set** that can answer the first-generation Neuro-TMR questions rigorously.

---

# 2. Why the August Path V Sequence Must Be Refined

The original 2026-08-21 classification proposed the following broad sequence:

```text
Sleep-EDF baseline
        ↓
BOAS reduced-sensor validation
        ↓
Dreamento + SCCN/LSL + OpenBCI reference/prototype work
        ↓
SHHS / STAGES / HMC external/generalization tests
        ↓
ISRUC / DOD uncertainty & variability
        ↓
EESM17 sensor-reduction extension
        ↓
PhysioNet arousal safety-side work
        ↓
SleepLoopFM outreach after a first concrete baseline/result
```

That sequence was reasonable **before** Pre-Path V execution.

However, important evidence now exists that did not exist when the sequence was written:

1. NEMAR/BOAS ingestion is already implemented and regression-tested.
2. BOAS EDA is already complete.
3. BOAS has been judged `READY WITH CONSTRAINTS`.
4. Real participant identity (`pid`) and repeated-night structure are already understood.
5. N3 prevalence and N3 failure modes are already quantified.
6. SHHS and STAGES access requests are already submitted and waiting for review.
7. STAGES has been explicitly protected from routine tuning.
8. MESA has been moved to `RESERVE ONLY`.
9. The project already has a Python/MNE engineering stack; replacing it with an EEGLAB-centered stack is not justified.
10. Real hardware is not yet required to answer the first offline validation questions.

Therefore:

> **The old Path V classification remains strategically valid, but its original sequencing is no longer the optimal immediate engineering sequence.**

The most important consequence is:

> **Neuro-TMR should NOT restart with Sleep-EDF merely because it was originally called the first baseline dataset. BOAS is now the more rational starting point because the ingestion, label semantics, structural validation and EDA foundation already exist and BOAS directly tests the central V1 reduced-sensor question.**

Sleep-EDF remains useful as a contingency/reference resource, but it no longer deserves to delay the BOAS Path V core.

---

# 3. Current Path V Opportunity Classes

The 14 opportunities are now divided into seven practical classes.

| Class | Meaning | Opportunities |
|---|---|---|
| **P0 — CORE NOW** | Must drive the first actual Path V evidence cycle | OPP-075 BOAS |
| **P1 — EARLY ENGINEERING REFERENCES** | Use selectively after the offline baseline contract exists; do not adopt blindly | OPP-078B Dreamento; OPP-016 SCCN / LSL |
| **P2 — BASELINE-TRIGGERED SCIENTIFIC INPUT** | Activate only after a concrete first result creates a precise question | OPP-020 SleepLoopFM |
| **P3 — GENERALIZATION / EXTERNAL EVIDENCE** | Use after the BOAS baseline is substantially frozen | OPP-065 SHHS; OPP-067 STAGES; OPP-070 HMC |
| **P4 — CONDITIONAL SCIENTIFIC EXTENSIONS** | Valuable only when the first Path V evidence exposes the corresponding uncertainty | OPP-077 DOD; OPP-072 ISRUC; OPP-076 EESM17; OPP-074 PhysioNet Arousal |
| **P5 — HARDWARE-TRIGGERED** | Do not activate until software replay defines an actual acquisition/streaming requirement | OPP-123 OpenBCI |
| **P6 — RESERVE / CONTINGENCY** | Preserve, but do not spend active effort now | OPP-069 Sleep-EDF; OPP-066 MESA |

This classification is an **execution refinement**, not a re-ranking of the 53-opportunity Path E portfolio.

---

# 4. Immediate Decision Summary

| OPP ID | Opportunity | Current Path V Role | Execute Now? | Activation Trigger | Core Path V Requirement? |
|---|---|---|:---:|---|:---:|
| **OPP-075** | BOAS | Primary development + reduced-sensor evidence core | **YES** | Path V start | **YES** |
| **OPP-078B** | Dreamento | Closed-loop architecture/reference system | NO | Stable offline baseline + controller design begins | PARTIAL |
| **OPP-016** | SCCN / EEGLAB / LSL | Selective streaming/synchronization tooling reference | NO | Real-time replay / event-stream stage | PARTIAL |
| **OPP-020** | SleepLoopFM | External sparse-EEG / causal real-time methods challenge | NO | First concrete baseline/gating result | NO |
| **OPP-065** | SHHS | Large-scale robustness/generalization | NO | NSRR approval + baseline frozen enough to test | LATER |
| **OPP-067** | STAGES | Protected multi-site clinical external validation | NO | NSRR approval + model/controller configuration frozen | **LATER / PROTECTED** |
| **OPP-070** | HMC | Open clinical external-test fallback | NO | Baseline frozen; use if external evidence is needed before STAGES is available | LATER |
| **OPP-077** | DOD-H / DOD-O | Multi-scorer label uncertainty/calibration analysis | NO | Calibration/abstention uncertainty becomes a material question | OPTIONAL |
| **OPP-072** | ISRUC-Sleep | Repeated-night + two-scorer + clinical variability extension | NO | Specific variability question remains after core evidence | OPTIONAL |
| **OPP-076** | EESM17 | Alternative ear-EEG sensing-domain extension | NO | BOAS frontal/reduced-channel question already answered | OPTIONAL |
| **OPP-074** | PhysioNet 2018 Arousal | Dedicated arousal/sleep-disturbance safety branch | NO | Controller requires explicit arousal-risk detector/evaluation | OPTIONAL / SAFETY |
| **OPP-123** | OpenBCI | Real hardware acquisition/streaming prototype | NO | Software replay passes + concrete hardware need exists | TRIGGERED |
| **OPP-069** | Sleep-EDF Expanded | Pipeline contingency / classical benchmark reference | NO | BOAS pipeline unexpectedly blocks baseline work or a cross-check is specifically needed | RESERVE |
| **OPP-066** | MESA Sleep | Home/multimodal contextual comparison | NO | New question specifically requires home PSG/actigraphy context | **RESERVE** |

---

# 5. P0 — CORE NOW

## OPP-075 — Bitbrain Open Access Sleep (BOAS)

### Current decision

> **START PATH V HERE.**

BOAS is the only opportunity that should be considered **immediately active by default** at the beginning of Path V.

### Why BOAS is now the correct first resource

BOAS uniquely combines:

- simultaneous reference PSG and wearable/headband EEG;
- expert-consensus sleep-stage labels;
- repeated-night structure that has already been mapped to real `pid` identity;
- existing Neuro-TMR ingestion code;
- existing regression tests;
- completed engineering EDA;
- known N3 scarcity and failure modes;
- direct relevance to the first-generation reduced-sensor question.

The central V1 question is not simply:

> Can a model classify sleep stages?

It is closer to:

> Can EEG-based state estimation — especially N3 estimation — become sufficiently trustworthy to gate a later acoustic intervention, and what is lost when sensing is reduced?

BOAS is currently the best active resource for that question.

### Current evidence already established

Neuro-TMR's direct BOAS analysis has established:

- 128 recording nights;
- 100 real participants under the dataset's `pid` identity semantics;
- participant-aware splits must use `pid`;
- ~120k scored epochs;
- N3 is a minority class (~4.36%);
- N3 exists in enough participants/nights to remain a meaningful target;
- existing PSG-AI and headband-AI aggregate agreement can look similar while usable N3 performance differs materially;
- headband EEG and PSG EEG are not interchangeable sensing domains;
- signal-quality and unavailable/special outputs matter.

A public NEMAR landing page currently describes BOAS as 128 nights from 108 unique participants. Neuro-TMR's direct inspection of the released participant mapping found 100 unique real `pid` values. For Path V splitting, the direct dataset identity field that has already been validated by Neuro-TMR remains the operative source. This discrepancy should be preserved rather than silently erased.

### What BOAS should do in Path V

BOAS should support the first evidence cycle:

1. participant-aware train/validation/test design;
2. a reproducible EEG staging baseline;
3. explicit N3 performance analysis;
4. full PSG-EEG versus reduced PSG-EEG comparison;
5. true headband-domain comparison;
6. confidence/calibration/coverage analysis if justified;
7. causal offline replay using prerecorded data;
8. controller-oriented analysis after raw classifier behavior is understood.

### What BOAS should NOT trigger immediately

Do not:

- bulk-download the full dataset merely because it is open;
- train a large deep model first;
- use test participants during threshold/model selection;
- assume headband channels equal frontal PSG channels;
- optimize solely for overall accuracy;
- move directly into cueing before the state-estimation evidence is understood.

### First immediate Path V action

> **PV-0 — participant-aware split and evaluation-feasibility audit.**

Use already-available BOAS metadata/annotations to freeze the evaluation foundation before acquiring additional raw data.

The first Path V artifact should contain, at minimum:

```text
pid
→ contributing sub-* nights
→ total scored epochs
→ standard-stage epochs
→ N3 presence
→ N3 epoch count
→ per-stage distribution
→ proposed train / validation / internal-test membership
```

Only after that split is scientifically inspected and frozen should additional raw BOAS recordings be selectively fetched for the first baseline experiment.

### Immediate status

> **OPP-075 → ACTIVATE NOW / CORE PATH V RESOURCE**

---

# 6. P1 — EARLY ENGINEERING REFERENCES

These resources are useful, but they should **not** become the architecture simply because open tooling exists.

The rule is:

> **First define Neuro-TMR's own validation contract; then inspect external tools for ideas, interfaces, timing patterns and failure modes.**

---

## OPP-078B — Dreamento Open Sleep-EEG / Closed-Loop Research Toolbox

### Correct role

> **Real-time closed-loop engineering reference — not the Neuro-TMR model and not the first Path V task.**

Dreamento is especially relevant because it already connects several components Neuro-TMR will eventually need:

- real-time EEG monitoring;
- automatic sleep staging;
- event/annotation handling;
- sensory stimulation;
- offline post-processing;
- sleep microstructure detection;
- confidence-like sleep-stage probability outputs.

Its own documentation explicitly presents real-time autoscoring as still under development and warns about generalization limitations, including dependence on good two-channel EEG quality and training characteristics. That is precisely why Dreamento should be treated as an **engineering reference**, not as validated evidence that its inference path is sufficient for Neuro-TMR.

### When to activate

Activate after:

1. the BOAS split is frozen;
2. the first offline baseline contract exists;
3. the project knows what its own inference API and controller interface need to look like.

### What to extract from Dreamento

Inspect specifically:

- data-flow architecture;
- real-time buffering;
- stage-output interface;
- probability/confidence representation;
- event-marker handling;
- stimulation triggering path;
- modular separation between inference and stimulation;
- logging/timestamps;
- how offline and online modes are separated.

### What NOT to do

Do not:

- install/integrate Dreamento before the baseline design is frozen;
- inherit its classifier as the default Neuro-TMR classifier;
- treat its ZMax-oriented assumptions as device-independent;
- use Dreamento performance as evidence of Neuro-TMR performance.

### Status

> **OPP-078B → EARLY REFERENCE / ACTIVATE AFTER FIRST OFFLINE BASELINE CONTRACT**

---

## OPP-016 — Swartz Center for Computational Neuroscience / EEGLAB / LSL

### Correct role

The original classification grouped SCCN, EEGLAB and LSL as a broad Path V tooling opportunity.

The current engineering stack changes the interpretation:

- Neuro-TMR already uses Python + MNE;
- replacing preprocessing with an EEGLAB/Matlab-centered stack would add unnecessary divergence;
- LSL remains highly relevant for later streaming, timestamping and event transport.

Therefore the current role is narrower:

> **Use SCCN/LSL concepts selectively for real-time streaming and synchronization; do not replace the existing Python/MNE offline stack without evidence.**

### Why LSL matters later

LSL provides:

- unified live time-series streaming;
- timestamps;
- clock-offset information;
- near-real-time access;
- multi-stream recording via XDF/LabRecorder;
- Python interfaces through `pylsl`.

Its documentation also makes an important distinction for Neuro-TMR:

> online applications often care primarily about low latency; synchronization is a separate problem that becomes essential when events and streams must be aligned.

That distinction should later inform the latency audit.

### When to activate

Activate when Path V reaches:

> **offline model → causal prerecorded replay → stream/event interface**

This is later than the first staging baseline.

### First likely use

Start with a **synthetic or prerecorded EEG LSL stream**, not real hardware.

This allows Neuro-TMR to validate:

```text
stream
→ buffer/window
→ preprocessing
→ inference
→ eligibility decision
→ event timestamp
→ dummy trigger
```

before hardware variables are introduced.

### Status

> **OPP-016 → SELECTIVE REAL-TIME TOOLING / NOT AN IMMEDIATE PREPROCESSING MIGRATION**

---

# 7. P2 — BASELINE-TRIGGERED SCIENTIFIC INPUT

## OPP-020 — SleepLoopFM / Sensory-Motor Systems Lab, ETH Zurich

### Correct role

SleepLoopFM is one of the most conceptually aligned external opportunities because its current research direction explicitly concerns:

- sparse wearable EEG;
- real-time sleep staging;
- temporal context;
- immediate closed-loop intervention.

This is close to the Neuro-TMR boundary between:

> **sleep-stage inference → intervention eligibility**

### Why it should NOT be contacted immediately

Contact before Neuro-TMR has a result would produce a broad conceptual conversation.

Contact after a first baseline can produce a specific methodological question such as:

- how much temporal context is necessary causally?
- how should sparse-EEG confidence be treated near transitions?
- what evidence is required before a stage estimate gates intervention?
- how should online performance differ from retrospective staging evaluation?

### Activation trigger

> **First concrete BOAS baseline + N3/gating failure mode.**

The project should then formulate **one precise question** grounded in its own result.

### Status

> **OPP-020 → TRIGGER AFTER FIRST BASELINE EVIDENCE**

It does not block Path V start.

---

# 8. P3 — GENERALIZATION / EXTERNAL EVIDENCE

These opportunities should not become active training resources merely because they contain more data.

The correct sequence is:

```text
BOAS development + internal test
        ↓
substantially freeze model / preprocessing / controller assumptions
        ↓
then obtain external/generalization evidence
```

---

## OPP-065 — Sleep Heart Health Study (SHHS)

### Current role

> **Large-scale PSG robustness and cross-subject/acquisition-domain generalization.**

SHHS is extremely large relative to BOAS. NSRR documentation provides raw PSG for thousands of recordings/participants across two visits, with standardized scoring infrastructure.

That scale is valuable — but scale alone does not answer the reduced-sensor product question.

### Current state

Access request:

> **SUBMITTED / UNDER REVIEW**

No raw SHHS data should be downloaded until access is approved and a specific Path V experiment exists.

### Correct Path V use

Preferred role:

- test generalization of a BOAS-derived staging representation;
- evaluate participant-level robustness;
- study acquisition-domain shift;
- potentially support secondary development/pretraining only if explicitly justified.

### Critical boundary

If SHHS is used for:

- training;
- fine-tuning;
- threshold selection;
- representation learning;
- repeated hyperparameter selection;

then it is **not** an untouched final external test.

### Status

> **OPP-065 → WAIT FOR APPROVAL; LATE PATH V ROBUSTNESS RESOURCE**

---

## OPP-067 — STAGES

### Current role

> **Protected multi-site / clinical external generalization resource.**

STAGES is particularly valuable because it was collected across multiple sites/centers and includes clinically heterogeneous sleep evaluations.

Current NSRR documentation describes approximately 1,500 adult/adolescent patients across 20 data-collection sites from six centers.

### Current state

Access request:

> **SUBMITTED / UNDER REVIEW**

### Strong protection rule

> **DO NOT use STAGES for routine model tuning.**

The goal is to preserve its value as a strong external test of:

- site shift;
- center shift;
- clinical heterogeneity;
- acquisition-domain heterogeneity;
- N3 behavior outside BOAS.

### Site-aware caution

Current NSRR documentation includes a historical warning that Mayo Clinic PSGs were removed from the shared set because of EDF/annotation conversion issues pending reprocessing.

Therefore, if STAGES is approved and later activated:

1. inspect the then-current site availability;
2. preserve site/center identifiers;
3. document exclusions;
4. report site-aware performance;
5. avoid pooling away major site differences.

### Activation trigger

> **A substantially frozen Path V staging/controller configuration.**

### Status

> **OPP-067 → PROTECTED EXTERNAL TEST / DO NOT TOUCH EARLY**

---

## OPP-070 — HMC Sleep Staging Database

### Current role

> **Open clinical external-test fallback / supplemental external validation.**

HMC contains 151 whole-night clinical PSG recordings from a heterogeneous population referred for sleep-disorder evaluation and is openly available through PhysioNet.

This makes HMC strategically useful because it does not depend on NSRR approval.

### Why HMC matters now

HMC prevents a bad project dynamic:

> waiting for STAGES approval before Path V can obtain any external clinical evidence.

### Activation rule

Do **not** download HMC now.

After the BOAS baseline is substantially frozen:

- if STAGES is available and ready for protected evaluation, STAGES can remain the stronger multi-site external test;
- if STAGES remains unavailable/delayed, HMC becomes the preferred open clinical fallback;
- if the scientific question specifically needs a second clinical distribution, HMC can supplement STAGES later.

### Critical boundary

Once HMC is designated an external test for a specific model cycle:

> do not tune repeatedly against HMC results.

### Status

> **OPP-070 → OPEN EXTERNAL FALLBACK / ACTIVATE ONLY AFTER BOAS BASELINE FREEZE**

---

# 9. P4 — CONDITIONAL SCIENTIFIC EXTENSIONS

These opportunities can improve Path V evidence, but they are **not all required for Path V success**.

Their purpose is to answer specific residual questions, not to inflate the number of datasets.

---

## OPP-077 — Dreem Open Datasets (DOD-H / DOD-O)

### Unique value

DOD is stronger than a conventional single-label benchmark for one specific reason:

> **multiple expert scorers.**

Published descriptions report:

- DOD-H: 25 healthy participants;
- DOD-O: 55 participants with obstructive sleep apnea;
- five sleep technologists from different sleep centers scoring each dataset.

This makes DOD especially useful for studying:

- label uncertainty;
- scorer disagreement;
- consensus versus single-label evaluation;
- calibration around ambiguous epochs;
- transition uncertainty;
- abstention policies.

### When to activate

Only if the BOAS baseline reaches a point where questions such as these become material:

> Is model uncertainty actually tracking human disagreement?

> Are low-confidence predictions concentrated near genuine scorer ambiguity?

> Should controller abstention distinguish model uncertainty from label uncertainty?

### Why not now

Adding DOD before the first BOAS baseline would introduce:

- another ingestion path;
- another signal domain;
- another preprocessing problem;
- another evaluation protocol;

before the primary V1 question has been tested.

### Status

> **OPP-077 → HIGH-VALUE OPTIONAL UNCERTAINTY BRANCH**

---

## OPP-072 — ISRUC-Sleep

### Unique value

ISRUC includes:

- multiple cohorts;
- clinical and healthy subjects;
- two expert scorers;
- a small repeated-night subgroup;
- multi-signal PSG.

Its repeated-night and dual-scorer structure could support:

- night-to-night stability;
- scorer variability;
- clinical-distribution analysis.

### Why it is lower priority than DOD for uncertainty

DOD provides five-scorer annotations specifically designed for inter-rater comparison, making it more directly aligned with label-uncertainty questions.

ISRUC's value is therefore more specific:

> repeated-night + cohort/clinical variability.

### Activation trigger

Use only if Path V produces a concrete question that BOAS + external generalization + DOD cannot answer efficiently.

### Status

> **OPP-072 → OPTIONAL VARIABILITY EXTENSION**

---

## OPP-076 — Ear-EEG Sleep Monitoring 2017 (EESM17)

### Unique value

EESM17 contains nightly recordings from 9 healthy participants with:

- partial PSG;
- EEG/EOG/chin EMG;
- 14 ear-EEG electrodes.

It is useful for one narrow question:

> **Can sleep-state information survive in an alternative sparse/ear-EEG sensing domain?**

### Why it is NOT a current V1 validation dataset

Neuro-TMR's immediate reduced-sensor question is currently grounded in BOAS frontal wearable/headband EEG.

Ear-EEG is a different sensing geometry and acquisition domain.

Therefore:

> a good EESM17 result would not prove BOAS headband sufficiency, and a poor EESM17 result would not disprove frontal wearable EEG.

The dataset is also small, so it should not drive first-generation conclusions.

### Activation trigger

Only after BOAS has answered the primary full-versus-reduced frontal EEG question.

### Status

> **OPP-076 → OPTIONAL ALTERNATIVE-SENSOR EXTENSION**

---

## OPP-074 — PhysioNet / CinC 2018 Sleep Arousal Dataset

### Unique value

The PhysioNet 2018 challenge provides a dedicated large-scale arousal/sleep-disturbance task with sleep-stage and arousal annotations.

This is relevant to the long-term controller question:

> **Should cues be suppressed when signs of arousal/sleep disturbance are present?**

### Why it is NOT immediate

The full resource is extremely large — roughly 266.6 GB uncompressed across training and test sets — and would introduce a separate prediction problem before the core sleep-state gating problem is solved.

Current Neuro-TMR expert guidance makes arousal prevention scientifically important, but Path V has not yet frozen an explicit arousal detector as a first-cycle requirement.

Therefore:

> safety importance does not justify prematurely building a second large ML task.

### Activation trigger

Activate only when the controller architecture reaches a concrete decision such as:

- explicit arousal gating is required;
- sleep-preservation monitoring becomes part of the Validation-Lite stopping criteria;
- a specific arousal-risk metric must be tested.

If activated, begin with a documented small subset/sample and task definition — not the full 266+ GB acquisition.

### Status

> **OPP-074 → CONDITIONAL SAFETY BRANCH / NOT PART OF THE FIRST STAGING BASELINE**

---

# 10. P5 — HARDWARE-TRIGGERED

## OPP-123 — OpenBCI Cyton / Ganglion Open Hardware Ecosystem

### Correct role

> **Potential real EEG acquisition/streaming platform after the software loop is proven.**

OpenBCI is valuable because its ecosystem supports:

- raw EEG streaming;
- Python/BrainFlow integration;
- LSL streaming;
- real-time visualization and recording;
- relatively open developer access.

### Why hardware should not start Path V

Real hardware adds new variables:

- electrode contact quality;
- device-specific filtering;
- wireless transport;
- driver behavior;
- clock/timestamp behavior;
- packet buffering;
- hardware availability/cost;
- real participant acquisition issues.

None of those are necessary to answer the first offline question:

> Can our inference/control assumptions survive participant-held-out evaluation on known labeled EEG?

### Correct sequence

```text
BOAS offline baseline
        ↓
causal prerecorded replay
        ↓
software stream + timestamped dummy trigger
        ↓
measured software latency
        ↓
ONLY THEN decide whether real hardware adds necessary evidence
```

### Interaction with OPP-039 Engineering City

If Engineering City replies and provides a credible EEG acquisition/streaming route, Path V should compare that concrete local capability against the OpenBCI route rather than buying hardware automatically.

### Status

> **OPP-123 → HARDWARE TRIGGER WAIT**

Do not purchase or integrate an OpenBCI board at Path V start.

---

# 11. P6 — RESERVE / CONTINGENCY

## OPP-069 — Sleep-EDF Expanded

### Original role

The August plan assigned Sleep-EDF as:

> the first simple reproducible sleep-staging baseline.

### Updated role

That role has been overtaken by actual Pre-Path V progress.

BOAS already has:

- a working Neuro-TMR ingestion API;
- validated sleep-stage semantics;
- participant identity mapping;
- EDA;
- direct reduced-sensor relevance.

Starting Sleep-EDF first would now require a separate ingestion/standardization branch before answering the more important BOAS question.

### When Sleep-EDF remains useful

Keep it as:

- a classical open benchmark reference;
- a smoke-test contingency if BOAS raw acquisition unexpectedly blocks the first model cycle;
- a reproducibility cross-check if a later methodological question specifically benefits from it.

### What it should not do

It should not delay BOAS simply to preserve the historical August sequence.

### Status

> **OPP-069 → CONTINGENCY / NOT CURRENT FIRST BASELINE**

This is a sequencing refinement, not a claim that Sleep-EDF is scientifically unimportant.

---

## OPP-066 — MESA Sleep

### Current role

The latest A6 state already freezes MESA as:

> **RESERVE ONLY**

This supersedes the older broad Path V classification.

MESA provides valuable home PSG, actigraphy and contextual multimodal data, but the immediate V1 question is EEG-first stage-aware control.

### Activation trigger

Only activate if Path V creates a concrete question that specifically needs:

- home-context comparison;
- actigraphy overlap;
- broader multimodal context;
- demographic/generalization information not already addressed by the chosen core/external datasets.

### Status

> **OPP-066 → RESERVE / NO CURRENT ACTION**

---

# 12. Revised Path V Opportunity Road

The practical Path V road should now be:

```text
                         PATH V — VALIDATION-LITE

          ┌─────────────────────────────────────────┐
          │ P0 — BOAS CORE                          │
          │ participant split → baseline → N3       │
          │ → reduced-channel evidence              │
          └─────────────────────┬───────────────────┘
                                ↓
          ┌─────────────────────────────────────────┐
          │ FIRST EVIDENCE REVIEW                   │
          │ what failed? what remains uncertain?    │
          └───────────────┬───────────────┬─────────┘
                          │               │
                          ↓               ↓
        ┌───────────────────────┐   ┌───────────────────────┐
        │ P1 REAL-TIME REFERENCES│   │ P2 SCIENTIFIC TRIGGER│
        │ Dreamento + LSL/SCCN  │   │ SleepLoopFM question │
        └───────────┬───────────┘   └───────────────────────┘
                    ↓
        ┌───────────────────────────────┐
        │ CAUSAL REPLAY + LATENCY       │
        │ software stream → dummy cue   │
        └───────────────┬───────────────┘
                        ↓
        ┌──────────────────────────────────────────┐
        │ P3 GENERALIZATION                        │
        │ SHHS robustness if approved              │
        │ STAGES protected external if approved    │
        │ HMC open external fallback               │
        └───────────────┬──────────────────────────┘
                        ↓
        ┌──────────────────────────────────────────┐
        │ P4 CONDITIONAL EXTENSIONS                 │
        │ DOD / ISRUC / EESM17 / Arousal           │
        │ ONLY when evidence creates the question  │
        └───────────────┬──────────────────────────┘
                        ↓
        ┌──────────────────────────────────────────┐
        │ P5 REAL HARDWARE                         │
        │ OpenBCI or local partner only if needed  │
        └──────────────────────────────────────────┘

RESERVE THROUGHOUT:
Sleep-EDF contingency / MESA reserve
```

---

# 13. What Path V Must NOT Become

The 14-opportunity portfolio must not accidentally turn Validation-Lite into a multi-year benchmark program.

Do not interpret `PATH_V` as:

> use every dataset, install every toolbox, contact every lab, buy hardware, train multiple large models, and then decide whether the concept works.

That would violate the project principle.

Instead:

> **Each opportunity must earn activation by answering a currently unresolved Path V question.**

### Anti-sprawl rules

1. **One primary development dataset at a time.**
   - Start with BOAS.

2. **One protected external role per dataset.**
   - Do not let external tests become silent tuning sets.

3. **Do not add a dataset just because access is easy.**
   - New data must answer a new question.

4. **Do not add hardware until software replay creates a hardware requirement.**

5. **Do not adopt external model/toolbox architecture by default.**
   - Dreamento/SCCN/OpenBCI are references/resources, not governance over Neuro-TMR design.

6. **Do not let optional uncertainty/safety extensions block core completion.**

7. **Do not wait for external replies when the next internal experiment is already justified.**

---

# 14. Path V Opportunity Activation Gates

## Gate V-O1 — BOAS Core Gate

Required before leaving the first opportunity stage:

- participant-aware split frozen;
- raw acquisition plan defined from the split;
- first reproducible baseline completed;
- N3-specific metrics reported;
- reduced-channel comparison defined or completed;
- limitations documented.

If this gate fails because the data/pipeline cannot support the experiment, only then should Sleep-EDF or another resource be activated as a troubleshooting/reference branch.

---

## Gate V-O2 — Real-Time Reference Gate

Activate Dreamento and SCCN/LSL when:

- offline inference interface exists;
- causal information boundary is defined;
- controller input/output contract is known.

Goal:

> learn from existing real-time architectures without inheriting their unvalidated assumptions.

---

## Gate V-O3 — External Generalization Gate

Activate one or more of SHHS/STAGES/HMC when:

- BOAS preprocessing is frozen enough to reproduce;
- model family/configuration is substantially frozen;
- evaluation metrics are frozen;
- leakage controls are documented.

Preference:

1. SHHS for large-scale robustness if approved;
2. STAGES for protected multi-site external evidence if approved;
3. HMC as the open clinical fallback if a protected external result is needed before STAGES can be used.

Do not require all three in the first cycle.

---

## Gate V-O4 — Optional Extension Gate

Activate DOD, ISRUC, EESM17 or PhysioNet Arousal only when the evidence package contains a specific unresolved question:

| Question | Preferred Resource |
|---|---|
| Is uncertainty related to human scorer disagreement? | DOD |
| How stable is performance across nights / scorers / clinical cohorts? | ISRUC |
| Does the result extend to a different sparse ear-EEG domain? | EESM17 |
| Does the controller require explicit arousal/sleep-disturbance suppression? | PhysioNet 2018 |

No unresolved question → no activation.

---

## Gate V-O5 — Hardware Gate

Activate OpenBCI or another real EEG device only when:

- software replay works;
- latency is measured in software;
- the next uncertainty is genuinely acquisition/hardware-related;
- a concrete device comparison requirement exists.

If OPP-039 Engineering City becomes available, that local capability should be assessed before automatically procuring OpenBCI.

---

# 15. External Replies That May Modify This Road

The current road must remain stable enough to execute but flexible to evidence.

The following asynchronous Pre-Path V opportunities may modify specific gates without stopping Path V:

### OPP-015 — Michael Chee / NUS

Possible impact:

- N3 precision requirement;
- confidence/calibration;
- abstention;
- temporal stability;
- transition handling;
- reduced-sensor sufficiency.

If useful guidance arrives:

> convert it into an explicit Path V metric, experiment or guardrail.

### OPP-039 — Engineering City Neurotechnology Laboratory

Possible impact:

- real EEG acquisition path;
- streaming interface;
- event markers;
- synchronization;
- latency test;
- OpenBCI necessity.

A strong local capability could replace or postpone the OpenBCI branch.

### OPP-031 — COBRAIN / YSMU

Possible impact:

- scientific hosting;
- mentorship;
- institutional pathway;
- later ethics/governance;
- Post-Path V human-validation route.

It should not change the immediate BOAS baseline.

### OPP-064 — NSRR

Possible impact:

- SHHS/STAGES become technically available.

Approval means:

> **inspect metadata/manifests first — not bulk download.**

---

# 16. First Actual Execution Command

With the opportunity portfolio refined, the first Path V opportunity action is now unambiguous:

> **ACTIVATE OPP-075 — BOAS as the Path V core.**

The first experiment is not model training.

It is:

> **PV-0 — BOAS participant-aware split and evaluation-feasibility audit.**

### PV-0 objective

Create and inspect a deterministic real-participant split using `pid`, preserving repeated nights and ensuring that N3 is meaningfully represented in train, validation and internal-test partitions.

### PV-0 should use

- existing BOAS metadata;
- existing event annotations;
- existing validated ingestion/EDA knowledge.

### PV-0 should NOT require

- new dataset discovery;
- Sleep-EDF ingestion;
- SHHS/STAGES approval;
- Dreamento installation;
- OpenBCI hardware;
- additional BOAS bulk download;
- model training.

### After PV-0

Only after inspecting the split do we define:

1. the first selective raw BOAS acquisition set;
2. the exact baseline input domain;
3. preprocessing contract;
4. baseline classifier;
5. metrics and N3 controller-facing analyses.

---

# 17. Final Opportunity Decisions

## START NOW

### OPP-075 — BOAS

> **Primary Path V core. Begin here.**

---

## USE EARLY, BUT ONLY AFTER THE OFFLINE BASELINE CONTRACT

### OPP-078B — Dreamento

> real-time closed-loop architecture/reference.

### OPP-016 — SCCN / LSL

> selective streaming, timestamp and synchronization tooling; preserve Python/MNE offline stack.

---

## ACTIVATE AFTER FIRST CONCRETE RESULT

### OPP-020 — SleepLoopFM

> ask one evidence-backed sparse-EEG / causal-gating question.

---

## ACTIVATE FOR GENERALIZATION AFTER BASELINE FREEZE

### OPP-065 — SHHS

> large-scale robustness if approved.

### OPP-067 — STAGES

> protected multi-site clinical external test if approved; no routine tuning.

### OPP-070 — HMC

> open clinical external fallback/supplement; do not tune against it once assigned as test.

---

## OPTIONAL EXTENSIONS — ONLY IF A SPECIFIC QUESTION APPEARS

### OPP-077 — DOD

> scorer disagreement / label uncertainty / calibration.

### OPP-072 — ISRUC

> repeated-night / cohort / scorer variability.

### OPP-076 — EESM17

> alternative ear-EEG sensing-domain feasibility.

### OPP-074 — PhysioNet 2018

> arousal/sleep-disturbance safety branch.

---

## HARDWARE TRIGGER WAIT

### OPP-123 — OpenBCI

> real acquisition/streaming only after software replay proves the need.

---

## RESERVE / CONTINGENCY

### OPP-069 — Sleep-EDF

> no longer the default first baseline; retain as classical benchmark/smoke-test contingency.

### OPP-066 — MESA

> reserve only; activate on a concrete home/multimodal question.

---

# 18. Final Path V Opportunity Principle

> **Path V is not the execution of fourteen opportunities. Path V is the execution of a small number of scientific questions, with opportunities activated only when they are the best resource for answering the current question.**

The immediate road is therefore:

> **BOAS first → evidence first → real-time references second → external generalization third → optional extensions only when justified → real hardware only when software evidence creates the requirement.**

This preserves:

- evidence before engineering;
- participant-aware validation;
- N3 emphasis;
- reduced-sensor skepticism;
- external-test integrity;
- minimal data acquisition;
- reproducibility;
- a controlled transition from offline staging to real-time closed-loop engineering.

---

# 19. External Verification Notes — 2026-09-04

These sources were checked to verify that the opportunity roles used above remain technically grounded. They supplement the internal Path E documents; they do not override direct Neuro-TMR dataset inspection or frozen project decisions.

## OPP-078B — Dreamento

- Dreamento GitHub: https://github.com/dreamento/dreamento
- SoftwareX publication: https://doi.org/10.1016/j.softx.2023.101595

Relevant verified capabilities include real-time EEG monitoring, sleep staging, sensory stimulation, annotation/event handling and offline post-processing. Dreamento documentation also preserves limitations around its current autoscoring path, supporting its use as a reference rather than a Neuro-TMR validation authority.

## OPP-075 — BOAS / NEMAR

- NEMAR BOAS page: https://www.nemar.org/dataset/on005555
- NEMAR DOI: https://doi.org/10.82901/nemar.on005555

The public resource confirms simultaneous PSG and wearable EEG with consensus staging and on-demand acquisition routes. Neuro-TMR's own validated ingestion/EDA remains the governing source for internal `pid` split semantics and the already-established engineering constraints.

## OPP-067 — STAGES

- NSRR STAGES: https://sleepdata.org/datasets/stages

The current documentation confirms the multi-site clinical design and preserves site-specific acquisition considerations.

## OPP-065 — SHHS

- NSRR SHHS: https://sleepdata.org/datasets/shhs
- PSG documentation: https://sleepdata.org/datasets/shhs/pages/05-polysomnography-introduction.md

The resource provides large-scale overnight PSG and annotations suitable for robustness/generalization work.

## OPP-123 — OpenBCI

- OpenBCI GUI: https://docs.openbci.com/Software/OpenBCISoftware/GUIDocs/
- OpenBCI LSL documentation: https://docs.openbci.com/Software/CompatibleThirdPartySoftware/LSL/

Current documentation confirms real-time streaming paths and LSL/BrainFlow integration.

## OPP-076 — EESM17

- Open dataset mirror: https://github.com/OpenNeuroDatasets/ds004348
- Dataset DOI: https://doi.org/10.18112/openneuro.ds004348.v1.0.5

The released dataset contains 9 healthy participants, partial PSG and 14 ear-EEG electrodes, supporting its classification as a small alternative-sensor extension rather than core V1 evidence.

## OPP-020 — SleepLoopFM

- ETH Zurich project page: https://sms.hest.ethz.ch/research/current-research-projects/sleep-robotics/ai-based-real-time-sleep-decoding.html

The project explicitly targets sparse wearable EEG, real-time staging, temporal context and immediate closed-loop interventions.

## OPP-016 — SCCN / EEGLAB / LSL

- EEGLAB: https://sccn.ucsd.edu/eeglab/
- LSL introduction: https://labstreaminglayer.readthedocs.io/info/intro.html
- LSL time synchronization: https://labstreaminglayer.readthedocs.io/info/time_synchronization.html

These resources support selective use of streaming/timing infrastructure without requiring Neuro-TMR to replace its existing MNE/Python analysis stack.

## OPP-074 — PhysioNet 2018 Arousal

- PhysioNet Challenge 2018: https://physionet.org/content/challenge-2018/1.0.0/

The full resource is very large and defines a distinct arousal task, supporting conditional rather than immediate activation.

## OPP-069 — Sleep-EDF Expanded

- PhysioNet Sleep-EDF Expanded: https://physionet.org/content/sleep-edfx/1.0.0/

Sleep-EDF remains a strong classical open sleep-staging benchmark, but current Neuro-TMR BOAS readiness removes the need to restart Path V there by default.

## OPP-070 — HMC

- PhysioNet HMC Sleep Staging v1.1: https://physionet.org/content/hmc-sleep-staging/1.1/

The database contains 151 heterogeneous clinical PSG recordings and is openly accessible, supporting its role as an external clinical fallback.

## OPP-072 — ISRUC-Sleep

- ISRUC official dataset: https://sleeptight.isr.uc.pt/
- NEMAR ISRUC: https://www.nemar.org/dataset/nm000111

The resource includes multiple cohorts, two expert scorers and repeated nights in one subgroup.

## OPP-066 — MESA Sleep

- NSRR MESA: https://sleepdata.org/datasets/mesa

The resource provides PSG, actigraphy and multimodal sleep context, but the current A6 decision correctly preserves it as reserve for the EEG-first V1.

## OPP-077 — Dreem Open Datasets

- Publication: https://doi.org/10.1109/TNSRE.2020.3011181
- Open code/data tooling: https://github.com/Dreem-Organization/dreem-learning-open

DOD-H and DOD-O provide multi-scorer labels and are especially valuable for later uncertainty/inter-rater analysis.

---

# 20. Current Command

> **PATH V OPPORTUNITY REVIEW: COMPLETE**

> **IMMEDIATE EXECUTION TARGET: OPP-075 — BOAS**

> **FIRST PATH V ACTION: PV-0 — PARTICIPANT-AWARE SPLIT AND EVALUATION-FEASIBILITY AUDIT**

No other Path V opportunity should block this first action.
