# Handoff

Last updated: 2026-08-20

## Summary

This repository is a reusable baseline for the AI team operating model.

GitHub Project: `<project-name>` at `<project-url>`

GitHub issue `<setup-issue>` should track adaptation of this operating system inside a real project.

The current operating entrypoint is `ai-team/README.md`. It defines hard gates, obligation tiers, and the read-on-demand routing table.

This repo now includes deterministic process gates: increment report validation, state-file checks, branch-name checks, secret scanning, and maintainability ratcheting.

Install local hooks with `npm run setup`. Run `npm test` for checker tests and `npm run check` for the same process gate used by hooks/CI.

The reusable baseline includes workflows for increment delivery, solution design, maintainability, merge closeout, offline GitHub backfill, documentation, testing, intake/specification, and retrospectives.

## Next Best Actions

1. Review the refreshed branch and open a PR.
2. After merge, copy or fork this operating system into target projects.
3. Create or identify the target GitHub repository and Project.
4. Create a setup issue for adapting the operating system.
5. Define the first product goal and create the first software-build GitHub issue.
6. Use the increment workflow for the first software-build issue.
7. Define the target demonstration environment for the first build increment.

## Resume Instructions

A fresh Lead should read:

- `ai-team/README.md`
- `ai-team/constitution.md`
- `ai-team/model-policy.md`
- `ai-team/github-workflow.md`
- `ai-team/workflows/increment.md`, when doing product work
- `ai-team/workflows/testing.md`, when doing product work
- `ai-team/workflows/intake-and-specification.md`, when creating or refining issues
- `ai-team/workflows/branch-and-pr.md`, when changing code
- `ai-team/workflows/documentation.md`, when behavior, setup, architecture, deployment, user workflow, or operating rules may change
- `ai-team/workflows/retrospective.md`, after each increment
- `ai-team/project-profiles/web-app-local-first.md`, for the first web app
- `project-state/status.md`
- `project-state/handoff.md`

Then ask for or select the active GitHub issue.
