# Path E — Execution Phase Classification

**Date:** 2026-08-21  
**Source universe:** 53 active `KEEP` opportunities  
**Purpose:** Convert the active opportunity portfolio into one simple macro road:

> **PRE-PATH V → PATH V → POST-PATH V**  
> with **Path A ↔ Path E coordination running in parallel**

This file does **not** re-rank or re-score opportunities. It classifies each active opportunity by the point at which using it is expected to create the greatest value for Neuro-TMR.

---

## 1. Classification Rule

### `PRE_PATH_V`
Act on or initiate these opportunities **before serious Validation-Lite execution begins** because they can unlock infrastructure, prevent methodological mistakes, create local support, or remove a major execution dependency.

**Important:** Pre-Path V is not a hard requirement to wait indefinitely for external replies. Once the necessary outreach/access action has been made and the dependency is recorded, Path V may begin.

### `PATH_V`
These opportunities are part of the **Validation-Lite process itself**: datasets, infrastructure, open tooling, model/reference systems, acquisition/synchronization resources, or scientific input that becomes useful after the first baseline exists.

### `POST_PATH_V`
Activate these primarily **after the first coherent Path V evidence package exists**. At that point Neuro-TMR can approach scientists, institutions, hardware companies and strategic partners with a result, a concrete failure mode, a tested architecture, or a defined validation need.

### `PATH_A = YES`
This is a **parallel dependency flag**, not a fourth phase. Path E must obey A5 and avoid duplicate outreach while the Path A interaction is active.

---

# 2. PRE-PATH V — Act / Initiate Before Validation-Lite

**Count: 8**

The goal is to remove preventable blockers and obtain high-leverage guidance before technical work becomes expensive.

| OPP ID | Opportunity | Why this stage | Path A? |
|---|---|---|:---:|
| OPP-078A | NEMAR Research Infrastructure | Set up the open EEG discovery/download/compute workflow before validation begins. | NO |
| OPP-064 | National Sleep Research Resource (NSRR) | Open the NSRR account/request path early so approval clocks do not delay Path V. | NO |
| OPP-011 | Sleep and Memory Laboratory (Cecilia Forcato) | Automatic sleep-event detection and cue scheduling can improve the validation design before engineering deepens. | YES |
| OPP-014 | Hong-Viet V. Ngo-Dehning — Sleep, Memory and Real-Time Stimulation | Real-time stimulation timing and latency guidance can shape the Path V control assumptions before implementation. | YES |
| OPP-015 | Centre for Sleep and Cognition / Sleep and Cognition Laboratory (Michael Chee) | Real-time staging, acoustic stimulation and wearable-translation expertise can challenge the validation design before execution. | NO |
| OPP-039 | Neurotechnology Laboratory, Engineering City | Local EEG equipment and signal-processing support could materially improve how Path V is executed. | NO |
| OPP-031 | COBRAIN Scientific-Educational Center for Fundamental Brain Research | A local neuroscience host/affiliation route may unlock mentorship, compute eligibility and later institutional support. | NO |
| OPP-104 | Artificial Intelligence Virtual Institute / HPC State Support | Compute support is an enabling resource for Path V and should be pursued before the heavier validation workload starts. | NO |

### Current practical note

- **OPP-104 AIVI:** eligibility inquiry has already been sent; currently waiting for a response.
- **OPP-011 / OPP-014:** prepare the Path E collaboration route, but do not duplicate the active Path A contact. Their responses should not block Path V indefinitely.
- **OPP-078A / OPP-064:** opening the infrastructure/access route before Path V prevents later approval/setup delays.

### Pre-Path V completion condition

Before entering Path V deeply, Neuro-TMR should have:

1. NEMAR workflow ready;
2. NSRR access/request route opened;
3. AIVI route either active, resolved, or recorded as an external dependency;
4. the first local technical/institutional contacts initiated where useful;
5. the NUS scientific-methods outreach initiated;
6. Path A-overlap preparation complete for Forcato/Ngo without duplicate contact.

Then **start Path V even if some external replies are still pending**.

---

# 3. PATH V — Validation-Lite Execution

**Count: 14**

These opportunities should be used while building and validating the first technical evidence.

| OPP ID | Opportunity | Why this stage | Path A? |
|---|---|---|:---:|
| OPP-078B | Dreamento Open Sleep-EEG / Closed-Loop Research Toolbox | Use as a real-time closed-loop engineering reference while Neuro-TMR builds its own validated inference path. | NO |
| OPP-075 | Bitbrain Open Access Sleep (BOAS) | Core paired wearable-EEG versus PSG resource for the reduced-sensor V1 question. | NO |
| OPP-067 | STAGES | Use during Validation-Lite for multi-site generalization after the baseline pipeline is stable. | NO |
| OPP-123 | OpenBCI Cyton / Ganglion Open Hardware Ecosystem | Use the open software/hardware ecosystem during Path V for a hardware-agnostic acquisition and streaming prototype. | NO |
| OPP-076 | Ear-EEG Sleep Monitoring 2017 (EESM17) | Use during Path V for ear-EEG / reduced-channel feasibility analysis. | NO |
| OPP-020 | SleepLoopFM / Sensory-Motor Systems Lab | Approach after the first baseline exists, while Path V is active, with a concrete causal-staging/latency/gating question. | NO |
| OPP-016 | Swartz Center for Computational Neuroscience (SCCN) | Use SCCN/EEGLAB/LSL tooling during Path V for preprocessing, synchronization and event-stream handling. | NO |
| OPP-065 | Sleep Heart Health Study (SHHS) | Use as a large-scale PSG generalization resource during Validation-Lite. | NO |
| OPP-074 | PhysioNet / CinC 2018 Sleep Arousal Dataset | Use later inside Path V as the dedicated arousal/sleep-disturbance safety task. | NO |
| OPP-069 | Sleep-EDF Expanded | Use as the first reproducible end-to-end sleep-staging baseline. | NO |
| OPP-070 | HMC Sleep Staging Database | Keep as a clinical external-validation resource within Path V. | NO |
| OPP-072 | ISRUC-Sleep | Use during Path V for population, scorer and night-to-night variability analysis. | NO |
| OPP-066 | MESA Sleep | Use as a secondary multimodal/home-context comparison during Path V. | NO |
| OPP-077 | Dreem Open Datasets (DOD-H / DOD-O) | Use during Path V to quantify scorer disagreement and label uncertainty. | NO |

### Recommended Path V logic

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

MESA remains a secondary multimodal comparison rather than a core V1 requirement.

---

# 4. POST-PATH V — Activate With Core Evidence

**Count: 31**

These opportunities become materially stronger once Neuro-TMR can show what Validation-Lite actually produced.

| OPP ID | Opportunity | Why this stage | Path A? |
|---|---|---|:---:|
| OPP-124 | Bitbrain Ikon Sleep + SDK Ecosystem | Hardware/vendor discussion becomes stronger after Neuro-TMR has concrete model, channel and integration evidence. | NO |
| OPP-046 | Neurology, Electrophysiology & Sleep Laboratory | Local PSG/EEG validation is most useful after a concrete Path V result defines exactly what must be validated. | NO |
| OPP-129 | CGX Patch EEG + Sleep Technology / Partner Program | Low-channel hardware evaluation should follow core reduced-sensor evidence and a concrete device-test requirement. | NO |
| OPP-121 | Earable Neuroscience / FRENZ Research & B2B Partnership | A research/B2B conversation is materially stronger once Neuro-TMR can show a working validation artifact. | NO |
| OPP-026 | Surrey Sleep Research Centre | Surrey is best approached with an actual reduced-sensor result that can be methodologically challenged. | NO |
| OPP-004 | Neuroscience and Psychology of Sleep Lab (NaPS) / CUBRIC Sleep Research | Closed-loop/replay collaboration is stronger after a working Path V artifact and must remain coordinated with Path A. | YES |
| OPP-019 | Center for Ear-EEG / Neurotechnology Group | Approach the ear-EEG group after BOAS/EESM results create a specific success/failure mode to discuss. | NO |
| OPP-128 | ANT Neuro eego rt / eego Research Ecosystem | Reference-grade hardware access should be pursued only when Path V establishes a concrete benchmarking need. | NO |
| OPP-126 | Brain Products + sync2brain Real-Time Closed-Loop EEG Stack | Research-grade closed-loop hardware is better evaluated after the software/latency requirements are evidenced. | NO |
| OPP-001 | Cognitive Neuroscience Laboratory (Ken Paller) | TMR protocol and behavioral collaboration becomes more actionable after the technical Validation-Lite foundation exists. | YES |
| OPP-002 | Memory and Sleep Group (Bernhard Staresina) | Phase-aware physiology is a later refinement and should follow evidence from the stage-aware V1 path. | YES |
| OPP-007 | Institute of Medical Psychology and Behavioural Neurobiology / Sleep & Memory in Humans | Slow-oscillation closed-loop validation belongs after the primary stage-aware Validation-Lite evidence. | YES |
| OPP-163 | Phase-Specific Closed-Loop TMR — Open Data + Code Research Stack | Phase-specific TMR is future-horizon architecture and should not distract from primary stage-aware validation. | NO |
| OPP-003 | Cognitive Neuroscience of Sleep Lab (CogNoS) | Existing Path A feedback should shape Path V now; a new collaboration contact should wait for a concrete demo/result. | YES |
| OPP-122 | InteraXon / Muse Research Partnership + Muse SDK | Wearable SDK/device access becomes more valuable after the required sensing and integration constraints are evidenced. | NO |
| OPP-164 | Portiloop / Closed-Loop Sleep-Spindle Targeting | Spindle/microstate-aware control is later-generation work and should follow the stage-aware Validation-Lite gate. | NO |
| OPP-009 | Emmy Noether Memory Consolidation Group (Thomas Schreiner) | Oscillatory event-level collaboration is stronger after the basic sleep-stage/control pipeline exists. | YES |
| OPP-038 | Neuro-Psycholinguistics Laboratory | Language-memory human validation should wait for a stable prototype and a selected behavioral domain. | NO |
| OPP-051 | Hrayr Attarian | Clinical PSG/sleep-medicine guidance becomes most concrete when Path V produces a defined validation question. | NO |
| OPP-130 | g.tec Unicorn Hybrid Black + g.Pype | Developer EEG hardware evaluation should wait until Path V defines the real acquisition requirements. | NO |
| OPP-047 | Neurology & Epileptology / EEG ecosystem | Clinical EEG consultation should begin only when a concrete local neurophysiology/validation need exists. | NO |
| OPP-006 | DreamTeam — Sleep, Dreams, and Cognition | Cue-responsiveness/safeguard collaboration should be revisited with a concrete Path V artifact and through Path A. | YES |
| OPP-132 | Elemind Closed-Loop EEG Acoustic Neurotechnology | A strategic closed-loop industry partnership is stronger after Neuro-TMR can show technical evidence rather than only architecture. | NO |
| OPP-134 | European Sleep Research Society / Sleep Europe | The 2026 route is blocked; future ESRS/Sleep Europe networking is more valuable once core Path V evidence exists. | NO |
| OPP-005 | Cognitive Biopsychology and Methods / Sleep Laboratory (Björn Rasch) | TMR cueing/experimental-design collaboration is better leveraged after the technical prototype is grounded. | YES |
| OPP-143 | CuttingGardens / CuttingEEG Community | The 2026 attendance route is blocked; future Garden/replay/network use is better treated after core Path V progress. | NO |
| OPP-008 | York Sleep / Memory Reactivation Research (Scott Cairney and collaborators) | TMR/EEG-reactivation collaboration should be revisited after a concrete validation artifact and through Path A. | YES |
| OPP-138 | International Brain Research Organization | Keep IBRO monitored; activate a matching training/grant/network route when a concrete call aligns with the post-validation stage. | NO |
| OPP-127 | Wearable Sensing DSI EEG + DSI API | Dry mobile EEG vendor evaluation should follow a concrete sensing requirement from Path V. | NO |
| OPP-025 | In-Ear Physiological Sensing / Danilo Mandic Research | In-ear/multimodal collaboration should follow reduced-channel results that justify deeper investigation. | NO |
| OPP-029 | Mobile EEG / Neuropsychology Ecosystem (Stefan Debener) | Mobile/around-ear EEG collaboration should follow a real reduced-channel/home-acquisition result. | NO |

### Post-Path V activation principle

The trigger is **not a perfect final product**.

It is the existence of a coherent first evidence package—for example:

- a reproducible staging pipeline;
- a product-relevant reduced-channel result;
- at least one genuine external/generalization result;
- a documented real-time/control architecture or latency finding;
- clear remaining technical/scientific questions.

At that point, collaboration becomes evidence-backed rather than concept-only.

---

# 5. Path A ↔ Path E — Parallel Coordination

**Path A-overlap opportunities: 11**

These opportunities keep their ideal Path E stage above, but A5 controls **when** contact may occur.

| OPP ID | Opportunity | Ideal Path E stage | Current Path A state |
|---|---|---|---|
| OPP-011 | Sleep and Memory Laboratory (Cecilia Forcato) | `PRE_PATH_V` | `WAITING_PATH_A` |
| OPP-014 | Hong-Viet V. Ngo-Dehning — Sleep, Memory and Real-Time Stimulation | `PRE_PATH_V` | `WAITING_PATH_A` |
| OPP-004 | Neuroscience and Psychology of Sleep Lab (NaPS) / CUBRIC Sleep Research | `POST_PATH_V` | `WAITING_PATH_A` |
| OPP-001 | Cognitive Neuroscience Laboratory (Ken Paller) | `POST_PATH_V` | `PATH_A_REPLIED` |
| OPP-002 | Memory and Sleep Group (Bernhard Staresina) | `POST_PATH_V` | `WAITING_PATH_A` |
| OPP-007 | Institute of Medical Psychology and Behavioural Neurobiology / Sleep & Memory in Humans | `POST_PATH_V` | `PATH_A_AUTO_RESPONSE` |
| OPP-003 | Cognitive Neuroscience of Sleep Lab (CogNoS) | `POST_PATH_V` | `PATH_A_REPLIED` |
| OPP-009 | Emmy Noether Memory Consolidation Group (Thomas Schreiner) | `POST_PATH_V` | `WAITING_PATH_A` |
| OPP-006 | DreamTeam — Sleep, Dreams, and Cognition | `POST_PATH_V` | `PATH_A_AUTO_RESPONSE` |
| OPP-005 | Cognitive Biopsychology and Methods / Sleep Laboratory (Björn Rasch) | `POST_PATH_V` | `WAITING_PATH_A` |
| OPP-008 | York Sleep / Memory Reactivation Research (Scott Cairney and collaborators) | `POST_PATH_V` | `WAITING_PATH_A` |

### Rule

```text
Path A contact
    ↓
wait / receive reply
    ↓
convert feedback into project changes
    ↓
A5 decision
    ↓
enter PRE_PATH_V or POST_PATH_V action when justified
```

A Path A reply does **not** automatically mean “ask for collaboration.” A new Path E contact must have a specific new reason.

---

# 6. Current Exceptions Already Resolved

### OPP-134 — Sleep Europe
The 2026 participation route is currently blocked by the over-18 scientific-programme rule. Keep the opportunity for a later eligible cycle, preferably after Path V evidence exists.

### OPP-143 — CuttingGardens
The normal 2026 attendance route is currently blocked by participant-level fit and lack of global travel/accommodation support. Re-open only on a concrete Garden sponsorship/hosting trigger or for useful post-event material/replay.

### OPP-104 — AIVI
The compute-support route remains active and is waiting for an eligibility response. It is a Pre-Path V enabler, but Path V should not wait indefinitely if the response is delayed.

---

# 7. Final Macro Road

```text
                    PATH E

        ┌─────────────────────────┐
        │       PRE-PATH V        │
        │ unlock / clarify / set  │
        │ infrastructure & support│
        └────────────┬────────────┘
                     ↓
        ┌─────────────────────────┐
        │         PATH V          │
        │     VALIDATION-LITE     │
        │ build the core evidence │
        └────────────┬────────────┘
                     ↓
        ┌─────────────────────────┐
        │       POST-PATH V       │
        │ scientific / hardware / │
        │ institutional leverage  │
        └─────────────────────────┘

PATH A ──► expert responses ──► A5 ──► appropriate Path E stage
```

---

# 8. Coverage Check

| Classification | Count |
|---|---:|
| `PRE_PATH_V` | **8** |
| `PATH_V` | **14** |
| `POST_PATH_V` | **31** |
| **Total active opportunities** | **53** |
| Path A dependency (`YES`) | **11** |

**Every one of the 53 active opportunities is classified exactly once into the three-stage Path E road.**

---

# Classification Conclusion

> **First, initiate the opportunities that can materially enable or improve Validation-Lite. Then execute Path V using the technical/data resources that belong inside validation. Once core evidence exists, activate the larger scientific, institutional, hardware and strategic collaboration universe from a much stronger position. In parallel, keep Path A expert relationships asynchronous and route any collaboration through A5.**

**PATH E — EXECUTION PHASE CLASSIFICATION: COMPLETE**
