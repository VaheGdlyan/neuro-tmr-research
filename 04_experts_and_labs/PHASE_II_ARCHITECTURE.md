# Phase II — Execution Architecture

## 1. Purpose

Phase I of the Neuro-TMR project is complete.

It produced an evidence-derived first-generation reference hypothesis:

> **An EEG-guided, stage-aware, real-time closed-loop Targeted Memory Reactivation system integrated with compatible existing EEG hardware.**

This pathway enters Phase II as a **hypothesis under evaluation**, not as a validated system architecture.

Phase II exists to stress-test the Phase-I conclusions through three complementary forms of evidence:

* **Path A — External Expert Review**
* **Path E — Scientific Collaboration**
* **Path V — Validation-Lite**

The objective is to determine what survives external scientific criticism, what changes when practical constraints are introduced, what can be investigated using real EEG data, and what evidence is still required before serious engineering is justified.

Engineering remains gated throughout Phase II.

---

# 2. Phase II Mission

Phase II asks:

> **Does the Phase-I reference pathway survive contact with experts, real data, and practical scientific constraints?**

Phase II is therefore a **falsification and validation-planning phase**.

It is not:

* an attempt to defend Phase I;
* product development;
* full empirical validation of TMR;
* an attempt to obtain expert agreement;
* a publication race;
* three independent projects running without interaction.

The current pathway may survive Phase II unchanged.

It may also be revised, narrowed, expanded, returned to research, or rejected.

All of these are legitimate outcomes if they are evidence-driven.

---

# 3. Execution Model

The three paths will operate in parallel, but they will not begin randomly.

The initial execution order is:

```text
Phase II Architecture
        ↓
Path A Preparation
        ↓
Path A Outreach Begins
        ↓
Path E Preparation + Outreach
        ↓
Path V Begins While External Responses Are Pending
        ↓
A ↔ E ↔ V Continue in Parallel
        ↓
Track-Level Syntheses
        ↓
Phase-II Convergence Review
        ↓
PHASE_II_SYNTHESIS.md
        ↓
Decision Gate
```

## Why Path A Starts First

External expert review has the longest and least predictable response cycle.

The Phase-I work should therefore be placed in front of relevant experts as early as possible.

While responses are pending:

* Path E develops collaboration relationships.
* Path V proceeds with technical investigation.

Phase II should never become idle simply because an external response is pending.

---

# 4. Path A — External Expert Review

## Goal

Expose the Phase-I manuscript, conclusions, and reference pathway to researchers capable of identifying:

* scientific weaknesses;
* missing literature;
* unsupported assumptions;
* overstatements;
* alternative interpretations;
* methodological concerns;
* important validation questions.

The purpose is not to ask:

> “Do you agree with this project?”

The purpose is to ask:

> **“Where is this reasoning wrong, incomplete, or insufficiently supported?”**

---

## A1 — Define Expert Categories

The expert pool should cover complementary domains.

Initial categories:

1. Targeted Memory Reactivation
2. Sleep and memory consolidation
3. Sleep electrophysiology / EEG
4. Closed-loop sleep or neuroscience systems
5. Wearable sleep monitoring
6. Real-time sleep-stage classification

One researcher may belong to several categories.

The objective is not equal representation of every category, but sufficient coverage of the scientific assumptions underlying the Phase-I pathway.

---

## A2 — Build the Expert Long List

Identify approximately:

> **15–20 potentially relevant experts**

Record them in:

`expert_review/targets.md`

For each expert document:

* Name
* Institution
* Research focus
* Relevant publications
* Relevant Phase-I topic
* Why their perspective matters
* Which assumption or question they could challenge
* Contact information
* Priority
* Outreach status

---

## A3 — Select the First Outreach Group

Prioritize approximately:

> **10–12 experts**

Selection should favor complementary expertise rather than only the most famous names.

The group should contain researchers capable of challenging different parts of the pathway.

---

## A4 — Prepare the Review Package

The review package should remain concise.

It may include:

1. Phase-I manuscript
2. Public GitHub research repository
3. Short project introduction
4. Brief explanation of the current reference hypothesis
5. 3–5 targeted questions

Questions should be adapted to the recipient.

Possible questions include:

* Is the EEG-first reasoning scientifically defensible?
* Is stage-aware cueing a reasonable first-generation simplification?
* What evidence or literature is missing?
* Which assumption would you validate before engineering?
* Where does the manuscript overstate the available evidence?
* What alternative pathway would you consider more defensible?

The outreach must explicitly state that **critical feedback is desired**.

---

## A5 — Conduct the First Outreach Wave

Send personalized review requests to approximately:

> **10–12 high-priority experts**

Do not mass-email.

Each message should explain why that specific researcher was contacted.

A single respectful follow-up may be sent when appropriate after approximately two weeks.

---

## A6 — Expand Outreach if Necessary

The initial outreach number is an operational target, not a scientific threshold.

If the first wave produces too little technically useful feedback, expand the pool.

A practical rule:

> If fewer than approximately three substantive independent responses have been obtained after the first outreach cycle and follow-up period, identify and contact approximately five additional experts.

The objective is **quality and diversity of criticism**, not a particular response count.

---

## A7 — Define Substantive Feedback

A response is considered substantive when it does at least one of the following:

* challenges a specific scientific claim;
* qualifies an assumption;
* identifies missing evidence;
* recommends relevant literature;
* proposes an alternative interpretation;
* identifies a practical or methodological weakness;
* recommends a concrete validation question.

A response such as:

> “Interesting project, looks good.”

is appreciated but does not constitute substantive scientific review.

---

## A8 — Record Feedback

Store meaningful feedback under:

`expert_review/feedback/`

For each substantial response record:

* feedback received;
* claim or assumption challenged;
* reasoning provided;
* literature suggested;
* validation question suggested;
* possible implication for the project;
* whether the issue should be routed to another Phase-II track.

Expert feedback should not be treated as final authority.

It becomes one input into the Phase-II evidence base.

---

## A9 — Path A Completion

Path A becomes ready for synthesis when:

* several independent substantive reviews have been received;
* relevant scientific domains have reasonable coverage;
* repeated criticisms and disagreements can be identified;
* additional outreach is producing diminishing informational value.

The number of responses alone does not determine completion.

---

## A10 — Produce the Track-A Synthesis

Write:

`expert_review/TRACK_A_SYNTHESIS.md`

It should answer:

* What did experts repeatedly challenge?
* Where did experts agree?
* Where did experts disagree?
* What literature was missing?
* Which Phase-I assumptions strengthened?
* Which assumptions weakened?
* What new questions appeared?
* What should be investigated before engineering?

---

# 5. Path E — Scientific Collaboration

## Goal

Identify researchers, laboratories, and institutions with the expertise, infrastructure, data, or scientific interest required to investigate questions that cannot be answered through literature review or independent technical work alone.

Path E asks:

> **Who could realistically help us test, improve, or challenge the current pathway?**

---

## E1 — Define Collaboration Categories

Search across areas such as:

1. TMR and memory reactivation
2. Sleep and memory neuroscience
3. EEG / sleep electrophysiology
4. Closed-loop sleep stimulation
5. Wearable sleep monitoring
6. Real-time sleep-state estimation
7. Translational neurotechnology

Relevant researchers and institutions may be located:

* in Armenia;
* regionally;
* internationally.

Scientific fit is more important than geography.

---

## E2 — Build the Collaboration Long List

Identify approximately:

> **10–15 potentially relevant researchers, laboratories, or research groups**

Record them in:

`collaboration/labs_and_researchers.md`

For each target document:

* Institution
* Researcher / PI
* Country
* Research focus
* Relevant recent work
* Relevant infrastructure
* Existing datasets if known
* Why collaboration may make sense
* What scientific question they could help answer
* Priority
* Contact status

---

## E3 — Select the Initial Outreach Group

Prioritize approximately:

> **5–8 high-value targets**

The first group should remain small enough that every message can be genuinely personalized.

---

## E4 — Begin Exploratory Outreach

The first message should not begin with a complex collaboration proposal.

It should briefly explain:

* what Phase I produced;
* that Phase II is focused on external review and validation;
* why their work is specifically relevant;
* what scientific question connects the project to their expertise.

The initial goal may simply be:

> a useful email exchange or a short scientific conversation.

---

## E5 — Track Every Contact

Use:

`collaboration/outreach_log.md`

Recommended fields:

```text
Date
Researcher / Lab
Reason for Contact
Contact Method
Status
Response
Follow-Up
Next Action
Notes
```

Possible statuses:

* Identified
* Prioritized
* Prepared
* Contacted
* Follow-Up Sent
* Responded
* Scientific Conversation
* Active Discussion
* Actionable Opportunity
* Closed

---

## E6 — Collaboration Opportunity Levels

Collaboration should not be treated as binary.

### Level 1 — Exploratory Contact

Examples:

* positive reply;
* brief exchange;
* willingness to discuss the project.

Useful, but not yet collaboration.

### Level 2 — Scientific Engagement

Examples:

* substantive scientific conversation;
* repeated communication;
* detailed methodological feedback;
* discussion of possible experiments or datasets.

### Level 3 — Actionable Opportunity

Examples:

* potential dataset access;
* shared analysis;
* repeated scientific involvement;
* specific validation study discussion;
* laboratory access;
* prospective experimental collaboration;
* co-development of a protocol;
* credible path toward a formal research partnership.

The objective of Path E is not to maximize the number of contacts.

The objective is to discover whether **one or more genuine scientific opportunities exist**.

---

## E7 — Document Meetings

For every meaningful call or meeting create:

`collaboration/meetings/YYYY-MM-DD_name.md`

Record:

* participants;
* questions discussed;
* scientific criticisms;
* alternative interpretations;
* validation suggestions;
* datasets mentioned;
* available infrastructure;
* collaboration interest;
* unresolved issues;
* next action.

---

## E8 — Record Actionable Opportunities

When something concrete appears, document it under:

`collaboration/opportunities/`

Examples:

* wearable EEG dataset access;
* simultaneous PSG + wearable reanalysis;
* prospective TMR validation;
* joint signal-processing investigation;
* scientific advisory relationship.

Do not create opportunity documents for speculative possibilities.

---

## E9 — Path E Completion

Path E becomes ready for synthesis when:

* the major relevant collaboration categories have been explored;
* the highest-value targets have been contacted;
* meaningful responses have been followed through;
* the realistic collaboration landscape is understood.

A successful Track E does not require a signed collaboration agreement.

Possible valid outcomes include:

* actionable collaboration opportunity;
* several serious scientific relationships;
* access to valuable data or expertise;
* clear understanding that collaboration is not currently available.

All are useful information for the Phase-II decision.

---

## E10 — Produce the Track-E Synthesis

Write:

`collaboration/TRACK_E_SYNTHESIS.md`

It should answer:

* Who engaged meaningfully?
* What expertise became available?
* What resources or datasets may be available?
* What validation approaches appear realistic?
* What collaboration opportunities exist?
* What barriers exist?
* Which Phase-I assumptions were challenged by practical laboratory experience?

---

# 6. Path V — Validation-Lite

## Goal

Work directly with real sleep EEG data to investigate technical prerequisites relevant to the Phase-I reference pathway.

Track V asks:

> **What happens when some of our technical assumptions meet actual EEG data?**

Track V does not validate:

* TMR efficacy;
* wearable EEG as a complete modality;
* the final closed-loop architecture;
* product readiness.

Its purpose is to understand constraints, failure modes, and technical uncertainty.

---

# 7. Path V — Level 1: Baseline EEG Investigation

## V1.1 — Freeze the Initial Question

The initial domain is:

> **EEG-based sleep-state classification under reduced and causal information constraints.**

The exact classification target should be frozen before modeling begins.

Possible emphasis:

* NREM / N3 identification;
* N2 vs. N3 discrimination;
* cue-eligible vs. cue-ineligible states;
* uncertainty handling.

---

## V1.2 — Evaluate Candidate Public Datasets

Compare several suitable datasets.

Document:

* subject count;
* EEG channels;
* sampling rate;
* sleep-stage labels;
* scoring standard;
* population;
* recording duration;
* additional physiological signals;
* access conditions;
* license;
* suitability for the investigation.

Record the comparison in:

`validation_lite/dataset_selection.md`

---

## V1.3 — Select One Dataset

Begin with one dataset.

Selection should favor:

* multiple subjects;
* full-night recordings;
* reliable sleep-stage annotations;
* usable EEG;
* transparent access;
* suitability for subject-wise evaluation.

Do not combine datasets before understanding the first one properly.

---

## V1.4 — Understand the Data Before Modeling

Before training a classifier:

* inspect raw EEG;
* visualize full-night recordings;
* understand channel placement;
* inspect stage distributions;
* reproduce hypnograms;
* understand 30-second epoch structure where applicable;
* inspect representative epochs from each stage;
* inspect transitions;
* identify obvious artifacts.

The first objective is understanding sleep EEG.

Not model accuracy.

---

## V1.5 — Build a Baseline Classification Pipeline

Create a reproducible pipeline:

```text
EEG
 ↓
Preprocessing
 ↓
Epoching
 ↓
Feature Extraction / Model
 ↓
Sleep-State Prediction
 ↓
Subject-Wise Evaluation
```

Evaluation must prevent subject leakage.

Epochs from the same sleeper should not be randomly distributed across training and test sets in a way that creates unrealistic performance estimates.

---

## V1.6 — Evaluate Relevant Metrics

Do not rely only on overall accuracy.

Depending on the selected question, investigate:

* precision;
* recall;
* F1 score;
* confusion matrix;
* N3 sensitivity;
* N2 ↔ N3 confusion;
* Wake / NREM confusion;
* subject-to-subject variability;
* confidence / uncertainty;
* failure cases.

---

## V1.7 — Reduce Available Information

Progressively investigate reduced EEG information:

* available multi-channel EEG;
* reduced-channel configuration;
* potentially single-channel EEG.

The objective is to understand how classification changes as physiological observability is reduced.

Important:

> Reduced PSG EEG channels are **not equivalent to real wearable EEG**.

Results must not be described as wearable validation.

---

## V1.8 — Introduce Causal Constraints

A real closed-loop system cannot use future information.

After the retrospective baseline works, investigate classification using:

* current data;
* previous data;
* no future epochs.

This begins examining the difference between:

> **retrospective sleep scoring**

and

> **intervention-ready state estimation.**

---

## V1.9 — Document Failure Modes

Track V is successful even if the classifier performs poorly.

Document:

* difficult stages;
* difficult subjects;
* transition ambiguity;
* signal artifacts;
* confidence failures;
* reduced-channel degradation;
* causal-performance degradation;
* generalization problems.

Failure modes are a primary output.

---

# 8. Path V — Level 2: Realism Upgrade

Level 2 is conditional.

It becomes possible only if Phase II obtains more representative data through:

* Path E collaboration;
* openly available wearable EEG datasets;
* simultaneous wearable EEG + PSG data;
* another scientifically defensible source.

Possible questions:

* Do conclusions from V1 survive with actual wearable EEG?
* How does real wearable signal quality change performance?
* How stable is the signal across an entire night?
* How does electrode displacement affect classification?
* How large is the gap between laboratory EEG and wearable EEG?
* How well does the system generalize across unseen users?

If representative wearable data cannot be obtained during Phase II, this does **not** make Track V a failure.

The unresolved limitation should instead be documented explicitly:

> **Wearable-level validation remains unresolved and requires future collaborative or empirical work.**

---

## V3 — Path V Completion

Track V is complete when:

* the predefined investigation question has been answered as far as the available data allow;
* baseline classification has been reproduced;
* relevant reduced-information constraints have been investigated;
* causal constraints have been considered;
* important failure modes have been documented;
* further optimization is producing diminishing scientific value.

The objective is understanding, not benchmark competition.

---

## V4 — Produce the Track-V Report

Write:

`validation_lite/TRACK_V_REPORT.md`

It should answer:

* What worked?
* What failed?
* How much variability existed?
* What assumptions were supported?
* What assumptions weakened?
* Which conclusions cannot be made from the available data?
* What questions should now be taken back to experts?
* What questions require collaboration or future empirical validation?

---

# 9. Cross-Track Integration Protocol

The three tracks must not operate independently.

Use:

`TRACK_INTEGRATION_LOG.md`

to record important information that should move between tracks.

Recommended structure:

```text
Date:
Source Track:
Finding:
Why It Matters:
Target Track:
Required Action:
Status:
```

---

## Routing Rules

### A → V

If an expert identifies a technical assumption that can reasonably be examined using available data:

→ add it to Track V for consideration.

### V → A

If Track V produces an unexpected or ambiguous result:

→ formulate a specific scientific question for relevant experts.

### E → V

If a collaborator provides better data, methodological knowledge, or access to a more realistic dataset:

→ evaluate whether Track V should be upgraded.

### V → E

If Track V exposes a limitation that cannot be resolved independently:

→ identify labs capable of addressing that limitation.

### A → E

If expert review identifies a researcher, laboratory, dataset, or experimental capability relevant to Phase II:

→ add it to Path E.

### E → A

If a collaborating scientist challenges a major Phase-I assumption:

→ treat that criticism as scientific feedback and include it in Track A synthesis where appropriate.

---

# 10. Integration Review

During active execution, perform a brief integration review approximately once per week.

The purpose is not project management bureaucracy.

It is to ask:

1. What did Track A learn?
2. What did Track E learn?
3. What did Track V learn?
4. Did any finding create a question for another track?
5. Should any track change scope?
6. Has any major Phase-I assumption strengthened or weakened?

Important decisions should be recorded in:

`TRACK_INTEGRATION_LOG.md`

---

# 11. Evidence Conflict Rule

Tracks may disagree.

This is expected.

There is no universal hierarchy such as:

> empirical data > expert opinion > theoretical reasoning.

Instead, evidence should be judged according to how directly and reliably it addresses the disputed claim.

When evidence conflicts, evaluate:

1. **Relevance**
   Does the evidence answer the actual question?

2. **Similarity to Intended Conditions**
   How similar are the experimental conditions to the future use case?

3. **Methodological Quality**
   How strong is the study or analysis design?

4. **Independence**
   Is the evidence independent or derived from the same assumptions/data?

5. **Reproducibility**
   Has the finding appeared repeatedly?

6. **Expert Interpretation**
   Are specialists identifying limitations or alternative explanations?

7. **Remaining Uncertainty**
   What can still not be concluded?

The most directly relevant, methodologically defensible evidence should carry the greatest weight.

If conflict cannot be resolved:

> **The correct outcome is additional validation, not forced agreement.**

---

# 12. Work Strategy

Phase II should avoid idle waiting.

```text
Waiting for expert responses?
    → Continue Path E or Path V.

Waiting for collaboration responses?
    → Continue Path A research or Path V.

Track V blocked?
    → Work on expert targets, collaboration research,
      feedback synthesis, or newly recommended literature.

New criticism arrives?
    → Route it immediately to the relevant track.
```

Daily work can shift between tracks according to what is actionable.

---

# 13. Track Outputs

Before the Phase-II convergence decision, the tracks should produce:

### Path A

`expert_review/TRACK_A_SYNTHESIS.md`

### Path E

`collaboration/TRACK_E_SYNTHESIS.md`

### Path V

`validation_lite/TRACK_V_REPORT.md`

All three feed:

`PHASE_II_SYNTHESIS.md`

Conceptually:

```text
TRACK_A_SYNTHESIS ─────┐
                       │
TRACK_E_SYNTHESIS ─────┼──→ PHASE_II_SYNTHESIS
                       │
TRACK_V_REPORT ────────┘
```

---

# 14. Phase-II Convergence Review

The first major convergence review should occur approximately:

> **3–4 months after active execution begins**

This is a review milestone, not an automatic termination date.

At this point ask:

* Is enough expert feedback available?
* Is the collaboration landscape understood?
* Has Track V produced meaningful technical evidence?
* Are major external dependencies still active?
* Can a defensible decision already be made?

Possible outcomes:

### Evidence is sufficient

→ complete the Phase-II synthesis and make the decision.

### One high-value activity remains active

→ extend only the relevant track.

### Evidence remains insufficient across several tracks

→ reassess the Phase-II strategy rather than allowing indefinite continuation.

Phase II should remain finite, but scientifically valuable opportunities should not be discarded simply because an arbitrary calendar date has passed.

---

# 15. PHASE_II_SYNTHESIS.md

At convergence, write:

`PHASE_II_SYNTHESIS.md`

The synthesis should answer five questions:

## What Survived?

Which Phase-I assumptions remain defensible after expert review, collaboration discussions, and technical investigation?

## What Broke?

Which assumptions were contradicted, weakened, or shown to require qualification?

## What Changed?

What revisions should be made to the reference pathway?

## What Remains Unknown?

Which questions still require empirical evidence?

## What Happens Next?

Which Phase-II exit outcome is justified?

The document should be as long as required to make the decision clearly.

No predefined page count is necessary.

---

# 16. Phase-II Decision Gate

Phase II ends with one of five outcomes.

---

## Outcome 1 — PROCEED

Appropriate when:

* no major unresolved criticism invalidates the core direction;
* Track V reveals no technical show-stopper within the scope investigated;
* the remaining uncertainties are compatible with moving toward a controlled next-stage implementation or validation effort;
* a credible route toward further validation exists.

This does **not** mean the final product is scientifically validated.

It means the next engineering/validation phase is justified.

---

## Outcome 2 — VALIDATE FIRST

Appropriate when:

* the general pathway remains plausible;
* one or more critical assumptions remain unresolved;
* those assumptions can be addressed through a focused empirical study.

Possible examples:

* wearable EEG signal quality;
* real-time stage detection;
* cue-state uncertainty;
* post-cue arousal monitoring;
* EEG vs. peripheral sensing;
* stage-aware vs. finer temporal targeting.

The next phase becomes a focused validation study rather than full engineering.

---

## Outcome 3 — REVISE

Appropriate when:

* external criticism and/or technical evidence weakens a specific part of the reference pathway;
* an alternative pathway becomes more scientifically defensible.

Possible revisions may involve:

* sensing modality;
* sleep-state target;
* stage-aware vs. event/phase-aware control;
* real-time assumptions;
* cue-control logic;
* system requirements.

The revised hypothesis should be documented explicitly before proceeding.

---

## Outcome 4 — RETURN TO RESEARCH

Appropriate when:

* experts identify an important literature gap;
* a foundational scientific assumption was insufficiently investigated;
* Phase II exposes a question that cannot yet be evaluated without additional evidence synthesis.

Only the affected research question should be reopened.

Phase I should not be repeated unnecessarily.

---

## Outcome 5 — STOP / REFRAME

Appropriate when:

* major scientific assumptions fail;
* the translational pathway becomes insufficiently defensible;
* technical or empirical evidence undermines the central premise;
* continuing toward the current goal is no longer justified.

The project may:

* stop;
* narrow its scope;
* become a different research project;
* adopt an alternative neurotechnology direction.

Stopping or reframing because of evidence is a successful scientific outcome.

---

# 17. Scientific Guardrails

Throughout Phase II:

> **Expert authority is not proof.**

> **Public EEG classification is not wearable EEG validation.**

> **Reduced-channel PSG is not equivalent to real wearable EEG.**

> **Sleep-stage classification is not TMR efficacy validation.**

> **Technical feasibility is not product readiness.**

> **Collaboration interest is not scientific confirmation.**

> **Publication is not empirical validation.**

> **A high classification accuracy number is not sufficient without understanding subject variability, failure modes, and evaluation design.**

> **Negative results are useful results.**

> **Unresolved disagreement should produce a validation question, not forced consensus.**

> **The Phase-I reference pathway is allowed to change.**

> **Engineering remains gated until Phase II provides a defensible reason to proceed.**

---

# 18. First Execution Sequence

Once this architecture is frozen, Phase II execution begins.

## First — Path A

1. Define expert categories.
2. Identify 15–20 candidates.
3. Prioritize approximately 10–12.
4. Research why each person matters.
5. Prepare the review package.
6. Draft personalized outreach.
7. Send the first review requests.

---

## Second — Path E

1. Define collaboration categories.
2. Identify 10–15 labs/researchers.
3. Prioritize approximately 5–8.
4. Research their work and capabilities.
5. Prepare personalized exploratory outreach.
6. Begin contact.
7. Track all responses and opportunities.

---

## Third — Path V

1. Freeze the initial investigation question.
2. Identify candidate public sleep EEG datasets.
3. Compare datasets scientifically.
4. Select one dataset.
5. Understand its recordings and annotations.
6. Build the baseline classification pipeline.
7. Evaluate subject-wise performance.
8. Investigate relevant stage confusion.
9. Reduce available EEG information.
10. Introduce causal constraints.
11. Document failure modes.
12. Upgrade to representative wearable data if collaboration makes this possible.

---

## Then — Parallel Execution

After initialization:

```text
Path A
    ↕
Path E
    ↕
Path V
```

Continue routing important findings through:

`TRACK_INTEGRATION_LOG.md`

until the tracks are ready for synthesis.

---

# 19. Phase II Working Principle

> **Phase I asked what the literature allows us to believe.**
>
> **Phase II asks whether that belief survives contact with experts, real data, and practical scientific constraints.**

The objective of Phase II is not to prove the Phase-I pathway correct.

The objective is to determine:

> **what survives, what changes, what must still be tested, and what the evidence justifies doing next.**
