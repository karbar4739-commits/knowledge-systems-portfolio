# Analytical Case-Based RAG

Domain:
Structured analytical case knowledge.

Problem:
Case material contains mixed factual, narrative,
behavioral and interpretive content.

Key Design Decision:
Chunking is aligned with cognitive roles,
not token length.

Knowledge Units:
- fact summaries
- detailed descriptions
- behavioral patterns
- signature elements
- contextual factors

Retrieval Strategy:
- semantic retrieval
- section-prioritized ranking
- adaptive thresholding (single vs multi analysis modes)

Backend Logic:
- case ID extraction
- section priority reordering
- hybrid ranking (semantic score + cognitive role)

Failure Control:
- explicit threshold control
- mandatory case ID in single mode
- structured context framing for LLM consumption

Implementation intentionally omitted.
