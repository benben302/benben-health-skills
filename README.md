[README.MD](https://github.com/user-attachments/files/28103300/README.MD)
# benben-health-skills

> AI dialogue skills for digital health products in Chinese.  
> 面向中文数字健康产品的 AI 对话 skill 集合。

-----

## 背景

这个 repo 收录了我在开发两款数字健康产品过程中提炼出的 AI 对话 skill：

- **EatGuard** — 基于 CBT 框架的情绪性进食前置干预微信小程序
- **了了** — 基于 AI 的情绪陪伴日记微信小程序

两款产品的 AI 核心都是 DeepSeek + 微信云函数，面向中文 C 端用户。
Skills 基于循证框架（CBT / DBT / NSCA-CPT），针对数字健康场景设计。

-----

## Skills 列表

|Skill                                                      |来源产品    |框架依据    |适用场景            |
|-----------------------------------------------------------|--------|--------|----------------|
|[eatguard-fitness-coach](./eatguard-fitness-coach/SKILL.md)|EatGuard|NSCA-CPT|健身计划生成、用户评估、训练跟进|
|[emotion-naming](./emotion-naming/SKILL.md)                |了了      |身体感受具象化 |情绪命名、感受表达       |
|[companion-dialogue](./companion-dialogue/SKILL.md)        |了了      |CBT/人本主义|AI情绪陪伴对话        |
|[anti-sycophancy](./anti-sycophancy/SKILL.md)              |了了      |负面约束设计  |任何中文AI对话产品      |

-----

## 设计哲学

**不替用户说话。**
AI 只反射用户说过的词，不添加用户没有表达的内容。

**循证但不临床。**
框架来自 CBT/DBT/NSCA，但产品定位是日常工具，
不是治疗替代品。

**稳定性优先。**
所有 skill 都有明确的负面约束和降级策略，
防止 AI 在用户最脆弱的时刻输出有害内容。

-----

## 关于作者

通信工程专业大学本科在读学生 / 独立产品开发者 / NSCA-CPT 认证持有者

有个人情绪饮食管理经历，EatGuard 的核心干预逻辑来自亲身实践和 CBT 文献。

-----

*Skills 基于实际产品开发经验提炼，持续更新中。*
