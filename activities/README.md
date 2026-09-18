# Contributing Learning Activities

A learning activity is a teachable, assessable experience within the course. It may be a lab, case discussion, assignment, simulation, review, or retrospective.

The project accepts contributions through two paths so that a valuable professional experience does not need to arrive as a fully designed assignment.

## Path 1: contribute an activity idea

Use the [Learning activity idea](https://github.com/software-engineering-at-scale/course/issues/new?template=activity-idea.yml) issue form to share a production lesson, failure, misconception, or educational need.

An idea should identify:

- The professional or educational situation
- What students should be able to demonstrate afterward
- A possible student experience or source of evidence, when known
- Whether the contributor wants to remain involved

An idea does not need a complete assignment, rubric, test harness, or instructor guide. Other contributors may help develop it.

## Path 2: submit a complete specification

Copy [TEMPLATE.md](TEMPLATE.md) into a new activity directory and submit it through a pull request. The template is a Learning Activity Specification: a complete, reviewable design that aligns the student experience, learning outcomes, assessment evidence, evaluation, and instructor implementation.

Use a short lowercase name with hyphens:

```text
activities/<activity-name>/activity.md
```

A specification can be proposed before its code, fixtures, or protected instructor material are built. It should be complete enough for reviewers to judge whether the activity is worth developing.

## Shared terminology

- **Purpose** explains why the activity belongs in the course.
- **Learning outcomes** state what students will be able to demonstrate.
- **Authentic professional context** describes the consequential situation represented by the activity.
- **Student experience** defines what students receive, do, and submit.
- **Evidence of learning** is the artifact or observable behavior used to assess an outcome.
- **Assessment rubric** describes the quality of that evidence at defined performance levels.
- **Acceptance criterion** is an explicit condition that can be checked against evidence.
- **Evaluation protocol** explains how deterministic checks, AI-assisted review, and human judgment are combined.

## Activity lifecycle

Every activity has one maturity state:

1. **Proposal** (`activity: proposal`) — The need and intended learning are defined, but the design is still being reviewed.
2. **Ready for Development** (`activity: ready-for-development`) — The specification is accepted and implementation work can begin.
3. **Pilot-Ready** (`activity: pilot-ready`) — Student material, instructor preparation, rubric, and evaluation mechanisms have been exercised and are ready for an initial class.
4. **Piloted** (`activity: piloted`) — The activity has been used with students and has a pilot report.
5. **Validated** (`activity: validated`) — Evidence from one or more pilots supports the activity's intended outcomes, workload, assessment, and usability.

Publishing an activity does not make it validated. A validated activity must include evidence from actual use and document revisions made in response.

## Three review lenses

Activity reviews should deliberately solicit three perspectives:

### Academic review

Does the activity have observable learning outcomes? Are activities, evidence, and assessment aligned? Is the workload realistic, the assessment valid, and the design teachable and inclusive?

### Professional review

Does the scenario resemble consequential software work? Are its constraints, tradeoffs, artifacts, and Definition of Done credible in a mature organization?

### Student review

Are the instructions understandable, the purpose visible, the workload plausible, the tools accessible, and the evaluation transparent? Does the activity create productive difficulty without relying on hidden expectations?

The project maintainer retains merge authority. Review through these lenses is evidence used in the decision, not a transfer of governance.

## Evaluation boundaries

An activity must distinguish among three forms of evaluation.

### Deterministic checks

Software should evaluate conditions such as builds, tests, required artifacts, security scans, performance thresholds, and reproducible environment checks. Passing a check proves only the condition it measures.

### AI-assisted evidence review

An AI may apply explicit criteria to defined artifacts, locate supporting or conflicting evidence, and produce structured feedback. It must cite evidence, allow an indeterminate result, and escalate ambiguity. It must not infer authorship, honesty, effort, intent, or individual contribution, and it does not assign the final grade.

### Human review

A qualified human remains responsible for consequential judgments, including tradeoffs, unusual but valid solutions, individual understanding, oral defense, accommodations, conflicts in evidence, and the final competency or grade decision.

## Public and protected material

This repository is public. Learning Activity Specifications, student briefs, public rubrics, and public evaluation criteria should be open.

Do not commit hidden tests, staged revelations, reference solutions, credentials, or reusable instructor-only assessment material to a student-visible repository. A public specification may describe the purpose and category of protected material without revealing its contents. Protected material should live in an access-controlled instructor repository or a release-gated package. It may be published later when doing so will not compromise future assessment.

## Activity package after acceptance

An implemented activity may expand into:

- `activity.md` — purpose, outcomes, design, and alignment
- `student-brief.md` — exactly what students receive
- `instructor-guide.md` — public-safe preparation, facilitation, and debrief guidance
- `rubric.md` — student-visible assessment criteria
- `evaluation.md` — deterministic checks, AI review protocol, and human-review boundaries
- `pilot-report.md` — evidence and revisions from actual use
- `assets/` — public fixtures, diagrams, starter material, and supporting documents

Executable applications, private instructor assets, test harnesses, and tooling may live in other repositories with their own access controls and licenses.
