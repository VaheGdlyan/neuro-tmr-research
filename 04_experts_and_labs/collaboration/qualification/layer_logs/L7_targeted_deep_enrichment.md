# L7 — Targeted Deep Enrichment

## Layer Purpose

L7 performs targeted deep enrichment on the opportunities that survived the L6 Strategic Actionability gate.

The objective is **not** to create exhaustive profiles for every candidate.

Instead, L7 resolves only the remaining information that could materially affect how an opportunity should later be evaluated during L8.

The governing question is:

> **What do we still need to know about this opportunity before we can compare it intelligently with similar opportunities?**

---

## Input Population

L7 received all opportunities classified at L6 as:

* `ACTIONABLE`
* `ACTIONABLE_WITH_PREPARATION`
* `RESERVE_CANDIDATE`

L6 distribution:

| L6 Status                     | Count | L7 Treatment   |
| ----------------------------- | ----: | -------------- |
| `ACTIONABLE`                  |    37 | Advance        |
| `ACTIONABLE_WITH_PREPARATION` |    44 | Advance        |
| `RESERVE_CANDIDATE`           |    39 | Advance        |
| `WATCH`                       |    37 | Do not advance |
| `REJECT`                      |    10 | Do not advance |

Therefore:

**37 + 44 + 39 = 120 opportunities entered L7.**

The 47 opportunities classified as `WATCH` or `REJECT` remain outside the active qualification funnel.

---

# L7 Methodological Change

An earlier version of the Path E funnel described L7 broadly as deep research into areas such as:

* publications;
* projects;
* collaboration history;
* researcher background;
* institutional activity.

With 120 qualified opportunities, this approach would have produced excessive research without guaranteeing better decisions.

L7 was therefore refined into a **decision-critical enrichment layer**.

The final rule became:

> Research only the unknowns that could materially change the opportunity's later L8 evaluation.

This prevents L7 from becoming an encyclopedic profiling exercise.

---

# Functional Enrichment Architecture

Because the 120 opportunities are highly heterogeneous, they were not researched using one universal question set.

Instead, they were organized into eight functional enrichment families.

## F1 — Scientific Collaboration & Expertise

Includes opportunities whose principal value comes from:

* TMR expertise;
* sleep and memory neuroscience;
* EEG/sleep science;
* closed-loop stimulation;
* wearable neuroscience;
* experimental collaboration;
* methodological expertise.

Primary enrichment questions include:

* Is the relevant scientific activity still active?
* What capability is genuinely distinctive?
* What Neuro-TMR bottleneck could the collaborator help resolve?
* What realistic collaboration mechanism exists?
* What can only be determined through direct contact?

---

## F2 — Data / Research Infrastructure & Path V Resources

Includes:

* open EEG/PSG datasets;
* sleep datasets;
* analysis platforms;
* shared research infrastructure;
* computational resources;
* sleep software;
* Path V development resources.

Primary enrichment questions include:

* What modalities are actually available?
* Is raw EEG available?
* Are sleep-stage labels available?
* What is the access mechanism?
* What licensing restrictions exist?
* Can the resource directly support Validation-Lite?
* Does the resource provide something not already available elsewhere?

---

## F3 — Funding & Institutional Support

Includes:

* research grants;
* innovation funding;
* Armenian research-support mechanisms;
* international funding programs;
* institutional R&D support;
* startup/research financing mechanisms.

Primary enrichment questions include:

* Is the mechanism currently active?
* Who is eligible?
* Is institutional affiliation required?
* Is a consortium required?
* Can an Armenian organization participate?
* Is the opportunity suitable now or only at a later maturity stage?
* What application-cycle dependency exists?

---

## F4 — Fellowships / Placements / Training

Includes:

* research internships;
* neuroscience schools;
* advanced training programs;
* placements;
* fellowships;
* mentored research programs.

Primary enrichment questions include:

* What academic stage is required?
* Is the current application cycle open?
* Is institutional affiliation required?
* What is the deadline?
* Does the program provide research access, mentorship, training, or all three?
* Is it usable now or only at a later academic stage?

---

## F5 — Hardware / Industry / Technology Access

Includes:

* EEG hardware;
* wearable EEG;
* sleep technology companies;
* real-time physiological platforms;
* developer ecosystems;
* BCI systems;
* research-device companies.

Primary enrichment questions include:

* Does the system expose raw EEG?
* Is real-time streaming possible?
* Are APIs, SDKs, LSL, or other interfaces available?
* What sampling/channel configuration is available?
* Can external closed-loop software be integrated?
* Is the system EEG-core technology or only peripheral sensing?
* Which questions require direct vendor contact?

---

## F6 — Networks / Events / Multipliers

Includes:

* scientific societies;
* neuroscience conferences;
* EEG communities;
* diaspora networks;
* innovation ecosystems;
* networking programs;
* scientific events.

Primary enrichment questions include:

* Is the event/network currently active?
* What is the next participation window?
* Does it provide collaboration discovery, presentation, mentorship, or introductions?
* Is it directly useful or primarily a multiplier?
* At what project maturity does participation become valuable?

---

## F7 — Governance / Institutional Enablement

Includes:

* IRBs;
* ethics structures;
* institutional research-governance pathways;
* reliance mechanisms;
* regulatory infrastructure.

Primary enrichment questions include:

* What type of study does the mechanism govern?
* Is institutional affiliation required?
* Can it independently approve a study?
* What responsible-investigator requirements exist?
* What becomes relevant only when a human-subject protocol exists?
* What governance mechanisms are complementary rather than substitutes for IRB review?

---

## F8 — Future-Horizon Strategic Technologies

Includes:

* foundation models for sleep;
* advanced neural decoding;
* digital twins;
* future sensing paradigms;
* emerging computational neuroscience technologies.

Primary enrichment questions include:

* Is the technology sufficiently mature to affect the V1 roadmap?
* Does it solve a current Neuro-TMR bottleneck?
* Is it better treated as Gen-2/Gen-3 technology?
* Can it provide useful methods or representations now?
* Would adopting it prematurely increase unnecessary scope?

---

# Universal L7 Enrichment Fields

Where applicable, each opportunity was enriched using the following decision-oriented fields:

1. **Current State**
2. **Concrete Neuro-TMR Contribution**
3. **Access Route**
4. **Dependencies / Prerequisites**
5. **Timing / Application Window**
6. **Evidence Anchors**
7. **Decision-Critical Unknown**
8. **Impact of Remaining Uncertainty**
9. **Next Appropriate Action**
10. **L7 Status**

Not every field applies equally to every opportunity type.

The functional-family methodology determines which questions deserve the greatest research depth.

---

# L7 Stopping Rule

Research on an opportunity stops when:

> **Additional desk research is unlikely to materially change its later L8 evaluation.**

L7 does not require every uncertainty to disappear.

Some remaining uncertainties inherently require a future external event.

These were treated as legitimate residuals.

---

## Residual Uncertainty Classes

### `CONTACT_DEPENDENT`

Examples:

* willingness of a researcher to collaborate;
* laboratory capacity;
* possibility of mentorship;
* unpublished collaboration requirements.

These cannot be resolved through further browsing.

---

### `COMMERCIAL_OR_INTEGRATION_DEPENDENT`

Examples:

* hardware licensing;
* API permissions;
* SDK access;
* research pricing;
* commercial partnership terms.

These require vendor interaction.

---

### `FUTURE_CYCLE_DEPENDENT`

Examples:

* future grant calls;
* annual fellowship cycles;
* future conference deadlines;
* programs whose next call is not yet published.

---

### `ELIGIBILITY_OR_STAGE_DEPENDENT`

Examples:

* bachelor's-level eligibility;
* graduate-student requirements;
* institutional affiliation;
* researcher-status requirements.

---

### `EVENT_CYCLE_DEPENDENT`

Examples:

* conferences whose current edition has passed;
* annual community meetings;
* future workshops.

---

### `HOST_OR_INSTITUTION_DEPENDENT`

Examples:

* grants requiring a host university;
* human-subject research requiring an institutional investigator;
* programs requiring organizational affiliation.

---

### `STUDY_TRIGGER_DEPENDENT`

Examples:

* IRB requirements;
* clinical-investigation requirements;
* human-subject governance mechanisms.

These become relevant only after a concrete study/protocol exists.

---

### `FUTURE_HORIZON_DEPENDENT`

Examples:

* emerging neural foundation models;
* advanced decoding systems;
* digital-twin technologies;
* experimental future sensing systems.

These remain strategically relevant without modifying V1 prematurely.

---

# L7 Execution Rule

L7 did **not** perform:

* cross-family ranking;
* final prioritization;
* active/reserve outreach allocation;
* 80/20 outreach selection;
* outreach-wave construction;
* outreach drafting;
* candidate contact.

Those activities belong to downstream layers.

The purpose of L7 was information improvement rather than portfolio selection.

---

# L7 Result

| Measure                                    |  Result |
| ------------------------------------------ | ------: |
| Opportunities entering L7                  |     120 |
| Opportunities processed through enrichment |     120 |
| Opportunities removed at L7                |       0 |
| Opportunities advancing to L8              | **120** |

L7 was intentionally **non-eliminative**.

The 120 qualified opportunities remain in the candidate universe, but they now carry substantially better information for comparative evaluation.

---

# Family Completion

| Family                                                 | Completion |
| ------------------------------------------------------ | ---------- |
| F1 — Scientific Collaboration & Expertise              | `L7_READY` |
| F2 — Data / Research Infrastructure & Path V Resources | `L7_READY` |
| F3 — Funding & Institutional Support                   | `L7_READY` |
| F4 — Fellowships / Placements / Training               | `L7_READY` |
| F5 — Hardware / Industry / Technology Access           | `L7_READY` |
| F6 — Networks / Events / Multipliers                   | `L7_READY` |
| F7 — Governance / Institutional Enablement             | `L7_READY` |
| F8 — Future-Horizon Strategic Technologies             | `L7_READY` |

---

# L7 Gate Decision

**L7 COMPLETE**

The 120 opportunities that survived L6 have reached the targeted-enrichment stopping threshold.

They are now ready for:

> **L8 — Within-Family Comparative Evaluation and Ranking**

L8 will introduce comparison and ranking.

L7 itself makes no final prioritization decision.
