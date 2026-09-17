# Repository Templates

Give a new or existing project a lightweight, spec-driven working agreement:

> Set up this project using LookingSharp/repo-template

An agent with access to this repository should follow the procedure below in
the destination repository. Read this file from the template's default branch
unless the user specifies another ref. Report inaccessible sources as blockers.

## Available variants

| Slug | Location | Purpose |
|---|---|---|
| `spec-driven` (default) | `templates/spec-driven/` | Spec-first development, team review, issue lifecycle, and release discipline. |

The one-line request selects `spec-driven` unless the user names another
available variant. Future variants get their own descriptive slug and directory
under `templates/`; do not combine variants implicitly.

## Files to install

Copy the **contents** of `templates/spec-driven/` into the destination root,
including `.github/` and `.gitkeep`. Do not copy the enclosing variant directory
or this repository's root maintenance files. No files need renaming or removal.

The variant contains `README.md`, `AGENTS.md`, `TEAM.md`, `CHANGELOG.md`,
`.github/copilot-instructions.md`, `specs/README.md`, `specs/Project-Spec.md`,
and `specs/speclets/.gitkeep`. The README and specification contain project
placeholders; the changelog already contains a suitable initial setup entry.

Preserve the destination license and Git history; do not replace them as part of
adoption. A new project's license is a separate owner decision; no license is
silently chosen by the variant. Cloning this repository or using GitHub's
"Use this template" copies the outer structure too; it is not the same as
installing a variant's contents.

## Adoption procedure

1. **Inspect first.** Read existing instructions, documentation, specifications,
   code, and checks. Preserve existing work and decisions. In existing projects,
   merge missing governance without discarding established rules; escalate
   material conflicts rather than overwriting them. Repeated setup must not
   duplicate files or reset customization.
2. **Install the permanent files.** Copy the selected variant's contents as
   described above. Keep the reference
   team personas intact; add project-specific review criteria separately rather
   than rewriting them. Dave is the named human owner, not an agent persona. If
   the destination has a different human owner, confirm and update that identity
   and its references.
3. **Define the contract.** Use the user's stated mission for a new project.
   For existing projects, derive the mission and behavior from established
   documentation and observable behavior, distinguishing intended behavior from
   known defects. Reuse an existing authoritative specification without creating
   a competing contract. If its path differs from `specs/Project-Spec.md`,
   preserve that path and update the installed references consistently; this is
   an exception to unchanged copying. Preserve existing acceptance identifiers.
   Ask about an unknown mission or material product decision rather than inventing
   requirements. If blocked, retain useful scaffolding and report the unresolved
   decision without declaring setup complete.
4. **Populate project content.** Replace every bracketed placeholder in the new
   specification and project README. Use "Not applicable" with a reason where
   appropriate; do not invent setup commands or features. For an existing
   README, preserve its content and integrate the working-agreement links from
   the variant's `README.md` rather than replacing it. Permanent governance files need
   no template-instruction removal.
5. **Initialize release history.** If absent, copy the variant's starter
   `CHANGELOG.md` unchanged. Otherwise preserve the existing changelog and
   versions, recording adoption where appropriate. Never import this repository's
   root changelog entries or assign a release during setup.
6. **Verify and report.** Confirm one authoritative spec, valid local links,
   no unresolved placeholders in populated content, and no template-only files
   in the installed set. For new projects, confirm permanent files match the
   source except for an explicitly required owner change; for existing projects,
   account for intentional merges and spec-path changes. Link existing behavioral
   tests to acceptance scenarios where practical and report coverage gaps without
   claiming unverified conformance. Run existing applicable checks without adding
   tooling solely for setup. Report changes and outstanding decisions using the
   completion format in `AGENTS.md`.

Setup changes governance and documentation only. Do not implement features,
overwrite unrelated work, commit, push, or change repository settings unless
separately requested.

This template intentionally has no product mission. Its specification and
project README contain placeholders; the adopting project supplies the contract.
