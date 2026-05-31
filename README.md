## Hitaish K G

AI/ML Engineer. I build agentic pipelines and production LLM systems.

B.Tech AI & Data Science, REVA University (2025). Open to AI/ML engineering roles - remote (US) and Bangalore.

---

### [Indian Trader](https://github.com/Hitaishkg/indian-trader)
10-stage autonomous trading pipeline for NSE equities. LangChain ReAct (Gemini + Tavily) for nightly news synthesis; Groq Llama 3.3 70B for morning signal confirmation; local Ollama as fallback. Architecture: rules lead, LLM is a veto layer. 14-year backtest across 441 trades: 1.42 profit factor, 9.07% max drawdown. Sharpe never cleared 1.0 - documented openly in DECISIONS.md. Currently in paper trading validation. 650 passing tests, ruff + mypy on every commit.

### [RAG Arena](https://github.com/Hitaishkg/RAG_Arena) - [live demo](https://rag-arena-322804211543.asia-south1.run.app/static/index.html)
4-strategy RAG benchmark over 5 SEBI regulations (1,367 chunks). BM25, Dense (BGE-small), Hybrid (BM25 + Dense + cross-encoder rerank), Tree Index (LlamaIndex + Gemini). Evaluated with 41 hand-crafted questions using RAGAS. Mid-project bug: MiniLM had a 256-token context window against 512-token chunks - swapping to BGE-small doubled precision scores across all four strategies. Deployed on GCP Cloud Run.

### [Demand Forecasting](https://github.com/Hitaishkg/Demand_forecating)
ABC-XYZ segmentation pipeline routing 30K+ SKUs to Prophet, LightGBM, or TFT by volatility profile. 15-20% modeled inventory cost reduction. Built during a Target Corporation apprenticeship.

The thread across these projects: agentic systems where deterministic rules lead and the LLM is held accountable.

---

**PwC India** (2025 - present): Production LLM pipelines at a Big-4 firm - multi-model SQL generation (OpenAI + Anthropic), 3-tier retry logic, FastAPI backend. 40% reduction in spec-to-SQL mismatches. Details are client-sensitive.

**Research**: 3 published papers. Best Paper at ICETCI 2024 (MLP-Mixer for stock prediction). IEEE CONNECT 2023 (MobileNet SSD). RITESI 2025 (YOLOv8 + RAG for medical imaging).

---

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white&style=flat-square)

**LLM / Agentic**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white&style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white&style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white&style=flat-square)
![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?logo=googlegemini&logoColor=white&style=flat-square)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)

**Retrieval / RAG**
![FAISS](https://img.shields.io/badge/FAISS-0078D7?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-FF6B6B?style=flat-square)

**Frameworks**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=flat-square)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white&style=flat-square)

**Cloud / Infra**
![GCP](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white&style=flat-square)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white&style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat-square)

**Tooling**
![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white&style=flat-square)
![ruff](https://img.shields.io/badge/ruff-D7FF64?logo=ruff&logoColor=black&style=flat-square)
![mypy](https://img.shields.io/badge/mypy-2A6DB5?style=flat-square)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square)

---

hitaishkg@gmail.com · [LinkedIn](https://linkedin.com/in/hitaishkg) · [X](https://x.com/HitaishKG)
