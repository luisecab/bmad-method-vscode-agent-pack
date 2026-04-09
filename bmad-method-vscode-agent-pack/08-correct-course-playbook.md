# Correct Course Playbook

Use this when the team discovers that the current plan is wrong, incomplete, or obsolete.

## Trigger conditions

- architecture no longer matches the product need
- a story exposes a missing requirement
- a dependency changed
- a major assumption was false
- the current story sequence no longer makes sense

## Recovery steps

1. Stop piling new code onto a broken assumption.
2. State exactly what changed.
3. Identify which docs are now stale:
   - brief
   - PRD
   - architecture
   - current story
   - future stories
4. Update the highest-level stale artifact first.
5. Redraft only the affected downstream artifacts.
6. Resume with a fresh story.

## Questions to answer

- What new fact changed the plan?
- Which acceptance criteria are affected?
- Which interfaces or data contracts are affected?
- Which existing work is still valid?
- What should be postponed or removed?

## Prompt for course-correction agent

```md
Perform a course correction for this project.

Tasks:
- identify what changed
- identify which artifacts are now stale
- propose the smallest safe set of updates
- rewrite only the affected planning documents
- produce the next correct story to resume execution

Inputs:
- current brief or PRD
- current architecture
- current story
- new facts or constraints
```
