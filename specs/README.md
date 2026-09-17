# Specifications

This directory contains implementation-independent behavioral specification
material for the project that adopts this template.

## Adoption

Follow the canonical [adoption procedure](../README.md#adoption-procedure).
`Project-Spec.md` is a scaffold, not an established product contract. Reuse an
existing authoritative spec if one exists; otherwise customize and rename the
scaffold. Replace this adoption section in the destination with the exact
authoritative spec path. Define the mission and initial contract before product
implementation begins.

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
