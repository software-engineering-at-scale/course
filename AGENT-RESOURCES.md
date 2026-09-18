# Shared agent resources

This repository is the canonical source for the basic AI-agent skills and rules used across the Software Engineering at Scale project.

## Included resources

- `.cursor/skills/evidence-driven-delivery/SKILL.md` defines the shared workflow for turning requirements into a Definition of Done, implementing changes, and reporting evidence.
- `.cursor/rules/project-principles.mdc` contains the project principles that should govern work in every related repository.
- `.cursor/rules/licensing.mdc` preserves the boundary between CC BY 4.0 curriculum and MIT-licensed software repositories.

## Use in related repositories

Related repositories should include a pinned copy of these resources or a documented reference to a specific tagged version of this repository. Avoid depending only on the moving `main` branch. A course release should tag the shared resources so application and scenario repositories can identify the exact guidance they use.

When a downstream repository needs additional guidance, keep the shared principles intact and add narrowly scoped local rules or skills for that repository.
