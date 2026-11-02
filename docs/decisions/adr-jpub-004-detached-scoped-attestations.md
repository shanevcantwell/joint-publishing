# ADR-JPUB-004: Keep attestations detached and scoped

**Handle:** `ADR-JPUB-004`  
**Status:** `proposed`  
**Proposal date:** 2026-11-02  
**Decision authority:** pending  
**Related records:** [ADR-JPUB-001](adr-jpub-001-repository-identity-and-boundaries.md), [ADR-JPUB-002](adr-jpub-002-publication-object-before-renderings.md)  
**Source lineage:** public candidate `docs/decisions/0003-detached-scoped-attestations.md` in the authorized source archive

## Context

Different actors may assert, reproduce, dispute, correct, or endorse different parts of one publication. Embedding accumulating signatures inside the bytes they sign creates identity churn and obscures scope. An untyped “verified” label would conflate key control, identity, method, and authority.

## Proposed decision

Use immutable subject identities with detached statements over exact digests, covered claim IDs, role, assertion, method, evidence, and limits. Keep cryptographic validity, identity continuity, method independence, reader trust, and collective authorization distinct. Select an established envelope only after interoperability and offline tests.

## Rationale and consequences

Detached statements could support independent disagreement and later correction without rewriting the core. Costs include discovery, bundle management, key rollover, compromise evidence, time semantics, and potential identity confusion. The same key must not masquerade as independent actors.

## Alternatives considered

- **Mutable signature list in the core:** easy to display but changes the subject on every addition.
- **Untyped verification flag:** compact but hides scope and method.
- **Global identity or truth service:** simplifies discovery but violates reader-local and non-service boundaries.
- **Immediate threshold signing:** may suit a later collective action but is not the same as independent attestations.

## Open questions

- [ ] Which existing envelopes can two independent implementations verify offline over the same fixture? **Resolution trigger:** cross-tool test.
- [ ] How are key rotation, compromise, and historical identity evidenced without implying trust? **Resolution trigger:** adversarial continuity fixture.
- [ ] How can readers discover optional later statements and distinguish absence from relay omission? **Resolution trigger:** two-relay divergence fixture.

## Supersession

**Supersedes:** none.  
**Superseded by:** none.
