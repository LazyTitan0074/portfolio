# Vlad — AI Systems & Agentic Workflows

**Technical portfolio · Portofoliu tehnic · 2026**

[![Python](https://img.shields.io/badge/Python-3.11%2B-3776ab?logo=python&logoColor=white)](https://www.python.org/)
[![Agentic workflows](https://img.shields.io/badge/agentic-workflows-7c3aed)](https://github.com/LazyTitan0074/roman-pipeline)
[![Tests](https://img.shields.io/badge/tests-88%2F88-brightgreen)](https://github.com/LazyTitan0074/roman-pipeline/actions)

**EN** — I build software with AI agents, not with a single "generate" button. Roles are separated, verification gates are explicit, and verdicts/logs stay in the repository next to the code. The human is the architect and the final reviewer. Every claim below traces back to source files, docs or git history.

**RO** — Construiesc software împreună cu agenți AI, nu cu un singur buton „generează”. Rolurile sunt separate, porțile de verificare sunt explicite, iar veredictele și jurnalele rămân în repository lângă cod. Omul e arhitect și reviewer final. Fiecare afirmație de mai jos se poate urmări până la un fișier sau un commit.

---

## View the portfolio / Vezi portofoliul

- **Interactive site:** open [`index.html`](index.html) — bilingual RO/EN toggle, fully offline, no dependencies.
- **PDF RO:** [`Portofoliu_RO.pdf`](Portofoliu_RO.pdf) · **PDF EN:** [`Portfolio_EN.pdf`](Portfolio_EN.pdf)
- **Live site:** [lazytitan0074.github.io/portfolio](https://lazytitan0074.github.io/portfolio/)

---

## Selected work / Proiecte selectate

| # | Project | What it does | Stack | Source |
|---|---|---|---|---|
| 01 | **Roman Pipeline** | Reusable Python pipeline for long-form fiction: concept → canon bible → per-chapter writing with writer/reviewer models and deterministic gates → EPUB. Rejected chapters are rewritten, never patched. | Python, Typer, Pydantic, google-genai, pytest, Ruff, GitHub Actions | [public repo](https://github.com/LazyTitan0074/roman-pipeline) |
| 02 | **The Glass Crown** | Canon-locked novella, 10 chapters / ~24k words, delivered in one day on free-tier models + local Ollama reviewer. Documented rejections, reviewer errors and tooling defects. | Python, LibriScribe, YAML/JSON, Ollama, EPUB | case study in the portfolio; private repo |
| 03 | **Gladiators Ascent** | Same pipeline applied to a 30-chapter novel: 60 canon/structure verdicts and a deterministic EPUB build. | Python, JSON verdicts, Markdown, EPUB | included in `roman-pipeline` |
| 04 | **Lara Master Collection** | Structured AI persona / lore / game-design vault: 25 persona cards, narrative scenarios and a LibriScribe novel project repaired for `mistral-large-latest`. | JSON, Markdown, DOCX, LibriScribe | private repo |
| 05 | **Homelab DNS** | Self-hosted Pi-hole/FTL stack via Docker Compose, with dnsmasq config and an autonomous server-restore runbook written for AI agents. | Docker Compose, Pi-hole, dnsmasq, AUR | configuration + runbook on server |
| 06 | **pragma-rpg** | AI-powered RPG campaign generator and live Dungeon Master, self-hosted with zero dependencies. | Python | [public repo](https://github.com/LazyTitan0074/pragma-rpg) |

**Numbers:** 50 chapters delivered · 88/88 tests passing · 7 drafts rejected for canon violations · 3+ real issues caught by human spot-checks · 400+ paragraphs traced source → manuscript → EPUB with 100% match · 2 custom agent skills.

---

## How I work / Cum lucrez

1. **Spec & canon** — rules, characters and constraints become versioned files (`AGENT.md`, `PROJECT_BRIEFING.md`, `CANON.md`), not notes in someone's head.
2. **Agentic planning** — agents propose structure, tasks and the order of verification gates.
3. **Iterate with gates** — writer model → different-model reviewer → deterministic check → full rewrite on failure.
4. **Evidence & docs** — verdicts, logs, audits and tests stay in the repository beside the code (`CASE_STUDY.md`, `AUDIT_2026-11-04.md`).

Agents used: **Hermes Agent** (pipeline assembly + custom skills), **OpenCode / Big Pickle** (independent audit), **Gemini CLI / Antigravity**, **Aider**, **OpenClaw**.

---

## Scope & honesty / Precizări

- The portfolio describes **authored work**. Third-party upstream code (Pi-hole, yay, Minecraft/Tekkit) is **not** claimed as AI-authored; it is listed only as an operating environment.
- Credentials, internal addresses, hardware serial numbers, unpublished manuscript text, adult content and personal data were **intentionally excluded**.
- The Glass Crown and Lara vault remain **private**; their summaries here are sanitised. Ask if you want a walkthrough.
- Content was compiled on 23 November 2026 from the project inventory on the local server and verified against code, documentation and git history.

---

## Contact / Contact

**Vlad** · bizoivlad@gmail.com · [github.com/LazyTitan0074](https://github.com/LazyTitan0074)
