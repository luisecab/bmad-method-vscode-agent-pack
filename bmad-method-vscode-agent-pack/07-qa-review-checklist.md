# QA Review Checklist

Use this after a developer pass.

## Review target

- Story ID:
- Reviewer:

## Story compliance

- Is the implemented work actually the story that was requested?
- Were any out-of-scope changes made?
- Are all acceptance criteria addressed?

## Architecture compliance

- Does the change follow the intended source tree?
- Are public interfaces aligned with the architecture?
- Were coding standards followed?

## Behavioral review

- Main path works
- edge cases covered
- failure handling is reasonable
- no obvious regressions introduced

## Verification review

- What tests were run?
- What was not tested?
- Are manual steps documented if automation was not available?

## Findings

- P1:
- P2:
- P3:

## Decision

- Approved
- Needs changes

## Prompt for QA agent

```md
Review this implementation against the story and architecture.

Priorities:
- bugs
- regressions
- missing tests
- scope drift

Do not focus on style unless it creates risk.

Inputs:
- story
- implementation diff
- relevant architecture sections
```
