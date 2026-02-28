# Procurement Mind Map (2026 Perspective)

This repository contains a mind map of concepts around fair, effective, transparent, and equitable procurement, specifically geared towards government and the year 2026.

## Information Architecture

### **[Interactive Visualizations & Knowledge Graph](docs/visualizations.md)**
View the **DITAP Competency & TechFAR Lifecycle Map** and global comparisons.

## Digital Procurement & USDS Alignment

Digital procurement in the US federal space is driven by the **United States Digital Service (USDS)** and the **Federal Acquisition Institute (FAI)**:

- **FAC-C-Digital Services (FAC-C-DS)**: A mandatory specialization for contracting professionals assigned to digital service acquisitions over the **FAR 13.500(c)** threshold.
- **DITAP**: The core training program designed to create "change ambassadors" capable of executing modern, agile digital procurements.
- **TechFAR Hub**: The central resource for implementing agile techniques (Modular Contracting, User Research, Tech Challenges) within the FAR framework.

## Structure

- **[Main Mind Map (YAML-LD)](docs/procurement.yamlld)**: Concepts, Principles, and **DITAP Performance Outcomes**.
- **[Digital Regulations Map (YAML-LD)](docs/digital-regulations.yamlld)**: Deep-dive into US (FAR/USDS) and UK (TCoP) digital standards.
- **[Global Comparative Analysis (YAML-LD)](docs/comparative-analysis.yamlld)**: Regional breakdowns (USA, UK, Canada, NZ).
- **[Agreement & Disagreement Analysis](docs/agreement-analysis.md)**: Global consensus vs. regional divergence.

## How to Contribute & Absorb Knowledge

This mind map is designed to evolve. To add new insights:

1.  **Identify the Concept**: Determine the core idea.
2.  **Update the YAML-LD**: Add it to the appropriate section in `docs/`.
3.  **Verify**: Run `python3 -c "import yaml; yaml.safe_load(open('docs/procurement.yamlld'))"`.
4.  **Submit**: Create a pull request to share your findings.
