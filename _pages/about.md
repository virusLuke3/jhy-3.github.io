---
permalink: /
title: ""
excerpt: "Huaiyu Jia is a Ph.D. student at HKUST(GZ), working on AI for Blockchain, on-chain data analytics, AI agents, and on-chain finance."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

Hi, I'm Huaiyu Jia (贾怀宇), a third-year Ph.D. student in the FinTech Thrust at [The Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/), advised by Dr. Shuo Sun. Before that, I received my bachelor's degree from the School of Information and Software Engineering at [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/), where I had the opportunity to work with [Prof. Dajiang Chen](https://yjsjy.uestc.edu.cn/gmis/jcsjgl/dsfc/dsgrjj/20218?yxsh=09).

My research interests lie primarily in AI for Blockchain (AI4Blockchain). In particular, I am interested in combining artificial intelligence with blockchain systems to analyze complex on-chain data, understand on-chain behaviors, and enable more intelligent and reliable on-chain decision-making and interactions. I am also broadly interested in AI agents, on-chain finance, and autonomous blockchain systems.

Beyond research, I am an enthusiastic participant in hackathons and technical competitions. I especially enjoy turning research ideas into working systems and interactive prototypes.

# 🔥 News

- *2026.04*: Preprint on a full-lifecycle dataset for Polymarket, from market creation through oracle settlement. [Paper](https://arxiv.org/abs/2604.20421) / [Project](https://www.polymonitor.club/)
- *2026.04*: Preprint on event-aware forecasting over 8.9 million on-chain events from Pendle, Uniswap v3, Aave, and Morpho. [Paper](https://arxiv.org/abs/2604.20374)
- *2026.02*: AlphaForgeBench, a benchmark that asks language models to write executable trading strategies, to appear at **KDD 2026**. [Paper](https://arxiv.org/abs/2602.18481)
- *2025.12*: TxSum preprint on user-centered explanations of Ethereum transactions. [Paper](https://arxiv.org/abs/2512.06933)
- *2024.11*: **FS2M** published in the *International Journal of Web Information Systems*. [Paper](https://doi.org/10.1108/IJWIS-06-2024-0169)

<span class='anchor' id='publications'></span>

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/publications/forecasting.png' alt="Forecasting Economy" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Unlocking the Forecasting Economy: A Suite of Datasets for the Full Lifecycle of Prediction Market

**\*Huaiyu Jia**, \*Luofeng Zhou, Wentao Zhang, Lin William Cong, Siguang Li, Shuo Sun

[**Paper**](https://arxiv.org/abs/2604.20421) | [**Code**](https://github.com/virusLuke3/polymonitor) | [**Project**](https://www.polymonitor.club/)

- A continuously maintained relational dataset of Polymarket, covering market metadata, fill-level trades, and oracle resolution from October 2020 to March 2026.
- The public interface is [PolyMonitor](https://www.polymonitor.club/). Huaiyu Jia and Luofeng Zhou contributed equally.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/publications/amm.png' alt="Event-aware AMM forecasting" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Towards Event-Aware Forecasting in DeFi: Insights from On-chain Automated Market Maker Protocols

**Huaiyu Jia**, Jiehshun You, Yizhi Luo, Jingyu Liu, Shuo Sun

[**Paper**](https://arxiv.org/abs/2604.20374) | [**Code**](https://github.com/yosen-king/Deep-AMM-Events)

- 8.9 million annotated on-chain events from Pendle, Uniswap v3, Aave, and Morpho, with transaction type and block-height timestamps.
- An uncertainty-weighted loss that reduces event-time error while keeping event-type accuracy.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2026</div><img src='images/publications/alphaforge.png' alt="AlphaForgeBench" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

AlphaForgeBench: Benchmarking End-to-End Trading Strategy Design with Large Language Models

Wentao Zhang, Mingxuan Zhao, Jincheng Gao, Jieshun You, **Huaiyu Jia**, Yilei Zhao, Bo An, Shuo Sun

[**Paper**](https://arxiv.org/abs/2602.18481) | [**Code**](https://github.com/finbrain-lab-hkustgz/AlphaForgeBench)

- Evaluates language models as quantitative researchers who write executable alpha factors and trading strategies.
- Separates financial reasoning from brittle step-by-step trade execution, then backtests the generated strategies.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/publications/txsum.png' alt="TxSum" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

TxSum: User-Centered Ethereum Transaction Understanding with Micro-Level Semantic Grounding

Zifan Peng, Jingyi Zheng, Yule Liu, **Huaiyu Jia**, Qiming Ye, Jingyu Liu, Xufeng Yang, Mingchen Li, Qingyuan Gong, Xuechao Wang, Xinlei He

[**Paper**](https://arxiv.org/abs/2512.06933)

- A token-flow explanation task for complex Ethereum transactions, built from user interviews.
- MATEX, a multi-agent framework that checks explanations against raw traces before showing them to users.

</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

FS2M: Fuzzy Smart IoT Device Pairing Protocol via Speak to Microphone

**Huaiyu Jia**, Dajiang Chen, Zhidong Xie, Zhiguang Qin

*International Journal of Web Information Systems, 2025*

[**Paper**](https://doi.org/10.1108/IJWIS-06-2024-0169)

- Pairs nearby IoT devices from ambient speech, so devices that hear a similar environment can agree on a key.
- Instantiates the pairing with an elliptic-curve asymmetric fuzzy encapsulation, AFEM-ECC.

</div>
</div>

<span class='anchor' id='projects'></span>

# 🛠 Projects

- **[PolyMonitor](https://www.polymonitor.club/)**. A live workspace on the Polymarket lifecycle data: prices, fills, oracle events, and macro context. [Code](https://github.com/virusLuke3/polymonitor)
- **[AlphaForgeBench](https://github.com/finbrain-lab-hkustgz/AlphaForgeBench)**. Benchmark and backtest harness for language models that synthesize executable trading strategies. [Paper](https://arxiv.org/abs/2602.18481)
- **[Deep AMM Events](https://github.com/yosen-king/Deep-AMM-Events)**. Code and preprocessed data for event-aware forecasting on four AMM protocols. [Paper](https://arxiv.org/abs/2604.20374)

<span class='anchor' id='education'></span>

# 📖 Education

- *2024.09 - Present*, **Ph.D. in FinTech**, [The Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/).
- **B.Eng.**, School of Information and Software Engineering, [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/).
