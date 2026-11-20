<div align="center">

# Giresh Velaga

**I build AI systems where retrieval does the heavy lifting — and where the model knows when to say "I don't know."**

CS undergrad at IIIT Sri City

`Python` · `LangGraph` · `FastAPI` · `PostgreSQL` · `Docker`

[portfolio](https://portfolio-eta-sandy-30.vercel.app) &nbsp;·&nbsp; [email](mailto:gireshvelaga@gmail.com)

</div>

---

## Currently

**[Placement Intelligence Agent](https://github.com/Giresh-458/IIITS-Placements)** — a bounded crawler that turns fragmented campus recruitment notices into structured, queryable leads. Discovery, extraction and PostgreSQL persistence work; end-to-end validation is still in progress.

Mostly thinking about the unglamorous half of AI: retrieval evaluation, abstention, and keeping tool calls bounded.

## Selected work

### 🏗 [AI Operations Agent](https://github.com/Giresh-458/ai-operations-agent) · [live demo](https://ai-operations-agent.streamlit.app)

Stateful LangGraph agent for operational workflows. The LLM is the easy part — the scaffolding is the work: intent routing with bounded retries, a corrective-RAG loop that grades its own retrieved evidence and rewrites weak queries, and a human approval gate before anything irreversible executes.

### 🏥 [HealthRAG](https://github.com/Giresh-458/Healthcare-Document-RAG-Assitant) · [live demo](https://healthrag.streamlit.app)

Document QA over clinical PDFs and scans. Hybrid BM25 + dense retrieval fused with Reciprocal Rank Fusion, and a sufficiency gate that abstains instead of answering without evidence. PHI is redacted on the way in.

### ⚡ [Vighna Trading Bot](https://github.com/Giresh-458/Vighna-Trading-Bot)

Listens to Telegram trading channels, parses options and futures signals against a live instrument master, and executes on Angel One's SmartAPI with risk controls. Handles the parts that break naive bots — expiry resolution, dual-direction breakouts, and targets that went stale before the signal arrived.

## Also here

[RestoConnect](https://github.com/Giresh-458/RestoConnect-React) — React · Express · MongoDB platform, Dockerised &nbsp;·&nbsp; [CGPA Calculator](https://github.com/Giresh-458/IIITS_CGPA_Calc) — [live](https://iiits-cgpa-calculator.onrender.com/) &nbsp;·&nbsp; [BPoW Simulator](https://github.com/Giresh-458/BPoW_Simulator) — proof-of-work mining simulator &nbsp;·&nbsp; [portfolio](https://github.com/Giresh-458/portfolio) — [live](https://portfolio-eta-sandy-30.vercel.app)
