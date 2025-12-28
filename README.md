# Agents, Skills, and Patterns (Vendor-Neutral Template)

This repo keeps AI agents, skills, and Fabric patterns portable across vendors (Claude, Codex, others) to avoid lock-in. Everything stays in plain Markdown so you can clone it and adapt with whatever tooling you prefer.

## What's inside
- 122 agents: role-specific prompt playbooks in `agents/`.
- 56 skills: task-focused helpers in `skills/` (one folder per skill, `SKILL.md`).
- 232 patterns: Fabric prompt patterns in `patterns/` (plus `loaded` and `pattern_explanations.md` references).
- Catalog: `catalog.yaml` consolidates every agent, skill, and pattern with paths, descriptions, and when-to-use notes.

## Using the patterns
Patterns originate from [Fabric](https://github.com/danielmiessler/Fabric). Run them with the Fabric CLI, chain them together, or embed them into your own workflows. They remain useful as plain prompts even without Fabric installed.

## Guidance
See `instructions.md` for local environment notes and navigation tips for agents, skills, and patterns.

- Local customizations: keep your own secrets in a local `.env` (git-ignored here). Personal tooling lives in `tools/`—this repo ignores that folder to stay portable; you can add your own scripts or MCP servers locally without affecting the template.

## License
MIT
