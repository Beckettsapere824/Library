# AI Learning — Machine Learning, Deep Learning & Beyond

Main learning catalog under Artificial Intelligence. Covers classical ML, deep learning, modern LLM practice, and related paths. Expand continuously.
人工智能下的主学习目录：经典机器学习、深度学习、现代 LLM 实践及相关路径。持续补充。

Prefer free / audit-friendly sources. Build a small project between stages.
优先免费或可旁听资源。每阶段之间做小项目。

Related: [ML-Practice](ML-Practice.md) · [LLM-Learning](LLM-Learning.md)

---

## Suggested order / 建议顺序

1. **Classical ML** (vocabulary + simple models)  
2. **Deep learning** (networks, train loop, one domain: CV or tabular)  
3. **From-scratch intuition** (Karpathy / micrograd-style)  
4. **Modern stack** (Hugging Face, practical transformers)  
5. **Specialize** (RL, agents, quant ML — only after honest baselines)

1. 经典 ML → 2. 深度学习 → 3. 手写直觉 → 4. 现代栈 → 5. 专项（RL / Agent / 量化 ML）

---

## 1. Classical machine learning / 经典机器学习

### [Google — Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)

Short, free, official intro to core ML vocabulary and TensorFlow-oriented practice.
免费、官方、偏短的核心 ML 词汇与 TensorFlow 向练习。

**Value:** Fast shared language before longer specializations.
**价值：** 在长专项之前快速建立共同语言。

### [Kaggle Learn — Intro / Intermediate ML](https://www.kaggle.com/learn)

Bite-sized, hands-on micro-courses with free certificates on real datasets.
短小动手微课，真实数据集，可拿免费证书。

**Value:** Lowest friction from “watched a video” to “ran a model”.
**价值：** 从「看过视频」到「跑过模型」摩擦最低。

### [Andrew Ng — Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction) (Coursera; audit)

Still the default structured fundamentals path (supervised learning, best practices).
仍是默认的结构化基础路径（监督学习与实践要点）。

**Value:** Interview- and industry-recognized baseline.
**价值：** 面试与业界都认的基础线。

### [Stanford CS229](https://cs229.stanford.edu/) (notes / materials)

Math-heavier classical ML reference when you outgrow crash courses.
超出速成课后的偏数学经典 ML 参考。

**Value:** Depth without a paid bootcamp.
**价值：** 无需付费训练营也能加深。

---

## 2. Deep learning / 深度学习

### [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/)

Top-down: train strong models early, then unpack how; free videos + notebooks + book.
自上而下：先训出强模型再拆解原理；免费视频、Notebook 与书。

**Value:** Best practical builder path; pairs well with math-first courses.
**价值：** 最佳动手建造路径；可与数学优先课程互补。

### [DeepLearning.AI — Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) (Andrew Ng; audit)

Systematic neural nets, CNNs, sequence models; long but complete.
系统化神经网络、CNN、序列模型；长但完整。

**Value:** Standard depth track when you want structure and certificates option.
**价值：** 要结构与可选证书时的标准深度轨道。

### [MIT 6.S191 — Introduction to Deep Learning](https://introtodeeplearning.com/)

Annual MIT intro with lectures and labs; free materials.
MIT 年度深度学习入门，讲座与实验；材料免费。

**Value:** University-paced survey in a short intensive format.
**价值：** 大学节奏的短平快总览。

### [Stanford CS231n](http://cs231n.stanford.edu/) (notes + assignments)

Flagship deep learning for computer vision; implement before heavy library use.
计算机视觉深度学习王牌课；先实现再重度用库。

**Value:** CV path and assignment discipline that transfers to other domains.
**价值：** CV 路径与作业纪律可迁移到其他领域。

### [Dive into Deep Learning (d2l.ai)](https://d2l.ai/)

Interactive textbook (multi-framework) — read, run, modify.
可交互教材（多框架）——读、跑、改。

**Value:** Textbook + runnable code in one place.
**价值：** 教材与可运行代码合一。

---

## 3. From-scratch & internals / 手写与内部机制

### [Andrej Karpathy — Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html)

Build from neurons to a GPT-style model in code; widely treated as the internals path.
从神经元写到类 GPT 模型；普遍视为内部机制路径。

**Value:** Removes “framework magic”; essential before serious LLM work.
**价值：** 去掉「框架魔法」；认真做 LLM 前几乎必经。

### Labs in this library

- [ML-From-Scratch](ML-Practice.md#1-eriklindernorenml-from-scratch) — pure NumPy algorithms  
- [machine-learning-experiments](ML-Practice.md#2-trekhlebmachine-learning-experiments) — train + browser demo  

**Value:** Reinforce courses with implementations you can read end-to-end.
**价值：** 用可读完的实现巩固课程。

---

## 4. Modern NLP / LLM stack / 现代 NLP · LLM 栈

### [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course)

Practical transformers, fine-tuning, and ecosystem tooling in the browser-friendly style.
实用 Transformer、微调与生态工具，偏可动手。

**Value:** Default open-source LLM engineering on-ramp.
**价值：** 开源 LLM 工程默认上车点。

### [Hugging Face — Deep RL Course](https://huggingface.co/learn/deep-rl-course)

Hands-on reinforcement learning units when you need RL, not only supervised nets.
需要强化学习（而不只是监督网络）时的动手单元。

**Value:** RL without jumping straight into opaque research code.
**价值：** 不必直接跳进晦涩研究代码也能碰 RL。

### See also

- [LLM-Learning.md](LLM-Learning.md) in this folder  
- Stanford CS224N (NLP with Deep Learning) materials when specializing in language  

---

## 5. What to delay / 可延后

- Heavy **quant ML** until you can backtest a simple rule without leakage ([Quant Finance](../Quant%20Finance/)).  
- **Agent frameworks** before you can train/fine-tune or at least evaluate a baseline model.  
- Collecting every course instead of finishing one path + one project.

- 不会诚实回测前，先少碰重型量化 ML。  
- 不会评估基线模型前，先少堆 Agent 框架。  
- 不要收集课程清单替代「一条路径 + 一个项目」。

---

## Expansion backlog / 后续可补

- Reinforcement learning depth (Sutton & Barto + clean codebases)  
- Evaluation / alignment short courses (DeepLearning.AI free shorts)  
- Vision-language and multimodal practical tracks  
- Chinese-language lecture mirrors where quality matches  
