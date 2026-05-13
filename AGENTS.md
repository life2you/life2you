# AGENTS.md

## AI Collaboration Rules

- Prefer `gh` for GitHub operations. Before using raw `git`, `curl`, or manual browser steps for PRs, issues, releases, or repository inspection, first check whether `gh` is installed and authenticated with `command -v gh` and `gh auth status`.
- Keep edits scoped, avoid unrelated churn, and update user-facing documentation when behavior changes.
- When release or upgrade flow changes in a managed tool repository, make sure the corresponding English and Chinese maintainer documentation is updated there as part of the same work.
- If this repository ever adds release automation, keep any release scripts and package metadata aligned in the same change.
