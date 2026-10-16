# Awesome-Algorithmic-Trading

# Top Algorithmic Trading Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Quantitative Strategy Development, Autonomous Agent Workflows & Production Execution*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Algorithmic Trading**. These tools enable developers and quantitative traders to design, backtest, and deploy automated trading strategies—from rule-based systems to increasingly sophisticated multi-agent LLM frameworks that mirror how real trading firms operate.

**Examples** include Alpaca, QuantConnect, TradingView, MetaTrader, Interactive Brokers, Tradovate, TradeStation, KuCoin API, TrendSpider, and Composer (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, backtesting, and autonomous trading agents—ideal for quantitative developers, traders, and researchers seeking transparent, vendor-independent infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Alpaca](https://alpaca.markets/)**  
  API-first brokerage with commission-free stock and crypto trading. Features **Paper Trading API** for strategy testing, **market data streams**, and **Python/JavaScript SDKs**. **The most developer-friendly brokerage** for algorithmic trading.

- **[QuantConnect](https://www.quantconnect.com/)**  
  **The largest open-source algorithmic trading platform** with cloud backtesting and live trading across multiple brokers. Features **LEAN engine**, **data from 40+ sources**, and **community strategies**.

- **[TradingView](https://www.tradingview.com/)**  
  Charting and social platform with **Pine Script** for strategy development. Features **backtesting**, **alerts**, and **broker integrations**.

- **[MetaTrader](https://www.metatrader4.com/)**  
  **The most widely used retail trading platform** with **MQL4/MQL5** for expert advisors. Features **backtesting**, **optimization**, and **VPS hosting**.

- **[Interactive Brokers](https://www.interactivebrokers.com/)**  
  **The most comprehensive broker API** for stocks, options, futures, and forex. Features **TWS API**, **FIX connectivity**, and **Python/Java/C++ SDKs**.

- **[Tradovate](https://www.tradovate.com/)**  
  Futures trading platform with **API access** for algorithmic trading. Features **backtesting**, **simulated trading**, and **low-latency execution**.

- **[TradeStation](https://www.tradestation.com/)**  
  Brokerage with **EasyLanguage** for strategy development. Features **backtesting**, **automation**, and **market data**.

- **[KuCoin API](https://www.kucoin.com/)**  
  Crypto exchange API with **spot, futures, and margin trading**. Features **WebSocket streams** and **REST endpoints**.

- **[TrendSpider](https://trendspider.com/)**  
  Automated technical analysis platform with **backtesting**, **strategy builder**, and **multi-timeframe analysis**.

- **[Composer](https://www.composer.trade/)**  
  No-code algorithmic trading platform with **symphony** strategy builder. Features **automated execution** and **backtesting**.

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
