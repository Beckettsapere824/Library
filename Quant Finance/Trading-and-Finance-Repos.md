# Trading & Finance Repositories

Ordered by priority for building or studying systematic / AI-assisted trading systems (production engine and accurate simulation first; retail UI and commercial products last).
按优先级排列：生产级引擎与准确仿真优先，零售界面与商业产品靠后。

Sources include curated picks and high-signal items from the maintainer’s GitHub stars.
来源含策展选型与维护者 GitHub stars 中的高信号项。

---

## 1. [nautilus_trader](https://github.com/nautechsystems/nautilus_trader)

Production-grade open-source trading engine with a Rust core and Python control plane.
生产级开源交易引擎，Rust 核心 + Python 控制面。

Covers research, deterministic backtest, and live multi-venue execution in one event-driven architecture.
在同一套事件驱动架构下覆盖研究、确定性回测与多市场实盘执行。

**Value:** Same semantics from simulation to live; suitable as a real system backbone, not only a notebook demo.
**价值：** 仿真与实盘语义一致，适合作为真实系统骨架，而非仅 Notebook 演示。

---

## 2. [hftbacktest](https://github.com/nkaz001/hftbacktest)

High-frequency and market-making backtester (Python/Numba and Rust) using full tick and L2/L3 order-book data.
高频与做市回测工具（Python/Numba 与 Rust），使用完整 tick 与 L2/L3 盘口数据。

Models feed latency, order latency, and queue position for fills; supports multi-asset and limited live bot paths (e.g. Binance/Bybit).
建模行情延迟、报单延迟与队列位置成交；支持多资产，并有有限实盘路径（如 Binance/Bybit）。

**Value:** Realistic HFT/MM research where naive bar backtests are misleading.
**价值：** 在朴素 K 线回测会失真的场景下，做更贴近真实的高频/做市研究。

---

## 3. [hikyuu](https://github.com/fasiondog/hikyuu)

High-performance quant framework (C++ core + Python) focused on strategy analysis and very fast backtesting.
高性能量化框架（C++ 核心 + Python），侧重策略分析与极速回测。

Strong China-market research workflow orientation.
对 A 股等研究工作流较友好。

**Value:** Engine alternative when you need speed and a mature CN-oriented quant stack.
**价值：** 需要速度与成熟中文市场向栈时的引擎备选。

---

## 4. [FinRL-Trading](https://github.com/AI4Finance-Foundation/FinRL-Trading)

AI-native modular infrastructure for quantitative trading from the FinRL / AI4Finance line (FinRL-X).
AI4Finance 路线的 AI 原生模块化量化交易基础设施（FinRL-X）。

**Value:** Bridge between RL/ML research code and trading-system modularity.
**价值：** 连接 RL/ML 研究代码与交易系统模块化。

---

## 5. [gs-quant](https://github.com/goldmansachs/gs-quant)

Goldman Sachs open Python toolkit for quantitative finance (risk, pricing-oriented building blocks).
高盛开源的量化金融 Python 工具包（风险、定价向积木）。

**Value:** Institutional library shape and API taste; study patterns even if you do not run GS workflows.
**价值：** 机构库形态与 API 品味；即使不跑高盛流程也可学其模式。

---

## 6. [anthropics/financial-services](https://github.com/anthropics/financial-services)

Anthropic reference agents, skills, and connectors for investment banking, equity research, PE, and wealth workflows.
Anthropic 面向投行、股票研究、PE 与财富管理的参考 Agent、Skills 与数据连接器。

**Value:** Institutional FSI agent patterns from a major lab.
**价值：** 来自主流实验室的机构金融 Agent 范式。

---

## 7. [TradingAgents](https://github.com/TauricResearch/TradingAgents)

Multi-agent LLM trading framework that mirrors a desk: fundamental, sentiment, technical analysts, trader, and risk roles.
多智能体 LLM 交易框架，结构类似交易台：基本面、情绪、技术分析、交易员与风控角色。

**Value:** Clear multi-agent trading research scaffold with published design (arXiv).
**价值：** 结构清晰的多智能体交易研究脚手架，有公开论文设计。

---

## 8. [TradingAgents-CN](https://github.com/hsliuping/TradingAgents-CN)

Chinese-enhanced multi-agent stock research system derived from TradingAgents, oriented to A-shares (also HK/US).
基于 TradingAgents 的中文增强多智能体股票研究系统，面向 A 股（亦支持港股/美股）。

**Value:** Best-fit entry for Chinese-market multi-agent research and teaching.
**价值：** 中文市场多智能体研究与教学的优先入口。

---

## 9. [OpenAlice](https://github.com/TraderAlice/OpenAlice)

AI trading agent product covering equities, crypto, commodities, forex, and macro — research through position lifecycle.
覆盖股、加密、商品、外汇与宏观的 AI 交易 Agent 产品：从研究到持仓生命周期。

**Value:** End-to-end “one-person desk” agent product reference (starred; evaluate claims carefully).
**价值：** 端到端「一人交易台」Agent 产品参考（来自 stars；主张需自行验证）。

---

## 10. [Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)

Personal trading-agent product stack (LLM + tools + backtest + UI) from HKUDS.
港大数据科学团队的个人交易 Agent 产品栈（LLM + 工具 + 回测 + 界面）。

**Value:** End-to-end “agent + trading” product reference; high activity.
**价值：** 端到端「Agent + 交易」产品参考；活跃度高。

---

## 11. [free-stockdb](https://github.com/hello245m/free-stockdb)

Local-first A-share quant data engine: daily/minute bars, incremental sync, adjust factors, indicators, multiple query APIs.
本地优先的 A 股量化数据引擎：日/分钟 K、增量同步、复权、指标与多种查询 API。

**Value:** Removes remote API rate limits for full-market local research on China equities.
**价值：** 让 A 股全市场本地研究摆脱远程 API 限频。

---

## 12. [OpenStock](https://github.com/Open-Dev-Society/OpenStock)

Open-source stock web app (Next.js + Finnhub + TradingView).
开源股票 Web 应用（Next.js + Finnhub + TradingView）。

**Value:** Full-stack market UI reference; not an execution engine.
**价值：** 全栈行情界面参考；非执行引擎。

---

## 13. [KovaView](https://kovaview.com/)

Commercial screener / research / journaling workspace.
商业化筛选 / 研究 / 交易日志工作台。

**Value:** Product UX reference; paid SaaS.
**价值：** 产品 UX 参考；付费 SaaS。

---

## Related / 相关

- [Quant-Trading-Resources.md](Quant-Trading-Resources.md) — sites, digests, platforms  
- [investing-for-beginners](https://github.com/xuchonglang/investing-for-beginners) — US equities / options / crypto knowledge framework (CN notes; education, not an engine)  
  美股、期权与加密知识框架（中文笔记；教育向，非引擎）
