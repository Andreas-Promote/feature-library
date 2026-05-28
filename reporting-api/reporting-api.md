# Reporting API

**Status:** Available (requires technical setup)
**Category:** Reporting · Analytics
**Pillar:** Training Management
**Audience:** L&D / Enterprise · Training Providers (decision-makers, L&D leads, Operations)

---

## Summary

The Promote Reporting API lets organisations connect Promote to external BI tools — such as Power BI, Tableau, or Looker — and pull learning data automatically on a schedule. Instead of manual exports, your dashboards stay current and your learning data can sit alongside other business data in a single view.

---

## The problem it solves

Organisations using Promote for learning often want to report on training data at a level that goes beyond what's inside the platform — combining it with HR data, performance data, or company-wide dashboards. Without an API, that means manual exports, stale spreadsheets, and data that lives in a silo.

The Reporting API removes that friction entirely. Once set up, data flows automatically — no ongoing manual work, no disconnected reports.

---

## What it unlocks

- **Live dashboards** — learning data stays current in any BI tool, updated on schedule without manual intervention
- **One view of the business** — combine Promote data with HR, performance, or operational data in a single report
- **Set it up once** — a developer or BI specialist configures the integration once; from there it runs automatically

---

## Available data

| Data type | What it covers |
|-----------|---------------|
| Learner progress | Individual activity, task completion, and engagement across programs |
| Program summary | Aggregated completion rates, task counts, and engagement per program |
| Goals | Goal progress per learner and program |
| Coaches & facilitators | Activity, engagement, and pending review tasks across the delivery team |
| User qualifications | Qualification records including type, version, validity, and status |
| AI conversations | Interactions between learners and AI assistants in programs |
| Comments & discussions | Individual comments and discussion activity across programs |
| Users & permissions | User account data, sign-in information, and roles |

All data can be filtered by program or user, and supports paginated export for large datasets.

---

## What you could build

- A live Power BI or Tableau dashboard showing completion rates, engagement, and goal progress across all programs — updated automatically
- A single report combining Promote learner data with HR or performance data to measure the impact of training on business outcomes
- An automated compliance report pulling qualification status for every employee — always audit-ready, no manual chasing
- A coach and facilitator activity overview across multiple programs, surfacing where delivery is strongest and where support is needed
- An AI usage report showing how learners engage with AI assistants — to inform how AI-enabled programs are developed going forward

---

## Getting started

Decide what you want to build, then loop in a developer or BI specialist. The API documentation is available directly inside Promote. Promote support can help scope the right approach.

---

## Positioning notes

- **This is a decision-maker article** — the audience is L&D leads, Operations, or anyone who sees the value and can commission a technical implementation. Do not lead with API mechanics.
- Lead with the **outcome**: live, connected dashboards — not the how.
- The strongest angle for **enterprise customers** is combining learning data with HR/performance data in a single view — this is often a key ask that feels out of reach.
- For **Training Providers**: the compliance reporting use case (qualification status, audit-ready) is the most compelling angle.
- The **AI conversations** data point is a future-facing differentiator — worth highlighting for customers already using or considering AI features.
- This requires a developer or BI specialist to set up — frame as "set it up once, runs forever" not as a barrier.
- **Do not cover** the user/program management API — that is a separate topic for a future article.

---

## Links

- Help Center article: [Using the Promote API for reporting](https://promote.zendesk.com/hc/en-us)
- Web version: `reporting-api-web.html`
- Email version: `reporting-api-email.html`

---

*Last updated: May 2026*
