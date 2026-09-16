# Career Evidence Loop

> An open research project exploring how learners, educators, domain experts, and AI systems might work together to support evidence-informed learning and career discovery over time.

**Status:** Early concept / open research exploration

---

## Why this project exists

Career guidance often asks important questions:

- What am I interested in?
- What am I becoming good at?
- Which careers might fit me?
- What should I learn next?

But these questions are difficult to answer well.

A learner may repeatedly search for fashion, cooking, engineering, medicine, acting, agriculture, aviation, or marine science. That tells us something about curiosity and interest, but it does not necessarily tell us about ability, learning potential, long-term motivation, or career fit.

AI systems can observe some parts of a learner's development:

- questions and conversations;
- learning activity;
- written work;
- digital projects;
- assessment results;
- patterns of improvement.

But many meaningful abilities are best observed through real-world performance and human expertise.

An AI cannot taste food like an experienced chef.

It cannot fully evaluate a live performance like an acting coach, observe field judgment like an experienced farmer, or independently determine whether someone is ready for a safety-critical profession.

This project starts from a simple idea:

> **AI should not decide what a learner should become. It should help learners and the people supporting them gather better evidence about what may be worth exploring next.**

---

## Core hypothesis

Career fit may be more useful when treated as a **hypothesis to test**, rather than a verdict to accept.

Instead of saying:

> "You should become a designer."

a system might say:

> "Design currently appears to be a promising direction. Here is the evidence supporting that hypothesis, what remains uncertain, and what experience could help us test it further."

The proposed loop is:

**Teach  
→ Observe  
→ Gather evidence  
→ Update the learner model  
→ Form career hypotheses  
→ Identify missing evidence  
→ Design the next experiment  
→ Receive human or expert feedback  
→ Update the evidence  
→ Reconsider the hypothesis**

The process is longitudinal. The picture should change as the learner changes.

---

## Guiding principles

### Interest is evidence of curiosity, not proof of aptitude

Repeated interest matters, but it should not automatically become a claim about ability.

### No recommendation should be stronger than the evidence supporting it

The system should distinguish between:

**Observation**

> The learner completed eight analytical tasks independently.

**Inference**

> This may indicate strong analytical reasoning.

**Career hypothesis**

> Analytical career families may be worth exploring further.

These are different levels of claim.

### Absence of evidence is not evidence of absence of potential

If a learner has never had the opportunity to try acting, engineering, cooking, farming, design, or another field, the correct conclusion may simply be:

> **Not yet assessed.**

### Human experts are part of the system

Teachers, mentors, career counselors, coaches, and professionals can contribute evidence that an AI system cannot reliably obtain on its own.

AI can help organize, compare, connect, and revisit that evidence over time.

### The system should look for missing evidence

A useful system should not only ask:

> "What do we know?"

It should also ask:

> "What do we still need to learn?"

and:

> "What experience could help us find out?"

### The learner remains an active decision-maker

The purpose is not to assign people to careers.

The purpose is to help learners understand themselves, explore possibilities, test assumptions, and make better-informed decisions.

---

## A possible evidence loop

```text
Learner activity
      ↓
Observation
      ↓
Evidence
      ↓
Competency hypothesis
      ↓
Career hypothesis
      ↓
Missing evidence
      ↓
Learning or career experiment
      ↓
Human / expert evaluation
      ↓
New evidence
      ↓
Updated learner model
```

## What already exists

This project builds on established work rather than assuming that its individual components are new.

Relevant research areas include:

* Intelligent Tutoring Systems and Adaptive Learning
* Learner Modeling
* Knowledge Tracing and Cognitive Diagnosis
* Evidence-Centered Design
* Psychometrics
* Authentic and Performance Assessment
* Learning Analytics
* Educational Data Mining
* Dynamic Assessment
* Human-in-the-Loop AI
* Vocational Psychology
* Career Development Theory
* Person–Environment Fit
* Career and Job Recommender Systems
* Occupational and Skills Taxonomies
* Meaningful Work and Decent Work

See [`docs/RESEARCH-MAP.md`](docs/RESEARCH-MAP.md) and [`research/REFERENCES.md`](research/REFERENCES.md).

## What may be worth exploring

The possible contribution of this project may not be a single new algorithm.

It may instead lie in how several existing ideas can be combined into a longitudinal, evidence-seeking system for learning and career development.

Some questions that interest this project are:

* How should different kinds of learner evidence be represented?
* How should uncertainty be communicated?
* How can human expert judgment be incorporated without treating every judgment as equally reliable?
* How can a system avoid confusing interest with ability?
* How can it avoid confusing lack of opportunity with lack of potential?
* How can career hypotheses be challenged rather than reinforced automatically?
* What experience should a learner try next when important evidence is missing?
* How can learners remain genuinely in control of decisions about their own lives?
* Can such a system improve real learning and career outcomes over time?

These are open questions, not settled claims.

## Contribution and return

Career development may involve more than finding a job that someone can perform.

A longer-term goal is to explore two directions at once:

### What could the learner contribute?

What problems, communities, organizations, or areas of society could benefit from this person's developing capabilities?

### What could the learner receive in return?

For example:

* income;
* stability;
* autonomy;
* learning;
* meaning;
* social connection;
* recognition;
* flexibility;
* mobility;
* a sustainable way of life.

This suggests a broader relationship:

**Person ↔ Work ↔ Society**

rather than only:

**Person → Job**

## Repository map

* [`docs/PROBLEM-STATEMENT.md`](docs/PROBLEM-STATEMENT.md) — the problem this project is trying to understand
* [`docs/RESEARCH-MAP.md`](docs/RESEARCH-MAP.md) — relevant research traditions and neighboring fields
* [`docs/CONCEPTUAL-ARCHITECTURE.md`](docs/CONCEPTUAL-ARCHITECTURE.md) — the proposed system-level model
* [`docs/EVIDENCE-MODEL.md`](docs/EVIDENCE-MODEL.md) — how evidence might be represented
* [`docs/CAREER-HYPOTHESIS-MODEL.md`](docs/CAREER-HYPOTHESIS-MODEL.md) — how career hypotheses might be formed and revised
* [`docs/HUMAN-IN-THE-LOOP.md`](docs/HUMAN-IN-THE-LOOP.md) — where human judgment belongs
* [`docs/ETHICS-AND-SAFETY.md`](docs/ETHICS-AND-SAFETY.md) — major ethical and safety concerns
* [`docs/OPEN-QUESTIONS.md`](docs/OPEN-QUESTIONS.md) — questions that remain unresolved
* [`research/`](research/) — references and literature notes
* [`examples/`](examples/) — small conceptual examples
* [`schemas/`](schemas/) — future structured representations of evidence and hypotheses

## This project is intentionally incomplete

I am publishing this repository early because I do not want the idea to develop inside a closed box.

I hope it becomes useful to people working in education, learning sciences, career development, psychology, assessment, AI, HCI, software engineering, and professional practice.

I also hope people will challenge it.

If an assumption is weak, please point it out.

If a research field already addresses part of the problem better, please add it.

If the proposed architecture could harm learners, reinforce bias, or misunderstand how education actually works, that criticism is especially valuable.

If you are a teacher, counselor, researcher, engineer, learner, chef, designer, artist, healthcare professional, farmer, pilot, scientist, tradesperson, or practitioner in another field, your perspective may reveal something that this project currently cannot see.

You do not need to agree with the project to contribute to it.

> **Strong counterarguments are contributions too.**

See [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Current phase

**Phase 0 — Problem framing and research mapping**

The immediate priorities are to:

1. sharpen the problem definition;
2. map relevant research and existing systems;
3. develop a defensible evidence model;
4. understand scientific, ethical, and practical limitations;
5. define the smallest meaningful version that could eventually be tested.

There is no current claim that this framework improves educational or career outcomes.

That would need to be demonstrated empirically.

## Guiding idea

> **Don't tell learners who they are. Help them gather enough evidence to discover what they could become.**
