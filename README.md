# Procurement Mind Map (2026 Perspective)

This repository contains a mind map of concepts around fair, effective, transparent, and equitable procurement, specifically geared towards government and the year 2026.

## Information Architecture

### **[Interactive Visualizations & Knowledge Graph](docs/visualizations.md)**
Click the link above to view the **Mermaid diagrams** that map core principles, regional regulations (US/UK/CANZ), and identify outliers like "Intergenerational Well-being."

## High-Level Principles

Modern government procurement is built on a foundation of integrity and value:

- **Fairness & Competition**: Ensuring a level playing field where innovation can thrive.
- **Transparency & Accountability**: Proactive disclosure of data across the entire lifecycle.
- **Social Value**: Using procurement to improve the social, environmental, and economic well-being of local areas.
- **Outcome-Focus**: Delivering real-world results rather than just checking compliance boxes.

## Digital Procurement & Global Regulations

Digital procurement is a critical focus, with specific regulatory support across major regions:

- **United Kingdom**: Guided by the **Procurement Act 2023** and the **Technology Code of Practice (TCoP)**.
- **United States**: Managed through the **FAR Part 39** and the **Revolutionary FAR Overhaul (RFO)**.
- **Global Consensus**: Widespread adoption of **Modular Contracting**, **Open Source**, and **Accessibility** standards.

## Structure

- **[Main Mind Map (YAML-LD)](docs/procurement.yamlld)**: Concepts, Principles, and DITAP Mappings.
- **[Digital Regulations Map (YAML-LD)](docs/digital-regulations.yamlld)**: Deep-dive into US and UK digital standards.
- **[Global Comparative Analysis (YAML-LD)](docs/comparative-analysis.yamlld)**: Regional data on policy drivers.
- **[Agreement & Disagreement Analysis](docs/agreement-analysis.md)**: Global consensus vs. regional divergence.
- **[Resource Reliability Vetting](docs/resource-vets.md)**: Analysis of the authority and reliability of all cited sources.

## How to Contribute & Absorb Knowledge

This mind map is designed to evolve. To add new insights:

1.  **Identify the Concept**: Determine the core idea.
2.  **Update the YAML-LD**: Add it to the appropriate section in `docs/`.
3.  **Map it**: Update the visualizations if the relationship changes.
4.  **Verify**: Run `python3 -c "import yaml; yaml.safe_load(open('docs/procurement.yamlld'))"`.
5.  **Submit**: Create a pull request to share your findings.
