# AI Team Operating System

Reusable operating artifacts for an AI software delivery team.

Core principle:

> The chat is temporary. The repository is memory. GitHub tracks work.

Start with `ai-team/README.md`. It defines the hard gates, routing table, and default delivery loop. For a new project, copy or adapt:

- `ai-team/`
- `project-state/`
- `.githooks/`
- `.github/workflows/process.yml`
- `package.json` scripts that run the process checks

Then update:

- `project-state/index.md`
- `project-state/status.md`
- `project-state/handoff.md`
- GitHub repository and Project references
- the active project profile

## Local Setup

Requires Node.js 20 or newer.

```bash
npm run setup
npm test
npm run check
```

`npm run setup` installs the repository hooks. The hooks are intentionally bypassable with `--no-verify`; the `Process` GitHub Actions workflow is the binding backstop once configured as a required status check.
