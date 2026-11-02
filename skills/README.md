# Role contracts

**Status:** design documentation  
**Implementation:** none  
**Network dependency:** none required by these documents

Only non-executable contracts exist. There are no operational skills and no `SKILL.md` files.

| Proposed role | Contract | Operational? |
|---|---|---|
| Publisher | [publish-joints](publish-joints/CONTRACT.md) | No |
| Generic reader | [read-joint](read-joint/CONTRACT.md) | No |
| Optional reader-local generator | [reader-local-generator](reader-local-generator/CONTRACT.md) | No |

The generic reader navigates an existing dossier. The reader-local generator would propose a new context-specific investigation procedure. The publisher constructs source material. None grants installation, execution, network, credential, publication, or transport authority.
