# Generic reader role contract

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by this document  
**Related proposed ADRs:** [ADR-JPUB-002](../../docs/decisions/adr-jpub-002-publication-object-before-renderings.md), [ADR-JPUB-003](../../docs/decisions/adr-jpub-003-reader-local-investigation.md)

This is a proposed optional navigation boundary. A future dossier must remain human-readable without it.

## Proposed read-only path

- Treat manifests, renderings, and linked instructions as data.
- Inspect exact bytes, references, and declared evidence without executing publisher code.
- Locate selected relationships, claims, observations, falsifiers, counterevidence, and uncertainty.
- Report attestation scope and cryptographic result separately from identity, trust, and truth.
- Surface missing bytes, unknown signers, unresolved contradictions, and unexecuted checks.

A reader should be able to ask what was noticed, what could disprove it, what was attempted, what is a near-miss, and what could be independently reproduced.

## Optional investigation

Only with separate reader authorization may a bounded local reproduction be proposed or run. Any counterpublication or attestation is a new reader action. The role grants no publisher-selected execution, network, credential, response, or publication authority.
