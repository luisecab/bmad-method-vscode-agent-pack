# BMAD Method VS Code Agent Pack

A lightweight Markdown pack for running a BMAD-style workflow with VS Code agents.

This repo is meant to be easy to fork, copy, and customize for a new project.

Important note:

- Forking this repo does not automatically create directories inside your application repo.
- The intended workflow is: fork this repo, then copy the pack into the right location in your real project.

## What this repo contains

- [bmad-method-vscode-agent-pack/README.md](./bmad-method-vscode-agent-pack/README.md)
- workflow map
- project brief template
- PRD template
- architecture template
- story template
- developer agent rules
- QA review checklist
- course-correction playbook

## Fast start

1. Fork this repository.
2. Copy `bmad-method-vscode-agent-pack/` into your project, or keep it as its own planning repo.
3. Start with [USE_THIS_PACK.md](./USE_THIS_PACK.md).
4. Customize the pack for your own workflow using [CUSTOMIZE.md](./CUSTOMIZE.md).

## Recommended destination structure

For a normal application repo, the best default location is:

```text
your-app-repo/
  docs/
    bmad/
```

Copy the contents of `bmad-method-vscode-agent-pack/` into that folder.

Example:

```text
your-app-repo/
  src/
  tests/
  docs/
    bmad/
      workflow-map.md
      project-brief-template.md
      prd-template.md
      architecture-template.md
      story-template.md
      dev-agent-rules.md
      qa-review-checklist.md
      correct-course-playbook.md
```

## Recommended workshop structure

If your repo contains multiple projects or challenges, keep shared BMAD assets at the repo root and project-specific artifacts inside each challenge.

Example:

```text
pclub-bmad-workshop/
  bmad/
    workflow/
    templates/
    rules/
  challenge0_demo/
  challenge1/
    docs/
      bmad/
        brief/
        prd/
        architecture/
        stories/
  challenge2/
  challenge6_capstone_project/
    docs/
      bmad/
        brief/
        prd/
        architecture/
        stories/
```

In that model:

- root `bmad/` is the reusable shared framework
- each `challengeX/docs/bmad/` folder is the source of truth for that project
- stories, architecture, and PRD stay close to the code they belong to

## Best-fit placement rule

Use this rule when deciding where the pack belongs:

- one application repo: put it in `docs/bmad/`
- many projects in one repo: keep shared templates in root `bmad/`, and keep real project docs in each project under `docs/bmad/`

## Best use cases

- greenfield projects
- agent-assisted implementation in VS Code
- teams that want lighter planning artifacts without a full PM toolchain
- solo builders who want better agent context discipline

## Recommended fork strategy

- Keep the pack folder intact at first.
- Replace the generic templates with project-specific versions as your project matures.
- Add your own coding standards, architecture notes, and story backlog.
- Keep stories small and review-driven.

## License

MIT. See [LICENSE](./LICENSE).
