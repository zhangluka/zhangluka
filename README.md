<p align="center">
</p>

<h1 align="center">zhangluka (bobby)</h1>

<p align="center">
  <strong>AI 应用场景探索者</strong> —— 关注 AI 在真实业务中的落地，不只是 Demo。
</p>

<p align="center">
  从 <strong>Harness Engineering</strong> 到 <strong>Spec-Driven Development</strong>，<br>
  我在找那些<strong>能让 AI 从"能用"变成"好用"</strong>的关键环节。<br>
  相信好的 AI 应用不是调出来的，是设计出来的。
</p>

---

## 🚀 我在做什么

### handoff · AI 编程 Agent 的上下文接力

每次在 Claude Code 和 Cursor 之间切换，新 Agent 什么都不知道——你得重新解释项目结构、技术决策、当前进度。Handoff 解决这个问题：一条命令，自动从 Claude Code 的 session 日志提取关键信息，注入到 Cursor 的规则文件里。Cursor 开口就知道你之前做了什么。纯规则提取，不需要 LLM，零成本。

[![GitHub](https://img.shields.io/badge/仓库-181717?logo=github&logoColor=white)](https://github.com/zhangluka/handoff)

---

### claude-super-evolution · Claude Code 自我进化框架

Claude Code 很强，但每次会话结束就"失忆"——不会从经验中学习，下次可能犯同样的错误。这个项目借鉴 Hermes Agent 的设计哲学，用 Claude Code 现有的原语（Hooks、Cron、Memory、Skills）搭建了一个外挂式自我进化闭环：执行任务 → 评估结果 → 提取经验 → 更新策略 → 下次更好。

[![GitHub](https://img.shields.io/badge/仓库-181717?logo=github&logoColor=white)](https://github.com/zhangluka/claude-super-evolution)

---

### skills · Claude Code 个人技能库

写了这么多方法论，最终要落到日常使用上。这个仓库是我的 Claude Code 技能工具箱——5 个自用 skill，覆盖三类场景：写作风格（小约翰可汗体、谷雨公众号、博客体）、内容创作工作流、开发工具（临时文件清理、项目模板生成）。每个 skill 一个 SKILL.md，`/skill-name` 直接调用。

[![GitHub](https://img.shields.io/badge/仓库-181717?logo=github&logoColor=white)](https://github.com/zhangluka/skills)

---

### hermes-skill-audit · Hermes Agent 技能审计工具

Hermes Agent 会在每条消息中加载所有已安装的 skills，导致 token 浪费。110+ skills 每轮消耗 ~300K tokens。这个工具可以检测重复、估算 token、追踪使用频率、自动清理。

我在 10 小时内烧掉 6000 万 Credits 后，发现了这个问题，于是构建了这个工具。

[![GitHub](https://img.shields.io/badge/仓库-181717?logo=github&logoColor=white)](https://github.com/zhangluka/hermes-skill-audit)

---

### OpenSpec · 人和 AI 的协作契约

基于 Fission-AI/OpenSpec 做团队内化定制，增加 agent 适配层、工作流模板和代码审查集成。Spec 是驱动开发的单点可信源——AI 负责执行，人负责判断。

[![GitHub](https://img.shields.io/badge/仓库-181717?logo=github&logoColor=white)](https://github.com/zhangluka/OpenSpec)

---

### Ralph Loop · 自动化的变更执行

扫描 OpenSpec changes，自动识别可执行的变更，调用 Agent 完成编码。"需求 → Spec → 代码"的闭环真正跑起来。目前以 npm 包形式发布。

[![GitHub](https://img.shields.io/badge/仓库-181717?logo=github&logoColor=white)](https://github.com/zhangluka/ralph_npm)

---

### Harness Engineering · 让 AI 代码真正可交付

AI 写代码很快，但入库率很低。我在自己的 Nest.js 项目里用 OpenSpec + Ralph Loop 把 AI 代码一次性通过率从 **30% 提到 75%**，记录这套方法论的工程化落地。

[![GitHub](https://img.shields.io/badge/查看仓库-181717?logo=github&logoColor=white)](https://github.com/zhangluka/harness_engineering)
[![Docs](https://img.shields.io/badge/文档站点-4285F4?logo=google-chrome&logoColor=white)](https://zhangluka.github.io/harness_engineering/)

---

### china-travel-guide · 面向外国游客的英文中国旅行指南

用 Next.js 15 + Tailwind CSS 4 + MDX 构建的 SEO 优化静态站点，目标用户是来华外国自由行游客。覆盖 7 座城市（成都、北京、上海、重庆、西安、张家界、桂林）共 52 个城市详情页、16 篇生存指南（支付宝/微信/火车/预算/签证等）、2 条行程规划（10天/2周）、3 篇小众中国攻略、3 篇城市对比文章，合计 76 个内容页面。基于 Google/YouTube 搜索热词数据驱动内容规划，部署在 Cloudflare Pages。

[![GitHub](https://img.shields.io/badge/仓库-181717?logo=github&logoColor=white)](https://github.com/zhangluka/china-travel-guide)
[![网站](https://img.shields.io/badge/chinabound.online-10B981?logo=globe&logoColor=white)](https://chinabound.online)

---

## 💡 我相信的几件事

| 信念 | 说明 |
|------|------|
| **AI 的价值在场景，不在技术** | 再强的模型，找不到合适的应用场景也是白搭 |
| **好的 AI 应用是设计出来的** | Prompt 工程解决单次问题，流程设计解决系统问题 |
| **从"能用"到"好用"隔着一百个细节** | Demo 展示可能性，生产环境考验可靠性 |

---

## 📮 找到我

[推特](https://x.com/grainrain_young) · [邮件](zhangluka@gmail.com)

---

<p align="center">
  <i>如果你也在探索 AI 的真实应用场景，不管是代码生成、内容创作还是别的什么，欢迎来交流。</i>
</p>
