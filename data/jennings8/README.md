# Jennings 8 Machine-Readable Case Graph

This directory contains structured CSV data derived from the narrative research files.

Files:
- `case_nodes.csv` — victims, people, institutions, locations.
- `case_edges.csv` — sourced relationships between nodes.

## Evidence tiers

- **A** — official / primary / contemporaneous official-based reporting
- **B** — named family or firsthand witness
- **C** — later investigative journalism / claimed case-file material
- **D** — later documentary / secondary
- **E** — theory only

## Rules

1. The graph is **not a suspect scoring system**.
2. A social edge is not evidence of homicide involvement.
3. A law-enforcement relationship edge is not evidence of a cover-up.
4. `excluded` edges reflect a specific documented exclusion only.
5. Missing edges do not mean a relationship did not exist.
6. Filter to evidence tier A/B when building "documented-only" visualizations.
7. Keep disputed/unverified edges visibly different.

The goal is to make future network analysis reproducible and to prevent speculative relationships from becoming visually indistinguishable from documented facts.
