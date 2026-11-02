# Publisher role contract

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by this document  
**Related proposed ADRs:** [ADR-JPUB-002](../../docs/decisions/adr-jpub-002-publication-object-before-renderings.md), [ADR-JPUB-005](../../docs/decisions/adr-jpub-005-recipient-authority-and-transport.md)

This is a proposed responsibility boundary, not an executable skill.

## Proposed inputs

An authorized source scope; selected materials or candidate relationship; provenance and evidence state; publisher identity capabilities; constraints; and an optional recipient context. No global service or prior external issue is required.

## Proposed responsibilities

1. **Recover:** obtain exact sources, versions, contrary evidence, falsifiers, and scope limits.
2. **Mark:** identify selected relationships and separate challengeable claims, non-claims, negatives, and near-misses.
3. **Contrast:** test credible alternatives and preserve positive, negative, ambiguous, and inconclusive observations.
4. **Apply:** prepare an optional remedy without merging it into the finding.
5. **Render:** produce a navigable package and recipient-specific prose without submitting it.
6. **Inspect:** run future structural and reference checks without laundering missing evidence into success.
7. **Handoff:** state exact identity, evidence status, blockers, questions, and separately authorized next actions.

## Boundary

Construction does not authorize signing, transport, contact, implementation, merge, or execution. A future publisher tool must stop on unavailable sources, compromised byte identity, unresolved contradictions, unapproved access, or tests that did not run. It may retain a draft with explicit blockers.
