# world-structure / Agent Adapter

本文件是给通用 AI agent 的仓库级入口说明。  
它不重写作品正文；仓库的原始内容仍以 [README.md](README.md) 和 [skills/world-structure/SKILL.md](skills/world-structure/SKILL.md) 为准。

## 这个仓库怎么理解

- 根目录：作品展示、定位、安装说明与分发入口
- `skills/world-structure/`：实际可安装的 Codex skill 主体
- `docs/`：在线介绍页与静态资源
- 适配层：`CLAUDE.md`、`GEMINI.md`、`.cursor/rules/world-structure.mdc`、`.github/copilot-instructions.md`

## 读取优先级

1. [README.md](README.md)
2. [skills/world-structure/SKILL.md](skills/world-structure/SKILL.md)
3. [skills/world-structure/templates/analysis-template.md](skills/world-structure/templates/analysis-template.md)
4. [skills/world-structure/resources/guardrails.md](skills/world-structure/resources/guardrails.md)
5. [skills/world-structure/resources/world-model/00-index.md](skills/world-structure/resources/world-model/00-index.md)
6. 只有在确实需要更多方法论细节时，再继续读取 `world-model/` 下的分篇长文

## 何时调用这个模型

当任务实际上在问下面这些问题时，优先使用 `world-structure`：

- 团队、关系、项目、组织、制度、公共议题中的复杂失衡
- 为什么一个系统推进不动、越来越空、越来越僵、越来越碎
- 为什么表面上只是冲突，背后却像结构性故障
- 如果只能先修一处，最该修哪里
- 如何把一个复杂对象重新读成：锚点、约束、角色、推力链、扰动、阶段与干预优先级

当任务只是下面这些情况时，不要强行套用：

- 单纯事实查询
- 算术、工具操作、代码实现等非结构诊断问题
- 临床、法律、医疗、金融等高风险专业判断
- 只需要陪伴或安慰，不需要诊断分析的对话

## 默认分析框架

默认从这几个维度看系统：

1. 锚点
2. 约束
3. 角色与层级
4. 推力链
5. 扰动 / 漂移 / 熵增
6. 阶段
7. 干预优先级

## 推荐输出骨架

输出尽量收束成一个可用的结构面板，而不是散乱评论：

1. 关键信号
2. 结构判断
3. 核心矛盾
4. 主要风险方向
5. 最优先干预点
6. 不确定性 / 其他可能解释

## 边界与纪律

- 不要把模型变成人格审判器
- 不要把结构判断说成宿命
- 不要用结构语言去羞辱或武器化对象
- 不要在证据不足时装作“已经看透一切”
- 优先看高成本信号，而不是口号、自述或姿态

关于“爱”，保持和仓库正文一致的边界：

- 爱不是偷懒解释词
- 爱是中性的、具有超越性的概念
- 爱不是用来替代理论解释的，而是用来标记理论解释的边界

关于“理想”，保持和仓库正文一致的边界：

- 模型不预设理想必然失败
- 模型也不预设理想会自动实现
- 模型关心的是理想进入现实后如何被损耗、篡改，或保存

## 术语一致性

- 中文对外表述优先保持中文
- 统一使用“推力链”
- 如果历史英文文件中出现 `support chain`，按同一概念理解，不要再扩散新的术语分叉

## 修改这个仓库时

- 不要删除现有长文正文，除非用户明确要求
- 新增适配优先做“薄封装”，不要复制出多套逐渐漂移的正文
- 真正可安装的 Codex skill 路径始终保持为 `skills/world-structure/`
- 如果需要调整模型主体，优先更新 `README.md` 与 `skills/world-structure/SKILL.md`
