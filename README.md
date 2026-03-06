# Skills

Agent skills for coding assistants. Works with GitHub Copilot, Claude Code, Cursor, Codex, and [40+ other agents](https://github.com/vercel-labs/skills#supported-agents).

## Install

```bash
npx skills add labudis/skills
```

Install a specific skill:

```bash
npx skills add labudis/skills --skill mockup-prototype
```

## Available Skills

| Skill | Description |
|-------|-------------|
| [mockup-prototype](skills/mockup-prototype/SKILL.md) | Generate interactive HTML mockups, iterate on them, and deploy to GitHub Pages for sharing |

## Adding Skills

Each skill lives in `skills/<name>/SKILL.md`. See the [Agent Skills spec](https://agentskills.io) for the format.
