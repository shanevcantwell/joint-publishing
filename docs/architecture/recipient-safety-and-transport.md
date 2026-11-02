# Recipient safety and transport

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by this document  
**Related proposed ADR:** [ADR-JPUB-005](../decisions/adr-jpub-005-recipient-authority-and-transport.md)

Opening a dossier, reading a rendering, or checking an attestation must not grant filesystem, network, credential, installation, publication, or code-execution permission. Linked skills and reproduction instructions remain untrusted data until the recipient separately reviews and authorizes them.

## Proposed safety boundary

Read-only structural inspection precedes any optional execution. A separately authorized reproduction should use recipient-controlled isolation, pinned dependencies and fixtures, restricted mounts and secrets, explicit network policy, resource budgets, and captured observations. A container digest would identify bytes; it would not make those bytes safe.

Recipient admission is independent from format structure. Attention budgets, queue priority, spam controls, known-contributor policy, disclosure rules, and required evidence belong to the recipient. A package cannot assign itself priority or merge authority.

Transport should operate only on exact authorized bytes and record external readback. An issue, pull request, message, or preview is a rendering with its own approval and transport state. Deliberate divergence from recipient rules must be surfaced, not hidden behind local preference.

Reader-local analysis must not transmit a reader's private corpus to the publisher by default. Publishing a reader-derived finding is a new construction, authorization, and transport decision.
