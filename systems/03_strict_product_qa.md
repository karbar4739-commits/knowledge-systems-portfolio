# Strict Product Knowledge QA System

Domain:
Regulated cosmetic and supplement products.

Problem:
Answers must remain within product boundaries.
No cross-product hallucination allowed.

Key Concepts:
- strict_product_boundary flag
- product-scoped retrieval
- fact-question detection
- list-mode enumeration
- controlled fallback

Modes:
1. Strict product fact retrieval
2. Full product description assembly
3. Group-based enumeration
4. Semantic overview (low confidence)

Failure Philosophy:
When uncertain → explicit fallback.
No speculative answers.

Implementation intentionally not public.
