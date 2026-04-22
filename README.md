# zhangluka

**Harness Engineering 实践者** —— 把 AI 代码从"能跑"变成"能入库"。

我在自己的 Nest.js 项目里，用 OpenSpec + Ralph Loop 把 AI 生成代码的一次性通过率从 30% 提到 75%。
现在记录这套方法的工程化落地过程，开源给有同样痛点的团队。

---

## 我在做的事

**OpenSpec 内化版** · 让 Spec-Driven Development 在团队真正跑起来
> 基于 Fission-AI/OpenSpec 进行团队内化定制，增加 agent 适配层、工作流模板定制、代码审查集成。
> 让 Spec 不再是文档，而是驱动开发的单点可信源。

[zhangluka/OpenSpec](https://github.com/zhangluka/OpenSpec)

---

**Harness Engineering** · AI 代码质量工程化实践记录
> 从"调 Prompt"到"建流程"，记录把 AI 代码入库率系统性地做上去的全过程。
> 包含概念定义、实战项目复盘、工具链、思考笔记。

[zhangluka/harness_engineering](https://github.com/zhangluka/harness_engineering) · [文档站点](https://zhangluka.github.io/harness_engineering/)

---

**Ralph** · OpenSpec 变更自动应用工具
> 扫描项目中的 OpenSpec changes，自动识别已进入 apply 阶段的变更，调用 agent 执行编码任务。
> 让 Ralph Loop 从概念变成可运行的命令行工具。

[zhangluka/ralph_npm](https://github.com/zhangluka/ralph_npm)

---

## 我相信的几件事

**AI 代码质量问题，是工程问题，不是 Prompt 问题。**
> 调 Prompt 只能解决单次生成质量，建 Harness 才能系统性地提升入库率。

**Spec 是人和 AI 之间的契约。**
> 写清楚 Spec，AI 才能稳定地交付符合预期的代码。OpenSpec 是这个契约的载体。

**工具链比单点工具重要。**
> Ralph 不是独立的工具，是 OpenSpec → Agent → Code 这个流程里的关键一环。

---

## 找到我

[推特](https://x.com/grainrain_young) · [邮件](zhangluuka@gmail.com)

---

> 如果你也在用 AI 写代码，但受困于代码质量不稳定、review 成本越来越高，欢迎来聊聊。
