# Hey, I'm Igor Eduardo 👋

**Senior AI Product Engineer** · Austin, TX

I build production AI systems for healthcare. My focus is on **RAG pipelines that don't hallucinate**, **self-hosted medical models**, and **regulated AI infrastructure** (HIPAA/LGPD-grade).

---

### What I Built

I solo-engineered a **production clinical AI platform** from zero — 10 integrated modules serving physicians in pilot:

```
Query (natural language) → Hybrid RAG (BM25 + Semantic + RRF)
→ 5,300+ curated papers → Citation Verification → Zero hallucinations
→ Smart Model Routing (4-model fallback) → Response in <2s
```

**The numbers:**

| Metric | Value |
|---|---|
| Medical papers indexed | 5,300+ |
| Citation hallucination rate | **0%** (verified pipeline) |
| Landmark trials (NEJM/JAMA/BMJ) | 267 |
| Automated tests | 145+ |
| Due diligence audit score | **10/10** |
| Model routing cost reduction | 80–95% |
| Gross margin at scale | 94.9% |
| Physicians in pilot | 47 |

### Technical Depth

**AI/ML:** RAG (BM25 + semantic + RRF + pgvector HNSW), self-hosted LLM inference (AWQ quantization), model routing & fallback chains, citation verification, embedding pipelines, QLoRA fine-tuning prep, clinical NLP

**Healthcare:** HIPAA/LGPD compliance-as-code, PII scrubbing (Presidio + custom recognizers), 5-layer safety systems, drug-drug interaction checks (RxNorm/NIH), deterministic lab classification, ECG signal processing (ResNet-1D), ambient clinical scribe (Whisper + speaker diarization)

**Full-Stack:** Next.js 16, TypeScript (strict), PostgreSQL + pgvector, Supabase (Auth + RLS), Python, Redis, Stripe, Twilio WhatsApp API, Railway, Vercel

**Quality:** Vitest, Playwright, Semgrep (healthcare rules), Gitleaks, OpenTelemetry, Langfuse (LLM observability), CycloneDX SBOM

---

### Open Source

🔬 [`hybrid-rag-pipeline`](https://github.com/nomad-link-id/hybrid-rag-pipeline) — Production-grade RAG combining BM25 + semantic search + Reciprocal Rank Fusion. TypeScript + pgvector.

🛡️ [`citation-guard`](https://github.com/nomad-link-id/citation-guard) — Post-generation citation verification for RAG systems. Eliminates hallucinated references before they reach users.

🔀 [`model-router-chain`](https://github.com/nomad-link-id/model-router-chain) — Smart LLM routing with automatic fallback, complexity scoring, and cost optimization. 80–95% cost reduction vs single-model.

---

### Currently

- 🏥 Building [DocMinds.ai](https://docminds.ai) — Clinical AI platform for Brazilian physicians
- 🧠 Building [minds.ai](https://github.com/nomad-link-id) — Sovereign medical AI infrastructure
- 📍 Austin, TX
- 💼 Open to Senior AI Engineer / Staff AI Engineer roles in healthcare, AI startups, and Big Tech

---

<p align="center">
  <a href="https://linkedin.com/in/igor-eduardo-92a9a2b0">LinkedIn</a> ·
  <a href="https://docminds.ai">DocMinds.ai</a> ·
  <a href="https://igoreduardo.com">igoreduardo.com</a> ·
  <a href="https://medium.com/@igorcnnbd">Medium</a> ·
  <a href="https://scholar.google.com/citations?user=AOA75soAAAAJ&hl=en&authuser=1">Google Scholar</a>
</p>
