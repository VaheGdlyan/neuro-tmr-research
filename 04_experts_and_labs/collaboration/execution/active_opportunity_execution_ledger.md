# Path E — Active Opportunity Execution Ledger

**Date:** 2026-08-21  
**Source population:** `final_active_opportunities.md`  
**Active opportunities mapped:** **53 / 53**  
**Stage:** PATH E EXECUTION — E1 OPERATIONAL MAPPING  
**Wave sequencing:** NOT YET ASSIGNED

## Purpose

This document translates every active L8 `KEEP` opportunity into a concrete execution interpretation.

It answers:

> **What exactly should Neuro-TMR do with this opportunity, through which mechanism, after which prerequisite, and what outcome would count as useful progress?**

This is an execution map, **not a new ranking layer**. L8 scores, ranks, and `KEEP` decisions remain frozen.

The document deliberately does **not** assign Wave 1 / Wave 2 / later-wave positions. Those should be derived only after the operational actions and dependencies below are understood.

---

## 1. Execution Timing States

| State | Meaning |
|---|---|
| `EXECUTE_NOW` | The first meaningful action can start immediately and should not wait for another Path E result. |
| `PREPARE_THEN_EXECUTE` | The opportunity is active now, but a specific brief/specification/result should be prepared first so the action is credible and efficient. |
| `TRIGGER_DEPENDENT` | The opportunity remains active, but action should wait for a defined project result, eligibility condition, event/call, or later validation need. |

These states describe **readiness**, not strategic value. A globally top-ranked opportunity can correctly be `PREPARE_THEN_EXECUTE` or `TRIGGER_DEPENDENT`.

## 2. Controlled Execution Roles

| Role | Meaning |
|---|---|
| `DIRECT_RESOURCE_USE` | Obtain/use open data, software, infrastructure, or developer resources directly. |
| `SCIENTIFIC_OUTREACH` | Contact a scientist/lab with a specific scientific or collaboration objective. |
| `INSTITUTIONAL_COLLABORATION` | Establish a local/institutional route for facilities, hosting, validation, or future study enablement. |
| `TECHNICAL_ACCESS_REQUEST` | Obtain vendor/platform facts, SDK/API access, demo, quote, licensing, or partnership conditions. |
| `FUNDING_OR_COMPUTE_APPLICATION` | Apply to a concrete support mechanism. |
| `EVENT_OR_NETWORK_ACTION` | Register/participate/monitor with a defined networking or methods objective. |
| `STRATEGIC_TECH_INTEGRATION` | Reproduce/inspect future-horizon technical work and convert it into architecture knowledge without expanding V1 scope. |

## 3. Shared Preparation Artifacts

These should be created once and reused across many opportunities:

- **A1 — Path V Data & Benchmark Specification:** tasks, datasets, channel assumptions, splits, metrics, leakage rules, external-validation roles, licensing/data-use notes.
- **A2 — EEG Hardware Technical Requirements Sheet:** raw EEG, electrode/channel placement, sampling, timestamps, API/SDK/LSL, latency, event markers, overnight runtime, cue/audio integration, export, licensing, cost/support.
- **A3 — Scientific Collaboration Brief:** one-page Neuro-TMR summary, evidence-based V1 thesis, current Path V plan, exact problem, and one or two candidate-specific asks.
- **A4 — Local Validation / Institutional Brief:** what is being validated, what is not yet a human study/product claim, future PSG/EEG comparison needs, and the institutional questions to resolve.
- **A5 — Path A ↔ Path E Coordination Register:** existing expert-contact state, reply/auto-response/waiting state, follow-up date, and a hard rule against duplicate parallel outreach.
- **A6 — Execution Tracker:** action date, owner, channel, response, next step, status, and reserve-activation trigger.
- **A7 — Path V Compute Request Brief:** datasets, workload estimate, expected 3-month experiments, storage/compute need, and deliverables for compute-support applications.

## 4. Portfolio-Level Execution Snapshot

- `EXECUTE_NOW`: **19**
- `PREPARE_THEN_EXECUTE`: **26**
- `TRIGGER_DEPENDENT`: **8**

### Role distribution

- `DIRECT_RESOURCE_USE`: **15**
- `EVENT_OR_NETWORK_ACTION`: **3**
- `FUNDING_OR_COMPUTE_APPLICATION`: **1**
- `INSTITUTIONAL_COLLABORATION`: **5**
- `SCIENTIFIC_OUTREACH`: **18**
- `STRATEGIC_TECH_INTEGRATION`: **2**
- `TECHNICAL_ACCESS_REQUEST`: **9**

## 5. Path A Coordination Rule

Several active F1 opportunities overlap with the already-contacted Path A expert-review wave.

> **Do not send a second Path E cold email to an overlapping expert while the Path A interaction is still open.**

For those opportunities:

1. prepare the candidate-specific collaboration conversion note now;
2. continue in the existing Path A thread if a reply arrives;
3. if no human reply arrives, wait until the normal Path A follow-up window (roughly 7–10 business days from the original email) before one coordinated follow-up;
4. a later Path E message must contain a genuinely new collaboration objective, result, or artifact—not a repeated request for review.

Existing Path A replies should first be converted into project requirements/results before asking the same expert for more time.

## 6. Cross-Opportunity Dependency Logic

Several actions unlock many others:

- **A1 + first baseline** unlock stronger use of STAGES/SHHS/HMC/ISRUC and stronger technical outreach to sleep/wearable labs.
- **A2** unlocks comparable hardware/vendor inquiries across Bitbrain, CGX, FRENZ, ANT Neuro, Muse, g.tec, Elemind, Wearable Sensing and Brain Products.
- **A3 + A5** unlock coordinated scientific collaboration without duplicating Path A.
- **A4** unlocks credible local institutional discussions with Erebuni, COBRAIN, Arabkir and later behavioral-study partners.
- **BOAS/EESM17 reduced-channel results** unlock the strongest reason to approach ear-/mobile-EEG groups.
- **A working Path V demo/latency audit** creates a stronger second contact for experts who have already replied in Path A.

---

# 7. Candidate-by-Candidate Execution Map

## Global Rank #1 — OPP-078B — Dreamento Open Sleep-EEG / Closed-Loop Research Toolbox

**Organization:** Dreamento  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Open real-time sleep-EEG, event-detection, and stimulation tooling  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Use Dreamento as the first open reference implementation for the real-time sleep-EEG → state/event detection → sensory-stimulation loop.

**Concrete Next Action:** Clone the repository; create isolated offline and real-time environments; run the offline pipeline first; then document the real-time staging, event-detection, annotation, and stimulation modules and what can be reused in Path V.

**Prerequisite:** A1 — Path V Data & Benchmark Specification.

**Channel / Mechanism:** Open-source repository + local reproducibility test.

**Success Condition:** Dreamento runs reproducibly enough to produce an architecture note, module map, and a concrete reuse/gap list for Neuro-TMR. Its real-time scorer is treated as an engineering reference, not as ground-truth validation.

**Key Dependency / Trigger:** No external dependency. Real-time hardware-specific features may require compatible acquisition hardware.

**Execution Evidence Note:** Verified 2026-08-21: Dreamento is open-source; supports real-time EEG display, staging, event detection/annotations and sensory stimulation; its real-time autoscoring is explicitly still under development.

---

## Global Rank #2 — OPP-075 — Bitbrain Open Access Sleep (BOAS)

**Organization:** Bitbrain / NEMAR ecosystem  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Wearable EEG versus PSG validation  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Directly test the reduced-sensor V1 assumption using simultaneous wearable EEG and clinical PSG from the same nights.

**Concrete Next Action:** Download BOAS from NEMAR; validate BIDS structure; build subject/night alignment; identify wearable and PSG channels; ingest human-consensus labels; define the first paired wearable-vs-PSG baseline experiment.

**Prerequisite:** A1 — Path V Data & Benchmark Specification.

**Channel / Mechanism:** NEMAR dataset download / CLI.

**Success Condition:** BOAS is reproducibly loaded and a paired wearable-vs-PSG baseline experiment is specified and runnable.

**Key Dependency / Trigger:** No access blocker; compute/storage planning is needed for the full dataset.

**Execution Evidence Note:** Verified 2026-08-21: BOAS v1.0.0 contains 128 nights / 108 participants, simultaneous PSG + wearable EEG, expert-consensus labels, two EEG channels, CC0 license.

---

## Global Rank #2 — OPP-064 — National Sleep Research Resource (NSRR)

**Organization:** NHLBI-supported sleep-data infrastructure  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Large-scale PSG repository and dataset gateway  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Establish the large-scale PSG data gateway for cross-cohort training and external validation.

**Concrete Next Action:** Create/verify an NSRR account; define the exact cohorts needed through A1; submit data requests for the selected cohorts rather than downloading broadly; verify downloader/API workflow.

**Prerequisite:** A1 — Path V Data & Benchmark Specification.

**Channel / Mechanism:** NSRR account + dataset-specific data request.

**Success Condition:** At least the selected NSRR cohorts have an approved or submitted access path and are registered in the Path V data manifest with intended roles.

**Key Dependency / Trigger:** Dataset-specific access approval and data-use compliance.

**Execution Evidence Note:** Current NSRR access model uses account-based dataset requests; the resource provides large PSG cohorts without direct data-purchase cost.

---

## Global Rank #2 — OPP-078A — NEMAR Research Infrastructure

**Organization:** NEMAR  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** EEG data-discovery and computational research infrastructure  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Use NEMAR as the standard discovery/download/compute layer for open EEG resources relevant to Path V.

**Concrete Next Action:** Install `nemar-cli`; clone one small dataset and BOAS metadata; verify BIDS handling; test the no-cost NSG compute route on a minimal job; record the workflow for reproducibility.

**Prerequisite:** A1 — Path V Data & Benchmark Specification.

**Channel / Mechanism:** NEMAR + nemar-cli + Neuroscience Gateway.

**Success Condition:** A documented NEMAR workflow can discover, download and/or compute on a selected EEG dataset reproducibly.

**Key Dependency / Trigger:** NSG account may be required for remote compute.

**Execution Evidence Note:** Verified 2026-08-21: NEMAR is open access, BIDS-oriented, supports CLI download and NSG high-performance compute.

---

## Global Rank #5 — OPP-011 — Sleep and Memory Laboratory (Cecilia Forcato)

**Organization:** Instituto Tecnológico de Buenos Aires (ITBA)  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** TMR plus automatic sleep-event detection and cue scheduling  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `WAITING_PATH_A`

**Execution Objective:** Convert the existing expert-review relationship into a focused collaboration path around TMR + automatic sleep-event detection + cue scheduling.

**Concrete Next Action:** Prepare a one-page collaboration conversion note using A3. Do not send a separate Path E cold email while Path A is open. If a Path A reply arrives, continue in the same thread; if not, use one coordinated follow-up after the Path A waiting window.

**Prerequisite:** A3 + A5. Exact ask: feedback/collaboration on event detection and a minimal closed-loop validation design.

**Channel / Mechanism:** Existing Path A email thread.

**Success Condition:** A technical discussion/meeting, methods exchange, code/data pointer, or explicit collaboration/referral path is obtained.

**Key Dependency / Trigger:** Path A coordination; avoid duplicate contact.

**Execution Evidence Note:** Current ITBA work combines sleep/memory research with automatic sleep-event algorithm development.

---

## Global Rank #5 — OPP-014 — Hong-Viet V. Ngo-Dehning — Sleep, Memory and Real-Time Stimulation

**Organization:** University of Essex  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Real-time sleep-stimulation architecture, timing, and latency  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `WAITING_PATH_A`

**Execution Objective:** Obtain direct guidance on real-time stimulation architecture, timing/latency, and the boundary between stage-aware V1 and later phase-aware control.

**Concrete Next Action:** Draft a concise collaboration follow-up around the Path V latency/control audit. Keep it unsent while the Path A review window is open; continue in-thread if he replies.

**Prerequisite:** A2 + A3 + A5; preferably a draft Path V timing diagram.

**Channel / Mechanism:** Existing Path A email thread.

**Success Condition:** Concrete timing/latency requirements or a collaboration/mentorship pathway that can change the Path V control architecture.

**Key Dependency / Trigger:** Path A coordination.

**Execution Evidence Note:** Current Essex profile remains directly focused on sleep, memory consolidation, non-invasive/real-time stimulation.

---

## Global Rank #5 — OPP-015 — Centre for Sleep and Cognition / Sleep and Cognition Laboratory (Michael Chee)

**Organization:** National University of Singapore  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Real-time sleep staging, acoustic stimulation, and wearable translation  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Explore collaboration around real-time sleep staging, acoustic intervention and wearable translation—the closest direct scientific analogue to V1.

**Concrete Next Action:** Prepare a highly specific email to the NUS Centre for Sleep and Cognition: introduce the evidence-based V1, show the Path V architecture, and ask one concrete question about real-time staging/intervention validation or minimal wearable sensing.

**Prerequisite:** A3 + A2.

**Channel / Mechanism:** Official PI/lab email.

**Success Condition:** Reply leading to a technical conversation, validation guidance, relevant publication/code/data pointers, or collaborator referral.

**Key Dependency / Trigger:** Quality of the outreach depends on a precise technical ask, not a generic collaboration request.

**Execution Evidence Note:** Verified current NUS lab: Michael Chee directs the Centre for Sleep and Cognition; current work includes wearable/smartphone sleep technologies.

---

## Global Rank #5 — OPP-020 — SleepLoopFM / Sensory-Motor Systems Lab

**Organization:** ETH Zurich  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Real-time sparse-EEG sleep decoding and closed-loop gating  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Learn from an active sparse-wearable-EEG real-time closed-loop system that closely matches Neuro-TMR's technical control problem.

**Concrete Next Action:** After A2 is written and one Path V baseline exists, send a technical collaboration inquiry focused on sparse-channel causal staging, inference latency, uncertainty handling, and intervention gating—not on general sleep robotics.

**Prerequisite:** A2 + A3 + first baseline result from F2.

**Channel / Mechanism:** ETH Sensory-Motor Systems Lab contact route.

**Success Condition:** Specific architectural/validation guidance, code/model access if available, or a conversation with the project team.

**Key Dependency / Trigger:** A concrete technical baseline will materially improve the credibility of the ask.

**Execution Evidence Note:** Verified current ETH project: SleepLoopFM targets real-time staging from sparse wearable EEG followed by immediate auditory/tactile/vestibular intervention.

---

## Global Rank #5 — OPP-067 — STAGES

**Organization:** Multi-center sleep research consortium / NSRR  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Multi-site sleep-model generalization  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Use multi-site PSG to test whether Path V sleep-stage models generalize across collection sites and heterogeneous clinical settings.

**Concrete Next Action:** Submit/verify STAGES access through NSRR; once approved, inspect site identifiers, channel harmonization and scoring conventions; reserve STAGES as a multi-site external validation dataset rather than an initial development set.

**Prerequisite:** A1 — Path V Data & Benchmark Specification.

**Channel / Mechanism:** NSRR data request.

**Success Condition:** Access is secured/submitted and a cross-site holdout design is documented before model development can leak site information.

**Key Dependency / Trigger:** NSRR access approval.

**Execution Evidence Note:** Verified: STAGES is a multi-site sleep dataset with PSG and additional phenotyping; access is request-based.

---

## Global Rank #5 — OPP-124 — Bitbrain Ikon Sleep + SDK Ecosystem

**Organization:** Bitbrain  
**Family:** F5 — Hardware / Industry / Technology Access  
**L8 Contribution:** Sleep-specific wearable EEG and SDK integration  
**Execution Role:** `TECHNICAL_ACCESS_REQUEST`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Evaluate Bitbrain Ikon Sleep as the leading sleep-specific wearable EEG candidate for Path V hardware.

**Concrete Next Action:** Complete A2, then contact Bitbrain for a research quote/demo and ask for exact Ikon Sleep sampling/timestamp behavior, SDK access, LSL latency, raw data, overnight battery, cue/event synchronization, shipping/support, and whether an external audio-cue process can be integrated.

**Prerequisite:** A2.

**Channel / Mechanism:** Bitbrain product/research contact.

**Success Condition:** Vendor-confirmed compatibility matrix + realistic cost/access + go/no-go decision for prototype acquisition/testing.

**Key Dependency / Trigger:** Commercial procurement/budget.

**Execution Evidence Note:** Verified current Bitbrain: Ikon Sleep is a 2-frontal-EEG + PPG sleep system; SennsLite records raw data with LSL/CSV/EDF; Bitbrain SDK includes Python bindings and real-time acquisition.

---

## Global Rank #5 — OPP-046 — Neurology, Electrophysiology & Sleep Laboratory

**Organization:** Erebuni Medical Center  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Local PSG/EEG validation infrastructure  
**Execution Role:** `INSTITUTIONAL_COLLABORATION`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Establish the strongest local Armenian route for future PSG/EEG comparison and sleep-neurophysiology validation.

**Concrete Next Action:** Prepare A4, then request a short feasibility meeting with the sleep/electrophysiology team. Ask first about capabilities, collaboration conditions and what a future validation pathway would require—do not request participant access or a human study yet.

**Prerequisite:** A4 — Local Validation / Institutional Brief.

**Channel / Mechanism:** Local institutional contact / meeting request.

**Success Condition:** A named clinical/scientific contact, confirmed PSG/EEG capabilities, and a documented feasible pathway (or constraints) for later validation.

**Key Dependency / Trigger:** Future human work would require protocol, responsible investigator and ethics pathway; current action is only feasibility/institutional discussion.

**Execution Evidence Note:** L8 evidence identifies Erebuni as the strongest local sleep/PSG/EEG infrastructure route.

---

## Global Rank #5 — OPP-129 — CGX Patch EEG + Sleep Technology / Partner Program

**Organization:** CGX Systems  
**Family:** F5 — Hardware / Industry / Technology Access  
**L8 Contribution:** Low-channel frontal sleep-EEG validation  
**Execution Role:** `TECHNICAL_ACCESS_REQUEST`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Evaluate CGX Patch as a low-channel self-applied forehead EEG candidate for overnight V1 validation.

**Concrete Next Action:** Complete A2; request current sales/technical details; confirm 500 Hz raw Bluetooth stream/API behavior, timestamping, sleep-stager availability, electrode consumables, shipping and whether external cue/event markers can be synchronized.

**Prerequisite:** A2.

**Channel / Mechanism:** CGX sales/technical email.

**Success Condition:** Vendor-confirmed matrix and an acquisition/testing decision against Ikon Sleep/OpenBCI.

**Key Dependency / Trigger:** Commercial purchase and consumable electrodes.

**Execution Evidence Note:** Verified current CGX Patch: 2-channel research EEG, full raw access, validated sleep scoring, ~14 h runtime, Bluetooth/SD, public price $750.

---

## Global Rank #5 — OPP-123 — OpenBCI Cyton / Ganglion Open Hardware Ecosystem

**Organization:** OpenBCI  
**Family:** F5 — Hardware / Industry / Technology Access  
**L8 Contribution:** Open raw-EEG closed-loop prototyping  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Build the cheapest/openest raw-EEG acquisition prototype path before committing to proprietary hardware.

**Concrete Next Action:** Use OpenBCI/BrainFlow documentation and a synthetic board to implement the Path V acquisition adapter, timestamps, event markers and file format now; only then decide whether to purchase Cyton/Ganglion for a bench test.

**Prerequisite:** A2.

**Channel / Mechanism:** Open-source SDK/BrainFlow; procurement only after software adapter works.

**Success Condition:** Hardware-agnostic acquisition code works against a simulated/compatible stream and exposes the exact requirements any physical EEG device must satisfy.

**Key Dependency / Trigger:** Physical validation later requires hardware purchase/shipping.

**Execution Evidence Note:** L8 retained OpenBCI for open raw-EEG closed-loop prototyping and low integration friction.

---

## Global Rank #14 — OPP-121 — Earable Neuroscience / FRENZ Research & B2B Partnership

**Organization:** Earable Neuroscience  
**Family:** F5 — Hardware / Industry / Technology Access  
**L8 Contribution:** Real-time wearable sleep EEG, API access, and closed-loop audio  
**Execution Role:** `TECHNICAL_ACCESS_REQUEST`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Determine whether FRENZ can serve as an end-to-end research/B2B partner for wearable EEG + real-time sleep state + audio intervention.

**Concrete Next Action:** Complete A2/A3 and send a research/B2B inquiry asking specifically about raw EEG/EMG/EOG API access, real-time sleep-state outputs, external closed-loop audio control, latency/timestamps, research licensing, device access and geographic/logistical constraints.

**Prerequisite:** A2 + concise research/B2B use case.

**Channel / Mechanism:** Earable/FRENZ research partnership contact.

**Success Condition:** A vendor response that confirms or rules out a usable research integration path; if positive, schedule a technical call/demo.

**Key Dependency / Trigger:** Vendor-controlled API/licensing/device access.

**Execution Evidence Note:** L8 retained FRENZ for real-time wearable sleep EEG, API access and closed-loop audio; research/B2B access requires direct discussion.

---

## Global Rank #14 — OPP-076 — Ear-EEG Sleep Monitoring 2017 (EESM17)

**Organization:** OpenNeuro / ear-EEG research ecosystem  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Ear-EEG sensor-reduction experiments  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Measure how much sleep-state information survives in ear-EEG / low-burden electrode placements.

**Concrete Next Action:** Download EESM17; inspect exact ear/reference channels and synchronized reference signals; build a small reduced-channel staging feasibility test aligned with the BOAS sensor-reduction analysis.

**Prerequisite:** A1 — Path V Data & Benchmark Specification.

**Channel / Mechanism:** OpenNeuro dataset access.

**Success Condition:** A reproducible ear-EEG channel experiment is defined and produces comparable staging metrics against the reference labels/signals.

**Key Dependency / Trigger:** Small dataset size limits conclusions; use as a sensor-placement experiment rather than a definitive benchmark.

**Execution Evidence Note:** L8 evidence identifies EESM17 as an open overnight ear-EEG + reference physiological dataset.

---

## Global Rank #16 — OPP-026 — Surrey Sleep Research Centre

**Organization:** University of Surrey  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Wearable-versus-PSG sleep validation  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `TRIGGER_DEPENDENT`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Use Surrey's clinical-grade PSG, digital-health and wearable-validation expertise to challenge the reduced-burden sensing assumptions after an initial Path V result exists.

**Concrete Next Action:** Prepare the collaboration target now, but send only after the first BOAS/reduced-channel baseline is available. Share one concrete result and ask for methodological critique of wearable-vs-PSG validation/generalization.

**Prerequisite:** A3 + first BOAS/reduced-channel result.

**Channel / Mechanism:** Surrey Sleep Research Centre official contact.

**Success Condition:** Methodological feedback or collaboration route that materially strengthens external validation design.

**Key Dependency / Trigger:** Trigger: first defensible Path V reduced-sensor result.

**Execution Evidence Note:** Verified current Surrey research includes digital-health sleep technology, AI, home monitoring, full PSG and high-density EEG facilities.

---

## Global Rank #17 — OPP-039 — Neurotechnology Laboratory, Engineering City

**Organization:** Enterprise Incubator Foundation (EIF), Engineering City  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Local EEG/neurotechnology support for Path V  
**Execution Role:** `INSTITUTIONAL_COLLABORATION`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Create a local technical partner for EEG acquisition, processing and Path V experimentation.

**Concrete Next Action:** Prepare A2/A3 and request an in-person or video meeting with the Engineering City Neurotechnology Lab. Present the minimal Path V architecture and ask which EEG equipment, signal-processing support and experimental collaboration are actually available.

**Prerequisite:** A2 + A3.

**Channel / Mechanism:** Local lab/institution contact.

**Success Condition:** A named technical counterpart plus a concrete next step such as equipment access, signal-processing support, mentorship, or a small joint technical test.

**Key Dependency / Trigger:** Needs a narrow technical ask to avoid becoming a generic networking meeting.

**Execution Evidence Note:** L7/L8 evidence identifies the lab as a local EEG/neurotechnology capability relevant to Path V.

---

## Global Rank #18 — OPP-016 — Swartz Center for Computational Neuroscience (SCCN)

**Organization:** University of California, San Diego  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** EEG preprocessing, synchronization, artifact handling, and tooling  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Adopt mature EEG preprocessing/synchronization infrastructure before seeking collaboration from SCCN itself.

**Concrete Next Action:** Use EEGLAB/LSL documentation to standardize timestamped EEG + event/cue streams in Path V; create a minimal LSL test with synthetic or available EEG; contact SCCN only if a specific unresolved methodological issue remains.

**Prerequisite:** A2.

**Channel / Mechanism:** Open-source software/documentation first; scientific contact only on a specific unresolved issue.

**Success Condition:** Path V has a reproducible LSL-based acquisition/event synchronization layer and documented latency checks.

**Key Dependency / Trigger:** No external collaboration required for initial value.

**Execution Evidence Note:** Current SCCN/LSL ecosystem remains a major open EEG synchronization and analysis reference.

---

## Global Rank #19 — OPP-065 — Sleep Heart Health Study (SHHS)

**Organization:** National Sleep Research Resource  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Large-scale PSG sleep-staging generalization  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Provide a large conventional PSG cohort for robustness and cross-subject generalization.

**Concrete Next Action:** Request SHHS through NSRR; define which EEG derivations and nights will be used; reserve a non-overlapping external test split and document cohort limitations before training.

**Prerequisite:** A1 — Path V Data & Benchmark Specification.

**Channel / Mechanism:** NSRR data request + downloader.

**Success Condition:** SHHS is accessible and assigned a precise training/validation/test role with leakage controls.

**Key Dependency / Trigger:** NSRR approval and large storage/compute requirements.

**Execution Evidence Note:** SHHS remains one of NSRR's major large-scale PSG cohorts.

---

## Global Rank #19 — OPP-004 — Neuroscience and Psychology of Sleep Lab (NaPS) / CUBRIC Sleep Research

**Organization:** Cardiff University  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Sleep engineering, EEG replay detection, and closed-loop auditory stimulation  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `WAITING_PATH_A`

**Execution Objective:** Convert Path A overlap with the Cardiff sleep-memory ecosystem into a focused discussion on EEG replay detection, sleep engineering and closed-loop auditory control.

**Concrete Next Action:** Prepare A3 with a single technical collaboration ask. Do not open a second contact thread while Penny Lewis/Path A is pending; use the existing relationship/thread or a coordinated follow-up.

**Prerequisite:** A3 + A5 + initial Path V architecture diagram.

**Channel / Mechanism:** Existing Path A relationship / relevant Cardiff lab contact.

**Success Condition:** A meeting, methodological critique, replay/closed-loop guidance, or referral to the appropriate engineer/researcher.

**Key Dependency / Trigger:** Path A coordination.

**Execution Evidence Note:** L8 evidence identifies NaPS/CUBRIC as a direct bridge between TMR, EEG decoding and closed-loop auditory stimulation.

---

## Global Rank #19 — OPP-019 — Center for Ear-EEG / Neurotechnology Group

**Organization:** Aarhus University  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Ear-EEG and sparse-channel sleep staging  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `TRIGGER_DEPENDENT`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Test whether ear-EEG / sparse-channel sensing is a credible later deployment path rather than assuming it from literature alone.

**Concrete Next Action:** First run the EESM17/BOAS reduced-channel analyses. If results justify the direction, send a focused inquiry to the Aarhus ear-EEG group with the observed failure/success modes and ask about sleep-staging constraints and out-of-lab deployment.

**Prerequisite:** A3 + completed first reduced-channel experiment.

**Channel / Mechanism:** Academic lab contact.

**Success Condition:** Expert interpretation or collaboration that clarifies electrode placement, signal quality, and sleep-staging limitations for a wearable path.

**Key Dependency / Trigger:** Trigger: reduced-channel results from F2.

**Execution Evidence Note:** The opportunity is specifically retained for ear-EEG and sparse-channel sleep staging.

---

## Global Rank #19 — OPP-128 — ANT Neuro eego rt / eego Research Ecosystem

**Organization:** ANT Neuro  
**Family:** F5 — Hardware / Industry / Technology Access  
**L8 Contribution:** Reference-grade real-time EEG validation  
**Execution Role:** `TECHNICAL_ACCESS_REQUEST`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Evaluate a research-grade real-time EEG stack as the reference system against which lower-burden hardware can be compared.

**Concrete Next Action:** Complete A2, then request a consultation/demo/quote for eego rt. Ask for exact SDK/LSL access, supported low-channel configurations, timestamp/trigger behavior, overnight practicality, and integration with an external audio-cue process.

**Prerequisite:** A2 — EEG Hardware Technical Requirements Sheet.

**Channel / Mechanism:** ANT Neuro consultation/demo request.

**Success Condition:** A completed technical compatibility matrix, realistic acquisition path/cost, and go/no-go role as reference-grade Path V hardware.

**Key Dependency / Trigger:** Commercial procurement and budget.

**Execution Evidence Note:** Verified current eego rt: real-time/BCI positioning, SDK, LSL integration, high-quality EEG, multiple channel configurations.

---

## Global Rank #19 — OPP-126 — Brain Products + sync2brain Real-Time Closed-Loop EEG Stack

**Organization:** Brain Products / sync2brain  
**Family:** F5 — Hardware / Industry / Technology Access  
**L8 Contribution:** Research-grade low-latency closed-loop EEG  
**Execution Role:** `TECHNICAL_ACCESS_REQUEST`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Assess a high-precision research closed-loop stack for latency/reference benchmarking, not as the default wearable product path.

**Concrete Next Action:** After A2, request technical information/demo from Brain Products/sync2brain focused on end-to-end latency, event detection hooks, trigger/audio integration, supported EEG configurations and research pricing.

**Prerequisite:** A2.

**Channel / Mechanism:** Vendor/research-platform technical inquiry.

**Success Condition:** A documented latency/reference architecture and a clear decision on whether access is justified for Path V benchmarking.

**Key Dependency / Trigger:** Commercial cost/access; likely better as reference system than deployment hardware.

**Execution Evidence Note:** L8 retained this stack for research-grade low-latency closed-loop EEG.

---

## Global Rank #24 — OPP-074 — PhysioNet / CinC 2018 Sleep Arousal Dataset

**Organization:** PhysioNet  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Arousal and sleep-disturbance detection  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Develop the safety-side capability to detect sleep disturbance/arousal around cue delivery.

**Concrete Next Action:** Download the PhysioNet 2018 arousal dataset and create an arousal-analysis subtask in A1; do not make it the first model task—activate modeling after the basic NREM/N3 staging baseline is stable.

**Prerequisite:** A1 plus a working baseline sleep-stage pipeline.

**Channel / Mechanism:** PhysioNet open dataset.

**Success Condition:** Arousal annotations are reproducibly loaded and an explicit post-cue/arousal monitoring experiment is ready to run after staging baseline completion.

**Key Dependency / Trigger:** Depends on the Path V baseline pipeline for proper sequencing.

**Execution Evidence Note:** Dataset is designed around PSG arousal detection and contains relevant physiological channels/annotations.

---

## Global Rank #25 — OPP-001 — Cognitive Neuroscience Laboratory (Ken Paller)

**Organization:** Northwestern University  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** TMR protocol, cue design, and behavioral-validation guidance  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `PATH_A_REPLIED`

**Execution Objective:** Use Ken Paller's existing Path A reply as a referral/conversion path rather than sending another broad review request.

**Concrete Next Action:** Review the existing reply and any suggested lab/group. Prepare one concise follow-on asking for the most appropriate person/group for a concrete TMR translation or validation discussion; send only if it adds a specific next step and does not repeat the earlier question.

**Prerequisite:** A3 + A5 + incorporate the existing Path A reply.

**Channel / Mechanism:** Existing Path A email thread.

**Success Condition:** Referral to a relevant collaborator/lab member or a concrete scientific discussion; otherwise close the loop respectfully without repeated emails.

**Key Dependency / Trigger:** Do not duplicate the already-completed expert-review interaction.

**Execution Evidence Note:** Current Northwestern profile remains directly relevant to sleep, memory and TMR.

---

## Global Rank #25 — OPP-002 — Memory and Sleep Group (Bernhard Staresina)

**Organization:** University of Oxford  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Sleep oscillation physiology and phase-aware closed-loop timing  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `WAITING_PATH_A`

**Execution Objective:** Seek collaboration/guidance on the scientific boundary between stage-aware V1 control and slow-oscillation/event-aware later control.

**Concrete Next Action:** Prepare a collaboration conversion note tied to Path V's stage-aware architecture; do not send a separate Path E email while the Path A message is awaiting response. Use one coordinated follow-up after the agreed waiting window if needed.

**Prerequisite:** A3 + A5 + clear stage-vs-phase question.

**Channel / Mechanism:** Existing Path A email thread.

**Success Condition:** Scientific guidance that changes/validates the control hierarchy or creates a collaboration route.

**Key Dependency / Trigger:** Path A coordination.

**Execution Evidence Note:** Oxford Memory and Sleep work remains directly relevant to high-density EEG, sleep oscillations, TMR and closed-loop stimulation.

---

## Global Rank #25 — OPP-007 — Institute of Medical Psychology and Behavioural Neurobiology / Sleep & Memory in Humans

**Organization:** University Hospital Tübingen  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Sleep-memory physiology and slow-oscillation closed-loop validation  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `PATH_A_AUTO_RESPONSE`

**Execution Objective:** Develop a potential validation relationship around sleep-memory physiology and slow-oscillation closed-loop methodology.

**Concrete Next Action:** Because the Path A contact produced an auto-response, keep the existing thread open. Prepare a short collaboration-specific follow-up for the end of the normal waiting window rather than sending a new cold message.

**Prerequisite:** A3 + A5.

**Channel / Mechanism:** Existing Path A route / relevant Tübingen group contact.

**Success Condition:** Human response leading to scientific guidance, referral, or concrete collaboration feasibility.

**Key Dependency / Trigger:** Path A coordination and availability of the relevant investigator/group.

**Execution Evidence Note:** Tübingen remains a major active sleep-memory and memory-reactivation research environment.

---

## Global Rank #28 — OPP-163 — Phase-Specific Closed-Loop TMR — Open Data + Code Research Stack

**Organization:** Multi-institution academic research collaboration  
**Family:** F8 — Future-Horizon Strategic Technologies  
**L8 Contribution:** Phase-aware TMR timing and closed-loop methodology  
**Execution Role:** `STRATEGIC_TECH_INTEGRATION`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Extract phase-aware control lessons for later generations without expanding V1 scope.

**Concrete Next Action:** Clone the published code; reproduce/inspect the slow-wave phase detection and cue-timing logic offline; request restricted raw data via DUA only if the code/source data are insufficient; create a `phase_aware_reference.md` documenting timing assumptions, latency needs and V1/V2 boundary.

**Prerequisite:** A2 plus a stable stage-aware architecture description.

**Channel / Mechanism:** Published code + paper/source data; restricted data request only if justified.

**Success Condition:** A reproducible technical reference note exists and explicitly identifies what phase-aware control would require beyond V1.

**Key Dependency / Trigger:** Raw dataset has a DUA/restricted-access path; code is public.

**Execution Evidence Note:** Verified: 2025 Nature Communications phase-specific CL-TMR study publishes code and a restricted raw-data access route.

---

## Global Rank #29 — OPP-003 — Cognitive Neuroscience of Sleep Lab (CogNoS)

**Organization:** University of California, Irvine  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** TMR neural decoding and future reactivation-feedback design  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `TRIGGER_DEPENDENT`  
**Initial Execution Status:** `PATH_A_REPLIED`

**Execution Objective:** Use Eitan Schechtman's existing Path A reply as scientific input, then revisit collaboration after Path V produces a concrete technical artifact.

**Concrete Next Action:** Do not ask for another review now. Convert his feedback into Path V requirements (correct timing/NREM detection, arousal avoidance, preserved sleep architecture). After the first working demo/latency audit, send a short update only if there is a new concrete collaboration question.

**Prerequisite:** Path V baseline/demo + A3 + A5.

**Channel / Mechanism:** Existing Path A reply thread.

**Success Condition:** The reply materially shapes Path V now; later success would be a focused follow-up discussion or collaboration on validation.

**Key Dependency / Trigger:** Trigger: a concrete Path V artifact that makes a second contact substantively new.

**Execution Evidence Note:** Current UCI CogNoS uses computational, neuroimaging and memory-reactivation methods during sleep.

---

## Global Rank #29 — OPP-069 — Sleep-EDF Expanded

**Organization:** PhysioNet  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Baseline reproducible sleep-stage classification  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Create the simplest reproducible first sleep-staging baseline before larger/heterogeneous datasets.

**Concrete Next Action:** Download Sleep-EDF Expanded; implement a clean loader and standard N1/N2/N3/REM/Wake epoch pipeline; use it to validate the end-to-end training/evaluation code before moving to BOAS/NSRR.

**Prerequisite:** A1 — Path V Data & Benchmark Specification.

**Channel / Mechanism:** PhysioNet open download.

**Success Condition:** A reproducible baseline model/evaluation pipeline runs end-to-end with fixed splits and documented metrics.

**Key Dependency / Trigger:** No external blocker.

**Execution Evidence Note:** Sleep-EDF Expanded remains openly downloadable and widely used for whole-night sleep-staging baselines.

---

## Global Rank #31 — OPP-104 — Artificial Intelligence Virtual Institute / HPC State Support

**Organization:** Ministry of High-Tech Industry of the Republic of Armenia  
**Family:** F3 — Funding & Institutional Support  
**L8 Contribution:** Compute infrastructure for Path V and ML experiments  
**Execution Role:** `FUNDING_OR_COMPUTE_APPLICATION`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Secure non-dilutive compute capacity for Path V model development and reproducible experiments.

**Concrete Next Action:** Prepare A7 with the Path V compute use case, estimated GPU/CPU/storage needs, planned datasets and 3-month deliverables; verify applicant details and submit through the current AIVI computational-support program.

**Prerequisite:** A7 — Path V Compute Request Brief.

**Channel / Mechanism:** Armenian Ministry of High-Tech Industry / AI Virtual Institute application.

**Success Condition:** Application submitted and, ideally, an AWS compute allocation is approved; if denied, obtain the reason and adjust the compute plan.

**Key Dependency / Trigger:** Program approval/allocation.

**Execution Evidence Note:** Verified 2026-08-21: the 2026 pilot provides AWS compute support; eligible applicants include RA residents, resident legal entities and individual entrepreneurs; stated application time ~5 minutes and provision period up to 3 months from application.

---

## Global Rank #32 — OPP-122 — InteraXon / Muse Research Partnership + Muse SDK

**Organization:** InteraXon / Muse  
**Family:** F5 — Hardware / Industry / Technology Access  
**L8 Contribution:** Wearable EEG/SDK prototyping  
**Execution Role:** `TECHNICAL_ACCESS_REQUEST`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Evaluate Muse as a comparatively accessible wearable EEG/SDK prototyping platform, without assuming it is a sleep-validated V1 solution.

**Concrete Next Action:** After A2, choose the correct Muse route: developer SDK application for independent prototyping, or research-partner contact if an academic/clinical host is established. Ask about raw EEG access, sleep-session duration, timestamps, platform support and licensing for a research prototype.

**Prerequisite:** A2 + clarify independent vs institution-hosted use.

**Channel / Mechanism:** Muse SDK/developer application or research-partner route.

**Success Condition:** SDK access/terms are confirmed and Muse is assigned a bounded role (prototype, research test, or reject for sleep V1).

**Key Dependency / Trigger:** License/use-case review; research applications are selectively reviewed.

**Execution Evidence Note:** Verified current Muse: SDK supports sensor access; academic/clinical researchers are directed to research-partner tools, while developer applications support prototyping.

---

## Global Rank #33 — OPP-164 — Portiloop / Closed-Loop Sleep-Spindle Targeting

**Organization:** Academic closed-loop sleep-neurotechnology ecosystem  
**Family:** F8 — Future-Horizon Strategic Technologies  
**L8 Contribution:** Future spindle/microstate-aware cue control  
**Execution Role:** `STRATEGIC_TECH_INTEGRATION`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Use Portiloop as an open engineering reference for event-aware closed-loop EEG, without prematurely building hardware or adding spindle targeting to V1.

**Concrete Next Action:** Clone the Portiloop software/training repositories; inspect detector/stimulator interfaces; run the software on recorded/simulated data if feasible; document how its modular pipeline differs from the stage-aware V1 architecture.

**Prerequisite:** A2 + stable V1 control diagram.

**Channel / Mechanism:** Open-source software/hardware repositories.

**Success Condition:** A closed-loop architecture comparison note and reusable interface ideas exist; hardware fabrication is explicitly deferred unless Path V later requires event-aware benchmarking.

**Key Dependency / Trigger:** No external dependency for code review; physical hardware build is a later trigger.

**Execution Evidence Note:** Verified: Portiloop openly publishes software/hardware; software supports real-time pattern detection, closed-loop stimulation and raw EEG recording.

---

## Global Rank #34 — OPP-009 — Emmy Noether Memory Consolidation Group (Thomas Schreiner)

**Organization:** Ludwig Maximilian University of Munich  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Oscillatory event detection and sleep-memory physiology  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `WAITING_PATH_A`

**Execution Objective:** Clarify event-level oscillatory markers and how slow oscillation/spindle coupling should influence later cue-control logic.

**Concrete Next Action:** Prepare a concise collaboration follow-up tied to a concrete Path V question. Do not duplicate the active Path A contact; use the same thread after the waiting window or on reply.

**Prerequisite:** A3 + A5 + event-detection question.

**Channel / Mechanism:** Existing Path A thread.

**Success Condition:** Specific methodological guidance, code/data pointer, or collaboration route around oscillatory event detection.

**Key Dependency / Trigger:** Path A coordination.

**Execution Evidence Note:** L8 retained the group specifically for oscillatory event detection and sleep-memory physiology.

---

## Global Rank #35 — OPP-038 — Neuro-Psycholinguistics Laboratory

**Organization:** H. Acharyan Institute of Language, NAS RA  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Language-memory task design with EEG-linked experimentation  
**Execution Role:** `INSTITUTIONAL_COLLABORATION`  
**Execution Timing:** `TRIGGER_DEPENDENT`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Preserve a local route for a later vocabulary/language-memory TMR paradigm with EEG-linked behavioral experimentation.

**Concrete Next Action:** Do not initiate a study now. Once Neuro-TMR has a stable technical prototype and chooses a first memory domain, prepare a local collaboration brief for a vocabulary/language-learning paradigm and request a feasibility discussion.

**Prerequisite:** A4 + selected behavioral memory domain + stable Path V prototype.

**Channel / Mechanism:** Local academic lab contact.

**Success Condition:** A viable experimental-task collaboration and local EEG/behavioral methods path for a later human validation study.

**Key Dependency / Trigger:** Trigger: selection of language/vocabulary as a validation domain and human-study planning.

**Execution Evidence Note:** L8 retained this Armenian lab for language-memory task design with EEG-linked experimentation.

---

## Global Rank #36 — OPP-070 — HMC Sleep Staging Database

**Organization:** Haaglanden Medisch Centrum / PhysioNet  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Clinical external sleep-stage validation  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Provide a clinically heterogeneous open external test for distribution-shift robustness.

**Concrete Next Action:** Download HMC v1.1; validate the 151-recording file list and labels; keep it outside initial training and use it as a clinical external validation set after baseline development.

**Prerequisite:** A1 plus first baseline model.

**Channel / Mechanism:** PhysioNet direct download.

**Success Condition:** HMC loads reproducibly and is frozen as an external clinical test set with no training leakage.

**Key Dependency / Trigger:** No access blocker; full dataset is ~15.7 GB.

**Execution Evidence Note:** Verified 2026-08-21: HMC v1.1 is CC BY 4.0, open access, 151 whole-night heterogeneous clinical PSG recordings with technician hypnograms.

---

## Global Rank #36 — OPP-051 — Hrayr Attarian

**Organization:** Northwestern University Feinberg School of Medicine / Northwestern Medicine  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Sleep medicine and PSG/EEG validation  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Add a clinically grounded sleep-medicine/PSG perspective and potentially strengthen Armenia–US sleep-science bridging.

**Concrete Next Action:** Prepare a short consultation request around PSG validation standards, sleep preservation and clinically meaningful monitoring. Keep the ask advisory and specific; do not ask for a study or broad mentorship.

**Prerequisite:** A3 + A4.

**Channel / Mechanism:** Official academic/clinical contact.

**Success Condition:** A short scientific/clinical consultation, validation guidance, or referral to a suitable sleep-lab collaborator.

**Key Dependency / Trigger:** Needs a concrete validation question to justify contact.

**Execution Evidence Note:** L8 retained Hrayr Attarian for sleep medicine and PSG/EEG validation.

---

## Global Rank #36 — OPP-130 — g.tec Unicorn Hybrid Black + g.Pype

**Organization:** g.tec medical engineering  
**Family:** F5 — Hardware / Industry / Technology Access  
**L8 Contribution:** Developer-oriented EEG/Python prototyping  
**Execution Role:** `TECHNICAL_ACCESS_REQUEST`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Assess a developer-oriented EEG/Python stack as a flexible prototyping alternative.

**Concrete Next Action:** Use public Unicorn/g.Pype documentation to populate A2, then request current pricing/access and confirm overnight/sleep suitability, electrode configuration, LSL/UDP behavior and Python deployment constraints.

**Prerequisite:** A2.

**Channel / Mechanism:** g.tec technical/sales inquiry + public SDK documentation.

**Success Condition:** A complete compatibility/cost matrix and clear role (prototype/reference/not suitable) for Path V.

**Key Dependency / Trigger:** Commercial hardware access.

**Execution Evidence Note:** Verified product documentation: Unicorn BCI Core supports LSL/UDP and g.Pype Python real-time pipelines.

---

## Global Rank #36 — OPP-047 — Neurology & Epileptology / EEG ecosystem

**Organization:** Arabkir Medical Center  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Clinical EEG and neurophysiology expertise  
**Execution Role:** `INSTITUTIONAL_COLLABORATION`  
**Execution Timing:** `TRIGGER_DEPENDENT`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Preserve a local clinical EEG/neurophysiology route for later signal-quality, artifact and clinical-neurophysiology consultation.

**Concrete Next Action:** Do not request access now. After A4 and a defined local validation need exist, request a feasibility conversation focused on EEG expertise and whether the center can support the specific technical/clinical question.

**Prerequisite:** A4 + defined clinical EEG need.

**Channel / Mechanism:** Local medical-center contact.

**Success Condition:** A named neurophysiology contact and a realistic future collaboration boundary.

**Key Dependency / Trigger:** Trigger: concrete clinical EEG/validation requirement.

**Execution Evidence Note:** L8 retained Arabkir for clinical EEG and neurophysiology expertise.

---

## Global Rank #40 — OPP-031 — COBRAIN Scientific-Educational Center for Fundamental Brain Research

**Organization:** Yerevan State Medical University (YSMU)  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Local Armenian neuroscience institutional bridge  
**Execution Role:** `INSTITUTIONAL_COLLABORATION`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Explore whether COBRAIN/YSMU can become an Armenian neuroscience host/bridge for mentorship, institutional affiliation or later research enablement.

**Concrete Next Action:** Prepare A3/A4 and request an exploratory institutional meeting with a narrow agenda: Neuro-TMR evidence base, Path V plan, and what forms of scientific hosting/mentorship/collaboration are actually possible.

**Prerequisite:** A3 + A4.

**Channel / Mechanism:** YSMU/COBRAIN institutional contact.

**Success Condition:** A named host/mentor or explicit next institutional step; if no concrete mechanism exists, document that rather than maintaining a vague relationship.

**Key Dependency / Trigger:** Institutional willingness and fit.

**Execution Evidence Note:** L8 retained COBRAIN specifically as a local Armenian neuroscience institutional bridge.

---

## Global Rank #41 — OPP-006 — DreamTeam — Sleep, Dreams, and Cognition

**Organization:** Paris Brain Institute / Sorbonne Université / INSERM  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Cue eligibility, sleep responsiveness, and stimulation safeguards  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `PATH_A_AUTO_RESPONSE`

**Execution Objective:** Use the DreamTeam/Oudiette Path A overlap to refine cue eligibility, sleep responsiveness and stimulation safeguards.

**Concrete Next Action:** The current Path A interaction has an auto-response. Prepare one concise collaboration-specific follow-up, but wait for the normal response window; do not start a parallel Path E thread.

**Prerequisite:** A3 + A5 + a concrete cue-eligibility/safeguard question.

**Channel / Mechanism:** Existing Path A contact route.

**Success Condition:** Human response, referral, or concrete scientific guidance on responsiveness/safeguards.

**Key Dependency / Trigger:** Path A coordination.

**Execution Evidence Note:** L8 retained DreamTeam for cue eligibility, sleep responsiveness and stimulation safeguards.

---

## Global Rank #42 — OPP-072 — ISRUC-Sleep

**Organization:** University of Coimbra research ecosystem  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Population and night-to-night variability validation  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Test population heterogeneity and limited night-to-night within-subject variability.

**Concrete Next Action:** Download/inspect ISRUC-Sleep; map its three groups; use the repeated-night subset for within-subject stability analysis and the broader groups for cross-condition robustness.

**Prerequisite:** A1 plus baseline loader conventions.

**Channel / Mechanism:** ISRUC-Sleep public dataset.

**Success Condition:** Group-specific experiments are pre-registered in the Path V plan and the dataset loads with two-expert scoring accounted for.

**Key Dependency / Trigger:** No major access blocker; harmonization with other datasets is required.

**Execution Evidence Note:** Verified 2026-08-21: ISRUC-Sleep contains 100 single-session subjects, 8 repeated-session subjects, and 10 healthy subjects with PSG scored by two experts.

---

## Global Rank #43 — OPP-132 — Elemind Closed-Loop EEG Acoustic Neurotechnology

**Organization:** Elemind  
**Family:** F5 — Hardware / Industry / Technology Access  
**L8 Contribution:** Closed-loop EEG-acoustic architecture and potential partnership  
**Execution Role:** `TECHNICAL_ACCESS_REQUEST`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Determine whether Elemind can provide a genuine research/integration route—not merely serve as an architectural analogy.

**Concrete Next Action:** After A2, send a narrow partnership/technical inquiry asking whether raw EEG, real-time API/SDK access, external event markers and externally controlled acoustic stimulation are available for research collaboration.

**Prerequisite:** A2 + short B2B/research use-case paragraph.

**Channel / Mechanism:** Official partnership/company contact.

**Success Condition:** Written confirmation of integration rights/capabilities and a feasible research-access path; otherwise mark the platform as reference-only for later execution planning.

**Key Dependency / Trigger:** Vendor-controlled access and unverified public integration surface.

**Execution Evidence Note:** L8 retained Elemind for closed-loop EEG-acoustic architecture and potential partnership, with integration access still a key uncertainty.

---

## Global Rank #44 — OPP-134 — European Sleep Research Society / Sleep Europe

**Organization:** European Sleep Research Society  
**Family:** F6 — Networks / Events / Multipliers  
**L8 Contribution:** Sleep-specific scientific networking and collaboration  
**Execution Role:** `EVENT_OR_NETWORK_ACTION`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Use Sleep Europe/ESRS to enter the concentrated European sleep-science and sleep-technology network with a concrete collaboration agenda.

**Concrete Next Action:** Immediately verify participation eligibility and digital/onsite options before paying. If eligible, make a go/no-go decision before regular registration closes; if attending, build a target list of relevant sleep-technology/TMR/wearable researchers and sessions instead of treating attendance as generic networking.

**Prerequisite:** Budget/eligibility check + A3.

**Channel / Mechanism:** ESRS Sleep Europe 2026 registration / congress participation.

**Success Condition:** A documented attendance decision; if attending, a pre-event target list and meeting/outreach plan tied to Neuro-TMR objectives.

**Key Dependency / Trigger:** Registration cost, travel/eligibility; participant terms must be checked before purchase.

**Execution Evidence Note:** Verified 2026-08-21: Sleep Europe 2026 is Oct 20–23 in Maastricht, hybrid; regular registration is open through Sep 30; Sleep Technology is a dedicated track.

---

## Global Rank #44 — OPP-066 — MESA Sleep

**Organization:** National Sleep Research Resource  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Home PSG and actigraphy multimodal comparison  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Bridge clinical PSG with lower-burden home/wearable-style measurements through concurrent actigraphy.

**Concrete Next Action:** Request MESA Sleep via NSRR; after approval, document PSG and actigraphy overlap and define a secondary multimodal comparison experiment rather than a primary V1 EEG model task.

**Prerequisite:** A1 — Path V Data & Benchmark Specification.

**Channel / Mechanism:** NSRR data request.

**Success Condition:** Access is submitted/approved and MESA has a clearly bounded multimodal role that does not distract from EEG-first V1 validation.

**Key Dependency / Trigger:** NSRR access approval.

**Execution Evidence Note:** NSRR describes MESA Sleep as unattended PSG plus wrist actigraphy in a large cohort.

---

## Global Rank #44 — OPP-077 — Dreem Open Datasets (DOD-H / DOD-O)

**Organization:** Dreem research ecosystem  
**Family:** F2 — Data / Research Infrastructure & Path V Resources  
**L8 Contribution:** Scorer disagreement and sleep-stage label uncertainty  
**Execution Role:** `DIRECT_RESOURCE_USE`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Quantify human scorer disagreement and avoid treating a single hypnogram as perfect ground truth.

**Concrete Next Action:** Download DOD-H/DOD-O and the reference code; reproduce label loading; calculate inter-scorer agreement/consensus ceilings and use that analysis to contextualize Path V model performance.

**Prerequisite:** A1 plus standard label schema.

**Channel / Mechanism:** Dreem open dataset / Zenodo + public code.

**Success Condition:** Human agreement/consensus statistics are reproduced and incorporated into Path V reporting as a realistic performance ceiling/context.

**Key Dependency / Trigger:** Legacy code may require environment modernization; dataset itself is openly distributed.

**Execution Evidence Note:** Verified: Dreem's open repository provides DOD-H/DOD-O download guidance and benchmark code with multiple-scored sleep data.

---

## Global Rank #47 — OPP-005 — Cognitive Biopsychology and Methods / Sleep Laboratory (Björn Rasch)

**Organization:** University of Fribourg  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** TMR cueing and sleep-memory experimental design  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `WAITING_PATH_A`

**Execution Objective:** Convert the existing Path A contact into a collaboration path around TMR cue design, sleep-stage dependence and experimental protocol quality.

**Concrete Next Action:** Keep the current Path A email as the single channel. Prepare a one-page collaboration follow-up but do not send before the waiting window; if a reply arrives, continue naturally in-thread.

**Prerequisite:** A3 + A5.

**Channel / Mechanism:** Existing Path A email thread.

**Success Condition:** Specific methodological guidance, protocol review, or collaboration/referral pathway.

**Key Dependency / Trigger:** Path A coordination.

**Execution Evidence Note:** L8 retained the Fribourg group for TMR cueing and sleep-memory experimental design.

---

## Global Rank #48 — OPP-143 — CuttingGardens / CuttingEEG Community

**Organization:** CuttingEEG  
**Family:** F6 — Networks / Events / Multipliers  
**L8 Contribution:** EEG methods and technical community  
**Execution Role:** `EVENT_OR_NETWORK_ACTION`  
**Execution Timing:** `EXECUTE_NOW`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Use the near-term CuttingGardens event for concrete EEG-methods learning and technical-network access.

**Concrete Next Action:** This week, inspect the 25 garden programs, choose a geographically/financially feasible participation route, verify registration, and select sessions/tutorials relevant to preprocessing, real-time EEG, ML and open/reproducible EEG. If participation is not feasible, capture publicly available program/materials for methods review.

**Prerequisite:** A2 + practical travel/registration check.

**Channel / Mechanism:** CuttingGardens 2026 local-garden registration / program.

**Success Condition:** A go/no-go participation decision plus a focused methods agenda; if attending, identify people/sessions relevant to Path V rather than broad networking.

**Key Dependency / Trigger:** Local garden availability, travel/registration feasibility.

**Execution Evidence Note:** Verified 2026-08-21: CuttingGardens runs Sep 21–25, 2026 across 25 gardens with EEG/MEG methods tutorials and networking.

---

## Global Rank #49 — OPP-008 — York Sleep / Memory Reactivation Research (Scott Cairney and collaborators)

**Organization:** University of York  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** TMR protocol design, EEG reactivation markers, and emotional-memory validation  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `WAITING_PATH_A`

**Execution Objective:** Develop a potential collaboration around TMR protocols, EEG reactivation markers and behavioral/emotional-memory validation.

**Concrete Next Action:** Do not duplicate the Path A message to Scott Cairney. Prepare a collaboration conversion note that can be sent in-thread after the waiting window or used immediately if he replies.

**Prerequisite:** A3 + A5.

**Channel / Mechanism:** Existing Path A email thread.

**Success Condition:** Protocol/method feedback, relevant dataset/material access, or a concrete research conversation.

**Key Dependency / Trigger:** Path A coordination.

**Execution Evidence Note:** Verified current York profile: sleep and emotional memory, memory reactivation, PSG; active SLEEPAWAY project runs 2025–2030.

---

## Global Rank #50 — OPP-138 — International Brain Research Organization

**Organization:** IBRO  
**Family:** F6 — Networks / Events / Multipliers  
**L8 Contribution:** Neuroscience training, mobility, and grant network  
**Execution Role:** `EVENT_OR_NETWORK_ACTION`  
**Execution Timing:** `TRIGGER_DEPENDENT`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Keep IBRO as a high-quality route to neuroscience training, mobility, grants and international introductions, but act only on a concrete matching program.

**Concrete Next Action:** Create a recurring opportunity check for IBRO schools, travel support, fellowships and regionally relevant calls; record only live opportunities whose stage/eligibility fits the project. Do not spend outreach effort on IBRO generically.

**Prerequisite:** None beyond a simple monitoring entry in A6.

**Channel / Mechanism:** IBRO program monitoring / specific future call.

**Success Condition:** A live eligible program is identified with a clear application/action path; otherwise the opportunity remains monitored without consuming active outreach time.

**Key Dependency / Trigger:** Trigger: a specific relevant open call or event.

**Execution Evidence Note:** L8 retained IBRO for neuroscience training, mobility and grant-network value rather than a single immediate transaction.

---

## Global Rank #50 — OPP-127 — Wearable Sensing DSI EEG + DSI API

**Organization:** Wearable Sensing  
**Family:** F5 — Hardware / Industry / Technology Access  
**L8 Contribution:** Dry mobile EEG with developer API  
**Execution Role:** `TECHNICAL_ACCESS_REQUEST`  
**Execution Timing:** `PREPARE_THEN_EXECUTE`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Evaluate dry mobile EEG as a lower-burden research platform with real-time developer access.

**Concrete Next Action:** After A2, request current DSI configuration/pricing and confirm API/LSL streaming, timestamp behavior, battery/overnight comfort, electrode locations and research support. Compare directly against CGX, Bitbrain and Muse rather than evaluating in isolation.

**Prerequisite:** A2.

**Channel / Mechanism:** Wearable Sensing technical/sales contact.

**Success Condition:** Comparable vendor matrix and clear go/no-go role for sleep-oriented Path V experiments.

**Key Dependency / Trigger:** Commercial access; sleep-specific validation is less direct than top F5 candidates.

**Execution Evidence Note:** DSI systems are research EEG instruments with developer/API capabilities; L8 retained this candidate for dry mobile EEG.

---

## Global Rank #50 — OPP-025 — In-Ear Physiological Sensing / Danilo Mandic Research

**Organization:** Imperial College London  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** In-ear EEG plus multimodal physiological sensing  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `TRIGGER_DEPENDENT`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Explore in-ear EEG + multimodal physiology only if reduced-channel experiments show that this direction is worth deeper investment.

**Concrete Next Action:** After EESM17/BOAS analysis, prepare a specific technical question for the Imperial in-ear sensing ecosystem around electrode placement, sleep-state fidelity and multimodal arousal monitoring. Do not send a generic collaboration request beforehand.

**Prerequisite:** A3 + reduced-channel experiment results.

**Channel / Mechanism:** Academic research contact.

**Success Condition:** Expert interpretation or collaboration that changes the future wearable-sensing roadmap.

**Key Dependency / Trigger:** Trigger: evidence from Path V that in-ear/reduced-channel sensing is promising or exposes a specific failure mode.

**Execution Evidence Note:** L8 retained this opportunity for in-ear EEG plus multimodal physiological sensing.

---

## Global Rank #50 — OPP-029 — Mobile EEG / Neuropsychology Ecosystem (Stefan Debener)

**Organization:** University of Oldenburg  
**Family:** F1 — Scientific Collaboration & Expertise  
**L8 Contribution:** Mobile/around-ear EEG and real-world acquisition  
**Execution Role:** `SCIENTIFIC_OUTREACH`  
**Execution Timing:** `TRIGGER_DEPENDENT`  
**Initial Execution Status:** `NOT_STARTED`

**Execution Objective:** Use mobile/around-ear EEG expertise to test real-world acquisition constraints after the reduced-sensor question has empirical results.

**Concrete Next Action:** After the first sensor-reduction experiment, contact the Oldenburg mobile EEG ecosystem with a concrete result/problem involving signal quality, electrode placement or home recording. Ask for methods guidance/collaboration, not general mentorship.

**Prerequisite:** A3 + reduced-channel result.

**Channel / Mechanism:** Academic research contact.

**Success Condition:** A methods-level answer or collaboration path that improves real-world EEG acquisition strategy.

**Key Dependency / Trigger:** Trigger: reduced-channel/home-EEG result from Path V.

**Execution Evidence Note:** L8 retained this opportunity for mobile/around-ear EEG and real-world acquisition.

---

# 8. Time-Sensitive Items Identified on 2026-08-21

These are not yet formal execution waves, but they should be protected from accidental delay:

- **OPP-143 — CuttingGardens 2026:** event runs **21–25 September 2026**; participation/program decision should be made promptly.
- **OPP-134 — Sleep Europe 2026:** congress runs **20–23 October 2026**; regular registration is open through **30 September 2026**. Participation eligibility/terms must be checked before payment.
- **OPP-104 — Armenian AI Virtual Institute compute support:** the 2026 AWS compute-support pilot is active; prepare the Path V compute brief and apply while the program is available.

# 9. E1 Completion Gate

**53 / 53 active opportunities have an explicit execution interpretation.**

This document establishes:

- what value is being sought from each opportunity;
- the first concrete action;
- the prerequisite;
- the timing state;
- the execution channel;
- the success condition;
- the dependency/trigger;
- and Path A coordination where applicable.

## What E1 Does Not Yet Decide

E1 does **not** decide:

- Wave 1 / Wave 2 / later execution groups;
- exact outreach dates for all candidates;
- message wording;
- budget allocation;
- hardware purchases;
- human-study initiation;
- reserve activation.

Those decisions should be made next by comparing the execution-readiness map, dependencies, time-sensitive windows, and the value of actions that unlock multiple downstream opportunities.

**E1 — ACTIVE OPPORTUNITY EXECUTION MAPPING: COMPLETE**

**Next formal operation:** derive execution sequencing and waves from this ledger.

# 10. External Current-State Evidence Anchors

Targeted current-state verification used during execution mapping (checked 2026-08-21):

- Dreamento open-source toolbox — https://github.com/dreamento/dreamento
- BOAS on NEMAR — https://nemar.org/dataset/on005555
- NEMAR — https://nemar.org/
- HMC Sleep Staging Database — https://physionet.org/content/hmc-sleep-staging/1.1/
- ISRUC-Sleep — https://sleeptight.isr.uc.pt/
- Dreem open benchmark code — https://github.com/Dreem-Organization/dreem-learning-open
- Bitbrain Ikon Sleep — https://www.bitbrain.com/neurotechnology-products/textile-eeg/ikon-sleep
- Bitbrain SDK — https://www.bitbrain.com/neurotechnology-products/software/programming-tools
- CGX Patch EEG — https://www.cgxsystems.com/patcheeg
- ANT Neuro eego rt — https://www.ant-neuro.com/products/eego-rt
- Muse developer/research route — https://choosemuse.com/pages/developers
- Armenia AI Virtual Institute — https://hightech.gov.am/en/artificial-intelligence-virtual-institute
- ETH SleepLoopFM — https://sms.hest.ethz.ch/research/current-research-projects/sleep-robotics/ai-based-real-time-sleep-decoding.html
- Surrey Sleep Research Centre — https://www.surrey.ac.uk/surrey-sleep-research-centre
- NUS Centre for Sleep and Cognition — https://medicine.nus.edu.sg/csc/research-labs/sleep-and-cognition-laboratory/
- CuttingGardens 2026 — https://cuttingeeg.org/cuttinggardens2026/
- Sleep Europe 2026 — https://esrs.eu/sleep-congress/
- Phase-specific closed-loop TMR study — https://www.nature.com/articles/s41467-025-57602-2
- Portiloop software — https://github.com/Portiloop/portiloop-software

Where a candidate's execution still depends on collaboration willingness, institutional policy, vendor licensing, or future study design, this ledger intentionally records that uncertainty rather than inventing an answer.
