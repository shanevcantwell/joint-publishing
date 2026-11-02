# ADR-JPUB-003: Keep contextual investigation reader-local

**Handle:** `ADR-JPUB-003`  
**Status:** `proposed`  
**Proposal date:** 2026-11-02  
**Decision authority:** pending  
**Related records:** [ADR-JPUB-001](adr-jpub-001-repository-identity-and-boundaries.md), [ADR-JPUB-002](adr-jpub-002-publication-object-before-renderings.md)  
**Source lineage:** public candidate `docs/decisions/0002-reader-local-investigation.md` in the authorized source archive

## Context

Publishers and readers have different corpora, questions, privacy boundaries, tools, and trust policies. A publisher-hosted analysis service cannot assume access to a reader's private environment, while a fixed prompt may be enough for simple use.

## Proposed decision

Keep three roles separable: a publisher constructs a source publication; an optional generic reader navigates an existing publication; an optional reader-local generator proposes an inspectable investigation procedure adapted to the reader's environment. No linked or generated procedure automatically executes or acquires permissions.

## Rationale and consequences

Local adaptation could preserve privacy and produce context-relevant investigation. It also adds complexity, compute cost, and risk of false analogy. Generated procedures must expose contrasts, permissions, and tests, and must be compared with a simpler no-generator baseline.

## Alternatives considered

- **Universal detector:** simpler deployment but forces shared representation and infrastructure.
- **Fixed application prompt:** cheaper and preferable unless generation adds measured value.
- **Publisher-hosted analysis:** convenient but creates privacy and maintenance dependence.
- **Bundle every tool:** aids availability but burdens uninterested readers.

## Open questions

- [ ] Does generation outperform direct use of identical examples under a matched budget? **Resolution trigger:** paired blinded experiment.
- [ ] Is the publication understandable with network access disabled and no optional reader tool? **Resolution trigger:** cold-reader fixture.
- [ ] Is a generator needed for the first useful case? **Resolution trigger:** successful no-skill comprehension and reproduction test.

## Supersession

**Supersedes:** none.  
**Superseded by:** none.
