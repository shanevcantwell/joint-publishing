# Open questions

The common founding posture remains: this repository is public; on 2026-11-02, the operator authorized publication of this exact curated 37-file transformed tree under GitHub's Terms of Service; no repository license has been selected beyond rights necessarily provided by GitHub's Terms of Service or applicable law; no broader permission to reuse, modify, or redistribute repository content is granted; public visibility is not a release; external substantive contributions are not currently accepted; no implementation or hosted service exists; no standard or conformance program exists; and only [ADR-JPUB-001](decisions/adr-jpub-001-repository-identity-and-boundaries.md) is accepted.

Every unresolved item has a trigger. These are not implied work assignments or answers.

| ID | Question | Why it matters | Resolution trigger |
|---|---|---|---|
| OQ-01 | What exact bytes are identified, serialized, and hashed? | Cross-implementation identity requires unambiguous byte domains. | First two-tool byte fixture and mutation test. |
| OQ-02 | How are validation-critical definitions available offline? | A live reference site must not become an availability authority. | Unplugged-machine fixture review. |
| OQ-03 | Which established attestation envelope and signature profile, if any? | Avoid bespoke cryptography and ambiguous scope. | Independent cross-tool sign and verify test. |
| OQ-04 | How are key rotation, compromise, time evidence, and identity continuity represented? | Key control is not durable identity or trust. | Adversarial continuity fixture. |
| OQ-05 | Which relationship types are minimally useful without freezing an ontology? | Premature vocabulary can distort selection. | Two materially different hand-authored fixtures. |
| OQ-06 | Can an unfamiliar reader understand a fixture without a skill or network? | The no-install path is a core boundary. | Blind offline reader test. |
| OQ-07 | Does reader-local generation add value over direct application? | Avoid unnecessary machinery and compute. | Equal-budget blinded comparison. |
| OQ-08 | How can reproduction be bounded and recipient-controlled? | Publisher instructions are untrusted. | Isolation fixture with deliberate dependency and permission failures. |
| OQ-09 | Which broader license, if any, and which broader reuse, modification, or redistribution permissions are intended? | The exact curated founding tree is authorized for public GitHub publication, but no broader repository license has been selected beyond GitHub Terms or applicable law. | Attribution and provenance allocation, intended-permission review, and an accepted ADR. |
| OQ-10 | Which future source contributions or imports may be published, reused, modified, or redistributed, and under what attribution? | Authorization for this exact curated tree does not resolve rights or provenance for later material. | Item-level rights, provenance, and attribution review before any affected public addition. |
| OQ-11 | What future contribution posture, if any, should replace the current non-acceptance posture? | Fork and pull-request capability does not grant decision, publication, acceptance, merge, or execution authority, and incoming material can create rights ambiguity. | Before accepting any external substantive contribution, with an accepted ADR or other explicitly authorized policy change. |
| OQ-12 | What constitutes a public release, version, or supported compatibility promise? | Founding documentation must not imply product maturity. | First candidate interoperable fixture and maintenance commitment review. |
| OQ-13 | Should JPUB ever define a standard or conformance program? | Standardization would add governance and compatibility obligations. | Evidence from multiple independent producers and an accepted ADR. |
| OQ-14 | How is independent reuse distinguished from popularity or copying? | Adoption claims require predefined evidence. | Before first measured public exemplar. |
| OQ-15 | Which public exemplar can pass rights, currency, safety, recipient-rule, and reproduction gates? | No exemplar is presently cleared. | Completed gate record for a current candidate. |
| OQ-16 | Do internal-representation experiments produce useful findings without becoming a format dependency? | Parallel research must not silently expand architecture. | Preregistered separate experiment with discriminating controls. |

When an item closes, record dated evidence, update affected decisions, and preserve rejected hypotheses rather than deleting history.
