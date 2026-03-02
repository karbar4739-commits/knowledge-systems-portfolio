# knowledge-systems-portfolio

Architectural notes and system designs for applied knowledge systems and RAG pipelines.

This repository presents selected knowledge system architectures
designed across analytical, operational, and product domains.

These systems are not demo chatbots.
They are structured knowledge interfaces built around
controlled retrieval, semantic modeling, and domain-aligned reasoning.

Full implementations are intentionally private.
This repository documents architecture and design decisions only.

---

## Systems Overview

### 1. Analytical Case-Based RAG
Domain: structured case analysis  
Focus: cognitive-aligned chunking and reasoning support  

→ systems/01_analytical_case_rag.md

### 2. Operational Entity-Centric System
Domain: property & concierge operations  
Focus: entity-level embeddings + metadata-driven logic  

→ systems/02_operational_entity_system.md

### 3. Strict Product QA System
Domain: regulated product knowledge  
Focus: boundary-controlled answers and compliance-aware retrieval  

→ systems/03_strict_product_qa.md

---

## Design Philosophy

All systems are built around:

- Knowledge structure first
- Retrieval as architecture, not feature
- Metadata-aware reasoning
- Controlled failure modes
- Explicit boundary enforcement

See: architecture/design_principles.md

## Publications

Related research notes available on Zenodo:

- https://zenodo.org/records/18258394
- https://zenodo.org/records/18826907
- https://zenodo.org/records/18827008
