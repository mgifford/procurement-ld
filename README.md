# Procurement Mind Map (2026 Perspective)

This repository contains a mind map of concepts around fair, effective, transparent, and equitable procurement, specifically geared towards government and the year 2026.

## Structure

The core information is organized in a [YAML-LD](https://yaml-ld.org/) document located at `docs/procurement.yamlld`.

The document includes:
- **@context**: Mapping terms to global ontologies.
- **Resources**: Credible sources for modern procurement.
- **Core Principles**: Definitions of fairness, effectiveness, transparency, equity, and open contracting.
- **Modern Concepts 2026**: Highlighting trends like "Government as Market Shaper", "Outcome-Based Procurement", and "Sovereign Capability".
- **DITAP Mappings**: Connecting these concepts to the [DITAP curriculum modules](https://github.com/usds/ditap-curriculum-update/).
- **Outliers and Emerging**: Concepts like "Intergenerational Well-being" and "Beneficial Ownership Transparency".

## Credible Resources

- **Procurement with Purpose** by Peter Smith & Mark Perera.
- **Posterity Global**: [User-centered and agile procurement](https://www.posterity.global/).
- **TandemGov**: [Government contracting expertise](https://www.tandemgov.com/).
- **Open Contracting Partnership**: [Global transparency standards](https://www.open-contracting.org/).
- **USDS DITAP**: [Digital IT Acquisition Professional Training](https://github.com/usds/ditap-curriculum-update/).

## Key Themes

### Outcome-Based Procurement
In 2026, the shift from buying hours to buying outcomes is central. Government requirements focus on solving specific problems and delivering measurable results, which allows for more objective evaluation and better alignment with strategic goals.

### Open Contracting
Open contracting is about proactive transparency throughout the entire procurement lifecycle. It uses data standards (like OCDS) to ensure that the public can monitor how money is spent, which helps combat corruption and improve efficiency.

### Government as Market Shaper
Government agencies are increasingly recognized for their role in helping to shape the economies in which they operate. By setting high standards and specific requirements (like accessibility or sovereign cloud requirements), they drive broader industry shifts and national capability.

### Accessibility
Accessibility is not just a checkbox but a fundamental driver of how software is created. Procurement mandates for accessible technology have successfully shifted the industry towards more inclusive design globally.

## How to Contribute & Absorb Knowledge

This mind map is designed to evolve. To add new insights from articles or research:

1.  **Identify the Concept**: Determine the core idea from the article (e.g., "Sovereign Capability").
2.  **Update the YAML-LD**: Add the concept to the appropriate section in `docs/procurement.yamlld`. If it's a new principle, add it to `core_principles`. If it's a specific trend, add it to `modern_concepts_2026`.
3.  **Map it**: If the concept relates to a DITAP module, update the `ditap_mappings` section.
4.  **Reference the Source**: Add the source to the `resources` section if it's a major organization or publication.
5.  **Verify**: Run a simple YAML syntax check to ensure the document remains valid.
    ```bash
    python3 -c "import yaml; yaml.safe_load(open('docs/procurement.yamlld'))"
    ```
6.  **Submit**: Create a pull request with your changes.
