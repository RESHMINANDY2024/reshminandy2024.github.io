---
layout: post
title: GCC 2.0 — From Support Center to Global Product Engine in 120 Days
description: A 40‑40‑40 playbook to move from tickets to outcomes with product funding, paved roads, and DORA/SPACE.
---

> **TL;DR:** In 120 days, you can move a GCC from “support factory” to **product engine** by re-wiring **(1) org & governance, (2) platform & paved roads, (3) metrics & rituals**. Track **lead time, deploy frequency, change failure rate, MTTR** weekly; publish ADRs and working agreements; fund by product/value stream, not by project.

**Why this matters.** Most GCCs plateau on cost arbitrage. The leadership ask now is **ownership**: take **end‑to‑end outcomes** for revenue‑critical capabilities. That requires an operating model, not heroics.

## The 40‑40‑40 Plan (120 days)
- **Days 1–40 — Org & Governance**: Map value streams; stand up product funding; appoint single‑threaded owners; publish **RACI** + **ADRs**.  
- **Days 41–80 — Platform & Paved Roads**: Minimum viable IDP (CI/CD, IaC, runtime, obs, portal); **golden paths** for API/data/UI.  
- **Days 81–120 — Metrics & Rituals**: Weekly **DORA/SPACE** reviews; run “build Wednesdays”; create a **scorecard** for pods and vendors.

![](/static/img/gcc-2-0-product-engine-120-days-org-before-after.svg)

## Value Streams & Roles
- Product Owner (business outcomes), Engineering Manager (quality/velocity), Architect (guardrails/ADRs), SRE (reliability), Analyst (insights).  
- Global alignment: co-located POs or time‑zone paired; budget tied to streams.

![](/static/img/gcc-2-0-product-engine-120-days-value-stream-map.svg)

## Platform & Golden Paths
- Self‑service: repo scaffold → pipeline → environment → observability in minutes.  
- Three paths to start: **API**, **data**, **frontend**. Measure **time to first deploy**.

![](/static/img/gcc-2-0-product-engine-120-days-dora-dashboard.svg)

## Metrics & Cadence (what to watch weekly)
- **Lead time for changes**, **deploy frequency**, **change failure rate**, **MTTR**.  
- Review wait time, decision latency, first‑time‑right %, maker:meeting ratio.  
- Publish a simple **pod scorecard** each Friday.

![](/static/img/gcc-2-0-product-engine-120-days-roadmap-120-day.svg)

## Risks & Anti‑Patterns
- Cargo‑cult squads without real product ownership.  
- “Half‑stack” platforms (no paved roads → zero adoption).  
- Vanity OKRs and KPI theater.  
- Tool sprawl; no ADRs; decision ambiguity.

---

### Loom (5‑min) — Script
- **00:00–00:45** — The mandate shift: tickets → outcomes; why 120 days.  
- **00:45–02:00** — Walk the **40‑40‑40** plan with the org diagram.  
- **02:00–03:30** — Golden paths demo storyboard; what changes in dev flow.  
- **03:30–04:30** — DORA/SPACE dashboard & pod scorecard.  
- **04:30–05:00** — 2 pitfalls and how to avoid them.

> **Note:** Replace metrics with your actual deltas when ready (lead time ↓ ⊕%, deploy freq ↑ ⊕x, MTTR ↓ ⊕%).

