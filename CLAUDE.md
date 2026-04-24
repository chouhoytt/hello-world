# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository status

This repository currently contains no source code. The only tracked file (besides this one) is `README.md`, a brief personal intro from the owner (Chou). There is no build system, test suite, linter, package manifest, or CI configuration.

When a future instance is asked to "build", "test", or "run" something here, first verify whether the relevant tooling has been added — do not assume any stack. If the user is starting a new project, ask which language/framework they want before scaffolding.

## Branching convention

Development happens on feature branches named `claude/<slug>` (e.g. `claude/add-claude-documentation-0zuJB`). PRs merge into `main` — see PR #1 (`readme-edits` → `main`) as the existing precedent.
