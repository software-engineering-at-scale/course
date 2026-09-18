---
name: evidence-driven-delivery
description: Plans, implements, reviews, and verifies work against explicit requirements and a Definition of Done. Use when designing course materials, changing project artifacts, implementing features, reviewing work, or deciding whether something is complete.
---

# Evidence-Driven Delivery

## Workflow

1. Ground the work in the repository's current source of truth.
2. State the intended outcome, constraints, and unresolved questions.
3. Convert the outcome into acceptance criteria and a Definition of Done.
4. Identify the evidence that will verify each criterion before implementation.
5. Implement the smallest coherent change that satisfies the agreed scope.
6. Run the planned checks and inspect their results.
7. Report what is verified, what is implemented but unverified, and what remains unresolved.
8. Update the relevant requirements, decisions, and documentation when the work changes them.

## Requirements and ambiguity

- Treat requirements definition as engineering work.
- Ask about consequential ambiguity rather than silently choosing an interpretation.
- Continue independent work that does not depend on the unanswered question.
- Do not reduce scope or redefine success to match the implementation.

## Definition of Done

A useful Definition of Done names observable outcomes and their evidence. Include relevant functional behavior, tests, security, performance, operability, documentation, and handoff expectations.

Do not count the existence of a test, document, log, or checklist as proof that it is useful. Verify that it detects, explains, or prevents the failure it is meant to address.

## Completion report

For each important criterion, report one of:

- **Verified:** Evidence demonstrates the criterion.
- **Implemented, not verified:** The change exists but the required evidence is missing or inconclusive.
- **Unresolved:** A decision, dependency, or failure prevents completion.

Never describe the whole task as complete while a required criterion is only implemented or unresolved.
