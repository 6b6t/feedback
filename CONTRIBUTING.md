# Contribute to the 6b6t feedback tracker

This is an invite-only public issue tracker. It does not contain server plugin source.
Keep the existing invitation requirements. Player support questions belong in [SUPPORT.md](SUPPORT.md).

## Report a problem

Search existing issues first. Use the bug form for a reproducible defect.
Include the affected game/server, minimal steps, expected result, actual result, and date/time with timezone.
Use synthetic examples. Remove player data, private messages, credentials, and server infrastructure details.
For an exploit or other security concern, use [private reporting](SECURITY.md).

## Suggest an improvement

Use the feature form. Explain the player task and current limitation.
Describe the proposed behavior and existing alternatives. A request does not promise a delivery date.
Use the tracker task form for a concrete follow-up with completion criteria.

## Improve tracker files

Validate YAML and form field IDs. Check that support links reach the intended channel.
This repository has no application build or runtime test suite. Include form and link validation results in the PR.

## Contribution Policy

**Scope.** One logical change per PR: a single feature, fix, or plugin. A PR may span several plugins or modules only when they implement one coherent cross-plugin feature; state that explicitly in the PR description. Unrelated changes belong in separate PRs.

**Base branch.** Every PR targets the default branch. PRs stacked on unmerged branches are rejected.

**Design first.** New shared libraries, cross-plugin systems, or architecture decisions need an approved issue before code is written.

**Upstream first.** Org-owned projects are not vendored. Changes to them go to the original project; a PR here must link the upstream change or issue.

**AI assistance.** Disclose AI-generated or AI-assisted code in the PR: which tool, and the approved issue it implements.

**Commit style.** Conventional Commits: `type(scope): description` (feat, fix, docs, style, refactor, perf, test, build, ci, chore, revert). CI enforces this on every PR.

**Evidence.** Build and test locally, and paste the evidence (commands run, logs, screenshots) in the PR.
