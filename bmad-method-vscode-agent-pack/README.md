# BMAD Method VS Code Agent Pack

This folder turns the extracted BMAD transcript into a practical Markdown pack for building with VS Code agents.

The intent is simple:

- keep planning explicit
- keep agent context small
- move one story at a time
- require review before drifting into the next task

## Files

- `01-workflow-map.md` - end-to-end flow for analyst, PM, architect, scrum master, developer, and QA
- `02-project-brief-template.md` - starting brief for a new product idea
- `03-prd-template.md` - product requirements document template
- `04-architecture-template.md` - architecture template with sections agents can use directly
- `05-story-template.md` - implementation story template for developer handoff
- `06-dev-agent-rules.md` - build rules for the coding agent
- `07-qa-review-checklist.md` - QA pass checklist
- `08-correct-course-playbook.md` - how to recover when scope or assumptions change mid-project

## Recommended use

1. Start with `02-project-brief-template.md`.
2. Turn that into `03-prd-template.md`.
3. Produce `04-architecture-template.md`.
4. Draft one story at a time from `05-story-template.md`.
5. Have the coding agent follow `06-dev-agent-rules.md`.
6. Run `07-qa-review-checklist.md` before marking work complete.

## Source

Derived from the extracted transcript in `transcript.txt`, especially the parts covering:

- brainstorming and analyst work
- PRD and architecture creation
- sharding large docs into smaller context units
- scrum-master story drafting
- developer implementation
- QA review and course correction
