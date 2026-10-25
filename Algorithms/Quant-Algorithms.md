# Quant Algorithms

Algorithms and methods for **systematic trading research** — not LeetCode. Starter set; expand with factors, execution, and microstructure later.
面向**系统化交易研究**的算法与方法——不是 LeetCode。起步集；因子、执行与微观结构后续再补。

Pair with [Quant Finance](../Quant%20Finance/) engines and [Beginner Path](../Quant%20Finance/Beginner-Path.md).
与 [Quant Finance](../Quant%20Finance/) 引擎及 [Beginner Path](../Quant%20Finance/Beginner-Path.md) 一起用。

---

## 1. Strategy families (learn the logic first) / 策略族（先懂逻辑）

| Family | What you are computing | Typical failure mode |
|--------|------------------------|----------------------|
| Trend / momentum | Persistence of returns over a horizon | Regime change, costs |
| Mean reversion | Distance from equilibrium / residual | Structural break |
| Stat-arb / pairs | Cointegration or residual spreads | Relationship dies |
| Market making | Inventory + adverse selection | Latency & queue |
| Vol / options | Surface dynamics, hedges | Model risk |

**Value:** Naming the family stops random indicator shopping.
**价值：** 先定策略族，避免乱堆指标。

---

## 2. Core algorithmic skills / 核心算法技能

### Signal → portfolio → risk

1. **Signal construction** — clean features, no leakage, horizon aligned with holding period.  
2. **Portfolio mapping** — weights, constraints, turnover penalty.  
3. **Risk** — volatility targeting, drawdown rules, exposure limits.  
4. **Execution-aware backtest** — fees, slippage, latency assumptions stated explicitly.

1. 信号 → 2. 组合映射 → 3. 风险 → 4. 含成本的回测（假设写清楚）。

### Research hygiene algorithms

- Walk-forward / purged CV for time series  
- Multiple-testing awareness (deflated Sharpe, etc.)  
- Simple baselines (buy-and-hold, equal weight) before complex models  

**Value:** Most “alpha” dies under correct validation, not under a fancier model.
**价值：** 多数「alpha」死在验证方式，而不是死在模型不够花。

---

## 3. Learning resources (starter) / 学习资源（起步）

### [QuantStart](https://www.quantstart.com)

Articles on backtesting pitfalls and systematic workflow.
回测陷阱与系统化工作流文章。

**Value:** Written craft for algo trading without hype.
**价值：** 少炒作的算法交易文字工艺。

### [stefan-jansen/machine-learning-for-trading](https://github.com/stefan-jansen/machine-learning-for-trading)

End-to-end ML-for-trading workflow code (data → research → execution-oriented chapters).
端到端「机器学习用于交易」工作流代码（数据 → 研究 → 偏执行章节）。

**Value:** Shows how ML sits *inside* a trading research pipeline, not as a standalone Kaggle score.
**价值：** 展示 ML 如何嵌在交易研究流水线里，而不是孤立刷分。

### Books (when ready)

- Ernest Chan — *Quantitative Trading* / *Algorithmic Trading* (practitioner strategy process)  
- López de Prado — *Advances in Financial Machine Learning* (research design, labels, CV) — advanced  

**Value:** Process and research design beat copying strategy pseudocode.
**价值：** 流程与研究设计比抄策略伪代码重要。

### In this library

- [Trading-and-Finance-Repos](../Quant%20Finance/Trading-and-Finance-Repos.md) — implement and stress-test ideas  
- [Quant-Trading-Resources](../Quant%20Finance/Quant-Trading-Resources.md) — papers and platforms  

---

## 4. What not to do early / 早期不要做的

- Optimize hundreds of parameters on one asset  
- Use future information in features  
- Skip transaction costs  
- Jump to deep RL before a linear baseline works  

- 单品种上狂调参  
- 特征里混进未来信息  
- 忽略成本  
- 线性基线都没有就上深度 RL  

---

## Expansion backlog / 后续可补

- Factor models & attribution  
- Execution algorithms (TWAP/VWAP, Almgren–Chriss intuition)  
- Order-book / HFT algorithm sketches (with [hftbacktest](../Quant%20Finance/Trading-and-Finance-Repos.md))  
- Explicit checklist templates for research logs  
