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

Hi, I'm Huaiyu Jia (贾怀宇), a third-year Ph.D. student in the FinTech Thrust at [The Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/), advised by [Dr. Shuo Sun](https://scholar.google.com/citations?user=kGgWv8IAAAAJ&hl=zh-CN). Before that, I received my bachelor's degree from the School of Information and Software Engineering at [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/), where I had the opportunity to work with [Prof. Dajiang Chen](https://yjsjy.uestc.edu.cn/gmis/jcsjgl/dsfc/dsgrjj/20218?yxsh=09).

My research interests lie primarily in AI for Blockchain (AI4Blockchain). In particular, I am interested in combining artificial intelligence with blockchain systems to analyze complex on-chain data, understand on-chain behaviors, and enable more intelligent and reliable on-chain decision-making and interactions. I am also broadly interested in AI agents, on-chain finance, and autonomous blockchain systems.

Beyond research, I actively participate in blockchain and AI hackathons. I particularly enjoy turning research ideas into working systems, especially prototypes that connect AI agents with on-chain data, payments, and executable blockchain workflows.

# 🔥 News

- *2026.10*: **TxSum** accepted at **EMNLP 2026** (October 24–29). [Paper](https://arxiv.org/abs/2512.06933)
- *2026.09*: **AlphaOpsBench**: Benchmarking End-to-End Alpha Strategy Operationalization in Prediction Markets. [Paper](https://arxiv.org/abs/2609.31390)
- *2026.08*: **Towards Event-Aware Forecasting in DeFi** accepted at **KDD 2026** (August 9–13). [Paper](https://arxiv.org/abs/2604.20374)
- *2026.08*: AlphaForgeBench, a benchmark that asks language models to write executable trading strategies, at **KDD 2026** (August 9–13). [Paper](https://arxiv.org/abs/2602.18481)
- *2026.04*: **Unlocking the Forecasting Economy: A Suite of Datasets for the Full Lifecycle of Prediction Market: [Experiments & Analysis]**. [Paper](https://arxiv.org/abs/2604.20421) / [Project](https://www.polymonitor.club/)
- *2024.11*: **FS2M** published in the *International Journal of Web Information Systems*. [Paper](https://doi.org/10.1108/IJWIS-06-2024-0169)

<span class='anchor' id='publications'></span>

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/publications/alphaops.png' alt="AlphaOpsBench" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

AlphaOpsBench: Benchmarking End-to-End Alpha Strategy Operationalization in Prediction Markets

**Huaiyu Jia**, Mingxuan Zhao, Jincheng Gao, Zifan Peng, Wentao Zhang, Siguang Li, Shuo Sun

[**Paper**](https://arxiv.org/abs/2609.31390)

- Tests whether a language model can turn a coarse prediction-market idea into an auditable executable program.
- Built on 581 source-preserving strategy records and a lifecycle-scale Polymarket dataset, comparing direct generation with a staged design-then-code protocol.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/publications/forecasting.png' alt="Forecasting Economy" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Unlocking the Forecasting Economy: A Suite of Datasets for the Full Lifecycle of Prediction Market: [Experiments & Analysis]

**\*Huaiyu Jia**, \*Luofeng Zhou, Wentao Zhang, Lin William Cong, Siguang Li, Shuo Sun

[**Paper**](https://arxiv.org/abs/2604.20421) | [**Code**](https://github.com/virusLuke3/polymonitor) | [**Project**](https://www.polymonitor.club/)

- A continuously synchronized Polymarket lifecycle dataset from October 2020 onward: 3.29 million markets, 1.90 billion fills, and 21 million oracle events.
- Experiments cover NBA calibration, CPI expectation reconstruction, and resolution prediction. The public interface is [PolyMonitor](https://www.polymonitor.club/). Huaiyu Jia and Luofeng Zhou contributed equally.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2026</div><img src='images/publications/amm.png' alt="Event-aware AMM forecasting" width="100%"></div></div>
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2026</div><img src='images/publications/txsum.png' alt="TxSum" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

TxSum: User-Centered Ethereum Transaction Understanding with Micro-Level Semantic Grounding

Zifan Peng, Jingyi Zheng, Yule Liu, **Huaiyu Jia**, Qiming Ye, Jingyu Liu, Xufeng Yang, Mingchen Li, Qingyuan Gong, Xuechao Wang, Xinlei He

[**Paper**](https://arxiv.org/abs/2512.06933)

- A token-flow explanation task for complex Ethereum transactions, built from user interviews.
- MATEX, a multi-agent framework that checks explanations against raw traces before showing them to users.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/publications/dao.png' alt="DAO-SIM overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

From Anonymous Wallets to Behavioral Agents: A Calibrated Policy Test Bed for DAO Governance

Peizhe Li, **Huaiyu Jia**, Liang Zhang, Shuo Sun

[**Code**](https://github.com/virusLuke3/DAO-Simulation)

- DAO-SIM builds heterogeneous behavioral agents from anonymous on-chain transfers, then simulates token flows with profile-level super agents and wallet-level child agents.
- On more than 3 million Uniswap transactions, it reproduces the whale effect, path dependence, and the rich-get-richer effect, and tests counterfactual governance policies.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJWIS 2025</div><img src='images/publications/fs2m.png' alt="FS2M" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

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
- **[Deep AMM Events](https://github.com/finbrain-lab-hkustgz/Deep-AMM-Events)**. Code and preprocessed data for event-aware forecasting on four AMM protocols. [Poster](https://finbrain-lab-hkustgz.github.io/Deep-AMM-Events/) / [Paper](https://arxiv.org/abs/2604.20374)
- **[Market Data](https://github.com/SuperPolyrio/market-data)**. Acquisition engine for Polymarket markets, OrderFilled trades, and oracle events.
- **[Paper Trading](https://github.com/SuperPolyrio/paper-trading)**. Polymarket paper-trading system with taker and maker execution, accounts, risk, and a public API.
- **[Backtest Lab](https://github.com/SuperPolyrio/backtest-lab)**. Replay lab for Polymarket order-fill, trade-only, and L2 backtests.

<span class='anchor' id='hackathons'></span>

# 🏆 Hackathon Projects

- **[POT-402 Gateway](https://github.com/virusLuke3/pot-402-gateway)** — *Portaldot Online Mini Hackathon S1*.  
  A Portaldot-native HTTP 402 gateway that turns native POT transfers into verifiable access receipts for pay-per-call APIs. The prototype demonstrates a complete challenge → payment → receipt verification → premium API unlock flow, and exposes the payment proof as a reusable primitive for downstream services.

- **[OmniYield](https://github.com/virusLuke3/OmniYield)** — *LI.FI Vibeathon*.  
  A multi-agent framework for cross-chain yield monitoring and execution that combines on-chain market sensing, risk-adjusted yield selection, and LI.FI MCP/quote routing. The system separates sensing, decision-making, and execution so that cross-chain rebalancing decisions can be explained and previewed before transactions are broadcast.

- **[SkillTip](https://github.com/virusLuke3/skillTip)** — *Hackathon Galactica — WDK / Tipping Bot track*.  
  An autonomous reward agent that discovers reusable AI skills, evaluates their utility and reuse signals, and settles rewards in Sepolia USDT through Tether WDK. It combines policy-constrained AI judging, a self-custodial treasury, pending-claim handling, and an auditable on-chain payout ledger.

- **[AutoScholar](https://github.com/virusLuke3/x402-research)** — *Stacks x402 hackathon project*.  
  A research molbot network that quotes premium research workflows, issues machine-readable x402 payment challenges, verifies Stacks testnet settlement, and releases both human-readable research dossiers and structured handoff packets for downstream agents.

<span class='anchor' id='education'></span>

# 📖 Education

- *2024.09 - Present*, **Ph.D. in FinTech**, [The Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/).
- *2020.09 - 2024.06*, **B.Eng.**, School of Information and Software Engineering, [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/).
