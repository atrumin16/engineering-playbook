# Pair Extraordinaire

## Summary

Git commit trailer conventions and `Co-authored-by` syntax for the Pair Extraordinaire achievement.

## Specifications

- **Scope**: Public GitHub repositories.
- **Merge Target**: Default branch (`main`).
- **Trailer Syntax**: `Co-authored-by: Name <id+username@users.noreply.github.com>`.
- **Identity Requirement**: The email in the Git trailer MUST resolve to an active, verified GitHub user account. Generic or unverified addresses (`@github.com` without user mapping) will not register in the GitHub event graph.
- **Tiers**:
  - Base: 1 co-authored merged PR
  - Bronze: 10 co-authored merged PRs
  - Silver: 24 co-authored merged PRs
  - Gold: 48 co-authored merged PRs

## Standards & Best Practices

1. Leave an empty line before the `Co-authored-by:` trailer in the commit message body.
2. Ensure both authors have distinct verified GitHub identifiers.
3. Squash or merge PRs cleanly to maintain verifiable git lineage.
