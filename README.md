
# Akasha Events

Akasha Events is the canonical **event schema and ingestion layer** for the Akasha ecosystem.

Everything that happens in Akasha — observations, API data, human reports, sensor data, discovery results — is recorded as an **Event**.

Events provide the universal language connecting:

- akasha-time-nexus (time context)
- akasha-apis (external data sources)
- akasha-grand-atlas (knowledge registry)
- discovery engines
- mythology engines

## Philosophy

Science advances when anomalies are recorded.

Akasha Events exists to capture observations without bias so correlations can later be discovered.

## Core Concept

All data becomes:

Event

Example:

event_id: akasha-0001
timestamp: 2026-03-30T20:00:00Z
location: 38.41,-82.44
category: astronomical
source: nasa_api
payload:
  solar_flare_class: M2
confidence: 0.92
