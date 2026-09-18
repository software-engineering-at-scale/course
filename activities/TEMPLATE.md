# Learning Activity: [Title]

## Metadata

- **Status:** Proposal
- **Format:** Lab | Case Discussion | Assignment | Simulation | Review/Retrospective
- **Course phase:** [Where this belongs in the semester]
- **Estimated student time:** [In-class and outside-class time]
- **Participation:** Individual | Pair | Team
- **Recommended team size:** [If applicable]
- **Prerequisites:** [Knowledge, skills, or earlier activities]
- **Contributor:** [Name or GitHub handle]
- **Version:** [Version and date]

## 1. Purpose

### Why this activity exists

[Explain the educational and professional reason for including this activity. What experience does it provide that students are unlikely to gain from a conventional programming assignment? What failure, misconception, or responsibility is it intended to expose?]

### Student learning outcomes

By the end of this activity, students will be able to:

- [Use an observable action such as diagnose, design, implement, evaluate, defend, prioritize, verify, communicate, or revise.]
- [Add additional outcomes only when the activity produces evidence for them.]

Avoid outcomes such as "understand," "learn about," or "be familiar with" unless they are followed by an observable demonstration.

### Course alignment

- **Course outcome:** [Identify the course-level outcome.]
  - **Contribution:** [Explain what new practice or evidence this activity adds.]

## 2. Authentic Professional Context

[Describe the professional situation represented by the activity.]

Include:

- The kind of organization or software system involved
- Relevant users and stakeholders
- The system's history and current condition
- Business, technical, regulatory, and operational constraints
- Why a reasonable engineer might make the wrong decision
- Consequences of an incomplete or superficially correct solution

The scenario must not expose confidential, proprietary, student-identifying, or unlicensed material.

## 3. Student Experience

### Student-facing brief

[Write or outline the instructions exactly as students will receive them. Explain the situation, requested outcome, known constraints, available materials, expected deliverables, timebox, and process for clarifying requirements.]

### What students receive

- [Source repository and starting revision]
- [Product or change request]
- [Architecture or system documentation]
- [Existing tests, logs, metrics, or incident reports]
- [Stakeholder, compliance, or security requirements]
- [Development environment and AI access]

### Information-release plan

For each item intentionally withheld or released later, document:

- **Information category:** [Do not reveal protected contents in this public file.]
- **Why it is withheld:** [Reason]
- **Release condition:** [Time, event, or student action]
- **Intended learning:** [What behavior or decision it is designed to reveal]

### Tasks and sequence

1. [Investigation or requirements clarification]
2. [Planning and decision-making]
3. [Implementation, analysis, or operation]
4. [Verification and review]
5. [Demonstration, defense, or retrospective]

Identify checkpoints where students receive feedback or encounter new information.

### AI use and student accountability

- **Required AI use:** [What students use AI to investigate, create, analyze, or verify]
- **Reason AI is necessary:** [Why the scope or pace makes appropriate AI use necessary]
- **Permitted context:** [What information students may provide to AI systems]
- **Prohibited context:** [Sensitive or restricted information]
- **Required evidence:** [Prompts, decisions, verification records, or other provenance]
- **Independent verification:** [What AI output students must check]
- **Student responsibility:** [Decisions for which students remain accountable]

Evaluate students' direction and verification of AI, not the volume of AI-generated output.

### Deliverables and evidence of learning

For each deliverable, state the related learning outcome.

- **Deliverable:** [Working code, tests, acceptance criteria, design decision, threat model, performance evidence, deployment plan, operational dashboard, incident analysis, AI-use record, demonstration, oral defense, or retrospective]
  - **Related outcome:** [Outcome]
  - **Evidence provided:** [What an evaluator can observe]

## 4. Instructor Implementation

### Preparation

- [Repositories, branches, environments, and accounts]
- [Seed data and public test fixtures]
- [Defects, vulnerabilities, or system states to introduce]
- [Protected or delayed information required]
- [Software and AI access]
- [Expected setup time and operating cost]

### Facilitation plan

[Explain how the activity is introduced, which questions instructors may answer, what ambiguity should remain, when checkpoints occur, when new information is released, how blocked teams are handled, and how the activity concludes.]

### Expected approaches and misconceptions

- **Reasonable approaches:** [Approaches]
- **Common shortcuts:** [Shortcuts]
- **Likely AI-generated mistakes:** [Mistakes]
- **Misleading signals:** [Signals]
- **Failure modes:** [Failures the activity is designed to expose]
- **False success:** [How students might satisfy artifact requirements without demonstrating the outcome]

### Debrief

[Explain how the instructor connects student decisions, system outcomes, professional practice, the team's Definition of Done, and changes students should make in future work.]

## 5. Assessment Design

### Evidence-to-outcome alignment

For each learning outcome, document:

- **Learning outcome:** [Outcome]
- **Practice opportunity:** [Task or activity]
- **Evidence:** [Artifact or observable behavior]
- **Rubric criterion:** [Criterion]
- **Evaluator:** Deterministic | AI-Assisted | Human | Hybrid

Every outcome must have corresponding evidence. Every required deliverable should support at least one outcome.

### Assessment rubric

Repeat this section for each criterion.

#### Criterion: [Name]

- **Related outcome:** [Outcome]
- **Evidence examined:** [Evidence]
- **Weight or importance:** [Weight or explanation]
- **Evaluator:** Automated | AI-Assisted | Human | Hybrid

**Exceeds expectations:** [Evidence of unusually strong judgment, execution, verification, or transfer.]

**Meets expectations:** [Minimum complete and professionally credible evidence.]

**Partially meets expectations:** [Incomplete, inconsistent, or weak evidence.]

**Not demonstrated:** [Missing evidence or work that does not demonstrate the outcome.]

Rubric descriptions must refer to observable evidence rather than personality, confidence, effort, or writing style unrelated to the outcome.

### Formative feedback and revision

- **Feedback before final evaluation:** [Feedback]
- **Revisable deliverables:** [Deliverables]
- **Expected use of feedback:** [Expectation]
- **Assessment role:** Formative | Summative | Both

### Individual accountability

[For team activities, explain how individual learning is evaluated. Possible evidence includes decision records, rotating ownership, individual reflection, demonstration, oral defense, or response to a changed requirement. Do not use commit counts as a productivity or learning score.]

## 6. Verification and Evaluation Protocol

### Deterministic checks

Repeat this block for each condition that software should evaluate.

#### AC-01: [Short name]

- **Condition:** [Explicit condition]
- **Evidence source:** [Artifact or system]
- **Verification mechanism:** [Test, command, scan, or measurement]
- **Expected result:** [Pass condition]
- **Failure result:** [Failure condition]
- **Related learning outcome:** [Outcome]

Examples include clean builds, required tests, regression tests, security scans, performance thresholds, and rollback checks. Passing a check proves only the condition it evaluates.

### AI-assisted evidence review

- **Artifacts provided to the evaluator:** [Exact artifacts]
- **Rubric and criteria:** [References]
- **Reference material:** [Allowed references]
- **Excluded information:** [Information the evaluator must not access]
- **Escalation conditions:** [Conditions requiring human review]

For every criterion, require this output:

- **Criterion ID**
- **Result:** Satisfied | Not Satisfied | Indeterminate
- **Evidence:** Exact file, section, line, test result, or observable artifact
- **Reasoning:** Brief connection between the evidence and criterion
- **Confidence:** High | Medium | Low
- **Human review required:** Yes | No

The AI evaluator must cite evidence, mark ambiguous or missing evidence as indeterminate, and distinguish a missing artifact from an incorrect artifact. It must not infer authorship, intent, effort, honesty, or individual contribution, and it must not assign the final grade.

### Human review

Identify what requires qualified human judgment, including:

- Appropriateness of tradeoffs
- Unusual but valid solutions
- Student explanation and defense
- Individual learning
- Conflicting or ambiguous evidence
- Accommodations and contextual factors
- Final competency or grade decisions

### Calibration cases

Provide or plan examples of:

- A clearly satisfactory submission
- A clearly unsatisfactory submission
- A polished submission with weak evidence
- A technically unusual but valid solution
- A case that should produce an `Indeterminate` AI result

## 7. Accessibility, Safety, and Responsible Use

Address:

- Accessibility of tools and materials
- Alternative ways to demonstrate an outcome when appropriate
- Hardware, software, account, and financial requirements
- Student privacy and sensitive data
- Security boundaries and external services
- Licensing and attribution
- Psychological safety during incidents, failures, peer review, and retrospectives

Identify barriers that could measure access to resources rather than the intended learning outcome.

## 8. Pilot and Validation Plan

- **Intended student population:** [Population]
- **Recommended class size:** [Size]
- **Observations or data to collect:** [Evidence]
- **Expected completion time:** [Time]
- **Signals the activity is too easy, difficult, or unclear:** [Signals]
- **Questions for students:** [Questions]
- **Questions for instructors:** [Questions]
- **Revision or retirement criteria:** [Criteria]

After a pilot, record what happened, what students demonstrated, where instructions or evaluation failed, differences among automated, AI-assisted, and human judgments, and changes made for the next version.

## 9. Definition of Done

An activity is ready for an initial pilot when:

- [ ] Learning outcomes are observable and aligned with course outcomes.
- [ ] Students have a complete and understandable brief.
- [ ] Instructor setup and facilitation requirements are documented.
- [ ] Required materials and environments can be reproduced.
- [ ] AI-use expectations and student responsibilities are explicit.
- [ ] Deliverables provide evidence for every learning outcome.
- [ ] The rubric describes observable performance at each level.
- [ ] Deterministic checks have been tested.
- [ ] AI-assisted evaluation requires cited evidence and permits an indeterminate result.
- [ ] Human judgment and escalation points are identified.
- [ ] Accessibility, privacy, security, cost, and licensing have been considered.
- [ ] The activity includes a debrief and revision plan.

Do not describe an activity as validated until it has been piloted and revised using evidence from students and instructors.

