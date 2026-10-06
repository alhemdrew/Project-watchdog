<p align="center">
  <img src="docs/showcase/branding/watchdog-mark.svg" width="120" alt="Watchdog logo" />
</p>

# Project Watchdog

### Nigeria-first community security & incident intelligence

Watchdog is a community security and incident-intelligence platform designed to help people understand what is happening around them through structured reporting, geographic context, evidence, corroboration, and human verification.

It is built for local situational awareness, not generic social engagement. The product is intentionally designed to separate reports, evidence, corroboration, and verification so that uncertainty remains visible.

## What Watchdog does

- Structured local incident reporting with location context
- Geographic and regional signal discovery
- Evidence-backed reporting and media support
- Search and discovery across relevant activity
- Corroboration and trust-aware review workflows
- Verification and moderation with explicit review outcomes
- Community discussions and alerts that remain distinct from verified fact

## The problem

Local security information is often fragmented across social posts, messaging groups, informal reports, and isolated updates. In fast-moving situations, it can be hard to distinguish between a claim, a corroborated signal, evidence, and a verified outcome.

Watchdog is designed to make those distinctions clear without pretending that every signal has the same confidence.

## How it works

Report
  ↓
Review
  ↓
Corroboration
  ↓
Verification
  ↓
Active / Resolved

Watchdog is not a truth detector. It is an evidence-and-corroboration system designed to help people understand the current state of an event or signal while keeping uncertainty visible.

## Trust model

Watchdog treats trust as a process, not a popularity score.

REPORTED → REVIEWING → CORROBORATED → VERIFIED → ACTIVE → RESOLVED

This means:

- a report is not automatically a fact
- evidence supports but does not replace review
- corroboration strengthens confidence
- verification is a deliberate outcome
- moderation and human review remain important
- conflicting signals remain visible when necessary

## Product areas

### Discovery

Users can understand what is happening in a neighborhood, region, or broader area through location-aware discovery and signal context.

### Incident reporting

Users can create structured reports with supporting information and geographic context.

### Geographic intelligence

The system incorporates map-aware and region-aware incident discovery to improve local situational awareness.

### Evidence and corroboration

Evidence and related reports remain distinct from the original claim so that confidence can be built through corroboration rather than assumption.

### Verification and moderation

The platform separates report state from verification outcome so review and moderation decisions remain explicit.

### Search and discovery

Relevant incidents and local activity can be searched and explored without collapsing everything into one generic feed.

### Community and alerts

Community discussions and notifications provide context without treating discussion as verified fact.

## Technology

- Next.js
- React
- TypeScript
- Python
- FastAPI
- PostgreSQL
- PostGIS
- Redis
- MapLibre
- Docker
- Playwright
- pytest

## Current status

This repository is a public product showcase for the current Watchdog direction. It presents the product concept, core capabilities, and technical foundation without including the private implementation or active development codebase.

The current product includes the implemented surfaces described above, while future intelligence and broader automation layers remain planned work.

## Roadmap

Planned work includes:

- stronger regional intelligence and contextual summary layers
- richer corroboration and review workflows
- broader official-source and organization integration
- improved situational briefing and alerting capabilities
- a longer-term Watchdog Intelligence layer built on the existing trust and verification model

## Repository note

This repository is intentionally a public-facing product showcase. It is not a public software source tree for the private Watchdog implementation.
