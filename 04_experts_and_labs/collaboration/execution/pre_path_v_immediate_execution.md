# Pre-Path V — Immediate Opportunity Execution List

**Date:** 2026-08-25
**Project:** Neuro-TMR — Phase II
**Stage:** PRE-PATH V
**Immediate active opportunities:** 5

## Governing Rule

These five opportunities should be **executed or initiated before Path V begins**.

Their external outcomes are **not prerequisites** for Path V.

The gate is:

> **Do what is under our control → record any external dependency → begin Path V without waiting for replies.**

The five opportunities are:

1. OPP-078A — NEMAR Research Infrastructure
2. OPP-064 — National Sleep Research Resource (NSRR)
3. OPP-015 — Centre for Sleep and Cognition / Michael Chee
4. OPP-039 — Neurotechnology Laboratory, Engineering City
5. OPP-031 — COBRAIN Scientific-Educational Center for Fundamental Brain Research

---

## 1. OPP-078A — NEMAR Research Infrastructure

**Organization:** NEMAR
**Global Rank:** #2
**Execution Type:** Direct resource / infrastructure use
**Current State:** `NOT_STARTED`

### Potential Influence on Neuro-TMR

NEMAR can become one of the main reproducible EEG-data infrastructure layers behind Path V.

Its strongest value is not simply access to another dataset. It can provide a standardized route for:

* discovering relevant EEG datasets;
* downloading datasets reproducibly;
* working with BIDS-organized EEG data;
* accessing directly relevant resources such as BOAS;
* potentially connecting local workflows to external neuroscience compute resources;
* documenting exactly how data used in Path V were obtained.

This matters because Path V should not become a collection of manually downloaded datasets with undocumented preprocessing origins.

NEMAR can therefore strengthen:

**reproducibility + data access + EEG workflow organization + later compute flexibility.**

### How We Treat This Opportunity

We treat NEMAR primarily as **infrastructure**, not as a collaboration target.

We do **not** need to introduce Neuro-TMR to the NEMAR team before using the platform.

No outreach is required unless:

* access fails;
* tooling behaves unexpectedly;
* an important technical capability requires clarification;
* or later collaboration becomes strategically useful.

### Immediate Connection / Execution Method

Use the platform directly.

Immediate sequence:

1. verify the current NEMAR workflow;
2. install/test the appropriate CLI/tooling;
3. discover or access one small relevant EEG dataset;
4. inspect BOAS availability/metadata;
5. verify BIDS handling;
6. test the download workflow;
7. investigate/test the NSG compute path only where practical;
8. document the reproducible process.

### Pre-Path V Completion Condition

NEMAR is complete for this gate when:

> Neuro-TMR has a documented, reproducible method for discovering and accessing a relevant EEG dataset through NEMAR.

We do **not** need to explore the entire NEMAR ecosystem before Path V.

---

## 2. OPP-064 — National Sleep Research Resource (NSRR)

**Organization:** NHLBI-supported sleep-data infrastructure
**Global Rank:** #2
**Execution Type:** Data-access gateway
**Current State:** `NOT_STARTED`

### Potential Influence on Neuro-TMR

NSRR gives Neuro-TMR access to something fundamentally different from a single benchmark dataset:

**large-scale PSG cohorts across multiple studies.**

Its long-term influence could be substantial because Path V eventually needs to know whether a sleep-stage model works beyond one convenient dataset.

NSRR can support later:

* cross-cohort validation;
* large-scale PSG analysis;
* heterogeneous-population testing;
* external validation;
* multi-site generalization;
* access to resources such as STAGES, SHHS and other relevant sleep datasets.

This protects Neuro-TMR from reaching conclusions based on only one dataset or one recording environment.

### How We Treat This Opportunity

NSRR is an **access mechanism**, not a scientific collaboration.

We should therefore avoid unnecessary outreach.

The correct behavior is:

> identify justified datasets → create/verify account → submit legitimate access requests → comply with dataset-specific requirements.

We should **not** request every available dataset simply because access exists.

Each requested cohort needs a defined role inside A1 / Path V.

### Immediate Connection / Execution Method

1. create or verify the NSRR account;
2. inspect the available access mechanism;
3. identify the Path V-relevant cohorts;
4. submit the justified access request(s);
5. verify downloader/API/data-access workflow;
6. record each requested resource and intended role.

### External Dependency Rule

If approval is required:

> `REQUEST_SUBMITTED → record dependency → continue`

We do **not** wait for approval before beginning Path V.

### Pre-Path V Completion Condition

NSRR is complete for the initiation gate when:

> the relevant access/request route has been opened and any required request has been submitted.

Actual approval may arrive during Path V.

---

## 3. OPP-015 — Centre for Sleep and Cognition / Michael Chee

**Organization:** National University of Singapore
**Global Rank:** #5
**Execution Type:** Scientific outreach
**Current State:** `NOT_STARTED`

### Potential Influence on Neuro-TMR

This is probably the most strategically aligned new scientific contact in the immediate Pre-Path V group.

The Centre for Sleep and Cognition combines expertise directly relevant to several layers of Neuro-TMR:

* sleep staging;
* real-time sleep-state estimation;
* acoustic intervention;
* sleep technology;
* wearable translation.

That combination maps unusually closely onto our intended architecture:

**EEG → real-time sleep-state inference → intervention eligibility → acoustic cue delivery.**

Useful feedback from this group could expose methodological assumptions before we invest heavily in implementation.

For example, they could influence:

* how real-time staging should be validated;
* what constitutes acceptable online performance;
* how reduced/wearable sensing should be interpreted;
* how an acoustic-intervention pipeline should be evaluated;
* what offline validation is insufficient for claiming real-time feasibility.

### How We Treat This Opportunity

We do **not** send a broad:

> “I am working on TMR and would like to collaborate.”

Instead, we approach them as a highly relevant scientific-methods contact.

The outreach should contain:

* a concise explanation of Neuro-TMR;
* our evidence-based EEG-first V1 direction;
* the fact that we are beginning Validation-Lite;
* one narrow methodological question;
* a clear reason their work specifically motivated the contact.

### Connection Strategy

Primary route:

**official Michael Chee / Centre for Sleep and Cognition academic contact route.**

The first message should ask **one primary question**, ideally around:

> real-time sleep-staging / intervention validation

or

> the minimum sensing/validation assumptions required before translating sleep staging toward wearable closed-loop use.

We can offer a short project brief or architecture summary if useful.

The full manuscript should not automatically be attached to the first message.

### Success Condition

Any of the following counts as success:

* direct methodological guidance;
* a relevant publication/code/dataset pointer;
* correction of a Path V assumption;
* referral to the appropriate lab member;
* willingness to discuss the technical problem;
* a future collaboration route.

A formal collaboration agreement is **not** required.

### Pre-Path V Completion Condition

For the initiation gate:

> the focused outreach has been sent.

After that, any reply becomes an external dependency and Path V proceeds.

---

## 4. OPP-039 — Neurotechnology Laboratory, Engineering City

**Organization:** Enterprise Incubator Foundation / Engineering City
**Global Rank:** #17
**Execution Type:** Local technical collaboration
**Current State:** `NOT_STARTED`

### Potential Influence on Neuro-TMR

Engineering City could become the most immediately useful **local technical EEG bridge**.

Its potential influence is practical rather than purely advisory.

Possible value includes:

* access to EEG/neurotechnology expertise;
* understanding what EEG equipment is locally available;
* signal-acquisition support;
* signal-processing guidance;
* synchronization expertise;
* artifact-management experience;
* eventual technical bench testing;
* a possible small Path V hardware/acquisition test.

This could reduce the gap between our software Validation-Lite work and later real EEG acquisition.

It also gives Neuro-TMR a local technical counterpart rather than depending entirely on international hardware vendors and remote researchers.

### How We Treat This Opportunity

We approach Engineering City as a **technical collaborator / feasibility partner**, not as:

* a funding request;
* a request for a complete experiment;
* a request for participant recruitment;
* or a generic mentorship request.

The first objective is simply to discover:

> What concrete EEG/neurotechnology capability exists locally, and is there a realistic technical collaboration point with Neuro-TMR?

### Connection Strategy

Request a focused technical discussion.

Present:

* the Neuro-TMR goal;
* the EEG-first architecture;
* the immediate Path V Validation-Lite plan;
* the type of EEG acquisition/signal-processing capability we may later require.

Then ask specifically about:

* available EEG systems;
* raw-signal accessibility;
* acquisition APIs/interfaces;
* event synchronization;
* signal-processing support;
* real-time capability;
* whether a small future technical test would be realistic.

### Success Condition

The ideal first outcome is:

> a named technical contact + confirmed capability + one concrete possible next step.

Even a negative answer is useful if it clearly tells us what capability is unavailable locally.

### Pre-Path V Completion Condition

For this gate:

> the focused local technical contact/meeting request has been initiated.

We do not wait for the meeting before Path V starts.

---

## 5. OPP-031 — COBRAIN Scientific-Educational Center for Fundamental Brain Research

**Organization:** Yerevan State Medical University
**Global Rank:** #40
**Execution Type:** Local scientific / institutional collaboration
**Current State:** `NOT_STARTED`

### Potential Influence on Neuro-TMR

COBRAIN has a different role from Engineering City.

Engineering City may help with **technical EEG execution**.

COBRAIN may help establish the **scientific and institutional environment around the project**.

Potential influence includes:

* neuroscience mentorship;
* connection to relevant researchers;
* institutional hosting;
* scientific affiliation;
* access to research infrastructure;
* future ethics/research pathways;
* strengthening applications requiring institutional participation;
* introductions to other Armenian neuroscience or medical groups.

This could become particularly important later if Neuro-TMR progresses from public-dataset Validation-Lite toward experiments involving real EEG acquisition or human participants.

### How We Treat This Opportunity

We approach COBRAIN as an **institutional/scientific bridge**.

We should not currently ask them to:

* approve a study;
* recruit participants;
* provide clinical access;
* formally endorse the project;
* or become a long-term institutional partner immediately.

The first question is much simpler:

> Is there a realistic scientific mentorship, hosting, affiliation or collaboration route through COBRAIN/YSMU for a project at Neuro-TMR's present stage?

### Connection Strategy

Request a short exploratory discussion.

Present:

* the Phase I evidence base;
* the current EEG-based V1 hypothesis;
* the Path V Validation-Lite plan;
* what has already been completed independently;
* what type of institutional/scientific support could become useful later.

Ask specifically about:

* mentorship;
* scientific hosting;
* appropriate researchers/groups;
* institutional affiliation mechanisms;
* possible future research support.

### Success Condition

Useful outcomes include:

* a named scientific contact;
* a mentor/referral;
* a realistic hosting mechanism;
* an affiliation possibility;
* a route to another YSMU group;
* or a clear statement that no suitable mechanism currently exists.

### Pre-Path V Completion Condition

For this gate:

> the exploratory institutional contact has been initiated.

Again, we do not wait for the response.

---

# Final Pre-Path V Gate

The active work before Path V is therefore:

### Infrastructure

**OPP-078A — NEMAR**
→ establish reproducible infrastructure workflow.

**OPP-064 — NSRR**
→ open the required access/request pathway.

### Scientific Input

**OPP-015 — NUS / Michael Chee**
→ send one highly focused scientific-methods outreach.

### Local Technical Support

**OPP-039 — Engineering City**
→ initiate focused EEG/neurotechnology feasibility contact.

### Local Institutional Support

**OPP-031 — COBRAIN / YSMU**
→ initiate exploratory scientific/hosting/institutional contact.

## Exit Rule

Pre-Path V is complete when all five actions under our control have been performed:

* NEMAR workflow established;
* NSRR access/request route opened;
* NUS outreach sent;
* Engineering City contact initiated;
* COBRAIN contact initiated.

External replies, approvals and meetings become dependencies.

They do **not** block the next transition:

> **PRE-PATH V COMPLETE → PATH V VALIDATION-LITE START**
