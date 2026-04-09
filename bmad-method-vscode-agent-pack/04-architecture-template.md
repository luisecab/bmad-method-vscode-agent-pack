# Architecture Template

Use this after the PRD is approved.

## Technical summary

- System shape:
- Runtime:
- Main components:
- Why this architecture fits the PRD:

## Source tree

```text
[define the expected project layout here]
```

## Tech stack

- Language:
- Framework:
- Storage:
- API style:
- Tooling:
- Testing:

## Domain model

- Entity:
- Fields:
- Relationships:

## Interfaces and contracts

- Public API:
- Internal boundaries:
- Input validation rules:
- Error handling conventions:

## Data flow

1. Input enters system
2. Validation occurs
3. Core logic runs
4. Persistence or side effects happen
5. Response or output is returned

## Coding standards

- naming rules
- file organization
- documentation rules
- comment rules
- logging rules
- error handling rules

## Testing strategy

- unit test scope
- integration test scope
- end-to-end test scope
- manual verification notes

## Operational notes

- config model
- secrets handling
- local dev setup
- deployment assumptions

## Prompt for architect agent

```md
Create an implementation-ready architecture from the PRD.

Requirements:
- define a concrete source tree
- make interfaces explicit
- include coding standards the developer agent must follow
- keep it practical, not academic
- write only the sections needed for implementation and review

Input PRD:
[paste here]
```
