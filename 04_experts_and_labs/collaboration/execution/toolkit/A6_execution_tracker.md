# A6 — Path E Execution Tracker

Date opened: 2026-08-21
Last updated: 2026-09-04
Stage: PATH E EXECUTION / PRE-PATH V
Toolkit Artifact: A6 — Live operational log for actions taken on active opportunities
Related documents: execution_roadmap.md, active_opportunity_execution_ledger.md, final_active_opportunities.md, path_e_execution_phase_classification.md, Pre-Path V/pre_path_v_immediate_execution.md

## Purpose

This file is the live record of what has actually been done for Path E opportunities.

active_opportunity_execution_ledger.md = what should be done for every active opportunity.  
execution_roadmap.md = what should happen first and in what order.  
path_e_execution_phase_classification.md = which execution phase each opportunity belongs to.  
Pre-Path V/pre_path_v_immediate_execution.md = what must be completed or initiated before Path V.  
A6_execution_tracker.md = what has actually been done, what is active, what is waiting, and what happens next.

Update this file whenever an email is sent, a call is made, an application is submitted, access is requested, a technical opportunity is activated, a reply arrives, a meeting is scheduled, or an opportunity becomes blocked/completed.

## Status Vocabulary

| Status           | Meaning                                                                  |
| ---------------- | ------------------------------------------------------------------------ |
| NOT_STARTED      | No execution action has started yet.                                     |
| PREPARING        | Material or information is being prepared before action.                 |
| SCHEDULED        | A concrete action is planned for a specific time/date.                   |
| ACTIONED         | The outbound action has been completed.                                  |
| WAITING_RESPONSE | Action was completed and we are waiting for the external party.          |
| IN_PROGRESS      | The opportunity is actively being executed through one or more steps.    |
| BLOCKED          | Progress cannot continue until an external constraint is resolved.       |
| COMPLETED        | The current intended objective has been achieved.                        |
| CLOSED           | We deliberately stop current execution for this opportunity.             |
| TRIGGER_WAIT     | Active opportunity is intentionally waiting for a later project trigger. |

## Live Execution Board

| OPP ID   | Opportunity                                                            | Current Action                                                                                                                                                               | Channel                    | Date       | Status           | Next Action                                                                                                                                                        | Next Check / Target                                      | Notes                                                                                                                                                                                                                                                                                                                                 |
| -------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------- | ---------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OPP-015  | Centre for Sleep and Cognition / Michael Chee — NUS                      | Candidate-specific scientific-methods outreach sent on validation evidence required before reduced-channel EEG N3 estimates are trusted to gate acoustic cues in a stage-aware closed-loop system | Email                      | 2026-09-04 | WAITING_RESPONSE | Wait for reply. Convert useful guidance into an explicit Path V requirement/experiment. If referred, follow the referral. If no reply, send one concise follow-up after ~7–10 business days | Follow-up window: ~2026-09-15 to 2026-09-18              | Outreach was grounded in Chee/NUS work on real-time sleep staging, confidence-aware inference, acoustic intervention, external validation and wearable translation. No attachments, funding request, mentorship request, hardware request or broad collaboration ask was made. |
| OPP-039  | Engineering City Neurotechnology Laboratory / EIF Science Incubator         | Deep local-collaboration due diligence completed and targeted institutional collaboration inquiry sent through the official High-Tech Accelerator / EIF route, requesting connection to the relevant Neurotechnology Laboratory technical/research lead and discussion of a small EEG/closed-loop validation collaboration | Email                      | 2026-09-04 | WAITING_RESPONSE | Wait for reply. If routed to a technical lead, schedule a short technical meeting/lab visit and build a direct capability map. If no reply after ~2–3 business days, use one controlled follow-up, preferably by phone when available | Follow-up target: ~2026-09-08 to 2026-09-09              | Local strategic opportunity. Public evidence confirms EEG acquisition/processing and active neurotechnology work, while exact equipment, real-time API/streaming, synchronization, sleep-specific capability, ethics route and external-project mechanism remain to be verified directly. First ask deliberately avoided funding, equipment loan, internship, human study or product-validation requests. |
| OPP-064  | National Sleep Research Resource (NSRR)                                | SHHS and STAGES Standard Individual data-access requests successfully submitted after completing the required scientific, compliance, security and guardian-signing workflow | NSRR portal + Email        | 2026-09-01 | WAITING_RESPONSE | Wait for NSRR review. Respond if additional information is requested. Do not download data until access is approved and Path V defines a justified acquisition step | Review window: up to ~2 weeks; check around 2026-09-15   | SHHS role = large-scale PSG robustness/generalization. STAGES role = protected multi-site/clinical external generalization. MESA remains reserve. No NSRR raw data has been downloaded and the download token remains unused. Submitted application/compliance records remain private outside Git.                                     |
| OPP-078A | NEMAR Research Infrastructure                                          | Pre-Path V NEMAR/BOAS technical objective completed: reproducible access, raw-data inspection, validated minimal ingestion, formal EDA, and engineering-readiness assessment | Direct technical execution | 2026-08-28 | IN_PROGRESS      | Stop further Pre-Path V deepening. Carry BOAS/NEMAR forward as a Path V data and validation resource                                                              | Re-enter during Path V                                   | The Pre-Path V NEMAR gate is satisfied. BOAS was assessed READY WITH CONSTRAINTS. `IN_PROGRESS` is retained because NEMAR remains an active Path V resource, not because additional Pre-Path V NEMAR work is required. Detailed technical implementation remains exclusively in the private engineering repository.                       |
| OPP-143  | CuttingGardens / CuttingEEG Community                                  | Organizer reply received: event is aimed at PhD students / advanced researchers; high-school participation is a major stretch; no global travel/accommodation support        | Email                      | 2026-08-21 | BLOCKED          | Do not pursue normal 2026 participation. Re-open only if a specific Garden sponsorship/hosting route becomes credible or if post-event replay material becomes available | Post-event replay check after 2026-09-25                 | Organizer did not state an absolute age ban, but level-fit is weak and the global organization cannot provide travel/accommodation support.                                                                                                                                                                                         |
| OPP-134  | European Sleep Research Society / Sleep Europe                         | Official registration reply received: scientific-programme participation is only available to participants over 18                                                         | Email                      | 2026-08-21 | BLOCKED          | No further funding/registration action unless the age requirement can be satisfied for the 2026 congress; otherwise retain ESRS for a future eligible cycle        | 2026 Sleep Europe cycle                                  | Congress Secretariat/Registration Manager replied directly. Financial-support questions are moot unless age eligibility is first satisfied.                                                                                                                                                                                          |
| OPP-104  | Armenian Artificial Intelligence Virtual Institute / HPC State Support | Official eligibility/program-status clarification received                                                                                                                   | Email                      | 2026-08-24 | TRIGGER_WAIT     | No application action now. Re-open when the government decision is adopted and the next application round is officially announced; reassess final eligibility rules | Trigger: official publication of next application round | Draft rules are still being developed. The described physical-person categories include higher-education students and persons with higher or secondary vocational education. General secondary-school student status alone was not listed. Second application round is not yet open.                                                 |

# Opportunity Action Log

## 2026-08-21

### OPP-143 — CuttingGardens / CuttingEEG Community

Initial action: Participation and financial-support inquiry sent by email.  
Response received: 2026-08-21.  
From: Adrien / CuttingEEG.

Response summary:

* the event is primarily aimed at PhD students and more advanced researchers;
* master’s students sometimes attend;
* participation as a high-school student would be a very large stretch;
* CuttingEEG does not provide travel or accommodation support at the global level;
* an individual Garden could potentially be approached regarding local sponsorship;
* post-event replay material may become available.

Interpretation: The standard 2026 attendance route is not practically viable at the current stage.

Money committed: None.  
Execution state: BLOCKED

Next step: Re-open only if:

* a specific Garden presents a credible sponsorship/hosting route; or
* useful post-event replay material becomes available.

### OPP-134 — European Sleep Research Society / Sleep Europe

Initial action: Participation eligibility and financial-support inquiry sent by email.  
Response received: 2026-08-21.  
From: Sleep Europe 2026 Congress Secretariat / Registration Manager.

Official response summary: Participation in the scientific programme is only available to participants over 18 years of age.

Interpretation: The 2026 Sleep Europe execution path is blocked by participant eligibility before funding, travel or registration-support questions become relevant.

Money committed: None.  
Execution state: BLOCKED

Next step: No further 2026 registration/funding action under the current eligibility condition. Preserve ESRS/Sleep Europe as a future opportunity.

### OPP-104 — Armenian Artificial Intelligence Virtual Institute / HPC State Support

Action history:

* Dedicated AIVI phone line attempted — no answer.
* Ministry information line attempted — no answer.
* Ministry hotline contacted successfully.
* Hotline advised calling again around 14:00 on 2026-08-21.
* Further attempts still did not produce a direct conversation with the AIVI program.
* A professional eligibility-clarification email was sent to the dedicated AIVI address.

Email purpose: Clarify eligibility and application conditions for using the AIVI/HPC compute-support mechanism for Neuro-TMR's EEG/AI technical-validation work.

Clarifications requested included:

* direct eligibility;
* treatment of independent scientific/technological work as supporting evidence;
* whether institutional affiliation is mandatory;
* possible host/supervisor routes;
* current application status and timing.

State after outbound action: WAITING_RESPONSE

## 2026-08-24

### OPP-104 — Armenian Artificial Intelligence Virtual Institute / HPC State Support

Response received: 2026-08-24  
From: AIVI team  
Channel: Email

### Official Response Summary

The AIVI team stated that the Government of Armenia is currently developing the draft decision establishing the procedure for providing public authorities, physical persons and legal entities with access to high-performance computing resources in the field of artificial intelligence.

Under the current draft described in the response, physical-person applicants are expected to include:

* students enrolled in first-, second- or third-cycle higher-education programs;
* persons holding higher education or secondary vocational education.

The response further stated that:

* an evaluation commission is planned within the AI Virtual Institute;
* applications will be evaluated against the criteria established by the eventual decision;
* evidence of scientific or technological activity will be assessed through the submitted application and supporting documents;
* the second application round has not yet been announced;
* the relevant government decision is still under development;
* application dates, conditions and further details will be published after adoption of the decision through the official Ministry, AIVI and program-platform channels.

### Interpretation

The original clarification objective has been achieved.

The current constraint is structural:

The next formal application mechanism is not yet open and the governing rules are not yet final.

The described draft eligibility categories do not explicitly list general secondary-school students. Therefore, eligibility based only on general-school status should not be assumed under the current draft.

Because the government decision is still being developed, the final eligibility conditions must be checked again when the next application round opens.

### Current Pre-Path V Interpretation

The Pre-Path V action for AIVI is resolved for the current stage:

* contact attempted;
* formal clarification requested;
* official response received;
* present application availability determined;
* future trigger identified.

AIVI therefore does not block Path V.

Current execution state: TRIGGER_WAIT

### Trigger for Re-Opening

Re-open OPP-104 when:

* the Government decision is adopted;
* the second/next application round is officially announced;
* final applicant-eligibility rules become available.

At that point:

* reassess eligibility;
* update compute/resource requirements using actual Path V workload evidence;
* prepare the required scientific/technical evidence package;
* submit only if the final rules permit a credible application route.

Current next action: None.

## 2026-08-25

### OPP-078A — NEMAR Research Infrastructure

Execution activated: 2026-08-25  
Execution type: Direct technical infrastructure  
Current state: IN_PROGRESS

### Objective

Establish a reproducible real-world EEG/PSG data-access workflow through NEMAR that can support the technical transition into Path V Validation-Lite.

### Current Action

The private `neuro-tmr-engineering` repository has been established as the technical workspace for Pre-Path V and Path V engineering.

NEMAR is the first active technical opportunity being executed through that repository.

The current execution sequence is:

* verify NEMAR-compatible tooling inside Ubuntu/WSL;
* verify access to the NEMAR ecosystem;
* identify the first relevant sleep EEG/PSG dataset;
* retrieve dataset metadata reproducibly;
* selectively retrieve a small real data subset;
* inspect EEG/PSG structure and sleep-stage labels;
* verify that the data can later be consumed by the Neuro-TMR engineering pipeline.

### Repository Boundary

All implementation details, commands, scripts, technical manifests, data-ingestion code, and reproducibility artifacts belong to the private:

`neuro-tmr-engineering`

repository.

This research repository records only:

* opportunity status;
* strategic purpose;
* major execution milestones;
* high-level outcomes;
* dependencies;
* completion decision.

### Pre-Path V Completion Condition

OPP-078A can satisfy the Pre-Path V gate when:

* NEMAR is operational from the engineering environment;
* one relevant sleep dataset has been identified;
* metadata can be retrieved reproducibly;
* a small real data subset can be accessed;
* the EEG/PSG and associated labels can be technically inspected/loaded;
* the workflow is documented reproducibly.

Model training, sleep-stage baseline development, latency analysis, and cueing are not required for completion of the Pre-Path V NEMAR objective. Those belong to Path V.

### Next Action

Proceed with NEMAR Stage 1 — Environment and access verification inside the private engineering repository.

## 2026-08-26

### OPP-078A — NEMAR Research Infrastructure

Execution type: Direct technical infrastructure  
Current state: IN_PROGRESS

### Major Execution Progress

The BOAS anchor-dataset work advanced substantially through controlled raw-data inspection and the first reproducible ingestion infrastructure.

Completed milestones:

* NEMAR environment and BOAS anchor-dataset setup already established;
* selective real-data retrieval for the locked pilot `sub-26 / pid=18` completed;
* NEMAR Step 7 — actual EEG/PSG + label inspection completed;
* raw PSG and headband EDF structure verified directly;
* PSG/headband sampling rate, sample count, duration and acquisition-start metadata verified;
* EDF units, calibration structure and channel semantics inspected;
* external BIDS annotation architecture verified;
* exact 30-second annotation-to-sample mapping established;
* 23-second unscored trailing segment identified and explained;
* core PSG EEG, headband EEG, PSG EOG and PSG EMG signal readability verified;
* Step 7 engineering inspection record completed in the private engineering repository.

### Minimal BOAS Ingestion Layer

NEMAR Step 8 — minimal Python ingestion — was officially started.

Completed Step 8 substeps:

* **8.1 — ingestion contract and Python package structure**
* **8.2 — BOAS path/file discovery**
* **8.3 — recording/night to real-participant identity resolution (`sub-* → pid`)**
* **8.4 — event loading and BOAS sleep-stage semantics**
* **8.5 — raw EDF opening with explicit BOAS physiological channel groups**
* **8.6 — automated structural validation**

The ingestion/helper layer now automatically verifies core BOAS structural assumptions before downstream analysis.

For the locked pilot `sub-26 / pid=18`, automated structural validation confirmed:

```text
Sampling frequency:          256 Hz
Raw samples:                 7,470,848
Raw duration:                29,183 s
Annotated epochs:            972
Epoch duration:              30 s
Samples per epoch:           7,680
First annotated sample:      0
Final annotated stop:        7,464,960
Unscored leading data:       0 s
Unscored trailing data:      23 s / 5,888 samples
PSG full preload:            False
Headband full preload:       False
```

### Engineering Boundary

Step 8 remains deliberately limited to ingestion.

No:

* preprocessing;
* filtering;
* normalization;
* artifact rejection;
* feature engineering;
* model training;
* staging baseline development

belongs inside this step.

### Next Action

Complete exact labeled epoch extraction, integrated validation and cross-recording generalization before beginning the BOAS EDA.


## 2026-08-27

### OPP-078A — NEMAR Research Infrastructure

Execution type: Direct technical infrastructure  
Current state: IN_PROGRESS

### NEMAR Step 8 — Minimal Python Ingestion COMPLETE

NEMAR Step 8 was completed and closed.

Private engineering implementation includes:

```text
src/neuro_tmr/ingestion/boas.py
tests/test_boas_ingestion.py
```

Core API:

```python
recording = load_boas_recording(data_root, sub_id)
epoch = recording.get_epoch(index)
```

Validated capabilities:

* BOAS subject/night discovery;
* `sub-* → pid` real-participant identity resolution;
* event-table loading;
* explicit BOAS sleep-stage semantics;
* PSG/headband EDF opening with `preload=False`;
* explicit physiological channel grouping;
* structural validation;
* exact labeled 30-second epoch extraction;
* annotation-to-sample alignment;
* integrated recording verification;
* cross-recording metadata/event generalization.

### Exact Labeled Epoch Validation

Locked pilot:

`sub-26 / pid=18`

Reference epoch:

```text
Epoch index:          288
Onset:                8640 s
Sample window:        [2211840:2219520]
Samples:              7680
Human consensus:      N3
PSG AI:               N2
Headband AI:          N2
PSG EEG shape:        (6, 7680)
Headband EEG shape:   (2, 7680)
Finite values:        confirmed
Full EDF preload:     False
```

Additional edge epochs were validated, including the first and final scored epochs.

The 23-second unscored trailing segment remained preserved and correctly excluded from scored-epoch extraction.

### Cross-Recording Generalization Check

A second BOAS recording:

`sub-1 / pid=89`

was discovered and loaded at the metadata/event level without code changes.

PSG and headband event tables contained:

```text
915 epochs
```

The first epoch mapped correctly to:

```text
onset:       0 s
duration:    30 s
begsample:   1
endsample:   7680
```

No second raw EDF pair was required for this metadata-level generalization check.

### Regression Protection

The ingestion test suite reached:

> **24 passed**

This closes NEMAR Step 8.

### Step 9 — BOAS EDA STARTED

The BOAS EDA was then started using the reproducible ingestion foundation.

Initial EDA focus:

* cohort structure;
* real participant identity;
* sleep-stage distributions;
* N3 availability;
* PSG AI vs human-consensus agreement;
* headband AI vs human-consensus agreement;
* reduced-sensor failure modes;
* signal-level stage structure.

A key split constraint was preserved:

> future train/validation/test separation must respect real `pid`, not merely `sub-*`, because some participants contribute repeated nights.

Current execution state: IN_PROGRESS

Next action: Complete the BOAS EDA and produce the final engineering-readiness assessment.

## 2026-08-28

### OPP-078A — NEMAR Research Infrastructure

Execution type: Direct technical infrastructure  
Current state: IN_PROGRESS

### NEMAR Step 9 — BOAS EDA COMPLETE

The formal BOAS exploratory data analysis and engineering-readiness synthesis were completed.

Final synthesis:

```text
inspection/boas_eda_engineering_readiness.md
```

Final decision:

> **BOAS — READY WITH CONSTRAINTS**

### Cohort / Stage Landscape

Dataset-level analysis established approximately:

```text
Recording nights:                   128
Real participants:                  100
Total scored epochs:                120,095
Approx. scored hours:               1000.8 h
Standard human-consensus epochs:    119,759
```

Future data splitting must use real participant identity:

> `pid`

rather than treating repeated `sub-*` recordings as independent participants.

### N3 Landscape

Human-consensus N3 represented approximately:

> **4.36%**

of standard scored epochs.

Approximate total N3:

> **43.5 hours**

N3 was present in:

```text
91 / 128 recording nights
77 / 100 real participants
```

Interpretation:

N3 is a minority class but is sufficiently represented to remain a meaningful scientific and engineering target.

Therefore:

> N3 must be treated explicitly in Validation-Lite rather than hidden inside aggregate multiclass accuracy.

### Existing AI Agreement

Approximate dataset-wide agreement with human-consensus staging:

```text
PSG AI mean agreement:       ~87.18%
Headband AI mean agreement:  ~86.61%
```

Aggregate accuracy alone was insufficient because headband predictions contained more unavailable/special outputs.

Effective correct usable N3 coverage:

```text
PSG:       ~67.77%
Headband:  ~53.80%
```

Interpretation:

* reduced-channel/headband staging remains plausible;
* aggregate accuracy does not establish sensor sufficiency;
* N3-specific performance remains a meaningful stress test;
* N1 remains difficult for both systems;
* reduced sensing must be validated rather than assumed equivalent to full PSG.

### Signal-Level N3 Finding

The locked pilot showed clear low-frequency/high-amplitude structure during human-consensus N3 in both PSG and headband EEG.

Pilot relative delta contribution:

```text
PSG_F3:  ~92.93%
HB_1:    ~90.31%
```

This is evidence of strong N3 slow-frequency structure in the pilot.

It is not evidence that:

* absolute PSG/headband amplitudes are interchangeable;
* a fixed µV threshold should transfer between devices;
* whole-epoch sigma power constitutes spindle detection;
* reduced headband EEG provides all information available in full PSG.

### Auxiliary Physiology

The PSG includes EOG and EMG information unavailable as dedicated modalities in the limited headband EEG.

Important engineering implication:

> Reduced headband staging is not simply “full PSG with fewer columns.”

EOG and EMG contain stage-discriminative information, particularly relevant to difficult distinctions involving N1 and REM.

### Engineering Guardrails

The EDA established that later Path V work must account for:

* participant-level leakage;
* minority-class N3 performance;
* special/unavailable predictions;
* device-specific amplitude scaling;
* signal-quality/artifact handling;
* acquisition-domain differences;
* reduced-sensor information loss.

### Final BOAS Readiness Interpretation

BOAS is suitable for:

* reproducible offline staging work;
* N3-focused development and evaluation;
* simultaneous PSG vs reduced-sensor analysis;
* participant-aware evaluation;
* reduced-sensor failure-mode analysis;
* signal-quality and artifact-handling work;
* establishing an offline data interface before real-time implementation.

BOAS alone does not validate:

* real-time inference latency;
* streaming acquisition reliability;
* cue-delivery latency;
* cue-trigger timing;
* post-cue arousal / sleep-preservation behavior;
* final hardware selection;
* final Neuro-TMR model performance;
* cross-dataset / broad-population generalization.

Those remain Path V questions.

### Pre-Path V Decision

The NEMAR Pre-Path V objective is now:

> **COMPLETE**

However, overall OPP-078A remains:

> **IN_PROGRESS**

because NEMAR/BOAS remains an active future Path V data and validation resource.

Earlier longer NEMAR Step 10–14 planning is no longer a Pre-Path V blocker.

Do not:

* deepen NEMAR further during Pre-Path V;
* start another broad BOAS EDA;
* download the full BOAS raw dataset;
* treat NEMAR as permanently finished.

Re-enter NEMAR/BOAS when Path V requires staging, modeling, evaluation or reproducibility work.

### Next Pre-Path V Opportunity

With the NEMAR Pre-Path V objective complete, active execution moves to:

> **OPP-064 — National Sleep Research Resource (NSRR)**

## 2026-08-31

### OPP-064 — National Sleep Research Resource (NSRR)

Execution activated: 2026-08-31  
Execution type: Controlled-access sleep-data infrastructure  
Current state at activation: IN_PROGRESS

### Objective

Establish a controlled-access large-scale PSG data gateway for Neuro-TMR Path V generalization work while preserving explicit dataset roles, data-use compliance, external-validation boundaries, and minimal necessary acquisition.

The execution philosophy is:

> **ACCESS NOW ≠ DOWNLOAD NOW**

The goal of Pre-Path V is to establish a legitimate and reproducible access route.

Bulk data acquisition is not a Pre-Path V requirement.

### Selected NSRR Dataset Roles

#### SHHS — Sleep Heart Health Study

Primary role:

> large-scale PSG robustness and cross-subject/acquisition-domain generalization.

Possible later secondary role:

> development/pretraining resource if justified by a defined Path V experiment.

Boundary:

SHHS must not automatically be described as a final untouched external test if SHHS data later participate in model development, tuning or representation learning.

#### STAGES

Primary role:

> protected multi-site / clinical external-generalization resource.

Reasons include:

* multi-site acquisition;
* clinical heterogeneity;
* cross-center variation;
* acquisition-domain heterogeneity;
* external-validation value.

Initial rule:

> **Do not use STAGES for routine model tuning.**

Future evaluation should preserve site/center information where available and report site-aware performance.

#### MESA

Current role:

> **RESERVE ONLY**

Do not request MESA merely to increase available data volume.

Activate only if Path V creates a concrete scientific need.

### NSRR Account / Access Preparation

Completed:

* NSRR account created;
* email confirmed;
* login and dashboard access verified;
* SHHS controlled-access route opened;
* private NSRR storage/compliance workspace established outside Git.

No NSRR raw data was downloaded.

The NSRR download token remained unused.

### Human Research Protection Preparation

Before completing the SHHS DAUA, foundational Human Research Protection training was completed.

Training completion records were retained privately outside Git.

The training is treated correctly as evidence of foundational human-research-protection education.

It is not treated as:

* IRB approval;
* institutional affiliation;
* professional research licensure;
* independent authorization to conduct prospective human-subjects research.

### SHHS Request Preparation

A Standard Individual SHHS request was prepared.

The application was developed around:

* offline secondary analysis of de-identified polysomnography;
* EEG-based sleep-stage inference;
* emphasis on NREM/N3;
* participant-aware evaluation;
* class-aware metrics;
* explicit N3-focused analysis;
* acquisition-domain generalization;
* no participant identification/re-identification;
* no use of SHHS to test TMR memory efficacy itself;
* no incorporation of NSRR controlled data into a public repository or product.

### Minor-Applicant Signing Clarification

Before the SHHS DAUA was signed, an administrative question regarding execution of the agreement by a minor applicant was identified.

A professional clarification request was sent to the NSRR Data Access Team.

The SHHS DAUA was kept unsigned until official guidance was received.

At the end of 2026-08-31:

> SHHS request prepared through the signature stage but not yet submitted.

OPP-064 remained:

> **IN_PROGRESS**

The external clarification did not block continued Pre-Path V execution planning.

## 2026-09-01

### OPP-064 — National Sleep Research Resource (NSRR)

Execution type: Controlled-access sleep-data infrastructure

### Official NSRR Signing Guidance Received

A direct response was received from the NSRR Program Manager regarding the correct application route for a minor.

The response established that:

* a minor applicant should not personally execute the DAUA;
* a parent/legal guardian may sign the application on behalf of the minor;
* the Specific Purpose should identify the person signing and their relationship to the applicant;
* the parent/legal guardian should review the application and DAUA language before signing;
* minor students should provide their actual school as the Institution;
* if the school does not provide a student email address, use of a personal email may be explained in the Specific Purpose;
* the Specific Purpose should clearly state the research goal, justify the dataset selection, identify relevant data/variables, and briefly describe the planned analysis.

This direct guidance resolved the outstanding SHHS signing-route uncertainty.

### SHHS Application Revision

The SHHS request was revised accordingly.

High-level corrections included:

* truthful student/institutional positioning;
* explicit explanation of the personal-email route where required;
* expansion of the Specific Purpose to include:
  * clear research objective;
  * scientific justification for SHHS;
  * EEG and sleep-stage annotations as primary analysis variables;
  * EOG/EMG as possible reference/comparison physiology;
  * participant-level separation;
  * stage-specific and N3-specific evaluation;
  * explicit research-stage boundaries;
* guardian-signing statement added;
* parent/legal guardian reviewed the DAUA and signed the application on behalf of the minor applicant.

No institutional affiliation, PI, supervisor, IRB approval or other status was invented.

### IRB Supporting Document Step

The NSRR portal presented an optional supporting-document step for evidence of:

* IRB approval; or
* an IRB exemption determination.

No such document exists for the current independent secondary-analysis project.

The portal explicitly instructed applicants without IRB review to skip this optional step.

Therefore:

> no IRB document was uploaded.

No unrelated document was substituted for an IRB determination.

### SHHS REQUEST SUBMITTED

On 2026-09-01, the SHHS Standard Individual data-access request was:

> **SUCCESSFULLY SUBMITTED**

NSRR confirmed that:

* the request was received successfully;
* access will become available if the request is approved;
* review may take up to approximately two weeks.

Current SHHS state:

> **SUBMITTED / UNDER REVIEW**

No SHHS raw data has been downloaded.

### STAGES Request Initiated

After SHHS submission, a separate Standard Individual request was opened for STAGES.

The STAGES application was deliberately kept scientifically distinct from SHHS.

Project role:

> **multi-site / clinical external validation**

The STAGES Specific Purpose emphasized:

* multi-site PSG;
* clinical heterogeneity;
* cross-center generalization;
* acquisition-domain heterogeneity;
* participant-aware evaluation;
* preservation of site/center information where available;
* stage-specific and N3-focused metrics;
* site-aware comparison;
* external generalization rather than routine development/tuning.

A key methodological boundary was stated:

> **STAGES is intended primarily as an external generalization resource and will not be used for routine model tuning.**

The same truthful minor-applicant and guardian-signing route established by NSRR was used.

No IRB document was uploaded because no IRB approval/exemption determination exists and the optional portal step permitted applicants without IRB review to skip it.

### STAGES REQUEST SUBMITTED

On 2026-09-01, the STAGES Standard Individual data-access request was:

> **SUCCESSFULLY SUBMITTED**

NSRR again indicated that review may take up to approximately two weeks.

Current STAGES state:

> **SUBMITTED / UNDER REVIEW**

No STAGES raw data has been downloaded.

### Private Documentation

Private records of both submitted applications and submission confirmations should be retained outside Git under:

```text
~/neuro-tmr-data/nsrr/requests/
├── shhs/
└── stages/
```

These private records may include:

* submitted application copy;
* submission confirmation;
* relevant NSRR correspondence;
* compliance/supporting records.

Do not commit:

* DAUA documents;
* signatures;
* personal contact/address information;
* training certificates;
* controlled NSRR data

to either Git repository.

### OPP-064 Completion Decision

The current action under Neuro-TMR's control has now been completed for both selected NSRR resources.

SHHS:

> **SUBMITTED / UNDER REVIEW**

STAGES:

> **SUBMITTED / UNDER REVIEW**

MESA:

> **RESERVE — NOT REQUESTED**

Therefore the overall OPP-064 execution state becomes:

> **WAITING_RESPONSE**

### Review / Follow-Up Rule

NSRR indicated a review window of up to approximately two weeks.

Target status check:

> **2026-09-15**

If a response arrives earlier:

* review it immediately;
* record the exact decision or information request;
* respond if action is required.

If no response is received by approximately the end of the stated review window:

* check the NSRR request dashboard;
* prepare a concise professional follow-up if necessary.

### Download Rule After Approval

Approval does not automatically trigger large-scale acquisition.

For either SHHS or STAGES:

1. confirm the exact approved access state;
2. inspect documentation and manifests;
3. inspect available file structure and sizes;
4. retrieve metadata/annotations first;
5. retrieve only a minimal structural PSG sample if required;
6. verify file/participant/annotation/channel linkage;
7. STOP;
8. acquire larger data only when Path V defines a concrete experiment.

Do not download hundreds of gigabytes simply because permission is granted.

### Final OPP-064 Pre-Path V Interpretation

The NSRR Pre-Path V objective is:

> **COMPLETE ON OUR SIDE / WAITING EXTERNAL REVIEW**

OPP-064 does not block continued Pre-Path V execution.

Active execution then moved to:

> **OPP-015 — Centre for Sleep and Cognition / Michael Chee**

## 2026-09-04

### OPP-015 — Centre for Sleep and Cognition / Michael Chee

Execution type: Scientific-methods collaboration  
Current state: WAITING_RESPONSE

### Candidate-Specific Due Diligence

Before outreach, OPP-015 was investigated as a specific methodological collaboration opportunity rather than generic networking.

The opportunity was refined to the following project role:

> challenge and improve the scientific boundary between automatic sleep-stage inference and intervention eligibility in a research-stage closed-loop TMR system.

Relevant capability overlap identified included:

* real-time automatic sleep-stage classification;
* confidence-aware sleep-state inference;
* acoustic intervention;
* external-dataset generalization;
* PSG-to-wearable validation;
* wearable EEG / translational sleep measurement;
* sleep-preservation and intervention methodology.

The opportunity was not treated as a request for:

* generic mentorship;
* funding;
* equipment;
* institutional affiliation;
* endorsement;
* an immediate human study;
* broad collaboration without a defined bottleneck.

### Neuro-TMR Bottleneck

BOAS analysis showed that aggregate PSG/headband staging agreement could appear relatively similar while intervention-relevant N3 usability differed materially.

Approximate existing BOAS staging-output observations:

```text
PSG AI overall agreement:       ~87.18%
Headband AI overall agreement:  ~86.61%

PSG correct usable N3 coverage:       ~67.77%
Headband correct usable N3 coverage:  ~53.80%
```

These are analyses of staging outputs supplied with BOAS, not performance claims for a Neuro-TMR model.

The observation motivated the distinction between:

> **sleep-stage classification performance**

and:

> **whether a sleep-state estimate is sufficiently trustworthy to control an intervention.**

### Frozen Primary Methodological Ask

The outreach was deliberately centered on one primary question:

> **For a first-generation stage-aware closed-loop TMR system, what validation evidence would you consider minimally sufficient before reduced-channel EEG estimates of N3 are trusted to gate acoustic cues, beyond conventional aggregate sleep-staging accuracy?**

Potential implications for Path V include:

* N3 precision / false-positive control;
* confidence calibration;
* abstention;
* temporal stability;
* transition handling;
* signal-quality gating;
* reduced-sensor sufficiency;
* external generalization;
* sleep-preservation logic.

These remain hypotheses and potential design consequences until supported by evidence or expert guidance.

### Backup Success Outcome

A valid secondary success condition was frozen as:

> referral to the member of the Centre for Sleep and Cognition most relevant to real-time staging, acoustic intervention, or wearable EEG validation.

A referral is treated as a successful scientific outcome rather than a failed attempt to reach the PI directly.

### Contact Route

The primary contact route was verified as Prof. Michael Chee's current official NUS academic email.

First-contact rules:

* direct email to Prof. Chee;
* no CC/BCC distribution to other lab members;
* no attachment on first contact;
* no broad evidence package;
* one methodological question;
* offer to share a concise technical summary if useful.

### Outreach Action

On 2026-09-04, a targeted scientific-methods email was sent directly to Prof. Michael Chee.

The email:

* introduced Neuro-TMR briefly as an independent EEG-guided, stage-aware closed-loop TMR research project;
* stated that the project is transitioning from evidence synthesis/offline validation toward Validation-Lite;
* connected the methodological question specifically to Chee/NUS work on real-time staging, confidence estimates, acoustic intervention and PSG-to-wearable validation;
* provided the relevant BOAS aggregate-vs-N3 observation;
* asked the single frozen methodological question;
* allowed a relevant reference or referral as a useful response;
* offered a concise technical summary if useful.

No:

* age information;
* generic mentorship request;
* funding request;
* hardware/lab-access request;
* endorsement request;
* broad collaboration commitment;
* manuscript attachment

was included.

### Success Conditions

Primary success:

> technically meaningful methodological guidance that changes, confirms or sharpens a Path V validation requirement.

Secondary success:

> referral to the CSC researcher most relevant to real-time staging, acoustic intervention or wearable EEG validation.

Additional useful outcomes:

* relevant paper/method/tool recommendation;
* invitation to share a concise technical brief;
* short technical discussion.

Long-term collaboration is not required for the first-contact action to succeed.

### Current State

The outbound action under Neuro-TMR's control is complete.

Therefore:

> **OPP-015 → WAITING_RESPONSE**

### Follow-Up Rule

If no response is received after approximately 7–10 business days:

* send one concise follow-up in the same email thread.

Approximate follow-up window:

> **2026-09-15 to 2026-09-18**

If a reply arrives:

* preserve the exact methodological content;
* separate direct guidance from interpretation;
* convert useful guidance into an explicit Path V requirement, metric, experiment or guardrail;
* follow any relevant referral rather than duplicating outreach blindly.

Do not delay other Pre-Path V execution while waiting.

### Next Active Opportunity

Active execution now advances to:

> **OPP-039 — Engineering City Neurotechnology Laboratory**

### OPP-039 — Engineering City Neurotechnology Laboratory

Execution type: Local institutional / technical research collaboration  
Current state: WAITING_RESPONSE

### Strategic Importance

OPP-039 was treated as a high-value local collaboration opportunity because it could potentially address a class of Neuro-TMR problems that remote scientific outreach and public datasets cannot solve directly:

* real EEG acquisition;
* signal-processing integration;
* real-time data streaming;
* event timing and synchronization;
* cue-trigger integration;
* end-to-end latency measurement;
* repeated local technical iteration;
* later prototype/instrumentation work.

The opportunity was not treated as a substitute for sleep-science expertise or as evidence that Engineering City already has a complete sleep-laboratory pathway.

### Institutional / Capability Due Diligence

Before outreach, the Engineering City / EIF / Neurotechnology Laboratory ecosystem was investigated in depth.

The opportunity was refined to the following role:

> **potential local engineering and experimental partner for Neuro-TMR Path V, beginning with technical EEG acquisition and closed-loop integration rather than a human efficacy study.**

Public evidence established that the Neurotechnology Laboratory operates within the EIF / High-Tech Accelerator / Engineering City ecosystem and is oriented toward neurotechnology, EEG acquisition/processing, data analysis and applied experimentation.

The broader local ecosystem also appears relevant to later:

* electronics/prototyping;
* hardware integration;
* scientific-incubation support;
* Armenian neuroscience/engineering network development.

### Important Unknowns Preserved

The outreach did not assume facts that were not directly verified.

The following remain to be established through direct contact or a technical meeting:

* exact EEG hardware/model/configuration;
* channel counts and electrode options;
* raw-data availability;
* sampling structure;
* real-time SDK/API support;
* LSL or equivalent streaming support;
* event-marker / synchronization capability;
* audio-trigger integration;
* sleep-specific or overnight acquisition capability;
* EOG/EMG/PSG capability;
* current Neurotechnology Laboratory technical/scientific lead;
* current internal neurotechnology projects;
* external independent-project collaboration mechanism;
* ethics / human-research pathway for any later prospective work.

These unknowns must be resolved before Neuro-TMR builds Path V assumptions around the laboratory.

### Frozen First Collaboration Objective

The initial institutional objective was defined as:

> **determine whether the Engineering City Neurotechnology Laboratory can become Neuro-TMR's local technical partner for real EEG acquisition and real-time closed-loop validation, beginning with a small technical integration test rather than a human efficacy study.**

The intended first technical step, if capability and collaboration fit are confirmed, would be a minimal integration feasibility test such as:

```text
EEG source / acquisition
        ↓
real-time data interface
        ↓
Python processing / event logic
        ↓
timestamped trigger
        ↓
dummy audio output
        ↓
end-to-end latency measurement
```

This is a candidate collaboration direction, not a committed experiment.

### Preferred Local Contact Strategy

Because the opportunity is local and the exact technical laboratory lead was not publicly clear, telephone-first contact was initially preferred.

The intended telephone objective was deliberately narrow:

> reach the correct Neurotechnology Laboratory / EIF Science Incubator person, briefly introduce Neuro-TMR, and secure a short technical meeting or lab visit.

The call was not intended to request equipment, funding, an internship, or a human study.

### Channel Adaptation

Telephone contact was not practically available at the time of execution.

Rather than delay the Pre-Path V action, the channel was adapted to professional email through the official High-Tech Accelerator / EIF institutional route.

This preserved the same objective:

* introduce Neuro-TMR briefly;
* state that scientific/offline EEG groundwork is already complete;
* explain the transition toward real-time Validation-Lite;
* identify the relevance of EEG acquisition, processing, timing and closed-loop integration;
* request routing to the person responsible for the Neurotechnology Laboratory's EEG/research work;
* propose a short technical meeting / local discussion if appropriate.

### Outreach Action

On 2026-09-04, a targeted institutional collaboration inquiry was sent.

The first-contact message intentionally did **not** request:

* equipment ownership/loan;
* funding;
* internship placement;
* broad mentorship;
* immediate human sleep experimentation;
* product validation;
* commercial endorsement.

The initial request was limited to determining whether a real technical collaboration fit exists.

### Success Conditions

Primary first-stage success:

> connection to the actual Neurotechnology Laboratory technical/research lead and a short technical meeting or lab visit.

A successful first meeting should establish:

1. **WHO** — who leads the EEG/neurotechnology work;
2. **WHAT** — exact hardware/software/research capabilities;
3. **ACCESS** — what collaboration or project-access mechanism is possible;
4. **NEXT TEST** — whether one small technically meaningful integration/validation step can be defined.

Secondary useful outcomes include:

* referral to another relevant EIF / Engineering City technical group;
* direct equipment/capability clarification;
* request for a concise Neuro-TMR technical brief;
* invitation to visit the laboratory;
* identification of a local neuroscience/engineering partner better suited to the project.

### Current State

The initial outbound action under Neuro-TMR's control is complete.

Therefore:

> **OPP-039 → WAITING_RESPONSE**

### Follow-Up Rule

If a reply arrives:

* preserve the exact response;
* distinguish direct capability evidence from interpretation;
* identify the named technical counterpart;
* schedule a technical discussion / lab visit if offered;
* build an OPP-039 capability map before proposing deeper collaboration;
* define only one small next technical action if the fit is real.

If no reply arrives after approximately 2–3 business days:

* use one controlled follow-up;
* prefer the official telephone route when practical;
* do not mass-email multiple Engineering City / EIF contacts simultaneously.

Do not delay other Pre-Path V work while waiting.

### Next Active Opportunity

Active execution now advances to:

> **OPP-031 — COBRAIN / YSMU**

# Current Pre-Path V Command Board

## Active Now

### OPP-031 — COBRAIN / YSMU

State:

> **NEXT ACTIVE EXECUTION**

Before contact:

1. investigate the current COBRAIN / YSMU structure and active people;
2. verify the current neuroscience / neurotechnology / EEG capabilities relevant to Neuro-TMR;
3. determine what local scientific, institutional or future human-validation bottleneck the opportunity could address;
4. distinguish its role from Engineering City's engineering/instrumentation role;
5. define one concrete collaboration objective;
6. verify the correct current contact route;
7. only then prepare outreach.

Do not begin with generic institutional networking language.

## Waiting Response

### OPP-039 — Engineering City Neurotechnology Laboratory

State:

> **WAITING_RESPONSE**

Primary objective:

> determine whether the laboratory can become a local technical partner for real EEG acquisition and closed-loop Validation-Lite integration.

Preferred successful next step:

> connection to the relevant technical lead + short technical meeting / lab visit + direct capability map.

Follow-up target:

> approximately **2026-09-08 to 2026-09-09** if no response arrives.

Do not wait for a reply before continuing Pre-Path V.

### OPP-015 — Centre for Sleep and Cognition / Michael Chee

State:

> **WAITING_RESPONSE**

Primary ask:

> validation evidence required before reduced-channel EEG N3 estimates are trusted to gate acoustic cues.

Follow-up window:

> **2026-09-15 to 2026-09-18**

Do not wait for a reply before continuing Pre-Path V.

### OPP-064 — National Sleep Research Resource

Overall state:

> **WAITING_RESPONSE**

#### SHHS

State:

> **SUBMITTED / UNDER REVIEW**

Role:

> large-scale PSG robustness / cross-subject and acquisition-domain generalization.

#### STAGES

State:

> **SUBMITTED / UNDER REVIEW**

Role:

> protected multi-site / clinical external generalization.

#### MESA

State:

> **RESERVE**

No active request.

Target NSRR status check:

> **2026-09-15**

No active work is required unless NSRR replies earlier.

## Path V Resource — Pre-Path V Objective Complete

### OPP-078A — NEMAR Research Infrastructure

Overall state:

> **IN_PROGRESS**

Pre-Path V objective:

> **COMPLETE**

BOAS:

> **READY WITH CONSTRAINTS**

Do not deepen BOAS/NEMAR further during Pre-Path V.

Re-enter when Path V requires actual staging, model-development, evaluation or reproducibility work.

## Trigger Wait

### OPP-104 — Armenian Artificial Intelligence Virtual Institute / HPC State Support

State:

> **TRIGGER_WAIT**

Re-open only when:

* the governing government decision is adopted;
* the next application round is officially announced;
* final eligibility conditions are published.

AIVI does not block Path V.

## Blocked / Future Cycle

### OPP-143 — CuttingGardens / CuttingEEG

State:

> **BLOCKED**

Re-open only if a credible sponsorship/hosting route or useful post-event material appears.

### OPP-134 — European Sleep Research Society / Sleep Europe

State:

> **BLOCKED**

Preserve for a future eligible cycle.

## Path A Protected

Do not duplicate Path A outreach for:

* **OPP-011 — Cecilia Forcato**
* **OPP-014 — Hong-Viet Ngo-Dehning**

Path A overlap remains protected.

# Remaining Pre-Path V Exit Gate

The current Pre-Path V opportunity state is:

1. **OPP-078A — NEMAR**
   * Pre-Path V objective COMPLETE.
   * Preserve as Path V resource.

2. **OPP-064 — NSRR**
   * SHHS submitted.
   * STAGES submitted.
   * Overall state = WAITING_RESPONSE.
   * No further immediate action required.

3. **OPP-015 — Centre for Sleep and Cognition / Michael Chee**
   * outreach sent;
   * overall state = WAITING_RESPONSE;
   * no further immediate action required unless reply/follow-up trigger occurs.

4. **OPP-039 — Engineering City Neurotechnology Laboratory**
   * targeted institutional collaboration inquiry sent;
   * overall state = WAITING_RESPONSE;
   * no further immediate action required unless reply/follow-up trigger occurs.

5. **OPP-031 — COBRAIN / YSMU**
   * **NEXT ACTIVE EXECUTION**;
   * research, capability mapping and contact preparation still to be completed.

6. **OPP-104 — AIVI**
   * TRIGGER_WAIT;
   * no current action required.

7. **OPP-011 / OPP-014**
   * Path A protected;
   * no duplicate Path E outreach.

External replies are not required before Path V once the remaining outbound actions under Neuro-TMR's control are completed.

# Transition Rule

When:

* OPP-064 remains correctly documented as `WAITING_RESPONSE`;
* OPP-015 remains correctly documented as `WAITING_RESPONSE`;
* OPP-039 remains correctly documented as `WAITING_RESPONSE`;
* OPP-031 contact has been initiated;
* AIVI remains correctly documented as `TRIGGER_WAIT`;
* Forcato/Ngo Path A overlap remains protected;

then:

> **PRE-PATH V → COMPLETE**

and:

> **PATH V — VALIDATION-LITE → START**

Do not delay Path V solely because:

* SHHS/STAGES approval is pending;
* Michael Chee / NUS has not replied;
* Engineering City / EIF has not replied;
* other external parties remain asynchronous.

# Current Immediate Command

> **BEGIN OPP-031 — COBRAIN / YSMU**

OPP-064, OPP-015 and OPP-039 now run asynchronously in `WAITING_RESPONSE` while active Pre-Path V execution moves forward.

