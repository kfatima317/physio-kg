# Physiotherapy Knowledge Graph (Research Project)

A verified, queryable knowledge graph for evidence-based physiotherapy interventions, built from WHO, CDC, Cochrane, and peer-reviewed guidelines.

## Structure

- `raw_data/` – Original PDFs and official documents (organized by source)
- `processed_data/` – Extracted triples, CSVs, normalized entities
- `provenance/` – Master tracking table (`master_provenance.csv`)
- `scripts/` – Data extraction, NLP, and validation code (Python, etc.)

## Data Sources

- World Health Organization (WHO)
- U.S. Centers for Disease Control and Prevention (CDC)
- Cochrane Library
- PubMed / National Library of Medicine
- NICE Guidelines

## Validation

All sources undergo PRISMA-inspired screening. Only peer-reviewed or official institutional publications are included.

## Tools

- Neo4j (property graph)
- Neosemantics (n10s) for RDF/SPARQL
- DiffBot API (structured extraction)
- spaCy / SciSpacy (NLP)

> Part of a Richter research project with Prof. Shengting Cao, Computer Science Department.
