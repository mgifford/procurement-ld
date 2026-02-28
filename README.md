# Procurement Mind Map (2026 Perspective)

This repository contains a mind map of concepts around fair, effective, transparent, and equitable procurement, specifically geared towards government and the year 2026.

## High-Level Principles

Modern government procurement is built on a foundation of integrity and value. The core principles include:

- **Fairness & Competition**: Ensuring a level playing field where innovation can thrive and favoritism is eliminated.
- **Transparency & Accountability**: Proactive disclosure of data across the entire lifecycle to build public trust.
- **Effectiveness & Outcome-Focus**: Delivering real-world results and strategic value rather than just checking compliance boxes.
- **Equity & Sustainability**: Using procurement to address systemic barriers and promote long-term societal well-being.
- **Integrity**: Upholding high ethical standards to combat corruption and ensure responsible spending.

## Digital Procurement & US Federal Regulations

Digital procurement is a critical focus, with specific regulatory support for agile and modular practices:

- **Modular Contracting**: Acquiring systems in successive, interoperable increments (FAR Part 39). This reduces risk and allows work to be distributed to small, coordinated teams.
- **Revolutionary FAR Overhaul (RFO)**: A major shift from "Rule-Based" to **"Principle-Based"** procurement, prioritizing mission effectiveness and common sense.
- **Open Standards & Open Source**: Prioritizing non-proprietary solutions to prevent vendor lock-in and ensure long-term sovereignty.
- **Phased Evaluations**: Moving toward "tech challenges" and practical demonstrations rather than just paper proposals.

## Structure

The core information is organized in a [YAML-LD](https://yaml-ld.org/) document located at `docs/procurement.yamlld`.

- **[Main Mind Map](docs/procurement.yamlld)**: Concepts, Principles, and DITAP Mappings.
- **[Digital Regulations Map](docs/digital-regulations.yamlld)**: Specific deep-dive into FAR Part 39 and RFO updates.
- **[Global Comparative Analysis](docs/comparative-analysis.yamlld)**: Regional data on policy drivers.
- **[Agreement & Disagreement Analysis](docs/agreement-analysis.md)**: Global consensus vs. regional divergence.

## Credible Resources

- **Procurement with Purpose** by Peter Smith & Mark Perera.
- **Posterity Global**: [User-centered and agile procurement](https://www.posterity.global/).
- **Open Contracting Partnership**: [Global transparency standards](https://www.open-contracting.org/).
- **USDS DITAP**: [Digital IT Acquisition Professional Training](https://github.com/usds/ditap-curriculum-update/).
- **Acquisition.gov**: [Federal Acquisition Regulation (FAR)](https://www.acquisition.gov/browse/index/far) and [FAR Overhaul](https://www.acquisition.gov/far-overhaul).

## How to Contribute & Absorb Knowledge

This mind map is designed to evolve. To add new insights from articles or research:

1.  **Identify the Concept**: Determine the core idea (e.g., "Sovereign Capability").
2.  **Update the YAML-LD**: Add it to `docs/procurement.yamlld` or the specific deep-dive documents.
3.  **Map it**: Update `ditap_mappings` or `engagement_calling_cards` if relevant.
4.  **Verify**: Run `python3 -c "import yaml; yaml.safe_load(open('docs/procurement.yamlld'))"`.
5.  **Submit**: Create a pull request to share your findings.
