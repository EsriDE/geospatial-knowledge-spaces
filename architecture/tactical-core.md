# Tactical Core Integration

## Purpose

The Tactical Core provides operational battlefield data.

Examples:

- Unit Positions
- Mission Tasks
- Sensor Reports
- Status Updates

---

## Philosophy

The Tactical Core is not the final destination.

The Tactical Core is a producer of operational observations.

Knowledge Spaces provide meaning.

---

## Architecture

```mermaid
flowchart LR

TC[Tactical Core]

GKS[Geospatial Knowledge Space]

AI[GeoAI]

DT[Operational Twin]

TC --> GKS
GKS --> AI
AI --> DT
```

---

## Example

Unit movement from Tactical Core becomes:

- movement patterns
- threat indicators
- mission context
- predictive assessments

inside the Geospatial Knowledge Space.