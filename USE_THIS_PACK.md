# Use This Pack

This file shows the simplest way to use the pack after forking this repo.

## Option 1: Keep it as a planning repo

Use this repository only for planning and agent workflow docs.

Good when:

- you want reusable planning artifacts
- you do not want these files mixed into your application repo yet
- you are testing different agent workflows

## Option 2: Copy the pack into your app repo

Copy the folder below into your actual application repository:

```text
bmad-method-vscode-agent-pack/
```

Good when:

- you want your planning docs near your code
- you want agents to read these files directly during implementation

## Suggested order

1. `02-project-brief-template.md`
2. `03-prd-template.md`
3. `04-architecture-template.md`
4. `05-story-template.md`
5. `06-dev-agent-rules.md`
6. `07-qa-review-checklist.md`

## Recommended workflow

### Step 1: write the brief

Describe:

- what you are building
- who it serves
- what success looks like
- what constraints exist

### Step 2: create the PRD

Turn the brief into:

- goals
- non-goals
- journeys
- functional requirements
- acceptance criteria

### Step 3: define architecture

Write:

- source tree
- interfaces
- data model
- coding standards
- testing strategy

### Step 4: draft one story

Do not create a huge implementation plan first. Draft one small story, build it, review it, then draft the next one.

### Step 5: build with the dev rules

Use `06-dev-agent-rules.md` as the execution contract for the coding agent.

### Step 6: review before continuing

Use `07-qa-review-checklist.md` before marking the story complete.

## Important habit

Large docs are useful for humans. Smaller focused docs are better for agents. If your PRD or architecture gets large, shard it into smaller sections and only load what the current story needs.
