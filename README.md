# AXM Organ Archive

Preservation archive for complete AXM organ bodies.

This repository is **not** a summary catalog. The archive target is the **full recoverable organ code/body** for every organ we intentionally preserve, categorized and accompanied by enough provenance to know exactly what it is and where it came from.

## Archive rule

For each archived organ, preserve the complete source package needed to understand and recover that organ as it existed at the archived version. Do not replace a full organ with a description, prompt, short summary, screenshot, or generated reconstruction.

Where applicable, an archived organ entry should retain:

- full source/code files;
- manifests/descriptors/contracts;
- tests and fixtures specific to the organ;
- organ-local docs/readmes;
- schemas/configuration/defaults;
- required small support files when they are part of the organ body;
- source repository + source path + exact commit/version;
- hashes/integrity evidence where practical;
- provenance/licensing/known dependency information;
- verification status and known limits;
- category + useful secondary tags;
- status such as active, historical, superseded, experimental, broken, or unknown.

Do not silently rewrite archived bodies to modernize them. A repaired or evolved organ should be archived as a new version while preserving the earlier body when continuity matters.

## Categorization

Every organ gets one primary category for navigation and may carry multiple secondary tags. Initial categories are:

- `perception/` — sensing, observation, interpretation inputs;
- `memory-continuity/` — memory, state continuity, identity/trace continuity;
- `reasoning-planning/` — reasoning structures, planning, decomposition, search;
- `truth-verification/` — evidence, validation, contradiction, provenance, checking;
- `agency-governance/` — consent, authority, boundaries, merge/governance logic;
- `coordination/` — collaboration, routing, handoff, multi-worker/multi-system coordination;
- `creation-design/` — creative construction, design reasoning, composition;
- `software-engineering/` — code understanding/build/test/repair structures;
- `simulation-state/` — deterministic state, simulation, causal/state-machine organs;
- `communication-interface/` — language, presentation, interaction/interface structures;
- `repair-recovery/` — rollback, repair, fault isolation, recovery;
- `domain-specialist/` — reusable domain-specific organs that do not fit a more general family;
- `experimental-unclassified/` — preserved candidates not yet confidently categorized.

Categories are for finding organs, not for forcing ontology. If an organ spans several domains, store one canonical body once and add secondary tags/cross-indexes rather than duplicating divergent copies.

## Relationship to Organ Fabric

`axm-organ-fabric` is the active growth/runtime system. This archive is the deep preservation layer. Workshop, WALMI, Mirror, the Organ Fabric, or future systems may donate organs here, but archive intake must preserve source identity instead of pretending every donor was originally built under one unified runtime.

## Constitutional boundary

Archive inclusion is preservation, not CANON promotion. Internal AXM merge/canon authority remains grounded in Truth, Agency / non-domination, Continuity, and Wisdom before speed.
