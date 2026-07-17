# Thomas Amoroso

**ML Engineer — Computer Vision & Applied LLM/GenAI**
Angers, France · Open to remote-first roles (FR / Switzerland / Luxembourg)

I build things end-to-end and ship them to production. My background is atypical — agronomy engineering, doctoral-level research, then a pivot into ML and full-stack development — which means I care less about which framework is trendy and more about whether the system actually works under real constraints.

---

## Currently building

**[forest-rag](#)** — a RAG pipeline over Shift Project reports on agriculture, built specifically to close the gap between "I've done ML" and "I've deployed ML."

- **Retrieval**: Qdrant (embedded mode) + `fastembed` for dense embeddings
- **Reranking**: `jinaai/jina-reranker-v2-base-multilingual` cross-encoder
- **Generation**: Groq API (`llama-3.3-70b-versatile`), grounded prompting with structured system/task/context/question ordering
- **Observability**: Langfuse
- **Ops**: FastAPI, Poetry, Docker, deployed on Render
- **Testing**: `pytest-asyncio` + `asgi-lifespan` for lifespan smoke tests

No LangChain — evaluated and dropped as unnecessary overhead for a straightforward retrieve-and-generate pipeline. I'd rather understand and control every layer than import an abstraction I don't need.

---

## Background

- **Agronomy engineering** foundation, doctoral-level research at INRAE/ASTREDHOR (plant physiology, not defended)
- **2 peer-reviewed publications** in plant physiology
- **3 years at Viabeez** (MedTech startup) as ML Engineer + Full-Stack Developer, full remote:
  - Built and maintained Node.js APIs handling several thousand daily requests in production
  - Delivered a RAG/LLM proof of concept (LangChain, MongoDB Atlas)
  - Computer Vision work: OpenCV, Structure from Motion (3D reconstruction), PyTorch/TensorFlow

---

## Stack

| Area | Tools |
|---|---|
| Languages | Python, JavaScript/Node.js, Bash |
| ML / CV | PyTorch, TensorFlow, OpenCV, fastembed |
| LLM / RAG | Groq API, Qdrant, LangChain (selectively), Langfuse |
| Backend | FastAPI, Node.js |
| Infra | Docker, Git, AWS, GCP, Linux, Render |

---

## What I'm looking for

ML Engineer role (Computer Vision or applied LLM/GenAI) where ML is a real technical decision, not a marketing line — environments with enough complexity that shipping to production is the hard part, not an afterthought.

---

📫 Reach out via [LinkedIn](#) or [email](#)
