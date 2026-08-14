# 👋 Hi, I'm Eduardo

**AI Systems Engineer** focused on building reliable AI infrastructure, RAG architectures, semantic search, and backend systems for AI applications.

I build production-oriented AI systems ranging from document intelligence platforms to reusable model infrastructure, with emphasis on clean architecture, reliability, observability, and provider-agnostic design.

---

## 🎯 Focus

* AI infrastructure & LLM integrations
* RAG systems & retrieval architectures
* Embeddings & vector databases
* Backend engineering with Python & FastAPI
* Resilient and observable AI systems
* Multi-tenant AI applications
* Document intelligence platforms

---

## 🚀 Featured Projects

### ModelCore — Provider-Agnostic AI Infrastructure

Open-source Python library for building reliable and provider-independent AI applications.

Designed as an infrastructure layer between applications and AI providers, keeping provider SDKs isolated while exposing normalized interfaces and reusable reliability components.

**Key capabilities:**

* Provider-agnostic chat generation
* OpenAI and Ollama adapters
* Async generation and streaming
* Embeddings
* Structured outputs with Pydantic
* Retry, timeout and exponential backoff
* Deterministic caching with TTL
* Multi-provider fallback
* Circuit breaker
* Model routing strategies
* Routing and generation telemetry
* Optional OpenTelemetry integration
* Tool calling with validated execution
* Fully asynchronous architecture
* Extensive deterministic test suite

Built around **composition over inheritance**, interface segregation, normalized internal models, and clean separation between application logic and external AI SDKs.

📦 Public Python library
🔗 [github.com/EduDev365/modelcore](https://github.com/EduDev365/modelcore)

---

### DocCore — AI Document Intelligence Platform

Multi-tenant SaaS for AI-powered document understanding, semantic retrieval, and knowledge interaction.

The platform implements a complete RAG pipeline for ingesting, processing, indexing, retrieving, and reasoning over documents.

**Architecture highlights:**

* Document ingestion and validation
* Text extraction and chunking
* Embedding generation
* PostgreSQL + pgvector vector storage
* Semantic retrieval
* Context construction for LLMs
* Async worker-based ingestion
* Redis-backed infrastructure
* Multi-tenant data isolation
* FastAPI backend

DocCore focuses on the **application/product layer**, while ModelCore focuses on reusable **AI model infrastructure**.

🔒 Private project — architecture available through showcase material.

---

## 🧠 Engineering Interests

I'm particularly interested in the engineering challenges behind production AI systems:

* How to abstract multiple AI providers without leaking SDK-specific behavior
* How to make LLM integrations resilient to failures and rate limits
* How to design observable AI pipelines
* How to route requests between models based on cost, latency, and quality
* How to build maintainable RAG architectures
* How to separate AI infrastructure from domain-specific application logic

---

## 🛠️ Tech Stack

**Languages & Backend**
Python • FastAPI • AsyncIO • REST APIs

**AI & Retrieval**
LLMs • RAG • Embeddings • Semantic Search • Structured Outputs • Tool Calling

**Data & Infrastructure**
PostgreSQL • pgvector • Redis • Docker

**Engineering**
Pytest • TDD • Clean Architecture • Protocol-based interfaces • Observability • Resilience Patterns

---

## 🎓 Education

**Bachelor's Degree in Software Engineering**

**Postgraduate Degree in Data Science & Artificial Intelligence** — ongoing

---

## 📫 Contact

📧 **Email:** [tof_eduardo@hotmail.com](mailto:tof_eduardo@hotmail.com)

💻 **GitHub:** [github.com/EduDev365](https://github.com/EduDev365)
