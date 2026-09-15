# Conceptual Architecture

This document describes an initial conceptual architecture for Career Evidence Loop.

It is a research hypothesis, not a finalized technical specification.

## Core loop

```text
Teach / expose
      ↓
Observe
      ↓
Record evidence
      ↓
Update learner model
      ↓
Form or revise career hypotheses
      ↓
Identify missing evidence
      ↓
Design next experiment
      ↓
Human / expert evaluation
      ↓
New evidence
      ↓
Repeat
```

## Proposed layers

### 1. Learning layer

Supports:

* teaching;
* practice;
* projects;
* feedback;
* adaptive challenge;
* learning progression.

### 2. Observation layer

Captures potentially relevant events such as:

* task performance;
* learner questions;
* voluntary exploration;
* persistence;
* revision behavior;
* response to feedback.

Observations should not automatically become conclusions.

### 3. Evidence layer

Stores evidence with provenance.

Possible fields include:

* source;
* date;
* context;
* artifact;
* evaluator;
* rubric;
* confidence;
* limitations.

### 4. Learner model

Represents developing hypotheses about:

* knowledge;
* skills;
* interests;
* motivation;
* learning velocity;
* preferences;
* behavior;
* uncertainty;
* evidence gaps.

The learner model should remain revisable.

### 5. Career reasoning layer

Connects learner evidence with possible career families or work environments.

Outputs should be hypotheses rather than assignments.

### 6. Evidence-gap layer

Asks:

* What important evidence is missing?
* Which conclusions currently rely on weak evidence?
* Which alternative explanations remain plausible?
* Which unexplored paths deserve attention?

### 7. Experiment layer

Proposes experiences that could generate informative evidence.

Examples:

* a design brief;
* a supervised kitchen task;
* a coding project;
* an acting exercise;
* a field observation;
* a simulated client interaction;
* a professional shadowing experience.

### 8. Human expert layer

Allows relevant humans to contribute structured or qualitative judgments.

Possible contributors include:

* teachers;
* mentors;
* career counselors;
* coaches;
* professional practitioners;
* supervisors.

### 9. Occupational knowledge layer

Represents information about:

* occupations;
* skills;
* knowledge;
* work activities;
* work environments;
* training requirements;
* career pathways.

### 10. Human decision layer

The learner remains central.

AI-generated hypotheses should support reflection and exploration, not replace personal or professional judgment.

## Architecture principle

AI manages hypotheses; people live the consequences.

The architecture should therefore make uncertainty visible and preserve meaningful human oversight.
