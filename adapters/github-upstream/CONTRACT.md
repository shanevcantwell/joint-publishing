# GitHub upstream rendering adapter contract

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by this document  
**Related proposed ADRs:** [ADR-JPUB-002](../../docs/decisions/adr-jpub-002-publication-object-before-renderings.md), [ADR-JPUB-005](../../docs/decisions/adr-jpub-005-recipient-authority-and-transport.md)

This is a proposed boundary for rendering an already constructed dossier into a GitHub issue or pull-request contribution. It is not an integration, executable adapter, submission permission, or promise that a recipient will accept the contribution.

## Proposed responsibilities

- Accept only a dossier whose source scope, evidence state, and unresolved gaps are explicit.
- Re-read the recipient's current contribution, security, issue, and pull-request rules at submission time.
- Check for duplicates and distinguish a defect, capability request, alternative design, and proposed remedy.
- Produce a concise rendering that is useful without installing JPUB tooling or following an external link.
- Bind publisher approval separately to the exact dossier identity and exact rendered bytes.
- Submit only through a separately authorized transport lane, then read back and record external state without rewriting the underlying evidence.

## Non-responsibilities

Structural validity does not authorize contact, execution, implementation, or merge. The adapter does not grant queue priority, bypass recipient policy, determine truth, enroll identities, or convert a proposed remedy into recipient approval. Security disclosure rules remain recipient-owned.

## Future demonstration gate

An unfamiliar reviewer should be able to locate the selected relationship, reproduce a bounded case when appropriate, inspect alternatives, and decide disposition without adopting JPUB. Missing tests, absent patches, and unexecuted steps must remain visible.
