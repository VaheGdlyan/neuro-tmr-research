# A6 — Path E Execution Tracker

Date opened: 2026-08-21
Last updated: 2026-09-01
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