# Component map

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by this document  
**Related proposed ADRs:** [ADR-JPUB-002](../decisions/adr-jpub-002-publication-object-before-renderings.md), [ADR-JPUB-003](../decisions/adr-jpub-003-reader-local-investigation.md), [ADR-JPUB-006](../decisions/adr-jpub-006-static-reference-library-and-exemplars.md)

| Proposed component | Intended consumer | Boundary | Current state |
|---|---|---|---|
| Publication model and future schema | Publishers and readers | Describe selected material, relationships, claims, evidence, and identities | Prose only |
| Publisher role | Publisher | Construct and inspect a dossier | Contract only |
| Read-only validator | Either side | Check structure, references, bytes, and supported attestations without execution | Absent |
| Portable dossier | Recipient | Carry inspectable evidence without requiring a service | No public exemplar |
| Generic reader role | Reader | Navigate an existing dossier | Contract only |
| Reader-local generator | Reader | Propose a locally adapted investigation procedure | Separate contract only |
| Recipient adapter | Publisher and recipient | Render, authorize, transport, and read back under recipient rules | Contract only |
| Static reference repository | Readers and future implementers | Distribute design documents and possible future artifacts | This documentation tree |

## Separate authority surfaces

- **Construction:** selection, evidence, contrasts, falsifiers, and optional remedies.
- **Authorization:** approval of exact bytes, scopes, attestations, permissions, and recipient-facing rendering.
- **Transport:** recipient-specific submission, readback, and disposition.

One surface does not silently authorize another. A rendering can point to an underlying object but is not automatically that object.

## Static and offline boundary

A future dossier should remain inspectable without a publisher-hosted API, account, subscription, registry, or live reference site. Optional links may aid discovery, but validation-critical bytes and human-readable evidence must not depend solely on continued GitHub availability. This repository is document distribution, not an availability or trust authority.
