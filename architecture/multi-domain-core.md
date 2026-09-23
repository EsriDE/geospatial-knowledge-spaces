# Multi Domain Core

## Purpose

The Multi Domain Core provides operational data spanning domains beyond the tactical land picture: air, maritime, cyber, and space.

Examples:

- Air Track Data
- Maritime Vessel Tracking
- Cyber Incident Reports
- Space and Signal Observations

---

## Philosophy

The Multi Domain Core is not a replacement for Tactical Core. It complements it by supplying cross-domain observations that Tactical Core does not cover.

Like Tactical Core, the Multi Domain Core is a producer of operational observations. Knowledge Spaces provide meaning.

---

## Architecture

```mermaid
flowchart LR

MDC[Multi Domain Core]

GKS[Geospatial Knowledge Space]

AI[GeoAI]

DT[Operational Knowledge Twin]

MDC --> GKS
GKS --> AI
AI --> DT
```

---

## Example

An air track and a maritime vessel report, combined with land-based Tactical Core data inside the Geospatial Knowledge Space, become:

- cross-domain movement correlation
- multi-domain threat indicators
- unified mission context

inside the Operational Knowledge Twin.
