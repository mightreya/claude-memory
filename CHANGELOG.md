# Changelog

## 0.2.0 (2026-03-19)

- Add cross-encoder reranking to hybrid search pipeline (~300ms for 20 docs on CPU)
  - Precision@7 (fraction of relevant results): 62% → 67%
  - MRR (how often the best result is ranked first): 79% → 93%
- Remove dead workflow-state extraction code

## 0.1.0

Initial release.
