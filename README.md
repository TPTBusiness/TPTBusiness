# Trading Prediction Technology · TPTBusiness

> Building AI-powered trading systems — from autonomous factor discovery to local LLM inference.  
> Supporter of open-source software and the communities that build it.

---

## 🚀 Main Project — Predix

<table>
<tr>
<td width="60%">

**[Predix](https://github.com/TPTBusiness/Predix)** is an autonomous AI agent for quantitative EUR/USD forex trading. It automates the full research and development cycle — from factor discovery to backtesting — using a multi-agent LLM framework on 1-minute data.

**What makes it different:**
- 🧠 **Autonomous factor evolution** — the agent proposes, codes, and validates its own alpha signals
- 🛡️ **Built-in risk management** — drawdown protection, cooldown periods, stoploss clustering detection
- 🔄 **Walk-forward validation** — avoids overfitting across 2020–2026 EUR/USD data
- 🖥️ **Real-time dashboard** — Streamlit UI for monitoring factor performance and model evolution
- 🔒 **60 integration tests** — every commit is checked before it lands

</td>
<td width="40%" align="center">

```
Market Data (CCXT / yfinance)
         ↓
  Feature Engineering
   (TA-Lib, pandas)
         ↓
  LLM Agent Loop
  (factor proposal
   + code generation)
         ↓
   Backtesting
   (Qlib, 1-min)
         ↓
  Risk Management
  (drawdown / cooldown)
         ↓
  Portfolio Output
```

</td>
</tr>
</table>

[![GitHub](https://img.shields.io/badge/TPTBusiness%2FPredix-View%20on%20GitHub-181717?style=flat-square&logo=github)](https://github.com/TPTBusiness/Predix)
[![License](https://img.shields.io/github/license/TPTBusiness/Predix?style=flat-square)](https://github.com/TPTBusiness/Predix/blob/master/LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/TPTBusiness/Predix?style=flat-square)](https://github.com/TPTBusiness/Predix/commits/master)
[![Stars](https://img.shields.io/github/stars/TPTBusiness/Predix?style=flat-square)](https://github.com/TPTBusiness/Predix/stargazers)

---

## 🧠 What I build

**Autonomous Trading Agents** — Multi-agent LLM frameworks that discover, evolve, and validate trading strategies end-to-end  
**Local LLM Integration** — Running AI systems fully offline with llama.cpp (no cloud dependency)  
**Open-Source Tools** — Pine Script strategies and Python frameworks for the trading community  
**Full Trading Pipelines** — From raw kline data to live execution, built and maintained independently

---

## 🗺️ Predix Roadmap

| Status | Phase | Feature |
|--------|-------|---------|
| ✅ Done | P0 | Data Loader — OHLCV loading, HDF5 caching, thread-safe feature matrix builder |
| ✅ Done | P1 | Strategy Worker — LLM call wrapper, backtest engine, FTMO compliance gate |
| ✅ Done | P2 | Strategy Orchestrator — multi-process pool, LLM semaphore, result deduplication |
| ✅ Done | P3 | Optuna Optimizer — TPE sampler, FTMO penalty logic, 20–50 trials per strategy |
| ✅ Done | P4 | CLI Commands — `generate_strategies`, Rich console output |
| ✅ Done | P5 | ML Training Pipeline — LightGBM, time-series split, feature importance analysis |
| ✅ Done | P6 | fin_quant Feedback Loop — ML feature importance → LLM prompt feedback |
| ✅ Done | P7 | Portfolio Optimizer — mean-variance, risk parity, Black-Litterman with LLM views |
| ✅ Done | P8 | Integration Tests — end-to-end pipeline, parallelisation, FTMO compliance |
| ✅ Done | P9 | Documentation — architecture diagrams, setup guide, data flow |
| ✅ Done | P10a | **Kronos-mini** — OHLCV foundation model inference on EUR/USD (4.1M params, AAAI 2026, MIT) |
| 📋 Planned | P10b | Kronos as factor generator — `kronos_predicted_return_96`, volatility, momentum, uncertainty |
| 📋 Planned | P10c | Kronos + LLM Ensemble — Optuna-optimized weighting of DL + LLM alpha signals |
| 📋 Planned | P10d | Kronos fine-tuning on EUR/USD 1-min custom tokenizer (optional) |
| 📋 Planned | P11 | Live execution — offline/online split, Telegram signal alerts |

---

## 🛠️ Stack

**Core & AI**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-00A1E0?style=flat-square&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FFF?style=flat-square&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white)

**Model Architectures**

![Transformer](https://img.shields.io/badge/Transformer-8A2BE2?style=flat-square&logoColor=white)
![LSTM](https://img.shields.io/badge/LSTM-6A0DAD?style=flat-square&logoColor=white)
![PPO](https://img.shields.io/badge/PPO%20(RL)-4B0082?style=flat-square&logoColor=white)
![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-512DA8?style=flat-square&logoColor=white)

**Data & Finance**

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![TA-Lib](https://img.shields.io/badge/TA--Lib-00897B?style=flat-square&logoColor=white)
![CCXT](https://img.shields.io/badge/CCXT-2C2D72?style=flat-square&logoColor=white)
![Qlib](https://img.shields.io/badge/Qlib-FF6B35?style=flat-square&logoColor=white)
![yfinance](https://img.shields.io/badge/yfinance-6B21A8?style=flat-square&logoColor=white)
![Binance API](https://img.shields.io/badge/Binance%20API-F0B90B?style=flat-square&logo=binance&logoColor=black)

**Local LLM & Inference**

![llama.cpp](https://img.shields.io/badge/llama.cpp-7B68EE?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-FF6C00?style=flat-square&logoColor=white)

**UI & Infra**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Pine Script](https://img.shields.io/badge/Pine%20Script%20v6-1E88E5?style=flat-square&logoColor=white)

---

## 🌍 Open-Source Contributions

| Project | Contribution |
|---------|-------------|
| [TradingAgents](https://github.com/TauricResearch/TradingAgents) ⭐ 34k | [Added llama.cpp local LLM support](https://github.com/TauricResearch/TradingAgents/pull/410) — run multi-agent stock analysis fully offline via `.env` config |
| [OpenStock](https://github.com/Open-Dev-Society/OpenStock) ⭐ 9.9k | [Updated deps, fixed Inngest v4 API, force-dynamic for auth routes](https://github.com/Open-Dev-Society/OpenStock/pull/63) — resolved 28 vulnerabilities, migrated Inngest v3→v4 |

---

## 📊 Activity

[![GitHub followers](https://img.shields.io/github/followers/TPTBusiness?style=flat-square&label=Followers)](https://github.com/TPTBusiness?tab=followers)
[![GitHub stars](https://img.shields.io/github/stars/TPTBusiness?style=flat-square&label=Total%20Stars)](https://github.com/TPTBusiness)
[![Predix commits](https://img.shields.io/github/commit-activity/m/TPTBusiness/Predix?style=flat-square&label=Predix%20commits%2Fmonth)](https://github.com/TPTBusiness/Predix/commits/master)
[![Predix issues closed](https://img.shields.io/github/issues-closed/TPTBusiness/Predix?style=flat-square&label=Predix%20issues%20closed)](https://github.com/TPTBusiness/Predix/issues)

---

## 📬 Contact

Premium models & collaborations → **tpt.requests@pm.me**  
Mastodon → [@TPTBusiness@mastodon.social](https://mastodon.social/@TPTBusiness)

---

> ⚠️ All content is for educational purposes only. Past performance does not guarantee future results.
