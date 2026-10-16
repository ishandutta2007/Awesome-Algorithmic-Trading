# Awesome-Algorithmic-Trading

## Top Algorithmic Trading Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Quantitative Strategy Development, Autonomous Agent Workflows & Production Execution*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Algorithmic Trading**. These tools enable developers and quantitative traders to design, backtest, and deploy automated trading strategies—from rule-based systems to increasingly sophisticated multi-agent LLM frameworks that mirror how real trading firms operate.



**Examples** include Alpaca, QuantConnect, TradingView, MetaTrader, Interactive Brokers, Tradovate, TradeStation, KuCoin API, TrendSpider, and Composer (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, backtesting, and autonomous trading agents—ideal for quantitative developers, traders, and researchers seeking transparent, vendor-independent infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global algorithmic trading market is valued at approximately **$18 billion to $20.2 billion** (projected to exceed $30B+ over the coming decade at a ~8–12% CAGR). The market exhibits a **moderately fragmented** structure across infrastructure and software tooling (with diverse niche SaaS platforms, charting vendors, and developer APIs competing), while execution and high-frequency liquidity provision remain highly concentrated among elite proprietary trading firms and institutional prime brokerages.

## SaaS/Hosted Platforms

| Platform | Valuation / Revenue Scale | Pricing | Free Tier Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Interactive Brokers](https://www.interactivebrokers.com/)** | **~$34B–$38B Market Cap** ($6.2B annual revenue) | $0/mo software fee ($0.005/share commissions, Pro/Lite tiers) | Free forever (Free TWS/Web/REST API access, non-consolidated Cboe One/IEX real-time US data, unlimited paper trading; funded account required for API execution) | Comprehensive multi-asset broker API for stocks, options, futures, and FX with TWS API, FIX connectivity, and Python/Java/C++ SDKs. |
| **[KuCoin API](https://www.kucoin.com/)** | **$10B Valuation** (Top-tier crypto exchange) | $0/mo platform fee (0.1% spot maker/taker fee, tiered by VIP level) | Free forever (Unrestricted REST & WebSocket market data access, VIP 0 baseline rate limits, free sandbox paper trading environment) | Crypto exchange API featuring spot, futures, and margin trading with WebSocket streaming endpoints and REST execution. |
| **[TradingView](https://www.tradingview.com/)** | **$3B+ Valuation** | Starts at $12.95/mo (Essential, billed annually) | Free forever (1 chart layout per tab, 2–5 indicators per chart, 10K historical bars, 1 watchlist of up to 30 symbols, ad-supported) | Premier charting and social platform with Pine Script for strategy prototyping, backtesting, and broker-integrated automated alerts. |
| **[NinjaTrader / Tradovate](https://www.tradovate.com/)** | **$1.5B Parent Valuation** ($115M Tradovate acquisition) | $0/mo Free Plan ($0.39/micro contract); or $99/mo | 14-day free trial ($50,000 simulated funds, full market replay, real-time futures data); $0/mo Free Plan for funded accounts with standard per-contract commissions | Cloud-based futures trading platform with REST API, automated order execution, simulated trading, and low-latency infrastructure. |
| **[Alpaca](https://alpaca.markets/)** | **$1.15B Valuation** ($60M–$100M+ ARR) | Starts at $99/mo (Algo Trader Plus); $0/mo standard | Free forever (200 REST API calls/min, 15-min delayed REST data, real-time IEX websocket stream capped at 30 concurrent symbols, unlimited paper trading) | Developer-first API brokerage offering commission-free stock and crypto trading with automated paper trading, market data streams, and Python/JS SDKs. |
| **[TradeStation](https://www.tradestation.com/)** | **Monex Group Subsidiary** (~$50M+ quarterly revenues) | $0/mo API platform fee ($10/mo inactivity fee if criteria unmet) | Free forever ($10/mo inactivity fee waived by maintaining $5,000 equity balance or 10 trades per 90 days; free desktop/web platform & API sandbox access) | Veteran brokerage with EasyLanguage engine, multi-timeframe backtesting, automated rule deployment, and institutional-grade market data. |
| **[MetaTrader](https://www.metatrader4.com/)** | **Est. $50M–$100M+ Annual Revenue** (Dominant FX infra) | $0/mo client terminal; Native VPS starts at $10–$15/mo | Free forever (Full MT4/MT5 desktop client terminal, MQL4/MQL5 strategy IDE, backtester with tick data simulation, and 24-hour native VPS trial) | The most widespread retail FX/CFD trading terminal supporting Expert Advisors (EAs) in MQL4/MQL5, strategy optimization, and automated VPS hosting. |
| **[Composer](https://www.composer.trade/)** | **SoFi Subsidiary** ($11.4M VC funding raised) | Starts at $10/mo (Advanced); $40/mo (Pro) | Free forever Starter Plan (1 automated live trading bot/strategy, unlimited backtesting, AI strategy builder, and community library access) | Next-generation no-code algorithmic trading platform with visual logic builder ("symphonies"), AI prompt-to-strategy generation, and automated execution. |
| **[QuantConnect](https://www.quantconnect.com/)** | **$9.7M Raised** (~$1M–$6M ARR) | Starts at $60/mo (Quant Researcher seat + compute) | Free forever (1 free `B-MICRO` backtesting node, max 200 backtests/day with 20-second queue delay, 32 KB IDE file limit; cloud live trading locked) | Institutional-grade open-source algorithmic trading engine (LEAN) with multi-asset cloud backtesting, 40+ datasets, and community strategy marketplace. |
| **[TrendSpider](https://trendspider.com/)** | **Private / Multi-Million ARR** | Starts at $54/mo (Standard, billed annually) | 14-day paid trial (Starts at $19 upfront, grants full access to multi-timeframe automated analysis, backtesting, and cloud alerts) | Automated technical analysis and algorithmic charting platform with multi-timeframe scanning, automated indicator recognition, and strategy backtesting. |



## Open-Source GitHub Projects



- **[TradingAgents (TauricResearch)](https://github.com/TauricResearch/TradingAgents)**  

  **The most rapidly adopted open-source multi-agent LLM financial trading framework** (Apache-2.0) . **109,232 GitHub stars** as of October 2026—one of the fastest-growing finance repositories in history . **The framework mirrors the dynamics of real-world trading firms** by deploying specialized LLM-powered agents: fundamental analysts, sentiment experts, technical analysts, trader, risk management team, and portfolio manager . **Analyst Team**: Fundamentals Analyst evaluates company financials, Sentiment Analyst gauges short-term market mood, News Analyst monitors global events, Technical Analyst uses MACD/RSI to detect patterns . **Researcher Team**: Bullish and bearish researchers critically assess analyst insights through **structured debates**—balancing potential gains against inherent risks . **Trader Agent** composes reports into informed trading decisions determining timing and magnitude . **Risk Management and Portfolio Manager** evaluates portfolio risk and approves/rejects transaction proposals . **Built with LangGraph** for flexibility and modularity . **Supports 10+ LLM providers**: OpenAI, Google, Anthropic, xAI, DeepSeek, Qwen, GLM, MiniMax, OpenRouter, Ollama (local), and Azure OpenAI . **Key innovation**: **Persistent decision log and reflection mechanism** —each completed run appends its decision to `~/.tradingagents/memory/trading_memory.md`, fetches realised return on next run, generates a reflection, and injects lessons into the Portfolio Manager prompt . **Point-in-time correctness** for SEC EDGAR filings—a run dated in the past reads statements exactly as they stood that day . **The reference implementation for multi-agent trading systems.**



- **[LEAN (QuantConnect)](https://github.com/QuantConnect/Lean)**  

  **The most comprehensive open-source algorithmic trading engine** (Apache-2.0) . **21,885 GitHub stars** . **Powers QuantConnect's cloud platform** with Python and C# support. Features **backtesting, live trading, and research** across equities, forex, crypto, futures, and options . **The standard open-source trading engine** for serious quantitative developers.



- **[Qlib (Microsoft)](https://github.com/microsoft/qlib)**  

  **AI-oriented quantitative investment platform** (MIT) . **49,180 GitHub stars** . **Aims to use AI tech to empower Quant Research** —from exploring ideas to implementing productions . Features **data processing, model training, backtesting, and portfolio management** . **The most comprehensive AI-native quant platform** from Microsoft Research.



- **[Freqtrade](https://github.com/freqtrade/freqtrade)**  

  **Free, open-source crypto trading bot** (GPL-3.0) . **54,878 GitHub stars** . **The most feature-rich open-source bot framework**: web UI, Telegram integration, Hyperopt for strategy optimization, and **100+ exchange support** via CCXT . **FreqAI** ships inside Freqtrade for ML trade signals with background retraining . **The standard for crypto algorithmic trading.**



- **[Backtrader](https://github.com/mementum/backtrader)**  

  **Python backtesting library for trading strategies** (GPL-3.0) . **23,407 GitHub stars** . Features **multiple data feeds, indicators, and strategy optimization** . **The most widely used Python backtesting framework** .



- **[VectorBT](https://github.com/polakowo/vectorbt)**  

  **The fastest backtesting engine for algorithmic trading** (Apache-2.0) . **9,284 GitHub stars** . **Run thousands of trading ideas before others finish one** —vectorized operations on NumPy/pandas. **The standard for high-performance parameter sweeps** .



- **[vnpy](https://github.com/vnpy/vnpy)**  

  **Python-based open-source quantitative trading platform** (MIT) . **45,626 GitHub stars** . **The most comprehensive Chinese-language quant framework** with support for futures, stocks, crypto, and options . Features **event-driven engine, CTA strategies, and spread trading** .



- **[ccxt](https://github.com/ccxt/ccxt)**  

  **Unified trading API for 100+ crypto exchanges** (MIT) . **44,211 GitHub stars** . **The foundation for most open-source crypto trading bots** —standardized interfaces across exchanges with rate limiting and reconnection handling.



- **[AI Hedge Fund](https://github.com/virattt/ai-hedge-fund)**  

  **AI Hedge Fund Team** (MIT) . **63,795 GitHub stars** . **Multi-agent framework with specialized agents** for different investment strategies . **The most popular open-source AI hedge fund implementation** .



- **[AlphaAgent](https://github.com/kamendula/AlphaAgent)**  

  **Leakage-aware (point-in-time) LLM trading agent** (open-source) . **Enforces PIT correctness at the tool boundary** —every input filtered to timestamp ≤ as-of date . **Two independent gates**: AI for qualitative call, rules for timing—never mixed . **Pipeline**: Pool → Filter → Agents (parallel specialists) → Entry (pure technical rules) . **Deterministic offline demo with zero keys** —`make demo` runs the whole chain on bundled snapshots .



### Additional Strong Open-Source Options



- **[Zipline](https://github.com/quantopian/zipline)** — Pythonic algorithmic trading library (Apache-2.0) . **20,136 GitHub stars** . The original Quantopian engine.

- **[FinRL](https://github.com/AI4Finance-Foundation/FinRL)** — Financial reinforcement learning (MIT) . **16,564 GitHub stars** . **The standard for RL-based trading research.**

- **[OpenBB](https://github.com/OpenBB-finance/OpenBB)** — Open Data Platform for analysts, quants and AI agents (AGPL-3.0) . **73,913 GitHub stars** . **The most comprehensive open-source financial data platform.**

- **[Kronos](https://github.com/shiyu-coder/Kronos)** — Foundation model for the language of financial markets (open-source) . **39,644 GitHub stars** .

- **[barter-rs](https://github.com/barter-rs/barter-rs)** — Rust framework for event-driven live-trading and backtesting (MIT) . **2,331 GitHub stars** .

- Community **n8n** workflows for trading signal routing and portfolio alerting.



**Frameworks for building custom systems**: Combine **TradingAgents** for multi-agent decision orchestration with **LEAN** or **Backtrader** for backtesting, **ccxt** for multi-exchange connectivity, **VectorBT** for high-performance parameter sweeps, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade algorithmic trading platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Algorithmic trading systems handling capital must follow security best practices and comply with applicable financial regulations.

- **TradingAgents is designed for research purposes, not financial advice.** The authors explicitly state: "Trading performance may vary based on many factors, including the chosen backbone language models, model temperature, trading periods, the quality of data, and other non-deterministic factors" . **It is not intended as financial, investment, or trading advice.**

- **Multi-agent architectures provide decision auditability.** Unlike single-model systems that output "buy" as a black box, TradingAgents provides a **decision audit chain**—every layer's reasoning, evidence, debate rounds, and risk assessment is traceable . **This transparency is the core value proposition.**

- **Point-in-time correctness is critical for backtesting validity.** LLM trading agents are especially vulnerable to lookahead bias—model weights already encode future events, and live tools return post-date data. **AlphaAgent enforces PIT correctness at the tool boundary** and bounds the model's parametric memory . **Without this discipline, backtest results are fantasy.**

- Self-hosted open-source solutions require proper security hardening, API key management, and ongoing maintenance. **Trading systems can lose money rapidly**—paper trade extensively before deploying capital.



---



**Made for quantitative developers, algorithmic traders, and researchers building transparent trading systems.**  

Let's make Algorithmic Trading more open, data-driven, and auditable.
