# Customize This Pack

This repo is intentionally generic. A fork becomes useful only after you adapt it to your own project.

## First changes to make

### Rename things that are too generic

Examples:

- rename the pack folder
- rename story IDs to match your backlog style
- rewrite examples to match your stack

### Make the architecture template real

Replace placeholders with:

- your actual source tree
- your actual runtime
- your actual interfaces
- your actual testing approach

### Tighten the developer rules

Add project-specific rules such as:

- API versioning rules
- error formatting rules
- log format rules
- migration rules
- review gates

### Make the QA checklist concrete

Add checks for:

- your critical flows
- regression-prone modules
- test commands
- deployment-sensitive behavior

## What to remove

If a file does not match your workflow, delete it. A smaller accurate pack is better than a larger generic one.

## What to add

Common additions after forking:

- `09-coding-standards.md`
- `10-source-tree.md`
- `11-backlog.md`
- `12-release-checklist.md`
- `13-agent-prompts.md`

## Fork-friendly advice

- keep `README.md` short and practical
- keep the file order obvious
- avoid burying the main workflow in long narrative docs
- prefer templates that are easy to overwrite
