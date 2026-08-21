# A3 — Scientific Collaboration Brief

**Toolkit:** Path E Execution Toolkit  
**Artifact:** A3  
**Status:** INITIAL / HIGH-LEVEL  
**Date:** 2026-08-21  
**Primary sources:** `final_active_opportunities.md`, `active_opportunity_execution_ledger.md`, `execution_roadmap.md`  
**Scope:** Reusable scientific-collaboration framing for Neuro-TMR Phase II outreach

---

## 1. Purpose

A3 defines the **standard scientific collaboration brief** used when Neuro-TMR approaches researchers, laboratories, technical academic groups, or scientific collaborators during Path E.

Its purpose is to prevent every collaboration approach from becoming a new explanation of the project.

> **A3 provides one stable Neuro-TMR scientific identity and collaboration framework, while every actual outreach message remains candidate-specific.**

A3 is not a mass-email template.

It is the common project brief from which focused collaboration messages, follow-ups, meeting notes, and candidate-specific requests can be built.

---

## 2. Why A3 Exists

The active Path E portfolio contains scientific opportunities with very different potential contributions:

- TMR protocol and cue-design expertise;
- sleep-memory physiology;
- slow-oscillation / spindle timing;
- EEG decoding and computational analysis;
- wearable / mobile / ear-EEG methods;
- sleep-stage and closed-loop engineering;
- behavioral-memory task design;
- clinical sleep interpretation;
- experimental-validation infrastructure.

A generic message such as:

> “I am working on a neuroscience project and would like to collaborate.”

is not sufficient.

A3 establishes a stronger rule:

> **Every scientific collaboration request must connect one specific Neuro-TMR need to one specific capability of the candidate.**

---

## 3. Scope Boundary

### A3 decides now

A3 defines:

- the standard Neuro-TMR project identity used in scientific collaboration;
- the current scientific and technical position of the project;
- the acceptable collaboration objectives;
- what Neuro-TMR can responsibly offer or share;
- what Neuro-TMR should and should not ask for;
- the structure of candidate-specific collaboration requests;
- the evidence package that may be shared;
- outreach-quality principles;
- collaboration-success criteria;
- the boundary between A3, A4, A5, and A6.

### A3 does not decide now

A3 does **not** decide:

- who is contacted first;
- exact outreach dates;
- the final wording of every email;
- whether a researcher will collaborate;
- research-study design;
- authorship;
- intellectual-property terms;
- institutional agreements;
- funding commitments;
- human-participant recruitment;
- ethics approval;
- final Path V technical architecture.

Those decisions belong to candidate-level execution, later scientific discussion, or other toolkit artifacts.

---

## 4. Standard Neuro-TMR Scientific Identity

The following is the stable scientific identity that should remain consistent across collaboration approaches.

### Project

**Neuro-TMR** is an independent neuroscience-to-neurotechnology research project focused on the evidence-based translation of **Targeted Memory Reactivation (TMR)** into a technically testable closed-loop system.

### Governing principle

> **Evidence before engineering.**

The project should not present a product assumption as established science.

The scientific and technical architecture is allowed to change when better evidence or expert criticism requires it.

---

## 5. Current Project State

### Phase I — Completed

Phase I established the scientific foundation through:

- structured research synthesis;
- literature-based evaluation of TMR;
- analysis of sleep staging and wearable sensing;
- translation of the evidence into an engineering-ready first-generation concept;
- completion of a full scientific research manuscript.

### Current V1 scientific position

The current first-generation direction is:

> **EEG-based, stage-aware, closed-loop TMR.**

At the current project level:

- EEG is the primary V1 sensing modality;
- stage-aware control is the V1 target;
- PPG-only TMR remains a later-generation possibility rather than an assumed validated solution;
- phase-aware / oscillation-aware stimulation is important but remains a later refinement rather than a current V1 requirement;
- cue delivery should preserve sleep and avoid unnecessary arousal.

### Phase II — Active

Phase II currently contains:

- **Path A — Expert Review**
- **Path E — Collaboration & Opportunities**
- **Path V — Validation-Lite**

Path E collaboration should strengthen one or more of these paths rather than create unrelated activity.

---

## 6. Current Technical Direction

At the high level, the intended future architecture is modular:

```text
EEG
 ↓
Signal Acquisition
 ↓
Preprocessing
 ↓
Neuro-TMR Sleep-State Inference
 ↓
Uncertainty / Eligibility Logic
 ↓
Cue-Control Decision
 ↓
Audio Cue Delivery
 ↓
Event Logging / Sleep-Preservation Monitoring
```

The exact implementation is intentionally not frozen yet.

### Model principle

Neuro-TMR intends to develop and validate its own sleep-stage inference architecture for its needs.

Existing systems, published models, and toolboxes may serve as:

- scientific references;
- baselines;
- reusable software components;
- comparison systems;
- architectural examples.

They are not automatically treated as the final Neuro-TMR intelligence layer.

---

## 7. Scientific Collaboration Objective Classes

Every collaboration approach should use one primary objective class.

### C1 — TMR Protocol / Cue Design

Use when the candidate can help with:

- cue modality;
- cue association;
- learning prerequisites;
- cue timing at the sleep-stage level;
- habituation;
- behavioral task design;
- interpretation of TMR efficacy.

Typical desired outcome:

> A stronger scientifically defensible TMR protocol or protocol decision.

---

### C2 — Sleep Physiology / Closed-Loop Control

Use when the candidate can help with:

- NREM / N2 / N3 interpretation;
- slow oscillations;
- spindles;
- sleep-state transitions;
- stimulation timing;
- arousal avoidance;
- sleep-architecture preservation.

Typical desired outcome:

> A clearer physiological rule or later control-system requirement.

---

### C3 — EEG / Computational Methods

Use when the candidate can help with:

- sleep-stage detection;
- causal inference;
- EEG preprocessing;
- event detection;
- signal quality;
- model validation;
- real-time processing;
- latency;
- decoding.

Typical desired outcome:

> A method-level recommendation, benchmark route, code/data pointer, or technical collaboration.

---

### C4 — Wearable / Mobile / Reduced-Sensor EEG

Use when the candidate can help with:

- sparse EEG;
- frontal EEG;
- ear-EEG;
- around-ear EEG;
- mobile EEG;
- home acquisition;
- signal-quality constraints;
- electrode placement.

Typical desired outcome:

> Evidence or methods guidance that changes the future wearable-sensing roadmap.

---

### C5 — Behavioral / Memory Validation

Use when the candidate can help with:

- memory-task selection;
- outcome design;
- language/vocabulary paradigms;
- emotional-memory paradigms;
- retention measurement;
- translational learning tasks.

Typical desired outcome:

> A scientifically defensible behavioral validation pathway.

---

### C6 — Experimental / Validation Collaboration

Use when the candidate may provide:

- PSG/EEG expertise;
- experimental infrastructure;
- protocol review;
- validation design;
- research supervision;
- access to a relevant laboratory or research group.

Typical desired outcome:

> A concrete feasibility discussion, validation pathway, or small collaborative experiment.

---

## 8. What Neuro-TMR May Ask For

A3 permits focused requests such as:

- methodological feedback on one defined scientific question;
- interpretation of one technical or physiological result;
- review of one protocol decision;
- recommendation of a relevant dataset, paper, codebase, or method;
- clarification of laboratory methodology;
- a short scientific discussion;
- a feasibility conversation;
- advice on a validation experiment;
- a research introduction or referral;
- access to publicly shareable tools/materials;
- discussion of a concrete future collaboration when sufficient project evidence exists.

The request should be proportional to the existing relationship and the maturity of the project.

---

## 9. What Neuro-TMR Should Not Ask For Initially

Initial scientific collaboration outreach should normally **not** ask for:

- broad or indefinite mentorship;
- open-ended “help with my project”;
- endorsement of Neuro-TMR;
- co-authorship before joint scientific work exists;
- access to confidential data without a defined scientific need;
- major laboratory resources without a concrete validation plan;
- funding without an appropriate funding mechanism;
- a commitment to run a human experiment;
- a commitment to adopt the Neuro-TMR architecture;
- repeated review of the same material already sent through Path A.

> **The first request should be small enough to answer and important enough to matter.**

---

## 10. Candidate-Specific Collaboration Block

Before any A3-based outreach is sent, the candidate should have the following fields completed.

| Field | Required Content |
|---|---|
| OPP ID | Path E opportunity identifier |
| Candidate / Lab | Exact person, group, or institution |
| Primary Objective Class | C1–C6 |
| Why This Candidate | One evidence-based reason |
| Neuro-TMR Need | The specific problem currently needing input |
| Candidate Capability | The capability that directly matches the need |
| Exact Ask | One main actionable request |
| Supporting Artifact | Manuscript / A1 / A2 / Path V result / none |
| Existing Relationship | Cold / Path A waiting / Path A reply / referral / prior contact |
| Trigger | Why contact is appropriate now |
| Success Condition | What useful outcome would count as success |
| Next Step if Positive | Discussion / material share / technical follow-up / meeting |
| A5 Check | Confirm no duplicate Path A outreach |

No candidate should be contacted through A3 without an explicit **Exact Ask**.

---

## 11. Standard Collaboration Brief Core

The following content is the reusable core of a candidate-specific scientific brief.

### 11.1 Project in one sentence

> **Neuro-TMR is an evidence-first research project translating Targeted Memory Reactivation into a testable EEG-based stage-aware closed-loop architecture.**

### 11.2 Current state in three points

- The foundational research phase is complete.
- A full scientific research manuscript has been produced.
- Phase II is now testing the most important scientific and technical assumptions through expert review, collaboration, and Validation-Lite engineering.

### 11.3 Current V1 hypothesis

> An EEG-based stage-aware closed-loop system is currently the most defensible first-generation direction, while PPG-only control and phase-specific stimulation remain later questions requiring additional validation.

### 11.4 Current collaboration principle

> Neuro-TMR is seeking targeted scientific collaboration around defined bottlenecks rather than general endorsement or broad project support.

### 11.5 Candidate-specific section

This section must always change.

It should state:

1. what specific work/capability of the candidate matters;
2. what current Neuro-TMR question it connects to;
3. the exact request;
4. why the request is timely;
5. what material can be shared if useful.

---

## 12. Outreach Construction Rule

A3-based scientific outreach should usually follow this structure:

```text
1. Why I am contacting you specifically
2. Neuro-TMR in 1–2 sentences
3. Current project stage
4. The exact scientific / technical bottleneck
5. One focused request
6. Optional evidence/material offer
7. Low-friction close
```

### Recommended balance

Approximately:

- **40% stable project context**
- **60% candidate-specific scientific relevance**

The candidate-specific section should dominate.

---

## 13. Evidence-Sharing Levels

Do not automatically attach the entire project package to every first contact.

### E0 — No Attachment

Use when:

- the first request is a simple clarification;
- a short email is sufficient;
- the recipient has not yet shown interest.

Possible offer:

> “I would be happy to share the manuscript or technical summary if useful.”

---

### E1 — Concise Project Summary

Use when:

- the recipient asks for more context;
- a one-page summary would make discussion easier;
- the scientific question requires basic project architecture.

---

### E2 — Full Scientific Material

May include:

- full research manuscript;
- relevant Phase I technical/research section;
- relevant literature synthesis;
- focused technical note.

Use only when scientifically relevant.

---

### E3 — Path V Evidence

May include:

- benchmark result;
- reproducible notebook/repository;
- latency result;
- reduced-channel experiment;
- model comparison;
- hardware test;
- concrete validation finding.

This is the strongest future collaboration trigger because the discussion can center on evidence rather than a proposal.

---

## 14. Scientific Integrity Rules

### A3-P01 — No Overclaiming

Do not describe the manuscript as peer-reviewed or published unless that becomes true.

Do not imply that TMR efficacy, wearable feasibility, or the V1 architecture has been proven beyond the evidence.

---

### A3-P02 — Specificity Before Prestige

A lower-ranked or less famous scientist with exactly the required capability may be more useful than a highly prestigious researcher with only broad topical overlap.

---

### A3-P03 — Collaboration Must Solve a Real Bottleneck

Every contact should answer:

> **What can this candidate materially change or clarify for Neuro-TMR?**

If there is no clear answer, outreach should wait.

---

### A3-P04 — One Primary Ask

Do not send five unrelated research questions in the same collaboration request.

One primary ask is preferred.

Secondary context can be added only when necessary.

---

### A3-P05 — Convert Feedback Into Project Changes

A useful expert response should not remain only in email.

It should be converted into:

- a requirement;
- an experiment;
- a methodological correction;
- a literature update;
- a Path V question;
- or a documented decision.

---

### A3-P06 — New Evidence Earns New Contact

A second approach to the same researcher should contain something genuinely new:

- a result;
- a revised question;
- a prototype;
- a validation finding;
- a specific collaboration possibility.

Repeated generic follow-up is not sufficient.

---

### A3-P07 — No Forced Agreement

Scientific collaborators are not expected to validate the current Neuro-TMR hypothesis.

A criticism that changes the architecture is a successful scientific outcome.

---

### A3-P08 — Preserve Scope

A collaboration opportunity should not automatically expand V1.

Examples:

- phase-aware timing may remain later-generation even if a collaborator is an expert in phase locking;
- replay decoding may remain future work even if technically exciting;
- multimodal sensing should not replace EEG-first V1 without evidence.

---

## 15. Path A Coordination

Several active scientific collaborators overlap with Path A expert-review contacts.

The execution ledger explicitly requires A3 + A5 for many of these opportunities, including existing TMR/sleep expert relationships. fileciteturn52file0

A3 therefore adopts the following rule:

> **Do not create a second Path E cold thread for a person whose Path A interaction is still active.**

For overlapping candidates:

- prepare the collaboration-specific conversion note;
- use the existing Path A thread when appropriate;
- first convert any existing expert feedback into project requirements;
- wait for the Path A coordination rule defined in A5;
- re-contact only when there is a genuinely new collaboration objective or result.

---

## 16. Relationship to A1, A2, A4, A5, and A6

### A1 — Data & Benchmark Specification
Defines what data resources mean and how they should be treated.

A3 may reference A1 when asking for:
- dataset guidance;
- validation strategy;
- sleep-staging methodology;
- data-access collaboration.

### A2 — EEG Hardware Requirements
Defines the hardware capabilities Neuro-TMR needs.

A3 may reference A2 when approaching:
- EEG researchers;
- wearable-EEG laboratories;
- real-time EEG experts;
- closed-loop engineering groups.

### A4 — Local Validation / Institutional Brief
Handles institutional feasibility, hosting, local experimental infrastructure, clinical/lab pathways, and local validation discussions.

A3 is scientific-collaboration focused; A4 is institution/validation-path focused.

### A5 — Path A ↔ Path E Coordination Register
Prevents duplicate expert outreach and controls conversion from expert review to collaboration.

A3 must obey A5.

### A6 — Execution Tracker
Records what has actually been sent, received, scheduled, or completed.

A3 defines the collaboration instrument; A6 records its execution.

---

## 17. High-Priority A3 Use Cases Already Identified

The current execution roadmap shows that A3 directly unlocks scientific collaboration with several active opportunities.

Examples include:

- **OPP-015 — Centre for Sleep and Cognition / Michael Chee:** real-time staging, acoustic intervention, wearable translation;
- **OPP-020 — SleepLoopFM / Sensory-Motor Systems Lab:** sparse-EEG causal staging, latency, and gating after a baseline result;
- **OPP-039 — Neurotechnology Laboratory, Engineering City:** focused EEG equipment / signal-processing / Path V technical discussion;
- **OPP-051 — Hrayr Attarian:** clinically grounded PSG-validation and sleep-preservation guidance;
- **OPP-031 — COBRAIN:** exploratory scientific support / hosting discussion alongside A4;
- Path A conversion opportunities such as Björn Rasch, Scott Cairney, Tübingen, DreamTeam, CogNoS, and others once A5 permits contact.

The roadmap explicitly states that scientific outreach should be concise and candidate-specific rather than generic. fileciteturn52file5 fileciteturn52file6

---

## 18. Candidate-Specific Mini-Brief Template

Use the following structure internally before drafting an email.

```text
OPP ID:
Candidate:
Organization:
Objective Class:

WHY THEM
[1–3 sentences grounded in their actual capability/work]

CURRENT NEURO-TMR NEED
[One concrete scientific or technical bottleneck]

EXACT ASK
[One main request]

WHY NOW
[Path V result / A1-A2 readiness / Path A follow-up window / current decision]

WHAT WE CAN SHARE
[None / one-page summary / manuscript / technical note / Path V result]

SUCCESS CONDITION
[What useful outcome would justify this outreach]

PATH A OVERLAP
[None / waiting / replied / auto-response]

A5 CLEARED
[Yes / No]
```

This is an internal preparation tool.

The actual external message should be shorter and written naturally.

---

## 19. Collaboration Success Definition

A collaboration approach does **not** need to produce a formal partnership to be successful.

Useful outcomes include:

- a methodological correction;
- a scientific answer;
- a dataset or code recommendation;
- a literature pointer that changes the plan;
- validation advice;
- a referral;
- a technical meeting;
- willingness to review a future result;
- access to a method/tool;
- agreement to discuss a defined experiment;
- a later formal collaboration.

The correct success condition should be defined before outreach.

---

## 20. Update Rule

A3 should be updated when:

- the core Neuro-TMR scientific position materially changes;
- Path V produces evidence that changes the standard collaboration framing;
- expert feedback changes the project's core assumptions;
- a repeated collaboration need emerges that is not represented by C1–C6;
- the standard evidence package changes;
- execution shows that the current collaboration brief creates systematic misunderstanding.

Candidate-specific details should **not** be added directly into A3.

They belong in the execution ledger, candidate notes, A5, or A6.

---

# A3 Completion Gate

A3 is complete at the execution-toolkit level when Neuro-TMR has:

- one stable scientific project identity;
- one stable high-level description of the current V1 direction;
- defined collaboration objective classes;
- a clear distinction between reasonable and unreasonable first asks;
- a candidate-specific preparation structure;
- evidence-sharing levels;
- scientific-integrity rules;
- Path A coordination requirements;
- a clear boundary with A4/A5/A6;
- enough structure to draft focused outreach without reinventing the project explanation each time.

**A3 — SCIENTIFIC COLLABORATION BRIEF: INITIAL HIGH-LEVEL VERSION COMPLETE**
