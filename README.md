<p align="center">
  <img src="docs/showcase/branding/watchdog-mark.svg" width="120" alt="Watchdog logo" />
</p>

# Project Watchdog

<p align="center">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="PostGIS" src="https://img.shields.io/badge/PostGIS-4E7A4E?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img alt="MapLibre" src="https://img.shields.io/badge/MapLibre-2D5BFF?style=for-the-badge&logo=mapbox&logoColor=white" />
</p>

## Global community security & incident intelligence

Watchdog is a global community security and incident intelligence platform built to help people understand what is happening around them without mistaking rumor, evidence, and verified status for the same thing.

The product is designed around signal quality: structured reporting, geographic context, corroboration, human review, and clear operational trust. It is not a generic social platform, and it does not pretend every report carries the same confidence.

> The live implementation remains private. This repository is a public product showcase only. The source code, environment files, and internal operational details are intentionally not included here.

## The problem

In fast-moving situations, people often consume safety information from fragmented sources: local conversations, social posts, scattered alerts, incomplete reports, and media updates that are hard to verify in context.

The challenge is not just collecting information. It is separating:

- a claim
- a piece of evidence
- corroborating context
- a review decision
- a verified status

Watchdog exists to make that structure visible.

## Why Watchdog matters

A report is not automatically a fact.

Evidence does not automatically equal certainty.

Corroboration adds confidence.

Verification is an explicit review outcome.

Trust is a process, not a popularity score.

The product lifecycle is intentionally modeled as:

REPORTED → REVIEWING → CORROBORATED → VERIFIED → ACTIVE → RESOLVED

## Product surfaces

### Discovery

The home experience brings local signals into place-first discovery without collapsing geography into a vague feed.

<p align="center">
  <img src="docs/showcase/screenshots/home.png" width="900" alt="Watchdog home dashboard" />
</p>

### Geographic intelligence

The map layer turns scattered reports into a navigable picture of local conditions, region-aware context, and signal density.

<p align="center">
  <img src="docs/showcase/screenshots/map.png" width="900" alt="Watchdog map view" />
</p>

### Incident feed

The feed exposes relevant activity in a form that balances visibility with context and status.

<p align="center">
  <img src="docs/showcase/screenshots/event.png" width="900" alt="Watchdog event feed" />
</p>

### Incident detail

Each event can carry context, review state, and evidence without flattening everything into one certainty label.

<p align="center">
  <img src="docs/showcase/screenshots/event-details.png" width="900" alt="Watchdog incident detail" />
</p>

### Reporting flow

Users can create structured reports with location context and supporting media in a clear workflow.

<p align="center">
  <img src="docs/showcase/screenshots/reporting.png" width="900" alt="Watchdog reporting flow" />
</p>

### Search and discovery

Watchdog supports search across relevant events and activity to surface the right signals in context.

<p align="center">
  <img src="docs/showcase/screenshots/search.png" width="900" alt="Watchdog search and discovery" />
</p>

### Moderation and review

Trust is operational. Review, escalation, and contributor standing are not treated as vanity metrics.

<p align="center">
  <img src="docs/showcase/screenshots/moderation.png" width="900" alt="Watchdog moderation workspace" />
</p>

### Community and alerts

Community discussion and notifications remain distinct from verified fact and review outcomes.

<div align="center">
  <img src="docs/showcase/screenshots/community.png" width="45%" alt="Watchdog community" />
  <img src="docs/showcase/screenshots/alerts.png" width="45%" alt="Watchdog alerts" />
</div>

### Profile and trust context

User context and trust signals give the platform a clearer sense of contributor standing and review history.

<p align="center">
  <img src="docs/showcase/screenshots/profile.png" width="900" alt="Watchdog profile and trust context" />
</p>

## Screenshot gallery

<div align="center">
  <img src="docs/showcase/screenshots/home.png" width="48%" alt="Home dashboard" />
  <img src="docs/showcase/screenshots/map.png" width="48%" alt="Map view" />
</div>

<div align="center">
  <img src="docs/showcase/screenshots/reporting.png" width="48%" alt="Report workflow" />
  <img src="docs/showcase/screenshots/moderation.png" width="48%" alt="Moderation workspace" />
</div>

<div align="center">
  <img src="docs/showcase/screenshots/event.png" width="48%" alt="Event feed" />
  <img src="docs/showcase/screenshots/profile.png" width="48%" alt="Profile and trust context" />
</div>

<div align="center">
  <img src="docs/showcase/screenshots/search.png" width="48%" alt="Search interface" />
  <img src="docs/showcase/screenshots/community.png" width="48%" alt="Community view" />
</div>

## Product principles

### Evidence does not equal truth

Watchdog clearly separates:

- report submission
- supporting evidence
- corroboration
- review and moderation
- verification state
- correction or revocation

This prevents the system from collapsing all incoming information into a single certainty claim.

### Geographic precision matters

The product distinguishes between device-level precision, approximate location, region scope, and broader area awareness. That matters for both trust and privacy.

### Trust is operational and visible

Contributor standing, moderation context, and explicit status changes are treated as product signals rather than simplistic popularity metrics.

## Architecture

The current platform is structured around a real multi-layer product stack: a frontend, API, relational and geospatial database, realtime services, and moderation/review workflows.

<p align="center">
  <img src="docs/showcase/architecture/watchdog-architecture.svg" width="1000" alt="Watchdog architecture overview" />
</p>

## Technology stack

| Layer | Stack |
| --- | --- |
| Web | Next.js · React · TypeScript |
| API | Python · FastAPI |
| Database | PostgreSQL · PostGIS |
| Runtime / state | Redis · Docker |
| Mapping | MapLibre |
| Quality | Playwright · pytest |

## Security and privacy

Watchdog is designed with an operational approach to trust and safety:

- user identity remains conceptually separate from public reporting
- moderation and review are explicit workflows
- evidence remains distinct from final verification state
- geographic precision can be scoped appropriately for privacy and utility
- internal implementation and operational details are kept private

## Roadmap

The product direction continues to push toward broader situational intelligence:

- regional intelligence and briefing layers
- official-source and organization integration
- richer corroboration and conflict tracking
- stronger live trust and review workflows
- broader public-safety coverage and intelligence layers

## Source code status

This repository is intentionally a public product showcase, not a public source tree for the live Watchdog implementation.

The product is private because it is a security-focused operational platform under active development. The implementation includes architecture, infrastructure, workflows, and operational details that are not suitable for public disclosure.

The public-facing direction remains real, visible, and product-accurate without exposing the private implementation.

## Final note

Watchdog is built for the hard problem of understanding fast-moving local events without treating raw information as fact.

It is a product for context, review, geography, and trust — not for noise, unchecked claims, or social amplification alone.

Watchdog is a global community security and incident intelligence platform.
