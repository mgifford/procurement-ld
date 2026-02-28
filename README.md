# Procurement Mind Map (2026 Perspective)

This repository contains a mind map of concepts around fair, effective, transparent, and equitable procurement, specifically geared towards government and the year 2026.

## Information Architecture

### **[Interactive Visualizations & Knowledge Graph](docs/visualizations.md)**
View the **Conceptual Bridge** diagram that connects the US FAR Overhaul (RFO), Outcome-Based Procurement (OBP), and DITAP curriculum.

## Cross-Document Mapping

A key feature of this repository is the ability to connect high-level principles to specific regulatory and training documents through "Bridging Approaches":

- **Principle-Led Discretion**: Maps the **RFO's** shift from rule-based to principle-based systems to **DITAP's** Outcome 5 (Leading Change).
- **Iterative Value Delivery**: Connects **FAR Part 39's** modular contracting to **DITAP's** agile buying techniques and iterative outcomes.
- **Outcome-Oriented Specifications**: Bridges the core tenet of **Outcome-Based Procurement** ("Results over Hours") to **DITAP's** Outcome 2 (Determining the Problem).
- **Market Shaping**: Links regional policies (UK Social Value, Canadian Indigenous Targets) to the global accessibility and sovereignty consensus.

## Structure

- **[Main Mind Map (YAML-LD)](docs/procurement.yamlld)**: Concepts, Principles, and DITAP Performance Outcomes.
- **[Principle Mapping (YAML-LD)](docs/principle-mapping.yamlld)**: The "Conceptual Bridge" between RFO, OBP, and DITAP.
- **[Digital Regulations Map (YAML-LD)](docs/digital-regulations.yamlld)**: US (FAR/USDS) and UK (TCoP) digital standards.
- **[Global Comparative Analysis (YAML-LD)](docs/comparative-analysis.yamlld)**: Regional breakdowns (USA, UK, Canada, NZ).

## How to Contribute & Absorb Knowledge

This mind map is designed to evolve. To add new insights:

1.  **Identify the Concept**: Determine the core idea.
2.  **Update the YAML-LD**: Add it to the appropriate document in `docs/`.
3.  **Verify**: Run `python3 -c "import yaml; [yaml.safe_load(open(f)) for f in ['docs/procurement.yamlld', 'docs/principle-mapping.yamlld']]"`
4.  **Submit**: Create a pull request to share your findings.
