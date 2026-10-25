# Trading & Finance Repositories

Ordered by priority for building or studying systematic / AI-assisted trading systems (production engine and accurate simulation first; retail UI and commercial products last).

按优先级排列：生产级引擎与准确仿真优先，零售界面与商业产品靠后。

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

## 3. [anthropics/financial-services](https://github.com/anthropics/financial-services)

Anthropic reference agents, skills, and connectors for investment banking, equity research, PE, and wealth workflows.
Anthropic 面向投行、股票研究、PE 与财富管理的参考 Agent、Skills 与数据连接器。

Installable as Claude Cowork plugins or deployable via Managed Agents API (pitch, earnings, comps, DCF-style workflows).
可作为 Claude Cowork 插件安装，或通过 Managed Agents API 部署（路演、财报、可比公司、DCF 类流程）。

**Value:** Institutional FSI agent patterns from a major lab; strong template for regulated-style research automation.
**价值：** 来自主流实验室的机构金融 Agent 范式，适合受监管风格的研究自动化模板。

---

## 4. [TradingAgents](https://github.com/TauricResearch/TradingAgents)

Multi-agent LLM trading framework that mirrors a desk: fundamental, sentiment, technical analysts, trader, and risk roles.
多智能体 LLM 交易框架，结构类似交易台：基本面、情绪、技术分析、交易员与风控角色。

Agents debate and escalate to portfolio decisions; multi-provider LLM support; research-oriented with paper/simulation focus.
Agent 辩论并上升至组合决策；支持多 LLM 提供商；偏研究与模拟。

**Value:** Clear multi-agent trading research scaffold with published design (arXiv).
**价值：** 结构清晰的多智能体交易研究脚手架，有公开论文设计。

---

## 5. [TradingAgents-CN](https://github.com/hsliuping/TradingAgents-CN)

Chinese-enhanced multi-agent stock research system derived from TradingAgents, oriented to A-shares (also HK/US).
基于 TradingAgents 的中文增强多智能体股票研究系统，面向 A 股（亦支持港股/美股）。

Debate-style single-stock research, NL screening, paper trading and learning materials; explicitly for study/research, not live advice.
辩论式个股研究、自然语言筛选、模拟交易与学习材料；明确用于学习研究，非实盘建议。

**Value:** Best-fit entry for Chinese-market multi-agent research and teaching.
**价值：** 中文市场多智能体研究与教学的优先入口。

---

## 6. [Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)

Personal trading-agent product stack (LLM + tools + backtest + UI) from HKUDS.
港大数据科学团队的个人交易 Agent 产品栈（LLM + 工具 + 回测 + 界面）。

Large community project covering quant libraries, agents, and desktop/frontend surfaces.
大型社区项目，覆盖量化库、Agent 与桌面/前端。

**Value:** End-to-end “agent + trading” product reference; high activity, not a minimal research library.
**价值：** 端到端「Agent + 交易」产品参考；活跃度高，非最小研究库。

---

## 7. [free-stockdb](https://github.com/hello245m/free-stockdb)

Local-first A-share quant data engine: daily/minute (and related) bars, incremental sync, adjust factors, indicators, multiple query APIs (Python/HTTP/Excel/MCP).
本地优先的 A 股量化数据引擎：日/分钟等 K 线、增量同步、复权、指标，以及多种查询方式（Python/HTTP/Excel/MCP）。

**Value:** Removes remote API rate limits for full-market local research on China equities.
**价值：** 让 A 股全市场本地研究摆脱远程 API 限频约束。

---

## 8. [OpenStock](https://github.com/Open-Dev-Society/OpenStock)

Open-source stock web app (Next.js + Finnhub + TradingView): search, watchlists, charts, company views as a free alternative to paid terminals.
开源股票 Web 应用（Next.js + Finnhub + TradingView）：搜索、自选、图表与公司视图，作为付费终端的免费替代。

**Value:** Solid full-stack market UI reference; not an execution or HFT engine.
**价值：** 扎实的全栈行情界面参考；非执行或高频引擎。

---

## 9. [KovaView](https://kovaview.com/)

Commercial screener / research / journaling workspace (US, HK, A-shares, etc.) with scores, charts, and AI features.
商业化筛选 / 研究 / 交易日志工作台（美股、港股、A 股等），含评分、图表与 AI 功能。

**Value:** Product reference for decision workflow UX; paid SaaS, not open source.
**价值：** 决策流程产品 UX 参考；付费 SaaS，非开源。
