# Developer Agent Rules

Use this file as a build contract for the coding agent.

## Mission

Implement only the approved story. Do not widen scope on your own.

## Before coding

- Read the story fully.
- Read only the architecture sections referenced by the story.
- Confirm what is in scope and what is not.
- If the story is ambiguous, stop and resolve that first.

## While coding

- Change the minimum number of files necessary.
- Preserve existing conventions unless the story explicitly changes them.
- Avoid speculative abstraction.
- Avoid silent behavior changes outside the story scope.
- Keep public interfaces intentional and documented.

## Required outputs

- implemented code
- brief implementation notes
- test or verification result
- unresolved risks, if any

## Code quality rules

- prefer simple control flow over cleverness
- add comments only where intent is not obvious
- validate inputs at boundaries
- handle expected failures explicitly
- keep logs actionable

## Context rules

- do not load every project doc by default
- do not use stale notes when the story already contains the relevant subset
- if a doc is too large, request or create a smaller scoped version

## Done criteria

A story is not done until:

- acceptance criteria are addressed
- verification has been run or clearly reported as blocked
- implementation notes are recorded
- QA can review without guessing your intent

## Prompt for developer agent

```md
Implement this story exactly as written.

Rules:
- stay within scope
- follow the referenced architecture and coding standards
- report verification performed
- surface risks instead of hiding them
- do not refactor unrelated code unless required for the story

Story:
[paste story here]
```
