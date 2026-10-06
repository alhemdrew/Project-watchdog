<p align="center">
  <img src="docs/showcase/branding/watchdog-mark.svg" width="120" alt="Watchdog logo" />
</p>

# Project Watchdog

### Nigeria-first community security & incident intelligence

Watchdog is a trust-aware incident intelligence platform for communities that need to understand what is happening locally, before fragmented reports turn into rumor, confusion, or false urgency. It gives people a structured way to report events, attach evidence, corroborate claims, and understand where review and verification are still needed.

<p align="center">
  <img src="docs/showcase/watchdog-hero.svg" alt="Watchdog product hero" width="100%" />
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/PostGIS-4B8BBE?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostGIS" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/MapLibre-3D8BFF?style=for-the-badge&logo=mapbox&logoColor=white" alt="MapLibre" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</div>

## Why Watchdog exists

Public reporting is often fragmented: social posts, local alerts, personal messages, media clips, and incomplete updates all arrive without a clear sense of what has been observed, what has been corroborated, and what still needs review.

Watchdog is designed to make that information more usable. It separates report creation from evidence, distinguishes corroboration from verification, and keeps moderation decisions explicit instead of collapsing everything into a single vague signal.

## The product idea

Watchdog is not a generic social feed and it is not a truth detector. It is an evidence-and-corroboration system built for local situational awareness.

The current product flow is:

REPORTED → REVIEWING → CORROBORATED → VERIFIED → ACTIVE → RESOLVED

This helps people understand where a report is in the process, rather than pretending that every signal carries the same confidence.

## Product experience

### Discover

Watchdog starts with place-first discovery. The product helps people understand what is happening in a neighborhood, region, or wider area without losing context about the local environment.

![Home dashboard](docs/showcase/screenshots/home.png)

### Understand

The event feed and geographic exploration layer turn scattered reports into a navigable incident picture.

![Map view](docs/showcase/screenshots/map.png)

![Event feed](docs/showcase/screenshots/events.png)

![Event detail](docs/showcase/screenshots/event-detail.png)

### Report

Users can submit incident reports, add geographic context, and attach supporting media when available.

![Report workflow](docs/showcase/screenshots/reporting.png)

### Corroborate and verify

Trust is operational, not simplistic. Watchdog keeps signals, evidence, and review decisions distinct so that confidence can be built over time.

![Search and discovery](docs/showcase/screenshots/search.png)

![Profile and trust context](docs/showcase/screenshots/profile.png)

![Moderation workspace](docs/showcase/screenshots/moderation.png)

### Community and alerts

Community context and notifications remain visible as part of the broader product experience, while still preserving the separation between discussion and verified status.

![Community discussions](docs/showcase/screenshots/community.png)

![Alerts and notifications](docs/showcase/screenshots/alerts.png)

## Core principles

- Evidence does not equal truth.
- Trust is a reviewable operational signal, not a popularity metric.
- Geographic precision matters.
- Community reports must remain understandable, traceable, and contextualized.
- Moderation and verification should be explicit and auditable.

## Architecture

The product combines a strong frontend experience with a service layer built around reports, evidence, moderation, and spatial awareness.

![Watchdog architecture](docs/showcase/architecture/watchdog-architecture.svg)

## Technology stack

- Next.js
- React
- TypeScript
- Python
- FastAPI
- PostgreSQL + PostGIS
- Redis
- MapLibre
- Docker
- Playwright
- pytest

## Security and privacy

The product model is intentionally careful about how incident information is surfaced. It separates user identity, public reporting, trust context, and review outcomes so that operational decisions remain distinct from raw signal content.

## Current status

The public showcase reflects the real product surface already present in the application: discovery, map exploration, reporting, evidence flow, moderation, community context, and trust-aware review.

## Roadmap

The next layer is a stronger intelligence layer for local warnings, corroboration analysis, and structured public-safety briefings. That future roadmap is consistent with the product’s current trust and verification model without overstating what is already shipped.

## Public repository note

This repository is a curated product showcase for Watchdog. It presents the public-facing product, brand, and product story without exposing the private source implementation or the active development codebase.

---

<p align="center">
  <img src="docs/showcase/watchdog-map-card.svg" alt="Watchdog map card" width="80%" />
</p>
