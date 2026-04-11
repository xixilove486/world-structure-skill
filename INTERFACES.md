# 多接口适配说明

这个仓库现在除了 Codex skill 入口之外，也内置了一组给其他常见接口使用的薄适配层。  
目标不是把正文复制成很多份，而是让不同用户在不同工具里都能接入同一套 `world-structure` 方法。

## 适配原则

- 原始正文仍以 `README.md` 与 `skills/world-structure/SKILL.md` 为准
- 新增接口文件只负责“入口”和“调度”，不重写整套作品
- 仓库主体继续保持中文
- 如果模型主体需要更新，优先更新正文，再回填薄适配层

## 当前支持的接口

| 接口 | 入口文件 | 用法 |
|---|---|---|
| Codex | `skills/world-structure/` | 保持现有 skill 安装方式不变 |
| Claude Code | `CLAUDE.md` | 打开仓库后作为项目级记忆入口 |
| Gemini CLI | `GEMINI.md` | 打开仓库后作为项目级上下文入口 |
| Cursor | `AGENTS.md` / `.cursor/rules/world-structure.mdc` | 既支持通用入口，也支持规则文件 |
| GitHub Copilot | `.github/copilot-instructions.md` + `AGENTS.md` | 提供仓库级 Copilot 说明，并和通用入口保持一致 |
| 通用 agent | `AGENTS.md` | 作为非特定厂商的默认入口 |

## 怎么部署

### 1. 直接打开这个仓库

如果用户直接在这些工具里打开 `world-structure-skill` 仓库，内置的入口文件就会被识别或引用。

### 2. 迁移到别的项目

如果用户想把这套方法带到自己的项目里，优先复制对应入口文件：

- Claude Code：复制 `CLAUDE.md`
- Gemini CLI：复制 `GEMINI.md`
- Cursor：复制 `AGENTS.md` 或 `.cursor/rules/world-structure.mdc`
- GitHub Copilot：复制 `.github/copilot-instructions.md`，并建议同时保留 `AGENTS.md`

迁移后，如果还需要完整方法论，再把这些路径一并带上或引用：

- `skills/world-structure/SKILL.md`
- `skills/world-structure/templates/analysis-template.md`
- `skills/world-structure/resources/guardrails.md`

### 3. 保持同步

当模型主体升级时，推荐按这个顺序维护：

1. `README.md`
2. `skills/world-structure/SKILL.md`
3. `AGENTS.md`
4. 其他接口入口文件

## 备注

- 这些适配层不会替代现有的 Codex 安装路径
- 这些适配层也不会改变介绍页、README、长文资源的原本角色
- 如果你只想最快开始，Codex 仍然是最直接的安装入口
