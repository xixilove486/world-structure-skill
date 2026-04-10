# Skill Smoke Tests

Use these prompts to test whether `world-structure` is being discovered and used appropriately after installation.

## Should Trigger

### 1. Team bottleneck
为什么这个创业团队明明人很多、开会很多，却总像在原地打转？

### 2. Relationship drift
帮我分析一下这段关系为什么没有直接崩，但明显越来越空心了。

### 3. Project diagnosis
这个项目不是没人努力，但就是推进不动。你用结构分析的方式看一下问题出在哪。

### 4. Organization stage judgment
这个组织现在更像是在扩张期、瓶颈期，还是已经开始僵化了？

### 5. Intervention priority
如果这个团队只能先修一件事，应该优先修什么？

### 6. Hidden-pattern analysis
表面看是几个人在吵架，但我怀疑背后是更深的结构问题。你来拆一下。

## Should Trigger Only in Deep Mode

### 7. Full-context request
不要只给我诊断，直接按完整世界模型的长文逻辑来分析。

### 8. Cross-section synthesis
请把阶段、概念、公理、诊断框架一起调动起来，完整分析这个系统。

### 9. Source request
这个模型背后的参考来源和验证状态是什么？请一起说明。

## Should Not Trigger

### 10. Simple math
12 × 37 等于多少？

### 11. Pure factual lookup
今天东京天气怎么样？

### 12. One-off coding question
帮我写一个 Python 冒泡排序。

### 13. Pure emotional comfort
我今天心情很差，你安慰我一下。

### 14. Exact prediction request
你预测一下这家公司三个月后会不会倒闭。

## What “Good Triggering” Looks Like

A good result usually means the response:
- identifies the system
- names the anchor or structural center
- distinguishes constraints from blame
- judges stage approximately
- identifies a core contradiction
- proposes a repair priority
- keeps uncertainty explicit

## What “Bad Triggering” Looks Like

A bad result usually means the response:
- ignores structure and jumps to moral judgment
- treats the issue as only personality conflict
- gives generic advice with no stage logic
- overuses the full long-form file when a lighter pass would work
- overclaims certainty
