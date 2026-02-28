# Procurement Knowledge Graph & Visualizations

## 1. The Conceptual Bridge (Linking RFO, OBP, DITAP)

This diagram shows how abstracted "Bridging Approaches" connect specific regulatory and training frameworks.

```mermaid
graph TD
    %% Abstract Bridges
    Bridge1(Principle-Led Discretion)
    Bridge2(Iterative Value Delivery)
    Bridge3(Outcome-Oriented Specs)
    Bridge4(Market Shaping)

    %% Specific Frameworks
    subgraph FAR_Overhaul_RFO
        Rule2Prin[Rule-Based to Principle-Based]
        CODiscretion[CO Discretion]
    end

    subgraph DITAP_Curriculum
        O5[Outcome 5: Leading Change]
        O3[Outcome 3: Buying Techniques]
        O2[Outcome 2: Determine Problem]
    end

    subgraph Outcome_Based_Procurement
        ResultsNotHours[Results over Hours]
        PerfAdjust[Performance Adjustments]
    end

    %% Mappings
    Bridge1 --- Rule2Prin
    Bridge1 --- O5
    Bridge1 --- ResultsNotHours

    Bridge2 --- O3
    Bridge2 --- PerfAdjust
    Bridge2 --- Bridge3

    Bridge3 --- O2
    Bridge3 --- ResultsNotHours

    %% Outliers
    Intergen((Outlier: Intergenerational Well-being))
    Bridge4 -.-> Intergen

    %% Styling
    classDef bridge fill:#ddf,stroke:#333,stroke-width:2px;
    class Bridge1,Bridge2,Bridge3,Bridge4 bridge;
```

## 2. Digital Lifecycle Comparison

```mermaid
graph LR
    subgraph TechFAR_Hub_USA
        US_Pre[Agile Teams] --> US_Sol[Modular Design] --> US_Ev[Demos]
    end

    subgraph TCoP_UK
        UK_Needs[User Needs] --> UK_Open[Open Standards] --> UK_Flex[Flexible Procedure]
    end

    US_Sol <--> UK_Open : "Shared Interoperability Goal"
```
