# Agentic Skills

High-use skill packs that change how coding agents behave or what they can reach.
常用、能改变 Agent 行为或可达能力的 Skills 包。

Ordered by practical impact for day-to-day agent coding.
按日常 Agent 编程的实用影响排序。

---

## 1. [ponytail](https://github.com/DietrichGebert/ponytail)

Skill pack that forces the agent to prefer the smallest working solution (skip → reuse → stdlib → one line → then minimal code).
强制 Agent 优先最小可行方案的技能包（跳过 → 复用 → 标准库 → 一行 → 再写最少代码）。

Works across major coding agents; includes review skill against over-engineering.
适配主流编程 Agent；含反过度设计的 review 技能。

**Value:** Cuts token cost and bloat; strongest default “behavior” skill for production coding agents.
**价值：** 降低 token 与代码膨胀；生产向编程 Agent 最强默认行为技能。

---

## 2. [andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)

Guidelines (CLAUDE.md / skill) from Karpathy-style LLM coding pitfalls: think before coding, simplicity, surgical edits, goal-driven execution.
源自 Karpathy 式 LLM 编程坑点的行为准则（CLAUDE.md / skill）：先思考、简单优先、外科手术式修改、目标驱动执行。

**Value:** Lightweight, universal anti-pattern filter; pairs well with ponytail.
**价值：** 轻量通用的反模式过滤器；可与 ponytail 互补。

---

## 3. [Agent-Reach](https://github.com/Panniantong/Agent-Reach)

CLI that gives agents access to platforms they cannot reach well alone (X, Reddit, YouTube, Bilibili, XiaoHongShu, etc.), often without paid APIs.
让 Agent 够到其原生难覆盖的平台（X、Reddit、YouTube、B 站、小红书等）的 CLI，多数无需付费 API。

**Value:** Extends agent “eyes” to login-walled and CN social/video content.
**价值：** 把 Agent 的「眼睛」扩展到登录墙与中文社交/视频内容。

---

## 4. [Understand-Anything](https://github.com/Egonex-AI/Understand-Anything)

Turns a codebase or docs into an interactive knowledge graph (explore, search, Q&A) via multi-agent analysis; plugin for Claude Code and other agents.
通过多智能体分析，将代码库或文档变成可探索、搜索与问答的知识图谱；适配 Claude Code 等 Agent。

**Value:** Onboarding and navigation for large unfamiliar repositories.
**价值：** 大型陌生仓库的入门与导航。
