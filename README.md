# Software Defined Defense

A capability-driven reference architecture for future defense ecosystems.

Software Defined Defense shifts military advantage from hardware-centric systems toward software, data, geospatial knowledge, and human-centered artificial intelligence.

## Pillars

- Software Defined Defense
- Military Knowledge Spaces
- Geospatial Knowledge Spaces
- Urban Geospatial Intelligence
- Operational Knowledge Twins
- Digital Battlespaces

## Demonstrations

### Tactical Core Integration

A reference implementation integrating Tactical Core services into a geospatial knowledge architecture.

### Battle Simulation

A simulated operational environment demonstrating:

- unit movement
- engagements
- mission execution
- situation awareness

### Urban Intelligence

An Urban GEOINT demonstration combining:

- IPB
- HUMINT
- OSINT
- Population Intelligence
- Threat Profiling

## Reference Architecture

```mermaid
flowchart TB

TC[Tactical Core]
MDC[Multi Domain Core]

TC --> GKS
MDC --> GKS

GKS[Geospatial Knowledge Spaces]

GKS --> MKS[Military Knowledge Spaces]

MKS --> OKT[Operational Knowledge Twin]

OKT --> DD[Decision Dashboard]
```

``