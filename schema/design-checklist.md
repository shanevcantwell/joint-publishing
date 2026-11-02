# Future schema design checklist

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by this document

## Candidate object identities

- [ ] Publication subject and revision lineage.
- [ ] Selected materials, provenance, declared absences, and selection reasons.
- [ ] Joint anchors, relationship type, consequence, negatives, and ambiguity.
- [ ] Claims, scope, support, contradiction, uncertainty, falsifiers, and asserting actor.
- [ ] Probes, controls, environment, resource bounds, expected observations, and actual runs.
- [ ] Optional applications kept separate from findings.
- [ ] Detached attestations with exact subject and scope.
- [ ] Renderings, exact-byte authorization, transport receipts, and recipient disposition.
- [ ] Corrections, retractions, and supersession that preserve attributed history.

## Mechanical gates

- [ ] Specify wire encoding, digest method, byte domains, deterministic serialization, and cross-implementation vectors.
- [ ] Reject traversal, unsafe references, duplicate or ambiguous fields, and unknown security-significant extensions.
- [ ] Carry validation-critical definitions by verified bytes suitable for offline inspection.
- [ ] Keep signature results distinct from identity recognition, trust, and accepted scope.
- [ ] Avoid subject/signature circularity.
- [ ] Represent absent, failed, stochastic, contradictory, and inconclusive evidence honestly.
- [ ] Provide a no-network, no-execution inspection mode.
- [ ] Include valid and adversarial fixtures before claiming interoperability.

## Reader gates

- [ ] A first screen identifies selected relationships, claims, uncertainty, known negatives, and cheapest falsifiers.
- [ ] Stable file and claim anchors work without specialized tooling.
- [ ] Independent readers find methods and scope without original chat history.
- [ ] Extension rules do not require an exhaustive ontology.

## Stop condition

Do not assign a version, generate code, select signing machinery, or claim a standard because this checklist exists. Test a hand-authored fixture first.
