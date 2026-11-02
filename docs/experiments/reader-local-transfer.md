# Reader-local transfer experiment

**Status:** unexecuted experiment proposal  
**Implementation:** none  
**Network dependency:** none required by this plan  
**Related proposed ADR:** [ADR-JPUB-003](../decisions/adr-jpub-003-reader-local-investigation.md)

## Null hypothesis

Selected positive joints, informative negatives, and boundary cases do not improve independent readers' recovery of consequential structural analogues in a held-out local corpus over direct prompting and topic-matched examples at equal review and compute budgets.

## Proposed comparison

Use a compact fixture with defensible positive, negative, and ambiguous relationships and a reader context not used to construct it. Compare:

- direct application of the same examples;
- a locally generated investigation procedure using the same materials; and
- shuffled or topic-matched but structurally wrong controls.

Freeze candidate pools, scoring rules, local questions, and privacy constraints before running. Separate ranking from retrieval. Track repeated-run variation, false analogies, review cost, and action-changing discoveries. Any scorer is an instrument, not a probability of truth.

## Falsification boundary

If local procedure generation adds no useful independently judged relationships under a matched budget, retain the simpler publication and reader paths. Failure of local transfer would not by itself disprove the value of an inspectable publication object.
