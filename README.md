# Spec-Driven Repository Template

Use this repository to give a new or existing project a lightweight,
spec-driven working agreement. Tell an agent with access to this repository:

> Set up this project using LookingSharp/repo-template

## Adoption procedure

For agents, that instruction means execute the following procedure in the
destination repository, not in this template. Read this README from the
template's default branch unless the user specifies another ref. If the source
cannot be accessed, report the blocker rather than claiming setup succeeded.

1. **Inspect first.** Read the destination's existing instructions, documentation,
   specifications, code, and available checks. Preserve existing work, project
   history, license, and established decisions.
2. **Install the working agreement.** Copy or merge `AGENTS.md`, `TEAM.md`,
   `.github/copilot-instructions.md`, `specs/README.md`, and
   `specs/speclets/.gitkeep`. Use `specs/Project-Spec.md` as the initial
   specification scaffold. Reuse an existing authoritative specification rather
   than creating a competing contract. Merge existing instructions without
   silently discarding rules; escalate material conflicts. On repeated setup,
   update what is missing without duplicating files or resetting customization.
3. **Define the project contract.** Derive the mission and initial behavior from
   established documentation and observable behavior, distinguishing intended
   behavior from known defects. For a new project, use the user's stated goal.
   Ask only when the mission or a material product decision cannot be determined;
   do not invent requirements to fill the template. If blocked, preserve useful
   scaffolding and report the unresolved decision without declaring setup complete.
4. **Customize in place.** Replace every bracketed specification placeholder;
   use "Not applicable" with a reason for irrelevant sections. Name the spec for
   the project and identify its exact path in `AGENTS.md` and `specs/README.md`.
   Update all references, including in the destination README. Replace
   template-only adoption instructions and no-mission statements with the
   project's contract and guidance. Tailor review criteria without inventing
   team members or owner decisions.
5. **Integrate project documentation.** Preserve the destination README, adding
   concise links to its working agreement and specification; for a new project,
   write a project introduction instead of copying this template README.
   Preserve existing changelog and release history. If absent, initialize
   `CHANGELOG.md` with the standards links and an `Unreleased` section. Record
   the adoption where appropriate, but do not import this template's changelog
   entries as the destination's history or assign a release version.
6. **Verify and report.** Check that the authoritative spec is unambiguous, all
   local links and renamed references resolve, and no unfilled placeholders or
   stale template-only instructions remain in adopted files. Preserve stable
   acceptance identifiers and link existing behavioral tests where practical;
   document coverage gaps without claiming unverified conformance. Use existing
   applicable checks, adding no tooling solely for setup. Report the adopted
   files and any outstanding decisions using the completion format in `AGENTS.md`.

Setup changes governance and documentation only. Do not implement product
features, overwrite unrelated work, commit, push, or change repository settings
unless separately requested. Once adopted, follow `AGENTS.md` for spec-first
changes, review, issue handling, validation, changelog, and release-impact checks.

This template intentionally makes no product, platform, privacy, security, or
behavioral claims. The adopting project defines those commitments in its
authoritative specification.
