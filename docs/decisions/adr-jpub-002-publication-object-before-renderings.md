# ADR-JPUB-002: Treat the publication object as primary to renderings

**Handle:** `ADR-JPUB-002`  
**Status:** `proposed`  
**Proposal date:** 2026-11-02  
**Decision authority:** pending  
**Related records:** [ADR-JPUB-001](adr-jpub-001-repository-identity-and-boundaries.md)  
**Source lineage:** public candidate `docs/decisions/0001-publication-object-before-renderings.md` in the authorized source archive

## Context

Conventional prose can hide the source selection, counterexamples, and claim boundaries through which a finding was reached. A raw source bundle preserves bytes but forces each reader to rediscover the selected relationship.

## Proposed decision

Explore a versioned, content-addressed publication core containing selected materials, consequential relationships, scoped claims, falsification routes, contrasts, and uncertainty. Treat essays, issues, pull-request descriptions, and previews as secondary renderings. Keep attestations and reader-local analyses separately addressable.

## Rationale and consequences

This could support cold-reader recovery, claim-level challenge, alternate renderings, and append-only correction. It would also introduce production burden, byte-identity choices, and the risk of a restrictive ontology. Incomplete relationships and defeasible interpretation must remain representable.

## Alternatives considered

- **Finished prose as primary:** familiar but can conceal selection and claim boundaries.
- **Source bundle alone:** preserves bytes but not the publisher's consequential selection.
- **Universal semantic ontology:** may aid machines but risks premature lock-in and distortion.

## Open questions

- [ ] What minimal core helps a human without tools? **Resolution trigger:** first blind cold-reader fixture.
- [ ] Does identity cover normalized logical objects or exact release bytes? **Resolution trigger:** first cross-implementation byte fixture.
- [ ] How are changing sources preserved without oversized bundles? **Resolution trigger:** first independently sourced exemplar candidate.

## Supersession

**Supersedes:** none.  
**Superseded by:** none.
