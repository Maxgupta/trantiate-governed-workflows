# Conceptual architecture

This diagram explains responsibilities and decision paths. It is not a verified diagram of the private implementation.

```mermaid
flowchart TD
    S["Human Seer"] --> W["Bounded work order"]
    W --> M["AI Maker"]
    M --> P["Proposal and evidence"]
    P --> C["AI Checker"]
    C --> R["Review record"]
    R --> B["Human Buyer"]
    B --> D["Recorded decision"]
    R -->|"Correction required"| M
    W --> E["Evidence and decision records"]
    P --> E
    R --> E
    D --> E
    M -->|"Mandate exceeded"| S
    C -->|"Uncertainty or conflict"| S
```

## Authority boundary

The Maker proposes; the Checker reviews; the Buyer accepts or rejects. This illustration grants no merge or deployment permissions. Technical enforcement of those boundaries must be demonstrated separately in an implementation.

## Evidence boundary

Records link the objective, proposal, review, and decision. A recorded assertion is not independently verified evidence. A real implementation should bind reviews and release decisions to immutable revisions and reproducible checks.
