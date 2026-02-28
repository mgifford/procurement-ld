# Procurement Mind Map (2026 Perspective)

This repository contains a mind map of concepts around fair, effective, transparent, and equitable procurement, specifically geared towards government and the year 2026.

## High-Level Principles

Modern government procurement is built on a foundation of integrity and value. The core principles include:

- **Fairness & Competition**: Ensuring a level playing field where innovation can thrive and favoritism is eliminated.
- **Transparency & Accountability**: Proactive disclosure of data across the entire lifecycle to build public trust.
- **Effectiveness & Outcome-Focus**: Delivering real-world results and strategic value rather than just checking compliance boxes.
- **Equity & Sustainability**: Using procurement to address systemic barriers and promote long-term societal well-being.
- **Integrity**: Upholding high ethical standards to combat corruption and ensure responsible spending.

## Engagement Calling Cards

Folks engage with modern procurement through these high-level "calling cards":

- **Results over Hours**: Shifting the conversation from inputs/credentials to actual problems solved.
- **Government as Market Shaper**: Using buying power to drive accessibility, resilience, and economic innovation.
- **Respecting Supplier Time**: Designing efficient, unbiased processes that don't waste market resources on unwinnable bids.
- **Proactive Disclosure**: Openly sharing selection criteria and results to ensure the "rules of the game" are clear.

## Global Comparative Analysis

Procurement practices vary by region, reflecting different geopolitical and social priorities.

- **[Comparative Analysis (YAML-LD)](docs/comparative-analysis.yamlld)**: Structured data on regional policy drivers (e.g., Buy American, Indigenous Targets, EU Green Procurement).
- **[Agreement & Disagreement Analysis](docs/agreement-analysis.md)**: A summary of global consensus vs. regional divergence (e.g., Open Markets vs. Domestic Preference).

## Structure

The core information is organized in a [YAML-LD](https://yaml-ld.org/) document located at `docs/procurement.yamlld`.

The document includes:
- **@context**: Mapping terms to global ontologies.
- **Resources**: Credible sources for modern procurement.
- **Core Principles**: Detailed definitions of foundational concepts.
- **Engagement Calling Cards**: High-level engagement themes.
- **Modern Concepts 2026**: Highlighting trends like "Sovereign Capability" and "Specialist Ecosystems".
- **DITAP Mappings**: Connecting these concepts to the [DITAP curriculum modules](https://github.com/usds/ditap-curriculum-update/).

## Credible Resources

- **Procurement with Purpose** by Peter Smith & Mark Perera.
- **Posterity Global**: [User-centered and agile procurement](https://www.posterity.global/).
- **Open Contracting Partnership**: [Global transparency standards](https://www.open-contracting.org/).
- **USDS DITAP**: [Digital IT Acquisition Professional Training](https://github.com/usds/ditap-curriculum-update/).
- **PQAR**: [Global standards for public procurement quality](https://pqar.org/public/).

## How to Contribute & Absorb Knowledge

This mind map is designed to evolve. To add new insights from articles or research:

1.  **Identify the Concept**: Determine the core idea (e.g., "Sovereign Capability").
2.  **Update the YAML-LD**: Add it to `docs/procurement.yamlld` or `docs/comparative-analysis.yamlld`.
3.  **Map it**: Update `ditap_mappings` or `engagement_calling_cards` if relevant.
4.  **Verify**: Run `python3 -c "import yaml; yaml.safe_load(open('docs/procurement.yamlld'))"`.
5.  **Submit**: Create a pull request to share your findings.
