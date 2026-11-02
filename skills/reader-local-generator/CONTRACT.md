# Reader-local generator role contract

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by this document  
**Related proposed ADR:** [ADR-JPUB-003](../../docs/decisions/adr-jpub-003-reader-local-investigation.md)

This separate optional role would propose an inspectable investigation procedure adapted to a reader-controlled corpus, tools, models, permissions, constraints, and relevance questions. It is not the generic reader and does not expose the private reader context to the publisher.

## Proposed behavior

- Identify publisher-selected relationships, defensible positives, negatives, ambiguous cases, and boundary conditions.
- Inventory only reader-authorized local capabilities.
- Propose discriminating experiments and matched controls.
- Write a draft procedure to a reader-owned location.
- Require review and tiny fixtures before any installation or execution.
- Distinguish retrieval, contrastive discrimination, and reader-local relevance.

Hard negatives are task- and instrument-relative. Scorer outputs are not probabilities of truth.

## Evaluation hypothesis

The extra generation step may improve useful local relation recovery over direct application of identical examples under matched cost. This is untested. If it does not add independently judged value, prefer the simpler reader path.
