# Trading Prediction Technology · TPTBusiness

> Solo developer building AI-powered trading systems — from autonomous factor discovery to local LLM inference.  
> Three years in, still shipping. Supporter of open-source software and the communities that build it.

---

## 🚀 Main Project — Predix

**[Predix](https://github.com/TPTBusiness/Predix)** is an autonomous AI agent for quantitative EUR/USD forex trading. It automates the full research and development cycle — from factor discovery to backtesting — using a multi-agent LLM framework on 1-minute data.

**What makes it different:**
- 🧠 **Autonomous factor evolution** — the agent proposes, codes, and validates its own alpha signals
- 🛡️ **Built-in risk management** — drawdown protection, cooldown periods, stoploss clustering detection
- 🔄 **Walk-forward validation** — avoids overfitting across 2020–2026 EUR/USD data
- 🖥️ **Real-time dashboard** — Streamlit UI for monitoring factor performance and model evolution
- 🔒 **134 integration tests** — every commit is checked before it lands

**Data Flow:**
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

## 🛠️ Stack

**Core & AI**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-00A1E0?style=flat-square&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white)

**Data & Finance**

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![TA-Lib](https://img.shields.io/badge/TA--Lib-00897B?style=flat-square&logoColor=white)
![CCXT](https://img.shields.io/badge/CCXT-2C2D72?style=flat-square&logoColor=white)
![Qlib](https://img.shields.io/badge/Qlib-FF6B35?style=flat-square&logoColor=white)

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

[![GitHub Streak](https://streak-stats.demolab.com?user=TPTBusiness&theme=default&hide_border=true&date_format=j%20M%5B%20Y%5D)](https://git.io/streak-stats)

[![TPTBusiness's GitHub stats](https://github-readme-stats.vercel.app/api?username=TPTBusiness&show_icons=true&hide_border=true&count_private=true&hide=prs)](https://github.com/TPTBusiness)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=TPTBusiness&layout=compact&hide_border=true)](https://github.com/TPTBusiness)

---

## 📬 Contact

Premium models & collaborations → **tpt.requests@pm.me**  
Mastodon → [@TPTBusiness@mastodon.social](https://mastodon.social/@TPTBusiness)

---

> ⚠️ All content is for educational purposes only. Past performance does not guarantee future results.
