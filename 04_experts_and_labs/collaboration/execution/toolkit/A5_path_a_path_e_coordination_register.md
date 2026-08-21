# A5 — Path A ↔ Path E Coordination Register

**Toolkit:** Path E Execution Toolkit  
**Artifact:** A5  
**Status:** INITIAL / LIGHTWEIGHT  
**Date:** 2026-08-21  
**Scope:** Prevent duplicate outreach and coordinate expert-review contacts with later collaboration activity

---

## 1. Purpose

A5 defines one simple coordination rule:

> **If a person is already being contacted through Path A, Path E should wait for that expert-review interaction before deciding whether and how to pursue collaboration.**

The goal is to avoid duplicate cold outreach, conflicting messages, and premature collaboration requests.

---

## 2. Core Flow

```text
Path A expert contacted
        ↓
Wait for response / follow-up window
        ↓
Interpret the expert's response
        ↓
Convert useful feedback into project changes
        ↓
Decide whether a real collaboration opportunity exists
        ↓
If yes → continue through the existing relationship/thread where possible
If no  → close Path E collaboration attempt for now
```

---

## 3. Coordination Rule

For every expert or lab that appears in both Path A and Path E:

### While Path A is still active
Use:

`WAIT_PATH_A`

Do not:
- send a separate Path E cold email;
- ask for collaboration before receiving scientific feedback;
- create two parallel conversations with the same person.

### After a Path A response
First ask:

1. Did the expert provide useful scientific or technical feedback?
2. Does that feedback reveal a realistic collaboration path?
3. Is there a specific next ask that is different from the original expert-review question?

If all three are true, Path E may move forward.

---

## 4. Response Interpretation

| Path A Outcome | Path E Action |
|---|---|
| No response yet | Wait; use normal Path A follow-up timing |
| Auto-response only | Keep waiting unless a different contact route is justified |
| Short scientific reply | Convert feedback into project requirements first, then evaluate collaboration |
| Detailed / engaged reply | Strong candidate for a focused collaboration follow-up |
| Referral to another lab/person | Treat the referral as a new Path E route |
| Decline / no capacity | Respect the response; do not push collaboration |
| Response identifies a future trigger | Record the trigger and re-contact only when it exists |

---

## 5. Collaboration Conversion Rule

A Path A contact should move into Path E collaboration only when there is a **new concrete reason to contact them**.

Good examples:

- a Path V result is now available;
- their feedback created a specific validation question;
- they suggested a dataset, method, or experiment that now needs follow-up;
- they invited continued discussion;
- their lab has a capability directly needed by Neuro-TMR;
- a specific collaboration opportunity becomes realistic.

Bad reason:

> “They replied, so now we should ask them to collaborate.”

---

## 6. Minimal Coordination Register

Use the following fields for overlapping contacts.

| Field | Meaning |
|---|---|
| Expert / Lab | Person or group |
| Path A Status | Waiting / replied / auto-response / closed |
| Key Feedback | One-line summary |
| Project Change | Requirement / experiment / decision created from feedback |
| Path E Potential | None / possible / strong |
| Next Trigger | What must happen before collaboration follow-up |
| Contact Route | Existing thread / referral / new institutional contact |
| A5 Status | WAIT_PATH_A / READY_PATH_E / HOLD / CLOSED |

---

## 7. Operating Principle

> **Path A earns the relationship through scientific exchange; Path E uses that relationship only when a real collaboration need emerges.**

This keeps expert review independent and prevents Neuro-TMR from treating every expert reply as a collaboration opportunity.

---

## 8. Relationship to Other Toolkit Artifacts

- **A3** defines how a scientific collaboration request should be framed.
- **A5** decides when an overlapping Path A contact is ready for that request.
- **A6** records the actual outreach, response, and next action.

---

# A5 Completion Gate

A5 is complete when Neuro-TMR has:

- one rule against duplicate Path A / Path E outreach;
- one simple response-to-collaboration decision flow;
- a minimal status register for overlapping experts;
- a requirement that collaboration follow-up must have a new, concrete reason.

**A5 — PATH A ↔ PATH E COORDINATION REGISTER: INITIAL VERSION COMPLETE**
