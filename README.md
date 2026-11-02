# Joint publishing

**Publish the consequential connection, not just the conclusion.**

A report usually gives the reader an author's finished interpretation. A raw evidence dump does the opposite: it leaves the reader to discover the important relationships unaided. Joint publishing explores a third option—**publish the selected relationship and enough of its evidence to let someone else investigate it independently**.

A **joint** is a relationship, contradiction, transition, or other connection that the publisher considers consequential. A joint is not automatically true or important just because someone marked it. The recipient gets to decide.

A proposed **joint publication** would keep the selected material, the marked connections, challengeable claims, counterevidence, falsification routes, and optional independently signed attestations together as a portable evidence object. A GitHub issue, pull request, essay, or video could be a useful *rendering* of that object rather than its only form.

> **Current status:** JPUB is a public, documentation-only exploration—not a released standard or working toolkit. There is no implemented schema, validator, executable skill, signing profile, or public dossier. See [STATUS.md](STATUS.md).

## A small example

Imagine an agent investigating a workflow tool. It finds three individually deliberate behaviors: arguments are provided inline, workflows run in the background, and completion notices shorten long results. Together, they may prevent a caller from passing a large generated input and recovering a complete report without another model-mediated transcription step.

A conventional issue might jump straight to “add file-backed arguments and result storage.” A joint publication would distinguish:

- **Observations:** the actual behaviors, exact revisions, and supporting source or test evidence.
- **The joint:** why those behaviors compose into a capability gap for a particular use case.
- **Claims and falsifiers:** what could demonstrate that the alleged gap does not exist.
- **Contrasts:** working small-input cases, counterexamples, alternatives, and uncertainties.
- **Candidate application:** one proposed correction, separate from the finding itself.
- **Attestations:** who claims to have reproduced, challenged, reviewed, or endorsed *which part*, under what conditions.

The maintainer could reproduce the observation and still reject the proposed fix. Another investigator could reproduce one claim while disputing the interpretation. Neither would need to rewrite the original evidence object.

*This is an illustration of the idea, not a completed or verified public JPUB exemplar.*

## Why separate attestations?

Instead of adding another reviewer's signature or verdict inside a publication, a future dossier could carry **detached, scoped statements** referring to exact artifact or claim identities. Signers could endorse different parts, report inconclusive results, or disagree.

The design deliberately separates **a valid signature**, **an identity claim**, **independence of investigation**, **the truth of an assertion**, and **the recipient's decision to trust or act**. Existing cryptographic formats and tools are under consideration; none has been selected for JPUB.

Likewise, no signature, schema, or publication would grant permission to execute untrusted code. The reader controls admission, verification, and execution.

## Watch the idea (optional)

These short, **AI-generated NotebookLM explainers** are informal introductions, not technical authority. They simplify the design and sometimes describe hoped-for benefits as though they were established. The repository documents are the source for actual scope and status.

- [Unbundling the Truth: The Anatomy of an AI Agent Claim or Bug Report](https://www.youtube.com/watch?v=FbsSNax0kpc) — 4:19 overview of the proposed approach.
- [How a Joint Publication Object Works](https://www.youtube.com/shorts/tQHFgWU8w4w) — 1:23 on evidence, selected relationships, and renderings.
- [How Detached Scoped Attestations Secure Digital Records](https://www.youtube.com/shorts/QmHhmjCyQhA) — 1:26 on independently signed statements that leave the original unchanged.

## Explore the design

| Start with | For |
|---|---|
| [Joints and selection](docs/concepts/joints-and-selection.md) | What a joint is—and is not |
| [Draft publication model](docs/draft-publication-model.md) | The proposed evidence object and its boundaries |
| [Start here](START-HERE.md) | A cold-reader path through the full repository |
| [Decision index](docs/decisions/README.md) | Accepted versus proposed architectural decisions |
| [Component map](docs/architecture/component-map.md) | The proposed schema, reader, publisher, and transport roles |
| [Open questions](docs/open-questions.md) and [roadmap](docs/roadmap.md) | What must be settled or tested before implementation |

The long-term experiment is modest: **can a useful, self-contained publication invite independent inspection and voluntary reuse without a service, registry, or standards campaign?** That adoption is a hypothesis to test, not an outcome to presume. This repository is intended as a static reference library, not a centralized trust authority.

## Project boundaries and permissions

Only [ADR-JPUB-001](docs/decisions/adr-jpub-001-repository-identity-and-boundaries.md) is accepted; the five technical ADRs remain proposals. No hosted service, release, supported protocol, or conformance program exists. External substantive contributions are not currently accepted.

**No broader repository license has been selected.** Public visibility and GitHub's Terms of Service do not themselves grant general permission to copy, modify, or redistribute the material. The intended permissions, provenance, and contribution posture are unresolved; see the [repository policy](docs/repository-policy.md) and [status](STATUS.md). Future independent adoption depends on resolving those rights, not merely encouraging imitation.
