# Mostafa Ali

**Revenue & Marketing Operations — I build the systems behind go-to-market.**

Most of what I ship isn't a product. It's the plumbing: the pipeline that turns a
domain name into a qualified account list, the dashboard that tells a brand team
what's actually working, the automation that removes a recurring manual hour.

Currently running marketing ops at **American Bath Group**, across a multi-brand
portfolio.

---

## What I work on

**GTM systems** — Turning ICP definitions into working sourcing and outreach pipelines.
Provider waterfalls, enrichment, scoring, routing.

**Analytics & dashboards** — Making brand and campaign performance legible to people
who don't want to open a BI tool.

**Web** — Building and maintaining brand sites across the portfolio.

**Automation** — n8n, webhooks, and API glue between HubSpot, Notion, Supabase, and
whatever else the stack needs that week.

---

## Selected work

| Project | What it does |
| --- | --- |
| [tam-sourcing-gtm-system](https://github.com/mostafaesso/tam-sourcing-gtm-system) | n8n pipeline: website URL → 3-tier ICP → tool/channel filtering → tiered outreach |
| [opsolutions](https://github.com/mostafaesso/opsolutions) | Multi-tenant client portal — training with certification, HubSpot-backed CRM status, GTM tooling, per-company module control |
| [ABG-Dashboard](https://github.com/mostafaesso/ABG-Dashboard) | Multi-brand performance dashboard |
| [Quote](https://github.com/mostafaesso/Quote) | Pulls a HubSpot deal and renders a branded, downloadable quote — [live](https://quote-ops-4bc7.vercel.app) |
| [skilltree-clone](https://github.com/mostafaesso/skilltree-clone) | Audit tool that maps a company's structure as an interactive tree |

Brand sites: [florestone-website](https://github.com/mostafaesso/florestone-website) ·
[california-cooperage](https://github.com/mostafaesso/california-cooperage)

---

## Stack

Grouped by the job it does, not by category. Everything here is in current use.

### Sourcing and enrichment

| | |
| --- | --- |
| **Company data** | Apollo · Ocean.io · AI Ark · DiscoLike |
| **Scraping** | Apify · Google Maps Places API · Firecrawl |
| **Enrichment** | Clay · Deepline |
| **Verification** | provider waterfalls with confidence thresholds |

### CRM and revenue systems

**HubSpot** — the centre of most of this. Deal and line-item APIs, private app tokens,
custom properties, workflow logic, and reporting. Both `Quote` and the client portal
read from it directly.

**Snowflake** — semantic-layer queries for pipeline, cohort, and attribution questions.

### Automation

**n8n** — where the GTM pipelines actually live. The TAM system is 73 nodes across
crawling, model calls, gated sourcing branches, dedupe, and sheet writes.

**Supabase Edge Functions** — for logic that needs a real backend, like ICP generation.

Webhooks and REST APIs between all of it.

### Building things

| Layer | |
| --- | --- |
| **Framework** | React 18 · Next.js · Vite · TypeScript 5.8 |
| **Interface** | Tailwind · shadcn/ui · Radix · Recharts |
| **State and forms** | TanStack Query · React Hook Form · Zod |
| **Backend** | Supabase — Postgres, auth, edge functions, row-level security |
| **Testing** | Playwright |
| **Deploy** | Vercel · Docker |

### AI in the workflow

**Claude Code** — most of what I build now starts here. I keep a private library of
skills for the work I repeat: prospecting, enrichment, call prep, audits.

**Claude via OpenRouter** — the model calls inside n8n workflows, where the pipeline
needs judgement rather than a rule.

**Codex CLI** — a second implementer for work I want to review rather than write.

### Analytics and compliance

Google Analytics 4 · Google Workspace · OneTrust consent management · Notion

## Reach me

[LinkedIn](https://www.linkedin.com/in/mostafa-ahmed-ali/) · mostafamoh4mmed@gmail.com

<!--
One thing left that only you can write: the opening two paragraphs. They were
drafted from what the repos show. If the emphasis is wrong, rewrite them in your
own words, then delete this comment.
-->
