# Closed-Loop Architecture

## Objective

This document records the architectural reasoning that led to selecting a **real-time closed-loop architecture** as the foundation of the product. Rather than describing implementation details, it documents the strategic engineering decisions made during the product discovery phase and the scientific reasoning behind those decisions.

The purpose of this document is to preserve the rationale for the selected architecture so that future engineering decisions remain consistent with the validated neuroscience research.

---

# Background

The completed neuroscience research demonstrated that **Targeted Memory Reactivation (TMR)** is not simply an audio playback process. Its effectiveness depends on delivering sensory cues under specific physiological conditions during sleep.

The literature consistently identified several important biological constraints:

- Memory reactivation occurs only during appropriate sleep states.
- Sleep architecture continuously changes throughout the night.
- The timing of sensory cues directly influences TMR effectiveness.
- Sleep patterns differ between individuals and even between consecutive nights.
- Physiological monitoring is required to determine when cue delivery is appropriate.

These findings indicate that successful consumer implementation requires continuous observation of the user's physiological state rather than relying on predetermined timing.

---

# Architectural Alternatives

## Open-Loop Architecture

An open-loop system operates according to predefined rules without continuously adapting to the user's physiological state.

Typical characteristics include:

- Fixed cue schedule
- Predefined stimulation intervals
- No physiological feedback
- No adaptation to real-time sleep changes
- Lower implementation complexity

Although easier to implement, this approach assumes that every user follows a predictable sleep pattern, which contradicts the variability observed in sleep physiology.

---

## Closed-Loop Architecture

A closed-loop system continuously analyzes physiological signals and dynamically determines the appropriate timing for cue delivery.

Typical characteristics include:

- Continuous physiological monitoring
- Real-time sleep-stage estimation
- Dynamic decision making
- Adaptive cue scheduling
- Continuous feedback throughout the night

Rather than assuming when stimulation should occur, the system continuously determines whether the required biological conditions are currently satisfied.

---

# Architectural Comparison

| Open Loop | Closed Loop |
|------------|-------------|
| Fixed schedule | Real-time physiological decisions |
| No feedback | Continuous physiological feedback |
| Cannot adapt to user state | Continuously adapts to changing sleep |
| Lower engineering complexity | Higher engineering complexity |
| Lower expected reliability | Higher expected biological reliability |

---

# Why the Open-Loop Approach Was Rejected

During the product discovery phase, the open-loop approach was evaluated as a potential architecture.

However, several limitations were identified:

- Sleep-stage transitions vary significantly between users.
- Sleep timing changes from night to night.
- Unexpected awakenings cannot be predicted.
- Cue delivery may occur during inappropriate sleep stages.
- The system cannot respond to real-time physiological changes.

Because TMR depends on delivering cues during appropriate biological conditions, an open-loop approach would likely reduce the probability of successful memory reactivation under real-world conditions.

For these reasons, the open-loop architecture was not selected as the primary design direction.

---

# Closed-Loop Architecture Decision

Based on the completed neuroscience research and the identified biological constraints, the project adopts a **real-time closed-loop architecture** as its primary engineering direction.

Within this architecture:

- Physiological signals are continuously monitored.
- The user's sleep state is estimated in real time.
- Cue delivery decisions are generated dynamically.
- The system continuously adapts to the user's physiological state throughout the night.

The objective is to maximize the probability of delivering cues during biologically appropriate conditions while minimizing unnecessary or mistimed stimulation.

---

# Stage Detection vs. Phase Locking

The scientific literature describes two primary approaches for triggering auditory cues:

## Sleep-Stage Detection

Cue delivery is triggered after detecting an appropriate sleep stage (primarily NREM Slow-Wave Sleep).

Advantages:

- Strong scientific evidence.
- Lower engineering complexity.
- Suitable foundation for consumer implementation.

---

## Slow-Wave Phase Locking

Cue delivery is synchronized with specific phases of individual slow oscillations.

Potential advantages:

- Greater temporal precision.
- Possible improvement in TMR effectiveness.

Limitations:

- Significantly higher computational complexity.
- Greater hardware requirements.
- Limited evidence regarding necessity for consumer applications.

---

# Current Architectural Decision

At the current stage of the project, the architecture will prioritize **real-time sleep-stage detection** rather than slow-wave phase locking.

This decision was made because:

- Sleep-stage detection is consistently supported throughout the scientific literature.
- It provides the necessary biological conditions required for TMR.
- It represents a more practical foundation for an initial consumer implementation.
- Phase locking can be investigated as a future optimization after validating the core system.

---

# Current High-Level Architecture

```text
Wearable Physiological Signals
                │
                ▼
    Real-Time Signal Processing
                │
                ▼
      Sleep Stage Detection
                │
                ▼
        Decision Engine
                │
                ▼
         Cue Scheduler
                │
                ▼
        Audio Cue Delivery
                │
                ▼
 Continuous Physiological Monitoring
```

This diagram represents the conceptual architecture only. Individual software components, algorithms, and infrastructure will be defined after the product validation phase.

---

# Future Validation Questions

Several critical engineering questions remain unanswered and will be addressed during the product validation phase.

Current research questions include:

- Can PPG-based wearables provide sufficient accuracy for real-time sleep-stage detection?
- Is EEG required to achieve meaningful TMR effectiveness?
- What detection accuracy is required for practical consumer use?
- What latency requirements must the closed-loop system satisfy?
- Which consumer market receives the greatest value from this capability?

The answers to these questions will determine the final implementation architecture.

---

# Current Status

**Architecture:** Closed-Loop (Selected)

**Decision Status:** Working Architectural Decision

**Scientific Foundation:** Completed

**Product Validation:** In Progress

**Implementation:** Not Started

---

# Summary

The completed neuroscience research demonstrated that successful Targeted Memory Reactivation requires continuous adaptation to the user's physiological state rather than predefined stimulation schedules. Based on this evidence, the project adopts a **real-time closed-loop architecture** as the primary architectural direction.

This decision establishes the engineering foundation of the project while allowing future validation studies to determine the most appropriate sensing hardware, detection algorithms, and implementation strategy.