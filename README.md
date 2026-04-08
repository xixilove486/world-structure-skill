# 世界结构.skill

> 把复杂对象当作**结构系统**来分析，而不是把一切都还原成情绪、偶然事件或单个人的问题。

`世界结构.skill` 是一个面向 AI 助手的结构分析技能包。  
它帮助模型从 **锚点、约束、角色、支持链、扰动、熵增与演化阶段** 出发，分析团队、关系、项目、制度、社群与复杂处境。

---

## 一句话简介

**一个用于分析团队、关系、项目、制度与复杂处境的结构分析 skill。**

---

## 它解决什么问题

这个 skill 适合处理下面这些问题：

- 为什么一个团队总在原地打转
- 为什么一段关系总反复失衡
- 为什么一个项目越来越忙却越来越空心
- 为什么一个制度表面稳定、内部却逐渐僵化
- 为什么某个组织正在分裂、漂移、失去活力，或者逼近转折点

它尤其适合：
- 重复出现的问题
- 多角色、多层级、多约束混合的问题
- 需要看“深层结构”而不是只看表面症状的问题

---

## 它不做什么

这个 skill **不是**：

- 未来事件的精确预测器
- 法律、医疗、金融等专业意见替代品
- 给人贴“本质标签”的工具
- 用来攻击、羞辱或武器化分析对象的语言系统
- “解释万物”的终极神谕

---

## 核心分析主轴

这个 skill 默认从以下七个方向看系统：

1. **Anchor**  
   系统围绕什么在维持、追求或漂移

2. **Constraints**  
   什么在限制它

3. **Roles and Layers**  
   谁在维持、谁在推动、谁在连接、谁在阻塞

4. **Support Chains**  
   资源、信任、记忆、合法性与情感投入从哪里来

5. **Disturbance / Drift / Entropy**  
   什么在让系统失真、漂移、僵化、分裂或空心化

6. **Stage**  
   它现在处于形成、扩张、瓶颈、转型、稳定、僵化、碎裂还是更新尝试

7. **Intervention Priority**  
   先修哪里最值

---

## 仓库结构

```text
world-structure-skill/
├── README.md
├── SKILL.md
├── CONTRIBUTING.md
├── ROADMAP.md
├── REPO_DESCRIPTION.txt
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
│       └── 08-extended-notes.md
├── templates/
│   ├── analysis-template.md
│   └── quick-diagnosis-template.md
└── examples/
    └── example-output.md
```

---

## 如何使用

### 对 AI 的使用方式
把 `SKILL.md` 当成轻量主入口。  
把 `resources/` 当成概念与长文参考层。  
把 `templates/` 当成输出模板。  
把 `examples/` 当成风格示范。

### 对人类读者的使用方式
先看：
- `README.md`
- `SKILL.md`

再按需深入：
- `resources/core-concepts.md`
- `resources/guardrails.md`
- `resources/world-model/`

---

## 技能定位

这个仓库不是在说“结构就是一切”。  
它只是提出：

> 很多复杂问题之所以难，不是因为没有答案，而是因为人们还没先把系统看成系统。

---

## 输出应该长什么样

一个好输出通常包含：

- **Structural Judgment**  
  当前系统发生了什么

- **Core Contradiction**  
  最深的结构矛盾是什么

- **Main Risk Direction**  
  如果不改，系统最可能往哪里坏

- **Best Intervention Priority**  
  先修哪里最值

- **Uncertainty / Alternative Readings**  
  还有哪些不确定项

---

## 设计原则

这个 skill 有四条硬原则：

1. **结构优先于责备**
2. **高成本信号优先于宣称**
3. **约束优先于建议**
4. **不确定性必须显式保留**

---

## 长文参考层

如果你想看完整的世界模型参考材料，请进入：

- `resources/world-model/00-index.md`

从那里你可以继续读到：
- 模型定位
- 核心原则
- 核心概念
- 阶段逻辑
- 诊断框架
- 干预规则
- 边界与警告
- 延伸说明

---

## 最后一句

**世界结构.skill 不是世界本身。**  
它只是试图用同一套结构语言，去看清复杂对象是怎么形成、维持、失衡、转折、更新与崩解的。
