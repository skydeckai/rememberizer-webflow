# Rememberizer Public Website

The public website of [Rememberizer](https://rememberizer.ai) — connect your knowledge to AI.

## What Rememberizer offers

**For individuals** — where user data drives AI personalization. Integrate your own documents, Slack discussions, Gmail, Dropbox, and Google Drive with OpenAI GPTs and other AI applications, so your AI apps know what you know.

**For teams** — a secure, business-first AI productivity platform. Give your team's AI a shared knowledge repository with semantic search across everything the team has connected.

**For developers** — enterprise vector database and RAG at scale. Hardware and software designed together: bare metal or Ubuntu Server with a pre-configured PostgreSQL + pgvector database, built for performance in Silicon Valley.

**Security you can verify** — SkyDeck AI is SOC 2 Type 2 certified (since June 2024) and the Rememberizer service passed CASA Tier 2 certification, aligned with the OWASP ASVS.

Learn more at [rememberizer.ai](https://rememberizer.ai) or read the [documentation](https://docs.rememberizer.ai). The site is available in 12 languages: English, French, Danish, German, Spanish, Portuguese, Japanese, Korean, Vietnamese, Simplified Chinese, Traditional Chinese, and Arabic.

## About this repository

This repo holds the static website served at [try.rememberizer.ai](https://try.rememberizer.ai) via GitHub Pages (see `CNAME`). Content is updated by an automated export — pages land here as pre-built HTML, so there is no build step and no pull requests are expected. Edit at the source, not in this repo; manual changes will be overwritten by the next export (commits titled `Static content update for rememberizer <timestamp>`).

### Layout

- `index.html` — the English homepage, also mirrored under `en/`.
- `ar/`, `da/`, `de/`, `es/`, `fr/`, `ja/`, `ko/`, `pt/`, `vi/`, `zh-cn/`, `zh-hk/` — the other 11 locales, each a full copy of the site.
- `blog/`, `solutions/`, `resources/`, `team/`, `portfolio/`, `search/` — site sections (one folder per page, each with its own `index.html`).
- `assets/` — images and other static assets, shared across locales.
- `401/`, `404/`, `404.html` — error pages.
- `google*.html` — Google Search Console site verification.
