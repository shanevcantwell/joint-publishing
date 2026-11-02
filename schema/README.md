# Schema design area

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by this document

No schema exists. This directory contains non-normative design questions and a [future design checklist](design-checklist.md), not `schema.json`, a protocol version, generated types, or a conformance claim.

Any future schema work must first resolve exact byte semantics, canonicalization choices, offline availability, reference safety, extension behavior, and the boundary between structural inspection and empirical investigation. See the [draft publication contract](../docs/architecture/publication-contract.md).

A data shape could check types and references; it could not prove that a reproduction was independent, an identity was trustworthy, or a conclusion was warranted. Do not publish an invented schema URL or claim compatibility with a nonexistent version.
