---
name: world-structure-repo
description: 世界结构 skill 仓库入口说明，实际可安装版本位于 skills/world-structure。
---

# 仓库入口说明

这个仓库已经整理成适合 Codex 安装的结构。

真正可安装、可被 Codex 读取的 skill 位于：

- `skills/world-structure`

也就是说：

- 根目录 `README.md` 负责作品展示与仓库说明
- 根目录 `SKILL.md` 负责告诉使用者安装入口在哪里
- `skills/world-structure/SKILL.md` 才是实际被安装和调用的 skill 主文件

## Codex 安装方式

### 方式 1：按 GitHub URL 安装

```powershell
py -3 "$HOME/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py" --url https://github.com/xixilove486/world-structure-skill/tree/main/skills/world-structure
```

### 方式 2：按仓库和路径安装

```powershell
py -3 "$HOME/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py" --repo xixilove486/world-structure-skill --path skills/world-structure
```

安装后重启 Codex，即可识别。

## 结构说明

如果你是来阅读作品本身，优先看：

- `README.md`
- `skills/world-structure/README.md`
- `skills/world-structure/SKILL.md`

如果你是来安装 skill，优先使用：

- `skills/world-structure`

## 备注

这个文件不是作品正文。
它只是仓库层的入口说明，用来避免仓库展示层和可安装 skill 层混在一起.
