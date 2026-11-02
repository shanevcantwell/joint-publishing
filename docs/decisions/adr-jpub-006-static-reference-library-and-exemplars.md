# ADR-JPUB-006: Prefer a static reference library and useful exemplars

**Handle:** `ADR-JPUB-006`  
**Status:** `proposed`  
**Proposal date:** 2026-11-02  
**Decision authority:** pending  
**Related records:** [ADR-JPUB-001](adr-jpub-001-repository-identity-and-boundaries.md), [ADR-JPUB-002](adr-jpub-002-publication-object-before-renderings.md), [ADR-JPUB-003](adr-jpub-003-reader-local-investigation.md), [ADR-JPUB-004](adr-jpub-004-detached-scoped-attestations.md), [ADR-JPUB-005](adr-jpub-005-recipient-authority-and-transport.md)  
**Source lineage:** public candidate `docs/decisions/0005-static-reference-library-and-exemplars.md` in the authorized source archive

## Context

The repository should not require a maintained service or adoption campaign. A static reference location could distribute documentation and future artifacts without becoming the identity, permission, or availability authority for independently inspectable dossiers.

## Proposed decision

Prefer a forkable static reference library and a small number of independently useful exemplars over a managed platform or standards campaign. Make any reference link optional for a recipient's first useful reading. Observe voluntary, independently authored reuse and report negative results rather than manufacturing adoption.

## Rationale and consequences

This reduces operational burden and permits independent inspection. It may also produce slow or no adoption, fragmented forks, compatibility questions, and weak observation of private reuse. Failure to spread would not by itself disprove local usefulness.

## Alternatives considered

- **Standards-first campaign:** may increase awareness but conflicts with utility-first, low-pressure adoption.
- **Hosted platform:** eases analytics but creates operations and central dependence.
- **Bundle every future tool in each dossier:** aids offline use but can create unnecessary burden.
- **Link-only evidence:** compact but fails when the reference disappears.

## Open questions

- [ ] Can an unfamiliar reader use an exemplar without installing anything? **Resolution trigger:** blind no-install test.
- [ ] What distinguishes independent reuse from author-driven copying? **Resolution trigger:** first observed external use under a predefined rule.
- [ ] What version and fork policy supports durable offline inspection? **Resolution trigger:** second unrelated producer or fork.

## Supersession

**Supersedes:** none.  
**Superseded by:** none.
