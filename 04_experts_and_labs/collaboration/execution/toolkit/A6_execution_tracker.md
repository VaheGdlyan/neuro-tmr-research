# A6 — Path E Execution Tracker

**Date opened:** 2026-08-21
**Last updated:** 2026-08-25
**Stage:** PATH E EXECUTION / PRE-PATH V
**Toolkit Artifact:** A6 — Live operational log for actions taken on active opportunities
**Related documents:** `execution_roadmap.md`, `active_opportunity_execution_ledger.md`, `final_active_opportunities.md`, `path_e_execution_phase_classification.md`

## Purpose

This file is the live record of what has actually been done for Path E opportunities.

* `active_opportunity_execution_ledger.md` = what should be done for every active opportunity.
* `execution_roadmap.md` = what should happen first and in what order.
* `A6_execution_tracker.md` = what has actually been done, what is waiting, and what happens next.

Update this file whenever an email is sent, a call is made, an application is submitted, access is requested, a reply arrives, a meeting is scheduled, or an opportunity becomes blocked/completed.

---

## Status Vocabulary

| Status             | Meaning                                                                  |
| ------------------ | ------------------------------------------------------------------------ |
| `NOT_STARTED`      | No execution action has started yet.                                     |
| `PREPARING`        | Material or information is being prepared before action.                 |
| `SCHEDULED`        | A concrete action is planned for a specific time/date.                   |
| `ACTIONED`         | The outbound action has been completed.                                  |
| `WAITING_RESPONSE` | Action was completed and we are waiting for the external party.          |
| `IN_PROGRESS`      | The opportunity is actively moving through several steps.                |
| `BLOCKED`          | Progress cannot continue until an external constraint is resolved.       |
| `COMPLETED`        | The current intended objective has been achieved.                        |
| `CLOSED`           | We deliberately stop current execution for this opportunity.             |
| `TRIGGER_WAIT`     | Active opportunity is intentionally waiting for a later project trigger. |

---

# Live Execution Board

| OPP ID  | Opportunity                                                            | Current Action                                                                                                                                                        | Channel | Date       | Status         | Next Action                                                                                                                                                                      | Next Check / Target                                     | Notes                                                                                                                                                                                                                                                                                |
| ------- | ---------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- | ---------- | -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| OPP-143 | CuttingGardens / CuttingEEG Community                                  | Organizer reply received: event is aimed at PhD students / advanced researchers; high-school participation is a major stretch; no global travel/accommodation support | Email   | 2026-08-21 | `BLOCKED`      | Do not pursue normal 2026 participation. Re-open only if a specific Garden sponsorship/hosting route becomes credible or if post-event replay material becomes available         | Post-event replay check after 2026-09-25                | Organizer did not state an absolute age ban, but level-fit is weak and the global organization cannot provide travel/accommodation support.                                                                                                                                          |
| OPP-134 | European Sleep Research Society / Sleep Europe                         | Official registration reply received: scientific-programme participation is only available to participants over 18                                                    | Email   | 2026-08-21 | `BLOCKED`      | No further funding/registration action unless the age requirement can be satisfied for the 2026 congress; otherwise retain ESRS for a future eligible cycle                      | 2026 Sleep Europe cycle                                 | Congress Secretariat/Registration Manager replied directly. Financial-support questions are moot unless age eligibility is first satisfied.                                                                                                                                          |
| OPP-104 | Armenian Artificial Intelligence Virtual Institute / HPC State Support | Official eligibility/program-status clarification received                                                                                                            | Email   | 2026-08-24 | `TRIGGER_WAIT` | No application action now. Re-open when the government decision is adopted and the next application round is officially announced; reassess final eligibility rules at that time | Trigger: official publication of next application round | Draft rules are still being developed. The described physical-person categories include higher-education students and persons with higher or secondary vocational education. General secondary-school student status alone was not listed. Second application round is not yet open. |

---

# Opportunity Action Log

## 2026-08-21

### OPP-143 — CuttingGardens / CuttingEEG Community

**Initial action:** Participation and financial-support inquiry sent by email.
**Response received:** 2026-08-21.
**From:** Adrien / CuttingEEG.

**Response summary:**

* the event is primarily aimed at PhD students and more advanced researchers;
* master’s students sometimes attend;
* participation as a high-school student would be a very large stretch;
* CuttingEEG does not provide travel or accommodation support at the global level;
* an individual Garden could potentially be approached regarding local sponsorship;
* post-event replay material may become available.

**Interpretation:** The standard 2026 attendance route is not practically viable at the current stage.

**Money committed:** None.
**Execution state:** `BLOCKED`

**Next step:** Re-open only if:

1. a specific Garden presents a credible sponsorship/hosting route; or
2. useful post-event replay material becomes available.

---

### OPP-134 — European Sleep Research Society / Sleep Europe

**Initial action:** Participation eligibility and financial-support inquiry sent by email.
**Response received:** 2026-08-21.
**From:** Sleep Europe 2026 Congress Secretariat / Registration Manager.

**Official response summary:** Participation in the scientific programme is only available to participants over 18 years of age.

**Interpretation:** The 2026 Sleep Europe execution path is blocked by participant eligibility before funding, travel or registration-support questions become relevant.

**Money committed:** None.
**Execution state:** `BLOCKED`

**Next step:** No further 2026 registration/funding action under the current eligibility condition. Preserve ESRS/Sleep Europe as a future opportunity.

---

### OPP-104 — Armenian Artificial Intelligence Virtual Institute / HPC State Support

**Action history:**

1. Dedicated AIVI phone line attempted — no answer.
2. Ministry information line attempted — no answer.
3. Ministry hotline contacted successfully.
4. Hotline advised calling again around 14:00 on 2026-08-21.
5. Further attempts still did not produce a direct conversation with the AIVI program.
6. A professional eligibility-clarification email was sent to the dedicated AIVI address.

**Email purpose:** Clarify eligibility and application conditions for using the AIVI/HPC compute-support mechanism for Neuro-TMR's EEG/AI technical-validation work.

**Clarifications requested included:**

* direct eligibility;
* treatment of independent scientific/technological work as supporting evidence;
* whether institutional affiliation is mandatory;
* possible host/supervisor routes;
* current application status and timing.

**State after outbound action:** `WAITING_RESPONSE`

---

## 2026-08-24

### OPP-104 — Armenian Artificial Intelligence Virtual Institute / HPC State Support

**Response received:** 2026-08-24
**From:** AIVI team
**Channel:** Email

### Official Response Summary

The AIVI team stated that the Government of Armenia is currently developing the draft decision establishing the procedure for providing public authorities, physical persons and legal entities with access to high-performance computing resources in the field of artificial intelligence.

Under the current draft described in the response, physical-person applicants are expected to include:

1. students enrolled in first-, second- or third-cycle higher-education programs;
2. persons holding higher education or secondary vocational education.

The response further stated that:

* an evaluation commission is planned within the AI Virtual Institute;
* applications will be evaluated against the criteria established by the eventual decision;
* evidence of scientific or technological activity will be assessed through the submitted application and supporting documents;
* the second application round has **not yet been announced**;
* the relevant government decision is still under development;
* application dates, conditions and further details will be published after adoption of the decision through the official Ministry, AIVI and program-platform channels.

### Interpretation

The original clarification objective has been achieved.

The main uncertainty is no longer whether AIVI has received the inquiry.

The current constraint is structural:

> **the next formal application mechanism is not yet open and the governing rules are not yet final.**

The described draft eligibility categories do not explicitly list general secondary-school students. Therefore, eligibility based only on 12th-grade general-school status should **not be assumed** under the current draft.

However, because the government decision is still being developed, the final eligibility conditions must be checked again when the next application round opens.

The response also confirms that scientific/technological evidence will be evaluated through applications and supporting documents rather than through an informal pre-approval mechanism.

### Current Pre-Path V Interpretation

The Pre-Path V action for AIVI is **resolved for the current stage**:

* contact attempted;
* formal clarification requested;
* official response received;
* present application availability determined;
* future trigger identified.

AIVI therefore does **not** block Path V.

**Current execution state:** `TRIGGER_WAIT`

### Trigger for Re-Opening

Re-open OPP-104 when:

1. the Government decision is adopted;
2. the second/next application round is officially announced;
3. final applicant-eligibility rules become available.

At that point:

* reassess eligibility;
* update A7 using actual Path V workload evidence;
* prepare the required scientific/technical evidence package;
* submit only if the final rules permit a credible application route.

**Current next action:** None.

---

# Response Log

| Date       | OPP ID  | From                                                          | Response Summary                                                                                                                                                                                                                                                                                      | Decision / Interpretation                                                                                                                                            | Next Action                                                                                |
| ---------- | ------- | ------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| 2026-08-21 | OPP-143 | Adrien / CuttingEEG                                           | Event targets PhD/advanced researchers; high-school attendance is a major stretch; no global travel/accommodation support; individual Garden sponsorship may be possible; replay material may become available                                                                                        | Standard 2026 attendance route is not currently practical                                                                                                            | Reconsider only on a concrete Garden sponsorship trigger or post-event replay availability |
| 2026-08-21 | OPP-134 | Sleep Europe 2026 Congress Secretariat / Registration Manager | Scientific-programme participation is only available to participants over 18                                                                                                                                                                                                                          | Eligibility blocks the present 2026 participation route                                                                                                              | No further current-cycle action; retain for future eligibility                             |
| 2026-08-24 | OPP-104 | Armenian Artificial Intelligence Virtual Institute team       | Government procedure is still under development; draft physical-person categories include higher-education students and persons with higher or secondary vocational education; scientific/technical evidence will be assessed with application documents; next application round is not yet announced | Current clarification objective achieved. No application can be pursued now. Final eligibility must be reassessed when formal rules and the next round are published | Move to `TRIGGER_WAIT`; monitor official program reopening; do not delay Path V            |

---

# Applications / Registrations / Access Requests

| Date | OPP ID  | Submission                                                                 | Status     | Confirmation / Reference                                                                | Next Step                      |
| ---- | ------- | -------------------------------------------------------------------------- | ---------- | --------------------------------------------------------------------------------------- | ------------------------------ |
| —    | OPP-104 | No formal AIVI compute application submitted                               | `NOT_OPEN` | AIVI confirmed on 2026-08-24 that the next application round has not yet been announced | Reassess when next round opens |
| —    | —       | No other formal application/registration/access request recorded in A6 yet | —          | —                                                                                       | —                              |

---

# Meetings / Calls

| Date       | OPP ID  | Contact / Organization                          | Purpose                                                  | Outcome                                                                                         | Follow-up                                                                             |
| ---------- | ------- | ----------------------------------------------- | -------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| 2026-08-21 | OPP-104 | Armenian Ministry of High-Tech Industry hotline | Find correct AIVI contact / clarify how to reach program | Hotline advised calling again around 14:00; later attempts still did not reach the program team | Inquiry moved to dedicated AIVI email; official response later received on 2026-08-24 |

---

# P0 Status Snapshot — 2026-08-25

| Opportunity              | Action Completed                                              | Current Status | External Dependency / Trigger                                                                     |
| ------------------------ | ------------------------------------------------------------- | -------------- | ------------------------------------------------------------------------------------------------- |
| OPP-143 — CuttingGardens | Organizer reply received                                      | `BLOCKED`      | Re-open only for credible individual-Garden sponsorship/hosting or post-event replay availability |
| OPP-134 — Sleep Europe   | Official eligibility reply received                           | `BLOCKED`      | Future eligible cycle / changed eligibility condition                                             |
| OPP-104 — AIVI           | Eligibility clarification sent and official response received | `TRIGGER_WAIT` | Adoption of government procedure + announcement of next application round                         |

**P0 execution state:** all three original P0 opportunities have now received sufficient current-cycle resolution.

* CuttingGardens: blocked under the present participation/support route.
* Sleep Europe: blocked under the present eligibility condition.
* AIVI: current clarification complete; waiting for a future program-opening trigger.

**Operational consequence:** No P0 opportunity should delay Pre-Path V completion or Path V execution.

---

# Pre-Path V Command Board — 2026-08-25

## Execute Now

1. **OPP-078A — NEMAR Research Infrastructure**

   * establish the reproducible discovery/download workflow;
   * verify BIDS handling;
   * test relevant infrastructure sufficiently for Path V.

2. **OPP-064 — National Sleep Research Resource**

   * create/verify account;
   * identify justified cohorts;
   * open/submit required access routes;
   * record external approval dependencies.

3. **OPP-015 — Centre for Sleep and Cognition / Michael Chee**

   * send one focused scientific-methods outreach around real-time staging/intervention validation or wearable translation.

4. **OPP-039 — Neurotechnology Laboratory, Engineering City**

   * initiate focused local technical contact regarding EEG equipment, acquisition, signal processing and possible Path V technical support.

5. **OPP-031 — COBRAIN / YSMU**

   * initiate exploratory institutional/scientific contact regarding mentorship, hosting, affiliation or appropriate neuroscience support.

## Path A — Do Not Duplicate

* OPP-011 — Cecilia Forcato
* OPP-014 — Hong-Viet V. Ngo-Dehning

Handle these only through the Path A ↔ Path E coordination route when their Path A state changes.

## Trigger Wait

* **OPP-104 — AIVI:** wait for formal government decision and next application-round announcement.
* **OPP-143 — CuttingGardens:** only re-open on a concrete sponsorship/replay trigger.
* **OPP-134 — Sleep Europe:** current 2026 route blocked; retain for future eligibility.

---

# Pre-Path V Exit Rule

Do not wait for NUS, Engineering City, COBRAIN or NSRR external responses after the appropriate action has been completed.

The gate is satisfied when:

* NEMAR workflow is operational enough for reproducible use;
* NSRR access/request route has been opened;
* NUS outreach has been sent;
* Engineering City contact has been initiated;
* COBRAIN contact has been initiated;
* AIVI remains correctly recorded in `TRIGGER_WAIT`;
* Path A-overlap opportunities remain protected from duplicate outreach.

Then:

> **PRE-PATH V → COMPLETE**

and

> **PATH V — VALIDATION-LITE → START**

---

# Tracker Update Rule

For every meaningful action, update the Live Execution Board and add a chronological note when useful.

For outbound opportunities:

`Action → Date → Channel → Status → External response → Next action`

For direct technical opportunities:

`Resource accessed → Experiment/repository action → Output produced → Next technical dependency`

For trigger-wait opportunities:

`Current route resolved → Future trigger defined → No active effort until trigger`

A6 remains the operational memory of Path E and should stay short enough to review quickly while preserving every meaningful execution decision.
