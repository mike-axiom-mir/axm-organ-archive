# Organ Archive Category Index

The archive stores one canonical preserved body per archived organ/version under a primary category. Secondary relationships belong in metadata/tags/cross-indexes rather than duplicate mutable copies.

## Primary categories

| Category | Intended contents |
|---|---|
| `perception/` | sensing, observation, parsing, interpretation inputs |
| `memory-continuity/` | memory, identity/state continuity, trace continuity |
| `reasoning-planning/` | reasoning structures, planning, decomposition, search |
| `truth-verification/` | evidence, validation, contradiction, provenance, checking |
| `agency-governance/` | consent, authority, boundaries, constitutional/merge logic |
| `coordination/` | routing, collaboration, handoff, multi-worker/system coordination |
| `creation-design/` | creative construction, composition, design reasoning |
| `software-engineering/` | code understanding, build, test, repair and software reasoning |
| `simulation-state/` | deterministic state, causal/state-machine and simulation organs |
| `communication-interface/` | language, presentation, interaction and interface structures |
| `repair-recovery/` | rollback, repair, fault isolation and recovery |
| `domain-specialist/` | reusable specialist/domain organs without a better general category |
| `experimental-unclassified/` | preserved candidates not yet confidently classified |

## Recommended entry layout

```text
<primary-category>/
  <organ-id>/
    <version-or-source-snapshot>/
      ARCHIVE_ENTRY.json
      body/                 # full preserved organ code/package
      tests/                # when organ-local tests exist
      docs/                 # organ-local docs if separate from body
      evidence/             # verification receipts/hashes when available
```

`body/` is the important part: it must contain the recoverable organ itself, not a prose substitute.

If the donor organ is multi-file, preserve the multi-file body. If it is a single file, preserve that file. If its operation requires a small organ-local support closure, archive that closure and declare it in `ARCHIVE_ENTRY.json`.
