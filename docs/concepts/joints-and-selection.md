# Joints and selection

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by this document  
**Related proposed ADR:** [ADR-JPUB-002](../decisions/adr-jpub-002-publication-object-before-renderings.md)

The following vocabulary is provisional design language, not standardized terminology.

A **joint** is a selected relationship, contradiction, transition, discontinuity, or cross-domain connection that may change how surrounding materials are interpreted, investigated, or acted on. It is more specific than a topic match or citation, and its significance remains open to disagreement.

A publication may expose part of a publisher's **selection** by carrying the relevant materials, marked connections, selection reasons, useful negatives, near-misses, and disputed boundaries. This is not a demand to publish every source or private reasoning trace.

A **claim** is a challengeable proposition about a joint. A **hypothesis** states a prospective relationship, method, expected observation, and failure condition. A **candidate application** is an optional action or remedy. A **rendering** is a recipient-facing account. These can succeed or fail independently: rejection of a remedy does not erase an observation, and one passing test does not prove a broad explanation.

Useful public design goals include:

- distinguish observation from inference and recommendation;
- retain counterevidence and negative controls;
- provide claim-level falsifiers and uncertainty;
- support scoped, conflicting interpretations;
- allow reader-local relevance without claiming access to the reader's private context; and
- leave an incomplete relationship incomplete rather than inventing closure to satisfy a data shape.
