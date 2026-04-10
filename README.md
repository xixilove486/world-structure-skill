# world-structure-skill

A Codex-installable repository for the `world-structure` skill.

This repository is now organized so Codex's GitHub skill installer can install the skill directly from a stable subpath:

- Skill path: `skills/world-structure`
- Install URL: `https://github.com/xixilove486/world-structure-skill/tree/main/skills/world-structure`

## Install In Codex

If you are using Codex's built-in skill installer, install from the repo path instead of cloning the whole repository manually.

### Option 1: By GitHub URL

```powershell
py -3 "$HOME/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py" --url https://github.com/xixilove486/world-structure-skill/tree/main/skills/world-structure
```

### Option 2: By repo and path

```powershell
py -3 "$HOME/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py" --repo xixilove486/world-structure-skill --path skills/world-structure
```

After installation, restart Codex so the new skill is loaded.

## Repository Layout

```text
world-structure-skill/
|- skills/
|  '- world-structure/
|     |- SKILL.md
|     |- README.md
|     |- resources/
|     |- templates/
|     '- examples/
|- docs/
|- CONTRIBUTING.md
|- FINAL_CHECKLIST.md
|- LICENSE
'- ROADMAP.md
```

## Where The Skill Lives

The actual reusable skill package is here:

- `skills/world-structure/SKILL.md`
- `skills/world-structure/README.md`
- `skills/world-structure/resources/`
- `skills/world-structure/templates/`
- `skills/world-structure/examples/`

## Notes

- `docs/` can stay at the repository root for GitHub Pages or public documentation.
- Root-level repository files are for presentation and maintenance.
- The installable skill payload should stay under `skills/world-structure/`.
