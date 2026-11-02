# Roadmap and stop gates

Founding identity is established by accepted [ADR-JPUB-001](decisions/adr-jpub-001-repository-identity-and-boundaries.md) together with the root commit containing this tree. Staging alone does not establish the repository snapshot. Public-side readback of the root commit and exact tree remains required before mint completion is announced. All implementation, schema, validator, attestation, exemplar, release, and adoption work remains future and separately gated.

## Phase 0 — founding documentation

- Establish public repository identity, `JPUB` code, no-broader-license posture, and sole decisions home.
- Curate a 37-file public tree without private bodies or stale exemplar evidence.
- Normalize five technical records as proposals rather than accepting them.

**Exit:** the accepted ADR and root commit establish identity, this exact founding tree passes its static validation gates, and public-side readback confirms the root commit and tree. Only then may mint completion be announced. This does not create a release or authorize later phases.

## Phase 1 — minimal private fixture

After rights and provenance review, hand-author one bounded fixture with one selected relationship, useful negative, counterclaim, falsifier, static evidence, and human entry point.

**Gate:** an unfamiliar reader recovers the relationship and falsifier offline without author explanation. Keep the fixture non-public until publication rights are clear.

## Phase 2 — schema and read-only validator

Resolve byte identity and serialization, prepare cross-implementation vectors, and design valid and adversarial fixtures. Any validator must work without network access or code execution.

**Gate:** exact offline validation behavior is reproducible; deliberate mutation and ambiguous serialization fail visibly. Requires an accepted decision before code enters this repository.

## Phase 3 — detached attestations and optional reader support

Evaluate an established envelope, contradictory scoped statements, unknown keys, continuity failures, and local notice policy. Build reader support only if it improves the no-tool baseline. Keep reader-local generation a separate experiment.

**Gate:** cryptographic validity, identity, independence, trust, and recipient authority remain correctly separated; no unauthorized execution occurs.

## Phase 4 — candidate public exemplar

Select a current case only after rights, confidentiality, current-code, recipient-rule, transport-authorization, and reproduction review. Compare credible alternatives and obtain exact-byte authorization before contact.

**Gate:** the recipient-facing artifact is independently useful without format adoption, and every transport action is separately authorized.

## Phase 5 — adoption observation

If useful exemplars exist, freeze indicators and an observation window before measuring independent reuse. Report negative outcomes and attrition.

**Gate:** do not infer a universal standard from one exemplar, popularity, copying, or favorable comments.

## Explicitly not on the roadmap without a new accepted ADR

A mandatory hosted service, registry, account system, network identity dependency, automatic submission pipeline, telemetry service, or availability authority.
