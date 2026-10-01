# Portfolio — Sai Ravi Teja Dasu

**Lead Forward Deployed AI Engineer** · Turing / Apollo Global Management · New York City Metropolitan Area

Live site: **https://dasusairaviteja.github.io/Portfolio/**

This repository contains the source for Sai Ravi Teja Dasu's personal portfolio website — a single-page, hand-built site showcasing 9+ years of production AI engineering: agentic AI systems, RAG, LLM evaluation and governance, and enterprise delivery leadership.

## What's inside

| File | Purpose |
|---|---|
| `index.html` | The entire site — markup, styles, and scripts in one self-contained file (no build step, no framework) |
| `assets/expertise-speaking.jpg` | Speaking photo used in the Expertise section (The AI Summit New York) |
| `README.md` | This file |

## Site sections

1. **Hero** — Name, title (Lead Forward Deployed AI Engineer), current role at Turing / Apollo, and an animated portrait.
2. **About** — "Engineering with *intention.*" — positioning statement: turning complex business problems into reliable production systems, from problem definition and architecture through deployment and iteration, with evaluation, guardrails, and observability built in.
3. **Skills** — "What I *build.*" — nine capability areas: Agentic AI & Multi-Agent Systems, RAG & Semantic Search, LLM Evaluation & Guardrails, Python & Machine Learning, NLP & Document Intelligence, Cloud Deployment & MLOps, Latency & Cost Optimization, Technical Delivery & Leadership, Stakeholder Collaboration.
4. **Expertise** — "Cutting-edge AI, *enterprise-grade.*" — four deep-dive cards with real-world enterprise context:
   - **Enterprise AI & Agentic Systems** — production multi-agent orchestration (LangGraph, LangChain), MCP-based tool calling, model routing, caching, layered guardrails — financial services (Vanguard) and enterprise delivery (Apollo).
   - **Generative AI & LLMs** — RAG frameworks, semantic search, embeddings and vector databases, LLM evaluation and LLM-as-judge; model-agnostic LLM gateways cutting inference costs ~50%.
   - **NLP at Scale** — BERT-based document classification, entity extraction, semantic search over federal court records, SHAP explainability, Kafka + Spark streaming/batch pipelines.
   - **AI Governance & Responsible AI** — evaluation, guardrails, observability in the engineering process; secure, compliant deployments on client infrastructure.
5. **Experience** — "The journey *so far.*" — full career timeline:
   - Lead Forward Deployed AI Engineer, Turing · Apollo Global Management (Sep 2026 — Present)
   - Senior Software Engineer, TCS · Vanguard ModelOps (May 2024 — Sep 2026)
   - Machine Learning Engineer, Advanity Technologies (Apr 2024 — May 2024)
   - Machine Learning Engineer, US Federal Government (Jul 2023 — Apr 2024)
   - Graduate Research Assistant, University of North Texas (Aug 2022 — May 2023)
   - Senior Lead Software Engineer, Amazon · Advertising / Sponsored Products Science (Jun 2016 — Dec 2021)
6. **Selected work** — four flagship projects: Financial Intent Orchestration (Vanguard Agentic AI), Advisor Change-History Platform (Vanguard GenAI), Advertising Prediction & Optimization (Amazon ML), Legal NLP & Forecasting (US Federal Government).
7. **Education** — Master's in AI (University of North Texas), MBA in Operations Management (NIBM Global), plus certifications (Machine Learning with Python, Google Project Management, ChatGPT Solutions Practitioner).
8. **Contact** — contact form and links.

## Technical details

- **Zero dependencies**: pure HTML + CSS + JavaScript in a single file. No framework, no build tooling, no package manager.
- **Theming**: dark theme by default with a light-mode toggle (`data-theme` attribute + CSS variables). Respects `color-scheme`.
- **Responsive**: fluid layout with `min()`-based widths; the Expertise two-column grid collapses to a single column under 900px.
- **Accessibility**: semantic landmarks (`header`, `main`, `section` with `aria-labelledby`), skip link, focus-visible outlines, descriptive `alt` text.
- **Images**: hero portrait is an inline WebP data URI; the Expertise speaking photo is served from `assets/` for faster initial load.
- **Motion**: subtle float animation on the hero portrait with a user-controllable motion toggle.

## Deployment

The site is deployed with **GitHub Pages** from the `main` branch (root). Every push to `main` rebuilds and redeploys automatically within ~1–2 minutes.

## Local preview

No server needed — just open the file:

```bash
open index.html        # macOS
xdg-open index.html    # Linux
```

Or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Author

**Sai Ravi Teja Dasu** — Lead Forward Deployed AI Engineer at Turing, deployed with Apollo Global Management.
- Portfolio: https://dasusairaviteja.github.io/Portfolio/
- LinkedIn: https://www.linkedin.com/in/sai-teja-ai-engineer/
- Location: New York, NY
