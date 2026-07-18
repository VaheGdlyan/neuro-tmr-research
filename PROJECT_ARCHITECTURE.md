# PROJECT_ARCHITECTURE

## 1. Executive Project Overview

This project investigates **Targeted Memory Reactivation (TMR)**, an experimental neuroscience technique that uses sensory cues during sleep to enhance memory consolidation. It operates within the problem space of neurotechnology, cognitive enhancement, and applied sleep science.

The current maturity level of the project is at a critical inflection point. The foundational scientific research is complete, and the project is actively transitioning from biological inquiry into applied technology design. 

**The project has completed scientific exploration and is entering product discovery.**

## 2. Research Philosophy and Methodology

The project has strictly followed a core philosophy: **"Evidence before engineering."**

Before writing a single line of software or designing any hardware, the project engaged in a rigorous, structured scientific research phase. This approach was chosen to ensure that any future technology is built upon validated biological mechanisms rather than assumptions or popular misconceptions about the brain.

The research was structured around a systematic series of Research Questions (RQs). Each question was addressed by consulting primary scientific literature to establish the biological reality before extracting the engineering and product implications. Engineering decisions were intentionally delayed to prevent premature product assumptions and to allow the neuroscience to fully dictate the technical requirements.

## 3. Complete Research Journey

The repository reflects a deliberate progression of scientific knowledge, divided into three completed foundational phases.

### Phase 1: Brain Foundations
The research began with the fundamental principles of neuroscience. This phase established how neural communication works, the basic structure of the brain, and general brain dynamics. This baseline was necessary to understand how memories are initially formed and physically represented in neural networks.

### Phase 2: Sleep Science
The project then focused on sleep architecture. The research clarified that sleep is an active, highly organized physiological state, not merely a passive shutdown. Key knowledge gained included:
- The distinction between NREM and REM sleep.
- The critical role of Slow-Wave Sleep (SWS) in the biological process of memory consolidation.
- How to measure and identify these distinct sleep stages.

This knowledge was necessary because TMR interventions must target specific biological states. Attempting TMR without understanding sleep architecture would result in mis-timed interventions that either disrupt sleep or fail to influence memory.

### Phase 3: Targeted Memory Reactivation
Building upon sleep science, the research fully explored TMR. 
- **Definition:** TMR is a technique to bias the brain's natural memory reactivation processes.
- **Biological Mechanism:** It relies on associative learning. 
- **Encoding Phase:** A person learns new information while exposed to a specific sensory cue (like a sound) during wakefulness.
- **Execution Phase:** The same cue is presented during Slow-Wave Sleep without waking the individual.
- **Cue-Memory Association:** The sleeping brain processes the cue, increasing the probability that the associated memory trace is selected for neural replay and consolidation.
- **Limitations:** Scientific evidence clearly limits TMR's capabilities; it can strengthen existing memory traces, but it **cannot** create entirely new declarative memories from scratch.

## 4. Current Scientific Understanding

After completing the research phase, we have a clear synthesis of established knowledge and defined boundaries.

**Established Knowledge:**
- TMR can strengthen previously encoded memories by biasing the brain's endogenous memory-processing system.
- The hippocampus naturally coordinates the replay of recently acquired memories during sleep; TMR cooperates with this existing system rather than bypassing it.
- Precise sleep-stage classification is a non-negotiable technical requirement. The brain must be in Slow-Wave Sleep (SWS) for optimal results.
- Cues must be delivered at an intensity that registers biologically but does not awaken the user.

**Open Hypotheses / Limitations:**
- We cannot create new declarative memories while a user sleeps.
- While the biological mechanisms are understood in controlled laboratory settings, the efficacy of TMR in uncontrolled consumer environments remains to be fully characterized.

## 5. Repository Architecture

The repository is intentionally organized to reflect the "evidence before engineering" methodology:

- `04_research_questions/`: The core engine of the project, containing the structured RQs divided into `01_foundations/`, `02_sleep/`, `03_tmr/`, and the newly active `04_translation_to_product/`.
- `01_literature_review/`: Synthesized notes and takeaways from primary scientific literature supporting the RQs.
- `02_signal_architecture/`: (Future/emerging) Will house the technical translation of biological signals into engineering architecture.
- `03_daily_logs/`: Process tracking and chronological logs of the research journey.

This structure allowed the project to isolate biological facts from engineering speculation.

## 6. Important Decisions Already Made

Several fundamental decisions have been locked in based on the repository's research:

- **Research-first approach:** The decision to delay all engineering until the science was understood.
- **No premature engineering:** Preventing the development of "solutions in search of a problem."
- **Focus on scientific validation:** Ensuring the technology relies on peer-reviewed biology, specifically targeting the natural consolidation process during Slow-Wave Sleep.
- **System Role:** The system will not attempt to teach new information. Its role is strictly to act as a closed-loop system that monitors physiological states and delivers cues to enhance natural memory retention.

## 7. Current Project State

It is extremely important to understand the current boundary of the project. 

**Completed:**
- Scientific exploration
- Neuroscience foundation
- Sleep understanding
- TMR understanding

**Not completed:**
- Product definition
- Target customer
- Market validation
- Business model
- MVP definition
- Technical architecture

The missing elements are not failures or oversights; they are intentionally the immediate next phase. The scientific foundation had to be solid before any product definitions could be made.

## 8. Transition Into Product Discovery

The project is entering a new phase. 

The current question is no longer:
*"How do we build a TMR system?"*

The current question is:
*"What valuable product opportunities can emerge from TMR technology?"*

Moving forward, the product architecture will not just depend on the biology; it will depend heavily on user needs, market conditions, business models, reliability requirements, and acceptable complexity. We must discover what applications of TMR are both scientifically possible and highly valuable to specific users.

## 9. Constraints and Design Space

Any future product must operate within the following discovered constraints:

**Scientific constraints:**
- Need for real-time sleep-stage awareness (specifically SWS detection).
- Need for precise timing of cue delivery.
- Need for appropriate cue intensity that does not cause arousal or awakening.

**Engineering unknowns:**
- Hardware choice (consumer EEG vs. alternative wearable sensors).
- Sensor configuration for robust, comfortable nightly use.
- ML architecture for real-time, low-latency physiological signal processing on edge devices.
- Consumer feasibility (usability, comfort, battery life).

**Product unknowns:**
- Target user segment (e.g., students, professionals, language learners, clinical populations).
- Value proposition and specific use case.
- Market positioning and viable business models.

## 10. Questions For External Expert Review

To assist in navigating this transition from science to product, we seek input on the following strategic questions:

1. What product opportunities exist based on this specific scientific foundation?
2. Which markets or user segments are most promising for an applied TMR technology?
3. What specific user problems could TMR solve effectively?
4. What core assumptions about consumer neurotechnology should we challenge right now?
5. What different product directions (e.g., software-only integrations, bespoke hardware, clinical vs. consumer) should be explored?
6. What risks (technical, market, or biological) are currently underestimated in this translation phase?
