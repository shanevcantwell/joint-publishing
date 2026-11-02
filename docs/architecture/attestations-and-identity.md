# Attestations and identity

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by this document  
**Related proposed ADR:** [ADR-JPUB-004](../decisions/adr-jpub-004-detached-scoped-attestations.md)

No cryptographic profile, identity registry, key-discovery service, trust policy, or signing tool has been selected.

## Proposed attestation boundary

A future detached attestation may identify a signer-controlled key, exact subject digest, covered claim IDs, role, statement, conditions, method, evidence pointers, limitations, and verification profile. Possible roles include assertion, reproduction, review, endorsement, dispute, correction, retraction, and recipient disposition.

The following judgments remain separate:

1. **Integrity and key control:** did a signature verify over exact bytes under a named method?
2. **Identity continuity:** what evidence associates the key with a claimed identity over time, including rollover or compromise?
3. **Method independence:** was the reported investigation operationally independent?
4. **Reader trust and relevance:** does this reader choose to rely on that actor for this scope?
5. **Recipient authority:** does local policy admit, prioritize, execute, or act on the material?

A cryptographically valid statement would not prove the claim, signer identity, independence, relevance, or permission. Multiple independent statements are not automatically a threshold collective authorization.

## Future evaluation requirements

Evaluate established envelope and signature mechanisms rather than inventing cryptography. Any selected profile must support exact byte semantics, offline verification evidence, scoped statements, contradictory authentic attestations, key rotation and compromise cases, and a clear account of unavailable revocation or time evidence.

Later attestations must reference immutable subjects rather than mutate the bytes they attest to. Corrections and retractions add attributed history.
