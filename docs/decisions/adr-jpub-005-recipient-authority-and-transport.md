# ADR-JPUB-005: Preserve recipient authority over admission and transport

**Handle:** `ADR-JPUB-005`  
**Status:** `proposed`  
**Proposal date:** 2026-11-02  
**Decision authority:** pending  
**Related records:** [ADR-JPUB-001](adr-jpub-001-repository-identity-and-boundaries.md), [ADR-JPUB-002](adr-jpub-002-publication-object-before-renderings.md), [ADR-JPUB-004](adr-jpub-004-detached-scoped-attestations.md)  
**Source lineage:** public candidate `docs/decisions/0004-recipient-authority-and-transport.md` in the authorized source archive

## Context

A structurally valid publication may be wrong, irrelevant, costly, unsafe to execute, or one of many submissions. A signature or proof of effort does not entitle material to attention. A global admission rule would turn a format into a gatekeeper.

## Proposed decision

Keep construction, exact-byte authorization, and recipient-specific transport separate. Let recipients set local admission, resource, endorsement, disclosure, execution, and disposition policy without changing the publication's evidentiary state. Treat a GitHub adapter as one possible rendering and transport boundary, not the definition of joint publishing.

## Rationale and consequences

This preserves independently inspectable material and recipient sovereignty. It also means acceptance varies and a valid package may be ignored. That is a recipient choice, not automatically a format failure.

## Alternatives considered

- **Submit after structural validation:** conflates validation with publication permission.
- **Mandatory proof of work:** measures resources rather than epistemic merit.
- **Signer-based triage bypass:** identity and scope do not grant priority without recipient opt-in.
- **Monolithic publisher and transport tool:** couples heterogeneous recipient rules and hidden side effects.

## Open questions

- [ ] What approval artifact binds both the dossier identity and rendered bytes? **Resolution trigger:** first locally reviewed transport fixture.
- [ ] How can executable reproduction cross heterogeneous sandboxes safely? **Resolution trigger:** isolated cross-environment reproduction.
- [ ] Which recipients accept discovery-only material without a remedy? **Resolution trigger:** first recipient policy requiring that distinction.

## Supersession

**Supersedes:** none.  
**Superseded by:** none.
