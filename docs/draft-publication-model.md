# Draft publication model

**Status:** design documentation; not a standard  
**Implementation:** none  
**Network dependency:** none required by this document  
**Related proposed ADRs:** [ADR-JPUB-002 through ADR-JPUB-006](decisions/README.md)

This revisable model describes properties worth testing. It is not a schema, protocol, conformance definition, release, or claim that an interoperable implementation exists.

## Publication object

A possible joint publication is a versioned, content-addressed, independently inspectable package of selected materials, marked consequential relationships, scoped claims, observations, contrasts, falsification routes, and optional detached attestations. Its purpose would be to expose consequential selection without compelling agreement.

The future authoritative subject, if one is accepted, would consist of explicitly identified bytes and relationships. Essays, issue bodies, pull-request descriptions, previews, and local analyses would be secondary renderings. Exact byte and serialization rules remain open.

## Claim and evidence discipline

Each consequential claim should have an identifier, precise scope, statement type, support, counterevidence, falsifiers, uncertainty, relations, asserting actor, and evidence state. “Unexamined,” “inconclusive,” “contradicted,” and “supported within a stated scope” must remain different.

A joint is not its remedy. A reader may accept an observation and reject a proposed patch; one passing engineering test does not automatically establish a broad explanation.

## Reproduction and safety

When execution is appropriate, a future dossier should state exact dependencies, environment, fixtures, permissions, resource bounds, expected observations, and actual results. It must represent stochastic, negative, and capability-gap cases without inventing deterministic success.

Read-only inspection must not execute publisher code. Execution, network access, installation, local publication, and credential use require separate recipient authority. Offline interpretability and executable reproducibility are distinct claims.

## Detached attestations

A future attestation may bind a key, exact subject digest, covered claim IDs, role, conditions, method, observed result, limitations, and a named verification mechanism. It must not mutate the subject it describes. Cryptographic validity would not establish identity, truth, independence, relevance, admission, or merge authority.

## Reader authority and lifecycle

A cold reader should be able to locate the selected relationship, observations, falsifiers, disputes, attestation scopes, and safe next actions without private chat history. The reader may reject, ignore, queue, or investigate.

Construction prepares the evidence object. Authorization approves exact bytes and scopes. Transport applies recipient rules and records readback. Corrections, disputes, retractions, reproductions, and recipient decisions append attributed records that reference prior identities rather than overwriting history.

## Distribution boundary

A future static reference library may aid discovery, but it must not be required as a live trust or availability service. A vanished reference site should not erase locally held evidence. One admired exemplar would not establish a universal standard.
