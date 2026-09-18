# Software Engineering at Scale

## Building, Operating, and Evolving AI-Assisted Systems

**Draft syllabus v0.1**  
**Senior capstone course**  
**Recommended credit:** 4 units

## Catalog description

Modern software engineers rarely build isolated systems from a blank page. They inherit large codebases, ambiguous requirements, changing dependencies, operational constraints, and responsibility for software that other people already rely on. They increasingly use AI agents to investigate, modify, test, and document those systems.

In this project-based course, students inherit a substantial open-source application and operate it through a semester of changing requirements and deliberately introduced production challenges. Use of AI development tools is required. The scope and pace of the work are intentionally designed to exceed what a student team could complete through manual implementation alone.

Students work in teams through two-week development cycles. For each change, they must clarify requirements, identify stakeholders and constraints, define acceptance criteria, and update a shared Definition of Done before directing AI agents to implement the work. Students remain responsible for every generated change and must provide evidence that the resulting system satisfies its agreed expectations.

Some defects, tests, constraints, and stakeholder expectations are intentionally withheld. Students must use investigation, experimentation, and clarification to discover what is missing. An AI-generated implementation that appears functional but violates the accepted requirements is incomplete.

Students are evaluated on the quality of their requirements, decisions, tests, evidence, reviews, documentation, and operational outcomes. The volume of code produced is not itself a measure of success.

## Learning objectives

By the end of the course, students should be able to:

1. Investigate and explain an unfamiliar software system with assistance from AI.
2. Convert incomplete or conflicting requests into explicit, testable requirements.
3. Establish and maintain a shared Definition of Done.
4. Direct AI agents to perform bounded engineering work while retaining human responsibility for the result.
5. Design evidence that verifies functional behavior and important quality attributes.
6. Build and use unit, integration, end-to-end, performance, and security tests appropriately.
7. Establish CI/CD controls that prevent known failures from silently reappearing.
8. Manage dependencies and software supply-chain risks over time.
9. Instrument and operate a system so that failures can be detected, diagnosed, and corrected.
10. Respond to incidents, revise team practices, and communicate consequential decisions.
11. Demonstrate selected controls associated with mature or regulated software organizations.
12. Transfer an operating system to another team without relying on undocumented personal knowledge.

## Course model

### One inherited system

Students begin with a substantial existing application rather than a blank repository. The system should be large enough that no student can hold it entirely in memory and mature enough to contain realistic design tradeoffs, dependencies, operational behavior, and technical debt.

### AI is required

Students are expected to use AI throughout the software development lifecycle, including investigation, requirements analysis, implementation, code review, test development, documentation, security analysis, and incident diagnosis.

Students must understand and defend the consequential decisions embodied in their work. AI assistance does not transfer responsibility to the tool.

### Two-week development cycles

Teams work in two-week iterations. Each cycle includes:

1. A change request, failure, or new constraint
2. Requirements clarification and stakeholder questions
3. Updated acceptance criteria and Definition of Done
4. AI-assisted investigation and implementation
5. Automated and human verification
6. Release or a justified decision not to release
7. Demonstration, retrospective, and process revision

The Definition of Done is not a static checklist supplied by the instructor. Each team develops it and revises it as failures expose missing controls or unproductive practices.

## Proposed scenario sequence

### 1. Inherit the system

Map the architecture, establish a development environment, identify unknowns, and create the team’s initial Definition of Done.

### 2. Define the change

Receive an incomplete or contradictory feature request. Identify stakeholders, clarify intent, document constraints, and create testable acceptance criteria before implementation.

### 3. Stop the regression

Modify existing behavior while instructor-controlled tests expose assumptions the team failed to preserve. Add meaningful automated protection against recurrence.

### 4. Secure the supply chain

Respond to a vulnerable or incompatible dependency. Evaluate impact, remediate safely, document the decision, and improve the team’s dependency-management process.

### 5. Operate under load

Diagnose a performance or reliability problem that does not appear in a developer’s local environment. Add measurements and tests that demonstrate improvement.

### 6. Respond to an incident

Detect, triage, contain, and correct a production-style failure. Conduct a blameless retrospective and revise the Definition of Done based on the evidence.

### 7. Demonstrate trust

Produce evidence for selected security, availability, change-management, and operational controls associated with frameworks such as SOC 2 or ISO 27001.

### 8. Hand off the system

Transfer responsibility to another team. The receiving team evaluates whether the tests, documentation, observability, release process, and decision history are sufficient to operate and change the system safely.

## Assessment model

- Requirements, acceptance criteria, and Definition of Done: **20%**
- Verification strategy and quality of evidence: **25%**
- Reliability, security, performance, and operability: **20%**
- Responsible and effective use of AI: **15%**
- Team process, retrospectives, and improvement: **10%**
- Documentation, communication, and final handoff: **10%**

## Evidence of learning

Students must provide more than a working demonstration. Course evidence may include:

- Requirement and acceptance records
- Decision records and unresolved questions
- Test suites and explanations of what they do and do not prove
- CI/CD results and release evidence
- Security, dependency, and performance findings
- Incident timelines and retrospective changes
- AI-use records for consequential work
- Documentation evaluated by the receiving team
- A final defense of why the system should or should not be released

## Prerequisites

Students should have completed foundational coursework in programming, data structures, and software systems, plus at least one substantial individual or team programming project. The course assumes that students can write and read code. It focuses on the practices required to evolve and operate software responsibly with AI assistance.

## Open design questions

- Which existing open-source application is the best starting system?
- How should instructor-only tests and scenario material be distributed while keeping the core project open?
- Which controls from SOC 2 and ISO 27001 are appropriate for an undergraduate simulation?
- How should the course assess individual understanding within team and AI-assisted work?
- Which capabilities should be demonstrated both with and without AI?
- What evidence would show that judgment transfers to an unfamiliar system?
