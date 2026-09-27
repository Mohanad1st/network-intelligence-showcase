<p align="center"><img src="assets/banner.svg" alt="Network Intelligence" width="100%"></p>

<p align="center"><b>Relationships, opportunities and content in one self-hosted workspace</b></p>

<p align="center"><b>Status:</b> Pilot, self-hosted &nbsp;·&nbsp; <b>Built by</b> <a href="https://github.com/Mohanad1st">Mohannad Hesham</a></p>

> Case study only: the source is private because it is built to hold personal contact data. Walkthrough on request.

## The problem

A solo consultant's network lives across LinkedIn, X and email, and the follow-ups, opportunities and content ideas that come out of it get lost between apps. This is a self-hosted workspace that ties people, conversations and posts together, with AI helping to draft — and a person approving everything that goes out.

## What it does

- One contact list across LinkedIn, X and email, with duplicates merged
- Opportunity tracking and reminders to re-engage past contacts
- Draft, review and approve posts, threads and newsletters in a consistent voice
- Schedule approved content to social channels (built and tested, not yet used live)
- A workflow hub with run history, and a chat assistant over your own data

## See it

How the work flows:

```mermaid
flowchart TD
  accTitle: How Network Intelligence handles contacts and content
  accDescr: Contacts from LinkedIn, X and email go into a local store, which feeds follow-ups and AI-assisted drafts; you review every draft, and only approved ones are scheduled.
  A[Contacts] --> B[(Local store)]
  B --> C[Follow-ups]
  B --> D[AI drafts]
  D --> E{You review}
  E -- approve --> F[Scheduled]
  E -- edit --> D
```

<sub>Screens are not shown because the app is built to hold personal contact data.</sub>

## Built with

Next.js · React · TypeScript · local database · Claude for drafting · a social scheduling service

## Built responsibly

- Nothing is published without a review and approval step
- No automated liking, commenting, following or messaging on LinkedIn — engagement stays manual by design
- No background scraping of social feeds
- Personal data is stored locally, and credentials are encrypted at rest
- Access fails closed, and 170+ automated tests run against an isolated test database

## What it deliberately doesn't do

- It is not a growth-hacking or automation bot. It organises your own relationships; it does not act for you.

## More from Impact Anchor

- [ImpactAnchor Reels](https://github.com/Mohanad1st/impactanchor-reels-showcase) — Recorded sessions in; scored, subtitled, scheduled short videos out
- [Impact Anchor — consulting site](https://github.com/Mohanad1st/impact-anchor-site-showcase) — From AI overwhelm to a working adoption plan, for mission-driven teams
- [AI Governance Roadmap](https://github.com/Mohanad1st/ai-governance-roadmap-showcase) — A free course that takes you from first definitions to a working AI governance plan
- [Anchor Learning Hub](https://github.com/Mohanad1st/anchor-learning-hub-showcase) — Interactive, bilingual, offline-ready learning for workshops and training programmes

---

<sub>© 2026 Mohannad Hesham. Showcase text and images only — no source code is published or licensed here. See all my work on <a href="https://github.com/Mohanad1st">my GitHub profile</a> · <a href="https://www.linkedin.com/in/mohannadhesham/">LinkedIn</a>.</sub>
