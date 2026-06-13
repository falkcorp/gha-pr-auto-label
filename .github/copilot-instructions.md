<!-- file: .github/copilot-instructions.md -->
<!-- version: 2.4.0 -->
<!-- guid: 4d5e6f7a-8b9c-0d1e-2f3a-4b5c6d7e8f9a -->
<!-- last-edited: 2026-06-13 -->

# gha-pr-auto-label — Additional Context

Org-wide coding standards (file headers, language rules, commit format) are at
**<https://github.com/falkcorp/.github>** and apply automatically to this repo.

For full project context: **CLAUDE.md** at the repo root.

## Project overview

GHA composite action: auto-label pull requests. Language: Python/YAML.

## Critical constraints

- This is a composite GitHub Action — the entry point is `action.yml`
- Python scripts live in the repo root alongside the action definition
- Pin all GitHub Action references to SHAs, not tags (supply chain security)
