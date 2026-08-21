# A2 — EEG Hardware Requirements & Evaluation Framework

**Toolkit:** Path E Execution Toolkit  
**Artifact:** A2  
**Status:** INITIAL / HIGH-LEVEL  
**Date:** 2026-08-21  
**Primary source:** `final_active_opportunities.md`  
**Scope:** High-level hardware evaluation framework for future Path V and Neuro-TMR V1 engineering

---

## 1. Purpose

A2 defines the **hardware requirements, evaluation logic, comparison structure, evidence classes, and vendor-question framework** that Neuro-TMR will use when assessing EEG hardware opportunities.

A2 is intentionally **not** the final hardware-selection document.

Its purpose is to ensure that future hardware decisions are made against the same Neuro-TMR-specific requirements rather than from vendor marketing, isolated specifications, prestige, or convenience.

> **A2 defines what Neuro-TMR needs from EEG hardware and how every active hardware opportunity should be evaluated before Path V makes the final technical choice.**

---

## 2. Scope Boundary

### A2 decides now

A2 defines:

- the active EEG hardware / technology opportunity landscape;
- the functional roles that different hardware platforms may serve;
- the high-level capabilities required by Neuro-TMR;
- which capabilities are core versus optional;
- how real-time integration should be evaluated;
- how overnight / wearable suitability should be evaluated;
- how data access, export, ownership, and synchronization should be treated;
- how research validity should be interpreted;
- how commercial access and partnership constraints should be recorded;
- the standard vendor / partner question bank;
- the evidence hierarchy used for hardware claims;
- the comparison template used across hardware opportunities;
- which decisions must be deferred to Path V.

### A2 does not decide now

The following are **explicitly deferred to Path V technical design and hardware testing**:

- the final V1 EEG device;
- the final number of EEG channels;
- the final electrode montage;
- the final sampling-rate requirement;
- the final acceptable end-to-end latency;
- the final impedance requirement;
- the final amplifier architecture;
- the final communication protocol;
- the final cue-output device;
- the final battery/runtime threshold;
- the final hardware budget;
- the final industrial/wearable form factor;
- the final procurement decision;
- the final hardware/software integration implementation.

---

## 3. Active Hardware / Technology Landscape

The active Path E portfolio contains ten F5 hardware / industry opportunities.

They represent different technical roles and should **not** be treated as if they are all competing for one identical function.

| OPP ID | Opportunity | High-Level A2 Role |
|---|---|---|
| OPP-124 | Bitbrain Ikon Sleep + SDK Ecosystem | Sleep-specific wearable EEG / V1-oriented candidate |
| OPP-129 | CGX Patch EEG + Sleep Technology / Partner Program | Low-channel frontal sleep-EEG / wearable validation candidate |
| OPP-123 | OpenBCI Cyton / Ganglion Open Hardware Ecosystem | Open prototyping / raw-EEG development candidate |
| OPP-121 | Earable Neuroscience / FRENZ Research & B2B Partnership | Integrated wearable sleep EEG + possible closed-loop / partnership candidate |
| OPP-128 | ANT Neuro eego rt / eego Research Ecosystem | Reference-grade real-time EEG validation candidate |
| OPP-126 | Brain Products + sync2brain Real-Time Closed-Loop EEG Stack | Research-grade low-latency closed-loop reference candidate |
| OPP-122 | InteraXon / Muse Research Partnership + Muse SDK | Accessible wearable EEG / developer prototyping candidate |
| OPP-130 | g.tec Unicorn Hybrid Black + g.Pype | Developer-oriented EEG / Python prototyping candidate |
| OPP-132 | Elemind Closed-Loop EEG Acoustic Neurotechnology | Closed-loop EEG-acoustic architecture / partnership candidate |
| OPP-127 | Wearable Sensing DSI EEG + DSI API | Dry mobile EEG / developer-access candidate |

---

## 4. Hardware Functional Roles

A2 separates hardware into functional roles because one system may be excellent for validation but unsuitable for deployment, while another may be excellent for prototyping but weaker as a research reference.

### H1 — Reference / Validation Hardware

Purpose:

> Provide high-quality EEG and reliable timing as a technical reference against which lower-burden or wearable systems can be compared.

Likely active candidates:
- OPP-128 — ANT Neuro eego rt
- OPP-126 — Brain Products + sync2brain

A1/A2 interpretation:
- these platforms may be valuable even if they are not the final wearable V1 route;
- their role can be to validate algorithms, timing, synchronization, and closed-loop behavior.

---

### H2 — Prototype / Development Hardware

Purpose:

> Provide open or developer-friendly access for building and testing the Neuro-TMR acquisition, streaming, inference, and cue-control stack.

Likely active candidates:
- OPP-123 — OpenBCI
- OPP-130 — g.tec Unicorn + g.Pype
- OPP-122 — Muse
- OPP-127 — Wearable Sensing DSI

A2 interpretation:
- the best prototyping platform does not have to become the final V1 device;
- openness, raw data, API/SDK access, and integration simplicity are especially important here.

---

### H3 — V1-Oriented Wearable / Sleep Hardware

Purpose:

> Test hardware that is closer to the intended overnight / wearable use case of an EEG-based stage-aware Neuro-TMR system.

Likely active candidates:
- OPP-124 — Bitbrain Ikon Sleep
- OPP-129 — CGX Patch
- OPP-121 — FRENZ

A2 interpretation:
- overnight use, reduced-channel sensing, practical self-application, and real-time data access become especially important;
- these systems are more directly relevant to future V1 deployment assumptions.

---

### H4 — Integrated Closed-Loop / Strategic Platform

Purpose:

> Provide architectural or partnership value where EEG acquisition, real-time analysis, and stimulation are already integrated or closely coupled.

Likely active candidates:
- OPP-121 — FRENZ
- OPP-132 — Elemind
- OPP-126 — Brain Products + sync2brain

A2 interpretation:
- an integrated system is not automatically superior;
- the key question is whether Neuro-TMR can retain control over the intelligence layer and cue logic.

---

## 5. Core Neuro-TMR Hardware Requirements

The following requirements are high-level enough to freeze now.

### A2-R01 — Raw EEG Access

A hardware platform intended for direct Neuro-TMR inference must provide access to the underlying EEG signal.

A system that exposes only proprietary sleep-stage outputs is insufficient as the sole Neuro-TMR sensing layer.

**Priority:** Core

---

### A2-R02 — Real-Time or Near-Real-Time Streaming

The hardware must support data access during the recording session if it is to participate directly in closed-loop TMR.

Post-night-only export may still be useful for offline validation but cannot support the live control loop.

**Priority:** Core for closed-loop use

---

### A2-R03 — Programmatic Integration

Neuro-TMR must be able to consume the EEG stream through a documented software interface such as:

- SDK;
- API;
- Python interface;
- LSL;
- another programmatically accessible streaming mechanism.

Exact protocol choice is deferred.

**Priority:** Core

---

### A2-R04 — Reliable Timing / Timestamps

EEG samples and external events must be timestampable well enough to support later inference-latency and cue-timing analysis.

The exact maximum timing error is deferred to Path V.

**Priority:** Core

---

### A2-R05 — External Event Synchronization

The future system must be able to associate cue events and other experimental markers with the EEG timeline.

This may occur through:
- event markers;
- trigger channels;
- LSL markers;
- SDK-level event insertion;
- synchronized external logging.

Exact mechanism is deferred.

**Priority:** Core

---

### A2-R06 — Neuro-TMR-Controlled Cue Output

The EEG device does **not** need to contain its own audio system.

However, the architecture must permit Neuro-TMR to synchronize or control an external cue-delivery mechanism.

Built-in audio is optional; external controllability is more important.

**Priority:** Core capability, implementation deferred

---

### A2-R07 — Raw Data Export

Recorded EEG should be exportable for:

- debugging;
- model development;
- offline validation;
- reproducibility;
- comparison with reference systems.

**Priority:** Core

---

### A2-R08 — Overnight Practicality

For V1-oriented hardware, the system should be evaluated for:

- overnight runtime;
- recording stability;
- comfort;
- electrode stability;
- connection reliability;
- self-application or low-burden setup;
- tolerance to normal sleep movement.

Exact thresholds are deferred.

**Priority:** Core for wearable/V1 candidates

---

### A2-R09 — Research Validity

The hardware should have enough technical transparency and/or scientific validation to justify using its signal as research evidence.

Evaluation should distinguish:
- vendor claims;
- official technical specifications;
- peer-reviewed validation;
- independent external validation;
- Neuro-TMR's own testing.

**Priority:** Core

---

### A2-R10 — Access Feasibility

A technically ideal platform that Neuro-TMR cannot realistically obtain, license, or integrate may have limited immediate execution value.

Record:
- purchase access;
- research access;
- SDK/license availability;
- geographic availability;
- support route;
- partnership path;
- known cost constraints.

**Priority:** Core for execution

---

## 6. Desirable but Non-Core Capabilities

These capabilities may increase strategic value but are not required at A2 level for every device.

### A2-D01 — Built-In Sleep Staging
Useful as a reference or comparator, but Neuro-TMR should not depend blindly on a proprietary staging output.

### A2-D02 — Built-In Audio / Stimulation
Useful for integrated systems, but external cue control can be sufficient.

### A2-D03 — Additional Physiology
EOG, EMG, PPG, accelerometry, ECG, or other sensors may improve research capability or future safety monitoring, but EEG remains the V1 core sensing modality.

### A2-D04 — Wireless Operation
Highly useful for wearable/home systems; not mandatory for every reference-grade validation platform.

### A2-D05 — Self-Application
Strongly desirable for later home deployment, but not required for early reference or laboratory validation hardware.

### A2-D06 — Open Source
Open hardware/software can reduce integration friction but is not mandatory if a proprietary platform exposes sufficient raw data and developer control.

---

## 7. High-Level Integration Path

A2 assumes a modular Neuro-TMR architecture.

```text
EEG Hardware
    ↓
Raw EEG Stream
    ↓
Acquisition / Timestamp Layer
    ↓
Neuro-TMR Processing + Inference
    ↓
Cue Eligibility Logic
    ↓
Cue Output
    ↓
Event Logging / Synchronization
```

### Governing principle

> **The hardware provides the signal; Neuro-TMR owns the intelligence and control logic.**

Integrated commercial platforms may provide useful internal processing, but Neuro-TMR should retain the ability to validate and control its own inference path.

---

## 8. Standard Hardware Information Fields

Every active hardware candidate should eventually have the same information fields.

| Field | Purpose |
|---|---|
| Device / Platform | Canonical name |
| OPP ID | Path E lineage |
| Functional Role | H1 / H2 / H3 / H4 |
| EEG Channels | Available EEG count / placement |
| Raw EEG Access | Yes / No / Unknown |
| Real-Time Stream | Yes / No / Unknown |
| Sampling Rate | Reported value |
| Timestamp Support | Yes / No / Unknown |
| SDK / API | Available interface |
| Python Support | Yes / No / Unknown |
| LSL Support | Yes / No / Unknown |
| External Markers | Yes / No / Unknown |
| External Cue Synchronization | Yes / No / Unknown |
| Built-In Audio | Yes / No / Unknown |
| Data Export | Formats / restrictions |
| Overnight Runtime | Reported / unknown |
| Wearability | High-level suitability |
| Research Validation | Evidence summary |
| License / SDK Terms | Open / commercial / restricted / unknown |
| Hardware Cost | Known / quote / unknown |
| Geographic Access | Available / unknown / restricted |
| Research / Partnership Route | Available / unknown |
| Evidence Level | See Section 10 |
| Neuro-TMR Status | Not contacted / researching / contacted / testing / rejected / selected |

---

## 9. Standard Vendor / Partner Question Bank

When public documentation does not answer a material requirement, the same core questions should be used across vendors.

### Signal / EEG

1. Can researchers access the **raw EEG signal**?
2. Which EEG channels / electrode positions are available?
3. What sampling rates are supported?
4. Is the signal filtered or transformed before access?
5. Can users control or disable internal preprocessing?

### Real-Time Access

6. Can EEG be streamed continuously in real time?
7. What SDK / API / software interface is provided?
8. Is Python supported?
9. Is LSL supported?
10. How are timestamps generated and synchronized?

### Closed-Loop Integration

11. Can external event markers be inserted into the recording?
12. Can an external application receive the EEG stream and make decisions in real time?
13. Can externally generated audio/stimulation events be synchronized with EEG timestamps?
14. Is there a documented or measured streaming / processing latency?

### Overnight / Wearability

15. What is the expected overnight runtime?
16. Is the system designed or validated for sleep recording?
17. Can users self-apply the device?
18. What happens if wireless connectivity drops?
19. Is local/offline recording available?

### Data / Ownership

20. Can full sessions be exported?
21. Which file formats are available?
22. Are there restrictions on storing or analyzing raw EEG?
23. Can data be used for independent model development?

### Access / Commercial

24. What is the hardware cost or research pricing?
25. Does SDK/API access require a separate license?
26. Are there restrictions on prototype or commercial integration?
27. Is a research partnership, academic program, or B2B route available?
28. Is technical support available for custom real-time integration?

---

## 10. Evidence Classification

Hardware claims must be labeled by evidence strength.

### `PUBLICLY_VERIFIED`

Supported by current official vendor / project documentation.

### `VENDOR_CONFIRMED`

Confirmed directly by the company or platform team through email, call, technical meeting, or written quote.

### `INDEPENDENTLY_VALIDATED`

Supported by peer-reviewed research or independent technical evaluation.

### `NEURO_TMR_TESTED`

Directly reproduced or measured by Neuro-TMR during Path V.

### `UNKNOWN`

No sufficiently reliable evidence yet.

### Governing rule

> **Unknown must remain `UNKNOWN`; it should never be converted into an assumption simply because the capability is likely.**

---

## 11. Requirement Priority Classes

Each requirement should be classified as:

### `CORE`
Without this capability, the hardware cannot perform the intended Neuro-TMR role.

### `STRONGLY_DESIRED`
Substantially improves research or deployment suitability.

### `OPTIONAL`
Useful but not necessary.

### `ROLE_SPECIFIC`
Required only for a particular functional role.

Example:

- raw EEG → `CORE` for direct Neuro-TMR inference;
- self-application → `ROLE_SPECIFIC` for H3 wearable deployment;
- research-grade wired amplifier → useful for H1 but not required for H3;
- built-in audio → `OPTIONAL` if external synchronization is possible.

---

## 12. High-Level Candidate Interpretation

A2 does not rank hardware again, but preserves the distinct reason each active F5 candidate exists.

| OPP ID | Candidate | A2 Interpretation |
|---|---|---|
| OPP-124 | Bitbrain Ikon Sleep | Strong sleep-specific wearable / SDK path |
| OPP-129 | CGX Patch | Strong low-channel frontal sleep-EEG path |
| OPP-123 | OpenBCI | Strong open prototyping / raw-data path |
| OPP-121 | FRENZ | Strong integrated wearable sleep / partnership path |
| OPP-128 | ANT Neuro | Strong reference-grade real-time validation path |
| OPP-126 | Brain Products + sync2brain | Strong research-grade closed-loop reference path |
| OPP-122 | Muse | Accessible wearable / developer ecosystem path |
| OPP-130 | g.tec Unicorn + g.Pype | Developer-oriented real-time Python path |
| OPP-132 | Elemind | Strategic closed-loop EEG-acoustic / partnership path |
| OPP-127 | Wearable Sensing DSI | Dry mobile EEG / developer-access path |

These interpretations come from L8 / active-opportunity evidence and are not final hardware-selection decisions.

---

## 13. Comparison Principle

Hardware comparison should be **role-aware**.

A reference-grade H1 system should not be penalized simply because it is not wearable.

A wearable H3 system should not automatically outrank an H1 system simply because it is easier to wear.

The correct question is:

> **How well does this platform satisfy the role Neuro-TMR needs it to perform?**

A future comparison may therefore select more than one hardware platform:

```text
Reference system     → H1
Prototype system     → H2
Wearable V1 test     → H3
Integrated partner   → H4
```

These roles may overlap.

---

## 14. Procurement Principle

> **Do not purchase expensive hardware before the technical requirements are clear and the major unknowns are resolved through documentation or vendor contact.**

Before purchase, Neuro-TMR should understand at minimum:

- raw EEG availability;
- real-time streaming;
- SDK/API terms;
- timestamp / event support;
- data export;
- expected overnight suitability;
- licensing;
- realistic total cost;
- intended Path V role.

---

## 15. Relationship to A1

A1 and A2 should remain aligned but distinct.

### A1 asks:
> What data should Neuro-TMR use and how should it be treated?

### A2 asks:
> What EEG hardware should Neuro-TMR evaluate and what must that hardware provide?

Together:

```text
A1 — Data / Benchmark Principles
        +
A2 — Hardware / Integration Principles
        ↓
Future Path V Technical Design
```

Path V will later connect specific datasets to specific hardware experiments.

---

## 16. Deferred Path V Decisions

The following remain intentionally unresolved:

- which hardware becomes the final V1 device;
- whether one platform can satisfy H1 + H2 + H3 simultaneously;
- exact channel/montage requirements;
- exact sampling-rate threshold;
- exact latency threshold;
- exact overnight battery requirement;
- exact acceptable artifact/signal-quality level;
- exact cue-output implementation;
- exact integration protocol;
- exact device procurement;
- exact validation experiment;
- exact hardware-vs-hardware benchmark.

These belong to Path V.

---

## 17. Update Rule

A2 should be updated when:

- a vendor confirms or denies a material capability;
- a public technical specification materially changes;
- Neuro-TMR obtains or tests hardware;
- a research partnership provides new access;
- Path V discovers that a high-level requirement is invalid;
- a new active hardware opportunity materially changes the comparison landscape;
- a hardware candidate becomes inaccessible.

Routine marketing updates should not rewrite A2.

---

# A2 Completion Gate

A2 is complete at the execution-toolkit level when Neuro-TMR has:

- a clear map of the active hardware opportunity landscape;
- functional roles for different hardware classes;
- frozen high-level hardware requirements;
- clear integration principles;
- a common vendor-question bank;
- a common evidence classification;
- a common comparison structure;
- a rule against premature procurement;
- a clear boundary between hardware evaluation and future Path V implementation.

**A2 — EEG HARDWARE REQUIREMENTS & EVALUATION FRAMEWORK: INITIAL HIGH-LEVEL VERSION COMPLETE**
