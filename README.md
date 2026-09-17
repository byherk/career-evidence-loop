# Career Evidence Loop

> How can we test career possibilities without turning incomplete evidence into labels about who someone is?

**Status:** Early concept / open research exploration

A learner shows sustained interest in design, performs well on several related tasks, and receives positive feedback from a teacher.

What does that actually tell us?

It may tell us something about interest, current performance, or developing capability. But it does not automatically establish aptitude, long-term motivation, learning potential, or career fit.

Career Evidence Loop is an open research project exploring how learners, educators, career counselors, domain experts, and AI systems might gather and revise evidence about learning and possible career directions over time.

The central idea is simple:

> **Career fit may be more useful as a hypothesis to test than a verdict to accept.**

The goal is not to tell people what they should become.

It is to help them gather better evidence about what may be worth exploring next.

---

## The problem

Career guidance often tries to answer questions such as:

- What am I interested in?
- What am I becoming good at?
- Which careers might fit me?
- What should I learn or try next?

These questions are difficult because the evidence is incomplete.

Interest does not necessarily imply ability.

Good performance on one task does not establish long-term career fit.

A lack of evidence may simply mean someone has not yet had the opportunity to try something.

AI systems may observe learning activity, written work, digital projects, assessment results, or patterns of improvement. But many meaningful abilities are better observed through real-world performance and human expertise.

Human judgment matters too, but it should not automatically become ground truth.

The challenge is therefore not only to gather more evidence.

It is to decide what different kinds of evidence actually support, what remains uncertain, and what experience could help us learn more.

---

## A possible evidence loop

One possible process is:

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
      ↓
Reconsider the hypothesis
````

The picture should change as the learner changes.

A career hypothesis should be revisable when new evidence appears.

---

## Evidence should not become a label

A useful system needs to preserve different levels of claim.

For example:

**Observation**

> The learner completed eight analytical tasks independently.

**Interpretation**

> This may indicate developing analytical reasoning.

**Career hypothesis**

> Analytical career families may be worth exploring further.

These are not the same claim.

A system should not silently turn one into another.

Similarly:

> **Not yet assessed**

is not the same as:

> **Not suitable**

Absence of evidence should not be treated as evidence of absence of potential.

---

## Where human judgment fits

Teachers, mentors, career counselors, coaches, and practitioners may observe things an AI system cannot reliably evaluate on its own.

An experienced chef can judge aspects of cooking performance that are not captured by a conversation log.

An acting coach can observe live performance.

A practitioner can recognize context-specific judgment that may be invisible in a digital assessment.

Human expertise should therefore be part of the evidence loop.

But expert judgment can also be incomplete, inconsistent, context-dependent, or wrong.

One open problem is how to use human judgment without either dismissing it or treating it as unquestionable.

---

## Questions this project is exploring

Some of the questions that currently matter most are:

* What should count as useful evidence of developing capability?
* How should conflicting evidence change a career hypothesis?
* How should uncertainty be represented and communicated?
* How can human expert judgment be incorporated without treating it as automatic ground truth?
* How can lack of opportunity be distinguished from lack of potential?
* What experience should someone try next when important evidence is missing?
* How can career hypotheses be challenged rather than reinforced automatically?
* How can learners remain genuinely in control of decisions about their own lives?
* What would need to be tested before a system like this could make any claim about real educational or career outcomes?

These are open research questions, not settled conclusions.

---

## Where contributions would help now

Career Evidence Loop is currently in:

**Phase 0 — Problem framing and research mapping**

The most useful contributions right now are those that help make the underlying questions more accurate and defensible.

You may be able to help by:

* pointing to research, frameworks, or existing systems that already address part of the problem;
* challenging an assumption with a counterexample;
* identifying a failure mode, ethical risk, or missing perspective;
* suggesting a better way to represent or evaluate evidence;
* bringing practitioner experience from education, assessment, career development, psychology, AI, HCI, or another relevant domain;
* identifying places where the project confuses different concepts;
* proposing a small experiment that could test an assumption;
* correcting an inaccurate or overstated claim.

You do not need to agree with the current framework to contribute.

A well-supported disagreement can be more useful than agreement.

---

## How to participate

If you have a question, critique, example, research reference, or alternative model, you can start with a GitHub Discussion:

[https://github.com/byherk/career-evidence-loop/discussions](https://github.com/byherk/career-evidence-loop/discussions)

For a specific problem, proposal, or bounded piece of work, open an issue:

[https://github.com/byherk/career-evidence-loop/issues](https://github.com/byherk/career-evidence-loop/issues)

For concrete changes, open a pull request.

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for contribution guidance.

---

## Research foundations

Career Evidence Loop builds on existing work rather than assuming that its individual components are new.

Relevant areas include:

* learner modeling;
* knowledge tracing and cognitive diagnosis;
* evidence-centered design;
* psychometrics;
* authentic and performance assessment;
* learning analytics;
* human-in-the-loop AI;
* vocational psychology;
* career development theory;
* person–environment fit;
* career and job recommender systems;
* occupational and skills taxonomies.

See:

* [`docs/RESEARCH-MAP.md`](docs/RESEARCH-MAP.md)
* [`research/REFERENCES.md`](research/REFERENCES.md)

The possible contribution of Career Evidence Loop may not be a new algorithm.

It may instead lie in how existing ideas could be connected into a longitudinal, evidence-seeking process for learning and career exploration.

Whether that combination is genuinely useful remains an empirical question.

---

## Repository map

* [`docs/PROBLEM-STATEMENT.md`](docs/PROBLEM-STATEMENT.md) — the problem the project is trying to understand
* [`docs/RESEARCH-MAP.md`](docs/RESEARCH-MAP.md) — research traditions and neighboring fields
* [`docs/CONCEPTUAL-ARCHITECTURE.md`](docs/CONCEPTUAL-ARCHITECTURE.md) — proposed system-level model
* [`docs/EVIDENCE-MODEL.md`](docs/EVIDENCE-MODEL.md) — how evidence might be represented
* [`docs/CAREER-HYPOTHESIS-MODEL.md`](docs/CAREER-HYPOTHESIS-MODEL.md) — how career hypotheses might be formed and revised
* [`docs/HUMAN-IN-THE-LOOP.md`](docs/HUMAN-IN-THE-LOOP.md) — where human judgment may belong
* [`docs/ETHICS-AND-SAFETY.md`](docs/ETHICS-AND-SAFETY.md) — major ethical and safety concerns
* [`docs/OPEN-QUESTIONS.md`](docs/OPEN-QUESTIONS.md) — unresolved questions
* [`research/`](research/) — references and literature notes
* [`examples/`](examples/) — conceptual examples
* [`schemas/`](schemas/) — future structured representations of evidence and hypotheses

---

## Research status

This project is intentionally early.

There is currently no claim that Career Evidence Loop improves educational or career outcomes.

There is also no claim that the individual ideas behind the project are novel.

Both the scientific value of the framework and the usefulness of combining these ideas would need to be demonstrated through research and empirical testing.

For now, the goal is more modest:

**make the questions better, make the assumptions easier to challenge, and identify what evidence would be needed to test them.**

## Guiding idea

> **Don't tell learners who they are. Help them gather enough evidence to discover what they could become.**
