# Workflow Map

## Purpose

Use this file to keep agent work sequenced and scoped.

## Operating model

### Analyst

Goal:

- refine the idea
- expose unclear assumptions
- produce a usable project brief

Output:

- concise project brief
- open questions
- constraints
- success criteria

### Product manager

Goal:

- turn the brief into a PRD with clear requirements

Output:

- user goals
- functional requirements
- non-functional requirements
- acceptance criteria
- risks and exclusions

### Architect

Goal:

- convert the PRD into an implementation-ready architecture

Output:

- source tree
- technical decisions
- interfaces and data shapes
- coding standards
- test strategy

### Scrum master

Goal:

- draft one self-contained implementation story at a time

Output:

- one story
- exact scope
- exact acceptance criteria
- architecture references needed for that story only

### Developer

Goal:

- implement only the approved story

Output:

- code changes
- local verification
- implementation notes

### QA

Goal:

- review against story and architecture, not just "does it run"

Output:

- findings
- regressions
- missing tests
- approval or rework request

## Hard rules

- Do not skip planning for greenfield work.
- Do not hand a developer agent a giant mixed document set.
- Do not implement multiple stories in one pass unless they are tightly coupled and explicitly approved together.
- Do not mark a story done without a QA pass.

## Context discipline

- Large docs are for humans.
- Small docs are for agents.
- If a document gets large, shard it by section and load only the relevant section in the next step.
