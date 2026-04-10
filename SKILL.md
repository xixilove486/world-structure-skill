---
name: world-structure-repo
description: Repository wrapper for the installable world-structure Codex skill.
---

# Repository Wrapper

This repository's installable Codex skill lives at:

- `skills/world-structure`

If you want to install this skill with Codex's GitHub installer, use one of these forms:

```powershell
py -3 "$HOME/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py" --url https://github.com/xixilove486/world-structure-skill/tree/main/skills/world-structure
```

or

```powershell
py -3 "$HOME/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py" --repo xixilove486/world-structure-skill --path skills/world-structure
```

The actual skill files are under `skills/world-structure/`.
The root of the repo is for packaging, docs, and maintenance.
