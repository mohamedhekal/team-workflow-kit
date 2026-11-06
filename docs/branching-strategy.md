# Branching strategy

`main` is always releasable. All work happens on short-lived branches.

| Prefix | Use for |
| --- | --- |
| `feature/` | New functionality |
| `fix/` | Bug fixes |
| `docs/` | Documentation only |
| `chore/` | Tooling, config, dependencies |
| `test/` | Tests only |
| `ci/` | Pipeline changes |

## Rules

- Branch from `main`, merge back through a pull request.
- Keep branches small and short-lived; prefer several small PRs over one large one.
- Delete the branch after merging.
- Avoid two people editing the same files at once to keep merges conflict-free.
