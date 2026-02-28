# Procurement Knowledge Graph & Visualizations

This document provides a visual representation of the repository's information architecture.

## 1. Core Relationship Mind Map

```mermaid
graph TD
    %% Core Concept Scheme
    Principles((CORE PRINCIPLES))
    Fairness[Fairness]
    Transp[Transparency]
    Unbundling[Unbundling Requirements]
    BestValue[Best Value to Crown]

    Principles --> Fairness
    Principles --> Transp
    Principles --> Unbundling
    Principles --> BestValue

    %% Regional Implementations
    subgraph USA
        FAR39[FAR Part 39]
        RFO[FAR Overhaul]
    end

    subgraph UK
        TCoP[Tech Code of Practice]
        Act2023[Procurement Act 2023]
    end

    subgraph Canada
        TBS[TBS Directive]
        CFTA[CFTA Chapter 5]
        IndTarget[5% Indigenous Target]
    end

    subgraph New_Zealand
        TeKupenga[Te Kupenga]
    end

    %% Linkages
    Unbundling --- TBS
    Unbundling --- FAR39
    BestValue --- TBS
    BestValue --- Act2023
    Transp --- CFTA
    Transp --- RFO

    %% Styling
    classDef principles fill:#f9f,stroke:#333,stroke-width:2px;
    class Principles,IndTarget,TeKupenga principles;
```

## 2. Digital Lifecycle Comparison

```mermaid
graph LR
    subgraph USA_TechFAR
        US_Pre[Agile Teams] --> US_Sol[Modular Design] --> US_Ev[Demos]
    end

    subgraph Canada_TBS
        CAN_Pl[Investment Planning] --> CAN_Un[Unbundling] --> CAN_It[Iterative/Phased]
    end

    US_Sol <--> CAN_Un : "Modular/Small Team Alignment"
```
