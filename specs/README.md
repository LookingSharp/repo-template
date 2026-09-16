# Specifications

This directory contains implementation-independent behavioral specification
material for the project that adopts this template.

## Adoption

1. Replace every bracketed placeholder in `Project-Spec.md`.
2. Rename it to the project's authoritative specification name.
3. Update the authoritative-specification references in `AGENTS.md` and this
   README.
4. Do not begin product implementation until the project mission or goal and
   initial behavioral contract are defined.

## Lifecycle

- The renamed project specification is the single authoritative current
  behavioral contract. Implementations and tests conform to it; its release-tag
  state defines the behavior released at that tag.
- `speclets/` contains focused proposed or in-progress behavioral changes.
  After acceptance, merge the decision into the authoritative specification and
  normally delete the speclet. Git history preserves the development record.
- `CHANGELOG.md` records notable unreleased and released changes under Keep a
  Changelog. Semantic Versioning release impact is assessed alongside behavior
  changes.
- Give each acceptance scenario a stable identifier. Tests added by the
  adopting project must cite the identifier(s) they verify.
