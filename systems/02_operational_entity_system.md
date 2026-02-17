# Operational Entity-Centric Knowledge System

Domain:
Property and concierge operations.

Knowledge Model:
Each real-world entity (apartment, resident, vehicle, procedure)
is represented as a single semantic object.

No document chunking is used.

Core Idea:
Embedding supports discovery,
but metadata controls correctness.

Retrieval Strategy:
- metadata-first filtering
- strict name matching
- rule-based branching before semantic fallback

Architecture Pattern:
Entity-level embedding + deterministic operational logic.

Failure Handling:
Semantic search only activates as fallback.
Operational answers are deterministic.

Full ingest and backend implementation are private.
