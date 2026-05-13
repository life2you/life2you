# AGENTS.md

## AI Collaboration Rules

- Prefer `gh` for GitHub operations. Before using raw `git`, `curl`, or manual browser steps for PRs, issues, releases, or repository inspection, first check whether `gh` is installed and authenticated with `command -v gh` and `gh auth status`.
- Keep edits scoped, avoid unrelated churn, and update user-facing documentation when behavior changes.
- When a managed tool repository ships new release-flow or upgrade-flow capabilities, make sure those highlights are included in that version's GitHub Release page notes/changelog in both English and Chinese.
- If this repository ever adds release automation, keep any release scripts and package metadata aligned in the same change.
