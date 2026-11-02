# Draft publication contract

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by this document  
**Related proposed ADR:** [ADR-JPUB-002](../decisions/adr-jpub-002-publication-object-before-renderings.md)

This document is design input for a possible future serializable dossier. It is not a schema, protocol, standard, or conformance definition.

## Proposed object boundaries

- **Publication identity:** stable object and revision identifiers, byte-domain and digest-method identifiers, and lineage.
- **Selected substrate:** materials by value or immutable reference, declared absences, selection reasons, and environment evidence.
- **Joints:** typed relationships, anchors, positive, negative, and ambiguous examples, plus why the relationship is consequential.
- **Claims:** scoped challengeable statements, support, counterevidence, falsifiers, uncertainty, relations, and asserting actor.
- **Probes:** predeclared hypotheses, methods, controls, resource bounds, expected observations, and actual run records.
- **Applications:** optional remedies or local uses, kept separate from findings and their evidence.
- **Attestation references:** detached statements over exact subjects; they do not rewrite the subject.
- **Renderings and receipts:** convenience texts, separate approval state, transport state, and recipient disposition.

## Byte identity questions remain open

A digest is meaningful only when its byte domain is unambiguous. Future work must decide encoding, deterministic serialization, duplicate-field handling, path and reference safety, normalization, recursive coverage, extension behavior, and offline availability of validation-critical definitions. A digest label alone does not settle those choices.

## Two different review layers

1. **Structural inspection:** parse data, check required fields and references, compute exact digests, and report supported attestation results without running publisher code.
2. **Semantic and procedural investigation:** test claims, reproduce bounded probes, and decide whether evidence warrants an assertion.

A structurally valid future publication could contain a false claim. A sound observation could exist before a future schema. Keep those judgments separate.
