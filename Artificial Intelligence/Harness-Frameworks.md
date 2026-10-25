# Harness Frameworks

A **harness** is the system around a model (prompts, tools, memory, skills, orchestration) that makes it act as an agent.
**Harness** 指模型外围的系统（提示、工具、记忆、技能、编排），使模型成为可行动的 Agent。

---

## 1. [deepseek-harness](https://github.com/deepseek-ai/deepseek-harness)

DeepSeek’s open-source agent harness (`dsh`): everything-is-a-plugin architecture on Cordis; Web UI and rapid iteration (developer preview).
DeepSeek 开源 Agent 框架（`dsh`）：基于 Cordis 的「一切皆插件」架构；含 Web UI，迭代快（开发者预览）。

**Value:** Full product-style harness to run and extend agents; major reference implementation from DeepSeek.
**价值：** 可运行、可扩展的完整产品级 harness；DeepSeek 侧重要参考实现。

---

## 2. [harness2](https://github.com/google-research/harness2)

Google Research framework for **recursive agent harnessing**: improve the harness (not model weights) via Propose–Probe–Compose on tasks, plus a persistent improvement harness.
Google Research 的**递归 Agent harness 优化**框架：在任务上用 Propose–Probe–Compose 改进 harness（不改模型权重），并维护持久的改进 harness。

**Value:** Research-grade method to raise agent performance by editing the surrounding system; papers and benchmarks included.
**价值：** 通过改外围系统提升 Agent 表现的研究级方法；含论文与基准。
