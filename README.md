<div align="center">

# 世界结构.skill

### 不是解释万物，而是看清复杂对象的结构。  
*See the structure, not just the symptom.*

<br>

![License: MIT](https://img.shields.io/badge/License-MIT-f5c542?style=flat-square)
![Skill](https://img.shields.io/badge/World%20Structure-Skill-7c3aed?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Hidden%20Patterns-2563eb?style=flat-square)
![Scope](https://img.shields.io/badge/Scope-Teams%20%7C%20Relationships%20%7C%20Projects-059669?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-black?style=flat-square)

</div>

---

> [!NOTE]
> **世界结构.skill** 不是“解释万物”的终极神谕。  
> 它是一套给 AI 和人都能用的**结构分析工具**：  
> 从**锚点、约束、角色、支持链、扰动、熵增与演化阶段**出发，判断一个系统如何形成、维持、失衡、转折、更新与崩解。

## 为什么需要这个 skill？

很多复杂问题之所以难，不是因为没有答案，  
而是因为人们太快去判断对错，却没有先把系统看成系统。

你看到的可能是：
- 一个团队总在原地打转
- 一段关系反复失衡
- 一个项目越来越忙，却越来越空心
- 一个制度表面稳定，内部却逐渐僵化
- 一个组织看似还活着，实际上正在漂移、碎裂或失去活力

**世界结构.skill** 想做的事很简单：

> **先看结构，再谈判断。**  
> **先看约束，再谈建议。**  
> **先看阶段，再谈症状。**

---

## 它能做什么？

这个 skill 主要适合：

- 团队分析
- 关系分析
- 项目诊断
- 组织与制度分析
- 社群与复杂处境分析
- 反复冲突、长期停滞、边界模糊、暗中漂移的系统判断

它最擅长输出五种东西：

1. **Structural Judgment**  
   当前系统发生了什么

2. **Core Contradiction**  
   最深的结构矛盾是什么

3. **Main Risk Direction**  
   如果不改，最可能往哪里坏

4. **Best Intervention Priority**  
   先修哪里最值

5. **Uncertainty / Alternative Readings**  
   还存在哪些不确定项

---

## Install

This skill can be installed either:

- per-user: available across your repos
- per-repo: shared inside one project

Codex-style skill loaders typically discover skills from standard skill folders and load them progressively, so the full long-form reference is only read when the skill is actually used.

### Per-user install

#### macOS / Linux
```bash
mkdir -p "$HOME/.agents/skills" && \
(test -d "$HOME/.agents/skills/world-structure-skill/.git" && \
git -C "$HOME/.agents/skills/world-structure-skill" pull --ff-only || \
git clone https://github.com/xixilove486/world-structure-skill.git "$HOME/.agents/skills/world-structure-skill")
```

#### Windows PowerShell
```powershell
New-Item -ItemType Directory -Force "$HOME/.agents/skills" | Out-Null
if (Test-Path "$HOME/.agents/skills/world-structure-skill/.git") {
  git -C "$HOME/.agents/skills/world-structure-skill" pull --ff-only
} else {
  git clone https://github.com/xixilove486/world-structure-skill.git "$HOME/.agents/skills/world-structure-skill"
}
```

### Per-repo install

#### macOS / Linux
```bash
mkdir -p .agents/skills && \
(test -d .agents/skills/world-structure-skill/.git && \
git -C .agents/skills/world-structure-skill pull --ff-only || \
git clone https://github.com/xixilove486/world-structure-skill.git .agents/skills/world-structure-skill)
```

#### Windows PowerShell
```powershell
New-Item -ItemType Directory -Force ".agents/skills" | Out-Null
if (Test-Path ".agents/skills/world-structure-skill/.git") {
  git -C ".agents/skills/world-structure-skill" pull --ff-only
} else {
  git clone https://github.com/xixilove486/world-structure-skill.git ".agents/skills/world-structure-skill"
}
```

### Update

#### macOS / Linux
```bash
git -C "$HOME/.agents/skills/world-structure-skill" pull --ff-only
```

#### Windows PowerShell
```powershell
git -C "$HOME/.agents/skills/world-structure-skill" pull --ff-only
```

### Notes

- Use the **per-user** install if you want this skill in all your projects.
- Use the **per-repo** install if you want to share it with a team inside one repository.
- The skill is designed for progressive loading: metadata first, full instructions only when needed.

---

## 它不做什么？

> [!WARNING]
> 这个 skill **不是**：
>
> - 未来事件的精确预测器
> - 法律、医疗、金融等专业判断的替代品
> - 给人贴“本质标签”的工具
> - 用来攻击、羞辱或武器化分析对象的语言系统
> - “我懂你的一切”的人格审判器

---

## 核心分析主轴

这个 skill 默认从七个方向看系统：

| 维度 | 问题 |
|---|---|
| **Anchor** | 系统围绕什么在维持、追求或漂移？ |
| **Constraints** | 什么在限制它？ |
| **Roles & Layers** | 谁在维持、谁在推动、谁在连接、谁在阻塞？ |
| **Support Chains** | 资源、信任、记忆、合法性与情感投入从哪里来？ |
| **Disturbance / Drift / Entropy** | 什么在让系统失真、漂移、僵化、分裂或空心化？ |
| **Stage** | 它正处于形成、扩张、瓶颈、转型、稳定、僵化、碎裂还是更新尝试？ |
| **Intervention Priority** | 先修哪里最值？ |

---

## 使用方式

### 给 AI 的使用方式
- 把 `SKILL.md` 当成轻量主入口
- 把 `resources/` 当成概念与长文参考层
- 把 `templates/` 当成输出模板
- 把 `examples/` 当成风格示范

### 给人类读者的阅读顺序
1. `README.md`
2. `SKILL.md`
3. `resources/core-concepts.md`
4. `resources/guardrails.md`
5. `resources/world-model/00-index.md`

---
## 仓库结构

```text
world-structure-skill/
├── README.md
├── SKILL.md
├── LICENSE
├── CONTRIBUTING.md
├── ROADMAP.md
├── FINAL_CHECKLIST.md
├── TAGLINE_OPTIONS.md
├── MOBILE_UPLOAD_STEPS.md
├── REPO_DESCRIPTION.txt
├── TOPICS.txt
├── resources/
│   ├── core-concepts.md
│   ├── guardrails.md
│   └── world-model/
│       ├── 00-index.md
│       ├── 01-model-positioning.md
│       ├── 02-core-principles.md
│       ├── 03-core-concepts.md
│       ├── 04-evolution-stages.md
│       ├── 05-diagnostic-framework.md
│       ├── 06-intervention-rules.md
│       ├── 07-boundaries-and-warnings.md
│       ├── 08-extended-notes.md
│       ├── 13-references-and-validation.md
│       └── world-model-full.md
├── templates/
│   ├── analysis-template.md
│   └── quick-diagnosis-template.md
└── examples/
    └── example-output.md
```

---

## 长文参考层

这个仓库现在包含三种长文结构：

### 1. 拆分版
位置：
- `resources/world-model/`

适合：
- 导航阅读
- 分段维护
- 技能检索
- 针对性更新

### 2. 完整单文件版
位置：
- `resources/world-model/world-model-full.md`

适合：
- 一次性完整阅读
- 存档
- 保留原始长文连续性

### 3. 参考与验证附录
位置：
- `resources/world-model/13-references-and-validation.md`

适合查看：
- 参考来源
- 理论对话
- 方法论说明
- 全局验证状态摘要

---

## 设计原则

<div align="center">

| 原则 | 含义 |
|---|---|
| **结构优先于责备** | 先看系统，再谈责任 |
| **高成本信号优先于宣称** | 先看行动，再听口号 |
| **约束优先于建议** | 先看承载，再谈改进 |
| **不确定性必须显式保留** | 不把模型当神谕 |

</div>

---

## 一个好输出长什么样？

```text
Structural Judgment
Core Contradiction
Main Risk Direction
Best Intervention Priority
Uncertainty / Alternative Readings
```

简洁、清醒、不武器化。  
这比“宏大、激烈、像在审判世界”的输出更有价值。

---

## 项目定位

> [!TIP]
> 这个仓库不是在说“结构就是一切”。  
> 它只是提出：
>
> **很多复杂问题之所以难，不是因为没有答案，  
> 而是因为人们还没先把系统看成系统。**

---

## 最后一句

<div align="center">

### **世界结构.skill 不是世界本身。**  
它只是试图用同一套结构语言，  
去看清复杂对象是怎么形成、维持、失衡、转折、更新与崩解的。

经过不断迭代与验证，我越来越确认一件事：为人民服务，不是道德口号，而是历史中最强大的结构性创造之一。
</div>
