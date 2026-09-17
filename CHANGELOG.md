# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog 1.1.0](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning 2.0.0](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Self-contained `templates/spec-driven/` variant with a project README and
  clean initial changelog, separate from root maintenance files.
- Root maintenance instructions and default variant selection for one-line
  adoption, with descriptive slugs reserved for future variants.
- One-instruction adoption procedure for new and existing repositories,
  including safe merging, project customization, and completion checks.
- Initial spec-driven repository governance and specification template.
- Reusable issue lifecycle covering issue creation, specification links,
  verification, resolution, and closure.

### Fixed

- Restored required all-perspective specification and requested team reviews,
  with advisory review for routine changes.
- Restored explicit rules against duplicate specification archives and
  independent specification versioning.
- Separated temporary adoption instructions from permanent authority rules so
  setup preserves the project's core governance.
- Standardized new projects on `specs/Project-Spec.md` to avoid spec renaming
  and governance reference rewrites during adoption.
- Restored the full reference team definition from compare-directorytree,
  including named personas and Dave's human decision-making role.
- Adoption instructions now require replacing every bracketed specification
  placeholder, not only placeholders beginning with `PROJECT`.
- New-project verification now distinguishes populated project content from
  source files that must remain unchanged.
- Existing-project adoption now explicitly omits the template specification
  when preserving an authoritative specification at another path.
