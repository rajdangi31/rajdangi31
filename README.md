<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0D0D,50:1a0533,100:0D0D0D&height=120&section=header" width="100%"/>

# Raj Dangi

**Systems Engineer · Intelligent Agent Architect · CS @ University of Toledo**

[![Portfolio](https://img.shields.io/badge/philosrach.com-000000?style=flat-square&logo=safari&logoColor=white)](https://philosrach.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raj-dangi/)
[![X](https://img.shields.io/badge/@philosrach-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/philosrach)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rach.dev0731@gmail.com)

</div>

---

I build at the intersection of **systems architecture** and **agentic AI** — frameworks that are as reliable as they are intelligent. Currently focused on operating systems internals, behavioral machine learning, and real-time distributed platforms. Seeking **Summer 2026 internships** in agentic workflows, systems automation, and AI engineering.

---

## Projects

### [NYXIS](https://github.com/rajdangi31/NYXIS) — Adversarial AI Operating System

> *"The personal evolution OS that doesn't care if you're ready."*

An experimental agent framework that monitors behavioral weaknesses, generates AI-driven directives via a two-stage cognitive pipeline (Strategist → Generator), and applies real consequences for inaction through a "Shadow Pressure" mechanic. Not a habit tracker — an adversarial system that adapts to close every escape route.

**Key engineering decisions:**
- **Dual-Brain AI pipeline** — Strategist brain reads behavioral state and sets quest parameters; Generator brain synthesizes interconnected quest chains with dependency graphs
- **EMA-based behavioral profiling** — tracks Consistency, Avoidance, and Intensity in real-time using an 80/20 Exponential Moving Average to feed back into quest generation
- **Persistent memory system** — after every 7-quest cycle, pattern detection etches behavioral memories into Postgres, injected into future Strategist context
- **Supabase Edge Functions** (Deno runtime) handle AI orchestration with OpenRouter; PL/pgSQL RPCs handle transactional state mutations

`Expo SDK 54` · `React Native` · `TypeScript` · `Supabase (Postgres + RLS + Edge Functions)` · `OpenRouter (GPT-4o-mini)` · `Deno`

---

### [GPT-2 from Scratch](https://github.com/rajdangi31/GPT-2) — Transformer Fundamentals

> *"Peeling back the abstraction layers of modern transformers."*

A ground-up implementation of the GPT-2 architecture using raw PyTorch — no high-level wrappers. Built to develop deep mechanical intuition for how attention, positional encoding, and autoregressive generation actually work before using any framework abstractions.

**Key engineering decisions:**
- **Character-level tokenizer** — manual ingestion of text into integer space, building the vocabulary from scratch
- **Causal self-attention** — QKV projection matrices with lower-triangular masking (`tril`) for autoregressive constraints
- **AdamW optimization** — trained on Plato's Dialogues; the model learns structured philosophical turn-taking from the data distribution

`Python` · `PyTorch` · `NumPy` · `AdamW`

---

### [takeApeek](https://github.com/rajdangi31/takeApeek) — Real-Time Social Platform

> *"Cinematic social discovery with a Glass & Glow design system."*  
> Live: [take-apeek.vercel.app](https://take-apeek.vercel.app)

A real-time social platform engineered for high-fidelity interactions. The core challenge was maintaining sub-second performance at scale while running complex real-time synchronization across clients.

**Key engineering decisions:**
- **Windowed fetching** — virtualized infinite scroll with prefetch boundaries for constant-time rendering regardless of feed size
- **Supabase Channels + broadcast listeners** — multi-directional real-time sync without polling; state deltas pushed via WebSocket subscriptions
- **TanStack Query v5** — declarative server state with optimistic updates and cache invalidation, keeping the UI reactive without manual state management

`React 18` · `Vite 6` · `TypeScript` · `Tailwind CSS v4` · `TanStack Query v5` · `Supabase` · `Framer Motion`

---

## Technical Stack

**Languages** — Python · C/C++ · TypeScript · SQL

**AI / ML** — PyTorch · Transformer architectures · RAG (Retrieval-Augmented Generation) · Agentic pipelines

**Infrastructure** — Supabase (Postgres · RLS · Edge Functions) · Deno runtime · Vercel · Failover architecture

**Frontend** — React · React Native · Expo · Vite · Tailwind CSS · Framer Motion · TanStack Query

**Methodology** — Atomic documentation · Map of Content (MOC) · Agile system development

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rajdangi31&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d0d0d&title_color=a855f7&icon_color=7c3aed&text_color=e5e7eb" />

</div>

---

<div align="center">

*"The goal is to build systems that are as reliable as they are intelligent."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0D0D,50:1a0533,100:0D0D0D&height=80&section=footer" width="100%"/>

</div>
