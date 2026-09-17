# Hi, I'm Amit 👋

Principal Product Manager at Microsoft. 18+ years building products across AI/ML, content, search, and data platforms — at Microsoft and at high-growth startups before that.

Some of what I've shipped: the News and Interests feed on Windows 10/11 (500M+ devices, 180 markets), content and personalization APIs for Microsoft Edge and msn.com, finance and currency answers on Bing, and more recently the evaluation platform and AI copilot skills used across Microsoft's commerce and sales organization (one patent filed along the way). I've led PM teams and currently lead a squad of data scientists and engineers, but I started my career writing Java, and I've never fully let go of building things myself.

This account is where I do that. Most of it is AI-first: take something messy, parse and classify it, put a usable interface on top, and find out whether the model actually earns its keep. It's also a running experiment in how far one PM can take an idea with modern tooling and a good coding agent.

## What's here

**[personalCFO](https://github.com/amitghosh80/personalCFO)** — Upload bank and card statements (CSV or PDF), get transactions parsed, classified, and encrypted, then ask a Claude-powered assistant about your spending. FastAPI + SQLModel backend, Next.js/TypeScript frontend, multi-tenant auth.

**[budget-spend-analyzer](https://github.com/amitghosh80/budget-spend-analyzer)** — The lighter, privacy-first cousin: PDF statements in, monthly cashflow out. Rules-based categorization with a Claude fallback, AES-256-GCM encrypted storage, 48-hour auto-delete. Python/FastAPI + React.

**[photo-manager](https://github.com/amitghosh80/photo-manager)** — Rank and shortlist a folder of trip photos. Classic CV for sharpness/exposure, Claude vision for composition, perceptual hashing for near-duplicates. About $0.10 per 100 photos with prompt caching.

**[quadrantlife](https://github.com/amitghosh80/quadrantlife)** — Eisenhower-matrix task manager built around roles and goals rather than just deadlines. React/TypeScript + Supabase. [Live demo](https://quadrantlife.vercel.app)

## How I work

- Start from a real problem I have, not a tech I want to try
- Ship the end-to-end thin slice first, then decide if it deserves more
- Treat model output as untrusted until it's measured — same rule at work and here
- Python / FastAPI on the back, React / TypeScript on the front, Claude in the loop

## Elsewhere

Seattle area. Open to conversations about AI product evaluation, PM tooling, and what "good" looks like for LLM features.
