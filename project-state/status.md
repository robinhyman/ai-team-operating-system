# Project Status

Last updated: 2026-08-20

## Current State

This repository contains reusable AI team operating artifacts. No application code is included.

The current OS is refreshed from the project-local `ai-team/` implementation in `key-results-generator`.

Hard gates, obligation tiers, and startup routing are defined in `ai-team/README.md`.

The repository includes Node-based process checks, local git hooks, a PR template, and CI workflow wiring.

Process check coverage includes increment report sections, secret scanning, state-file coherence and budgets, branch naming, and maintainability ratcheting.

GitHub repository: `robinhyman/ai-team-operating-system`

GitHub Project: `<project-name>` at `<project-url>`

Active GitHub issue: none linked for this refresh branch.

## Active Goal

Provide a reusable AI software delivery team operating system that can be copied into project repositories and validated mechanically.

## Current Runtime Assumption

- A Lead agent coordinates bounded worker tasks.
- GitHub issues inside the target GitHub Project provide work tracking and observability.
- Repo state files provide compact continuation memory.
- Product work should be delivered in increments, each tied to one primary GitHub issue.
- Any `Done` notification for product work must include a checked app/demo link the user can open.
- Each increment must define and report its verification plan.
- New actionable tickets should use `ai-team/templates/issue-spec.md` and meet Ready Criteria before `Agent Status: Ready`.
- Each completed, blocked, or paused increment must have a retrospective before the next increment starts.
- Retrospective improvement proposals require user approval before operating files are changed.
- Documentation impact must be assessed for every increment, and required docs are part of `Done`.

## Open Questions

- What project is this operating system being applied to?
- What GitHub repository and Project should be used?
- What is the first software product goal for the team to build?
