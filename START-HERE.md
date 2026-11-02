# Start here

This repository is a public, documentation-first incubation space for the `JPUB` design. It is not a released format, implementation request, standards campaign, or hosted service.

## Ten-minute path

1. Read [README.md](README.md) for the identity, status table, and non-goals.
2. Read [STATUS.md](STATUS.md) for the exact founding inventory.
3. Read accepted [ADR-JPUB-001](docs/decisions/adr-jpub-001-repository-identity-and-boundaries.md).
4. Use the [decision index](docs/decisions/README.md) to distinguish the five proposed technical decisions from the accepted founding decision.
5. Read the [draft publication model](docs/draft-publication-model.md) and [component map](docs/architecture/component-map.md) as design material, not an implemented specification.
6. Review [open questions](docs/open-questions.md), [roadmap](docs/roadmap.md), and [repository policy](docs/repository-policy.md) before proposing work.

## Boundary checklist

- **Joint / claim / application:** a selected consequential relationship, a challengeable assertion, and a proposed remedy are separate.
- **Core / rendering:** a proposed immutable evidence object and its recipient-facing prose are separate.
- **Core / attestation:** signatures or other attestations are detached records over exact subjects; no profile is selected.
- **Authenticity / judgment:** a valid signature would not prove truth, relevance, admission, priority, or execution permission.
- **Construction / authorization / transport:** preparing material, approving exact bytes, and submitting to a recipient are separate actions.
- **Reader / generator / publisher:** navigation, local procedure generation, and publication construction are separate roles.
- **Internal / serializable representation:** research about internal representations is parallel work, not a format dependency.
- **Repository / authority:** a static reference location is not a registry, trust service, or availability guarantee.

## Safe next action

The next useful step is not to invent a universal schema or service. It is to resolve the rights and provenance gates, then hand-author one small, non-public fixture and test whether an unfamiliar reader can recover its selected relationship, strongest counterevidence, and cheapest legitimate falsifier without network access or executable tooling. Any public exemplar requires the additional gates in [examples/README.md](examples/README.md).
