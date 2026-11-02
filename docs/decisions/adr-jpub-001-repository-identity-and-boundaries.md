# ADR-JPUB-001: Establish repository identity and boundaries

**Handle:** `ADR-JPUB-001`  
**Status:** `accepted`  
**Date:** 2026-11-02  
**Decision authority:** operator  
**Repository:** `shanevcantwell/joint-publishing`  
**Repository code / ADR-series code:** `JPUB`  
**Decisions home:** `docs/decisions/`

At founding, this repository is public; no repository license has been selected beyond rights necessarily provided by GitHub's Terms of Service or applicable law; no broader permission to reuse, modify, or redistribute repository content is granted; public visibility is not a release; external substantive contributions are not currently accepted; no implementation or hosted service exists; no standard or conformance program exists; and this is the only accepted decision.

## Context

The authorized source package preserved useful design candidates together with private reference material, stale recipient-specific evidence, obsolete package manifests, and provisional repository language. Publishing it verbatim would expose excluded material and overstate the maturity of the work. On 2026-11-02, the operator expressly authorized publication of this exact curated 37-file transformed tree in a public GitHub repository under GitHub's Terms of Service, without authorizing publication of excluded bodies.

## Decision

Establish `shanevcantwell/joint-publishing` as a public, documentation-first, incubating repository using `JPUB` for both repository and initial ADR-series identity.

1. Public visibility applies only to this exact curated 37-file founding tree. The operator's 2026-11-02 authorization resolves the public-push rights gate for this tree only; it does not claim ownership of excluded or private source bodies or clear future imports.
2. No repository license is selected. Rights necessarily provided by GitHub's Terms of Service or applicable law still apply, but no broader permission to reuse, modify, or redistribute repository content is granted. Public visibility is not a release declaration, endorsement, conformance claim, or maintenance promise.
3. Private reference bodies, their filenames and per-file checksums, and stale recipient-specific evidence are not repository content.
4. Source-object basename, archive digest, inspection result, and category-level exclusions identify the inspected source object and permit later integrity comparison; they do not prove custody, ownership, or provenance and do not require publishing excluded bodies.
5. The repository is static, forkable, and offline-inspectable. GitHub distributes documents; it is not a registry, availability authority, hosted trust service, registration authority, SaaS product, or network identity service.
6. Authenticity, truth, relevance, admission, priority, merge authority, and execution permission are separate judgments.
7. Construction, authorization, and transport are separate authority surfaces.
8. Detailed format, investigation, attestation, recipient, and exemplar decisions remain proposed until separately accepted.
9. Broader licensing, attribution and provenance allocation, rights for future imports, serialization, byte identity, signing profile, standardization, conformance, long-term contribution posture, and public exemplars remain unresolved. External substantive contributions are not accepted at founding; fork and pull-request capabilities grant no decision, publication, acceptance, merge, or execution authority.
10. There is no implementation, schema, validator, executable skill, package, protocol version, release, or supported service at founding.

## Rationale and consequences

A curated tree can make the public design reviewable without exposing excluded material or pretending that documentation is a product. The cost is deliberate incompleteness: beyond rights necessarily provided by GitHub's Terms of Service or applicable law, readers receive no broader reuse, modification, or redistribution permission, executable validation path, public exemplar, or interoperability claim. Later irreversible boundary changes require an accepted JPUB decision.

## Alternatives considered

- **Import the archive verbatim:** rejected because it would publish excluded bodies, stale evidence, old paths, and invalid manifests.
- **Create a private founding repository:** superseded for this mint by the operator's explicit public-repository authorization.
- **Select a broader license now:** rejected because attribution and provenance allocation, the intended scope of broader reuse rights, and rights for future imports remain unresolved.
- **Ship an implementation or hosted service:** rejected because the supplied public material is documentation and contracts, and the intended boundary is static and offline.

## Open questions

The unresolved technical and rights questions are indexed in [open questions](../open-questions.md). Each has a resolution trigger; none is answered by this decision.

## Supersession

**Supersedes:** the source package's provisional repository-identity and visibility posture for this curated mint only.  
**Superseded by:** none.
