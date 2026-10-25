# Quant Finance — Beginner Path

A curated on-ramp from zero to a first coherent quant toolkit.
从零到第一套完整量化工具箱的入门路径。

Order: **Math → Markets & products → Core quant texts/courses → Code practice**.
顺序：**数学 → 市场与产品 → 核心量化教材/课程 → 代码实践**。

Prefer free or audit-friendly sources; paid books are listed only when they are industry defaults.
优先免费或可旁听资源；付费书仅在其为行业默认时列出。

Not investment advice.
非投资建议。

---

## 1. Mathematics foundations / 数学基础

You need working fluency in probability, calculus intuition, and linear algebra — not a pure-math PhD.
需要概率、微积分直觉与线性代数的可用熟练度，而非纯数博士水平。

### Probability & statistics / 概率与统计

- **[Harvard Stat 110 — Introduction to Probability](https://stat110.cs.harvard.edu/)** (Blitzstein; lectures + free book online)
  Gold-standard probability course for quant interviews and models.
  面向量化面试与建模的概率金标准课程。

- **[Khan Academy — Probability & Statistics](https://www.khanacademy.org/math/statistics-probability)**
  Fast repair for gaps before Stat 110 or applied work.
  在进入 Stat 110 或应用工作前快速补缺。

### Calculus intuition / 微积分直觉

- **[3Blue1Brown — Essence of Calculus](https://www.3blue1brown.com/topics/calculus)**
  Visual derivatives, integrals, chain rule — enough for Greeks and continuous models later.
  可视化导数、积分、链式法则——后续理解 Greeks 与连续模型足够。

### Linear algebra / 线性代数

- **[3Blue1Brown — Essence of Linear Algebra](https://www.3blue1brown.com/topics/linear-algebra)**
  Vectors, matrices, eigenvectors as geometry; maps directly to portfolios and factors.
  向量、矩阵、特征向量的几何视角；直接对应组合与因子。

- **[MIT 18.06 Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)** (Gilbert Strang, OCW)
  Classic full course when you want more than the essence series.
  需要比精华系列更深时的经典完整课程。

### Math applied to finance (bridge course) / 金融中的数学（衔接课）

- **[MIT 18.642 — Topics in Mathematics with Applications in Finance](https://ocw.mit.edu/courses/18-642-topics-in-mathematics-with-applications-in-finance-fall-2024/)** (Fall 2024 OCW)
  Linear algebra, probability, stochastic processes, and numerical methods mixed with industry finance lectures; free videos and problem sets.
  线性代数、概率、随机过程与数值方法，穿插业界金融讲座；免费视频与习题。

**Value:** Builds the math layer every pricing, risk, and research workflow assumes.
**价值：** 搭建定价、风险与研究流程都默认具备的数学层。

---

## 2. Finance & markets foundations / 金融与市场基础

Learn products and market language before heavy models.
在上重模型之前先学产品与市场语言。

### Markets & trading vocabulary / 市场与交易词汇

- **[Zerodha Varsity](https://zerodha.com/varsity/)**
  Free, structured modules on markets, products, technical and fundamental basics; widely recommended as a beginner finance track.
  免费结构化模块，覆盖市场、产品、技术与基本面入门；常被推荐为金融入门路径。

- **[Yale — Financial Markets (Coursera / open materials)](https://www.coursera.org/learn/financial-markets-global)** (Robert Shiller)
  Broad intro to institutions, risk, behavioral themes, and the role of finance.
  制度、风险、行为主题与金融角色的宏观入门。

### Corporate finance & valuation / 公司金融与估值

- **[Aswath Damodaran — Valuation lectures](https://pages.stern.nyu.edu/~adamodar/New_Home_Page/webcast.htm)** (NYU Stern, free)
  Definitive free course on valuation and corporate finance intuition.
  估值与公司金融直觉的权威免费课程。

### Products for quant work / 量化工作相关产品

Focus next on: stocks, bonds (price/yield, duration), forwards/futures, options payoffs, basic swaps.
接下来重点：股票、债券（价格/收益率、久期）、远期/期货、期权损益、基础互换。

**Value:** You cannot model what you cannot name; this section is the shared language with traders and risk.
**价值：** 说不出名字就无法建模；本节是与交易员和风控的共同语言。

---

## 3. Core quant finance entry / 核心量化入门

### Textbook (industry default) / 教材（行业默认）

- **John C. Hull — *Options, Futures, and Other Derivatives***
  See this library’s note: [Hull-Options-Futures-and-Other-Derivatives.md](Hull-Options-Futures-and-Other-Derivatives.md).
  见本库笔记：[Hull-Options-Futures-and-Other-Derivatives.md](Hull-Options-Futures-and-Other-Derivatives.md)。

  Shared vocabulary: forwards, swaps, Black–Scholes, Greeks, vol surfaces.
  共同词汇：远期、互换、Black–Scholes、Greeks、波动率曲面。

### Gentler first pass (optional) / 更温和的第一遍（可选）

- **Paul Wilmott — *Paul Wilmott Introduces Quantitative Finance***
  More conversational path through similar ground before or alongside Hull.
  在 Hull 之前或并行、更口语化的同主题路径。

### Free university-style courses / 免费大学风格课程

- **[Columbia — Financial Engineering and Risk Management](https://www.coursera.org/learn/financial-engineering-1)** (Coursera; audit)
  Part I: options and Black–Scholes basics; Part II: portfolio and risk themes.
  第一部分：期权与 Black–Scholes 基础；第二部分：组合与风险主题。

- **[MIT 18.642](https://ocw.mit.edu/courses/18-642-topics-in-mathematics-with-applications-in-finance-fall-2024/)** again for applied math + finance in one place.
  再次推荐作为「应用数学 + 金融」合一入口。

**Value:** Moves from product literacy to pricing and risk language used on desks and in interviews.
**价值：** 从产品素养进入交易台与面试使用的定价与风险语言。

---

## 4. Programming & practice / 编程与实践

### Python for data / 数据向 Python

- Official tutorial + **NumPy / pandas** on real price series (returns, rolling vol, simple plots).
  官方教程 + 在真实价格序列上使用 **NumPy / pandas**（收益、滚动波动、简单作图）。

- Optional: material already in this library under Software Engineering (e.g. CS50 Python track).
  可选：本库 Software Engineering 下的材料（如 CS50 Python）。

### Algorithmic trading sandbox / 算法交易沙箱

- **[QuantConnect](https://www.quantconnect.com/)** (Lean engine; free tier + Boot Camp)
  Browser IDE, data, backtests; practical path to code a first strategy without building infra.
  浏览器 IDE、数据与回测；无需自建基础设施即可写第一个策略。

- **[QuantConnect/Lean](https://github.com/QuantConnect/Lean)**
  Open-source engine behind the platform; read when you care how production-style event engines work.
  平台背后的开源引擎；关心生产级事件引擎时再读。

### Hands-on free labs / 动手免费实验

- **[WorldQuant University — Applied Data Science Lab](https://www.wqu.edu/)** (free certificate tracks)
  Project-based data science with financial datasets; good portfolio practice.
  基于金融数据集的项目制数据科学；适合作品集练习。

**Value:** Turns reading into reproducible experiments; quant jobs are coding jobs.
**价值：** 把阅读变成可复现实验；量化工作本质是编程工作。

---

## 5. Suggested sequence (rough) / 建议顺序（粗略）

1. 3Blue1Brown calculus + linear algebra essences → start Stat 110 or Khan probability.
   3Blue1Brown 微积分与线性代数精华 → 开始 Stat 110 或 Khan 概率。
2. Zerodha Varsity (or equivalent) + Damodaran overview of valuation language.
   Zerodha Varsity（或同类）+ Damodaran 估值语言概览。
3. Hull (selected chapters) and/or Columbia FERM audit + MIT 18.642 videos as capacity allows.
   Hull（选章）和/或旁听 Columbia FERM + 有余力时看 MIT 18.642。
4. Python + QuantConnect Boot Camp: one simple backtest end-to-end.
   Python + QuantConnect Boot Camp：完整跑通一个简单回测。
5. Return to this library’s [Trading-and-Finance-Repos.md](Trading-and-Finance-Repos.md) for engines and advanced stacks.
   再回到本库 [Trading-and-Finance-Repos.md](Trading-and-Finance-Repos.md) 看引擎与进阶栈。

---

## 6. What to skip early / 早期可先跳过

- Full stochastic calculus (Shreve Vol II) until Hull + probability feel solid.
  在 Hull 与概率扎实前，先不要硬啃完整随机微积分（Shreve 第二卷）。
- HFT microstructure and production engines (see nautilus / hftbacktest later).
  高频微观结构与生产引擎（之后再看 nautilus / hftbacktest）。
- Heavy ML-for-finance before you can backtest a simple rule honestly.
  在能诚实回测简单规则之前，先不要堆大量金融 ML。

---

## Related in this library / 本库相关

- [Hull note](Hull-Options-Futures-and-Other-Derivatives.md)
- [Trading & Finance repos](Trading-and-Finance-Repos.md)
- Software Engineering: CS50 / Python courses
- Pure Mathematics: placeholder for deeper pure-math tracks
