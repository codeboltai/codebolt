# Codebolt Open Source

This repo is a public showcase shell for CodeBolt demo projects, reusable packages, and selected agents.

## Proposed layout

- `apps/` for runnable apps and UI surfaces
- `agents/` for agent packages and agent examples
- `packages/` for shared libraries and utilities
- `providers/` for provider/integration packages
- `plugins/` for optional extensions and plugins
- `examples/` for demo projects and showcases
- `templates/` for starters and scaffolds
- `docs/` for public documentation
- `tooling/` for repo-level scripts and helpers
- `legacy/` for deprecated or archived material that should stay visible but not treated as active product code

The repo is set up as a pnpm workspace with Turbo task orchestration.
