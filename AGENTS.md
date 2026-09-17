# Repository maintenance

This repository maintains reusable project templates, not an application.
Read `README.md` for the adoption contract.

- `templates/spec-driven/` is the default, self-contained variant. Its files
  are installed into a destination root; relative links must work there.
- Keep adoption instructions and this repository's changelog at the root.
  Never copy them into destination projects.
- Preserve the permanent governance and full team personas in the variant.
  For adoption-contract or governance changes, review each perspective in
  `templates/spec-driven/TEAM.md`. Dave is the human decision-maker; do not
  simulate his approval. Routine mechanical changes need no full team review.
- Update the root README before changing externally observable adoption
  behavior. Keep template changes focused and avoid speculative tooling.
- Update the root `CHANGELOG.md` for notable template changes. The variant's
  changelog is a clean starter, not a record of template maintenance.
- Follow Keep a Changelog 1.1.0 and Semantic Versioning 2.0.0. Assess release
  impact without assigning a version outside the release process.
- Validate the complete installed file set, including hidden files, relative
  links, and absence of maintenance-only files. Preserve intentional project
  placeholders in the source template.

Every completion report must include:

```text
Change compliance:
- Spec: <adoption contract/template updated | no change required - reason>
- Changelog: <updated | no entry required - reason>
- SemVer impact: <major | minor | patch | none>
- Tests: <updated/run/not run/etc.>
```
